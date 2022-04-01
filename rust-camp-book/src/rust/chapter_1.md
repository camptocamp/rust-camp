# Getting Started

## Install Rust

Follow the official documentation to [Install Rust](https://www.rust-lang.org/tools/install) using `rustup`.

In case a nightly toolchain is needed, use the `--allow-downgrade` option on install.

```sh
# add nightly toolchain
rustup toolchain install nightly --allow-downgrade
# make it the default
rustup default nightly
```

For more advanced setups consult the [rustup documentation](https://rust-lang.github.io/rustup/)

## Editor Support

Setup the [rust-analyzer](https://rust-analyzer.github.io/) or the [InteliJ Rust](https://www.jetbrains.com/rust/) plugin, depending on your editor of choice.
