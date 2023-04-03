# AOAAE
Simple password manager written in Rust. Educational purpose. Uses Rust nightly.
## Features
- Add, delete, display passwords information.
- Passwords are encrypted using `Fernet` with encryption key generated by CSPRNG.
- Deriving KEK from master password using `Argon2` and wrapping the encryption key with `AES-KW`
- Automatically exit after short period of inactive using asynchronous programming 

## To do
### New features:
- Database integrity check
- Fuzzy search
- Configuration file
- Command line arguments
- Password Generation
- Export passwords to file
- Change master password
### Code:
- Improve error handling
- (?)Handling sensitive data in memory

## Try
Make sure you have Rust with latest nightly toolchain. Create `data` folder inside the project directory.
```bash
mkdir data
```
And run:
```bash
cargo run
```

## License

Licensed under either of

 * Apache License, Version 2.0
   ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license
   ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.
