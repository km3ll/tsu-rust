# tsu-rust

- [modules](#modules)
- [commands](#commands)
- [references](#references)
- [crates](#crates)

## modules

- [guessing_game](guessing_game)
- [hello_cargo](hello_cargo)

## commands

```bash
# Compiler
rustc --version
rustc main.rs

# Cargo
cargo version
cargo new hello_cargo
cargo check
cargo build
cargo build --release
cargo run

## Documentation based on project's dependencies 
cargo doc --open

# Toolchain
rustup docs --book
rustup doc
rustup update

# Bash
./target/debug/hello_cargo
```

## references

- Rust Compiler `rustc`: [blog](https://doc.rust-lang.org/rustc/what-is-rustc.html)
- Rust Programming Language: [blog](https://doc.rust-lang.org/book/title-page.html)
- Semantic Versioning 2.0.0: [bloc](https://semver.org/)
- The `Cargo` Book: [blog](https://doc.rust-lang.org/cargo/index.html)
- TOML Format: [blog](https://toml.io/en/)

## crates

- `Rand` - Random number generators and other randomness functionality: [doc](https://crates.io/crates/rand)