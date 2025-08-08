# polars-plugin-practice

0. Initialize Pixi project:
```
pixi init .
pixi add rust rust-src compilers clang
```

1. Initialize Cargo project:
```
pixi shell
cargo init --lib --edition 2021 --name expression_lib
```
Then edit the `Cargo.toml` file to match the
[Polars plugin instructions](https://docs.pola.rs/user-guide/plugins/expr_plugins/#setting-up).
