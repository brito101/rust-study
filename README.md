# Rust Study

## Cross-compile (w64) with cargo:

- Add two lines into Cargo.toml file:
  - [target.x86_64-pc-windows-gnu]
  - linker = "x86_64-w64-mingw32-gcc"
- Run: `cargo build --target=x86_64-pc-windows-gnu`
