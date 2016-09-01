# A Rustls stub for TryTLS

A small program for testing [Rustls](https://github.com/ctz/rustls) (an embryonic Rust TLS library) with [TryTLS](https://github.com/ouspg/trytls) (a TLS implementation testing tool).

## Prerequisites

Install Rust toolchain from the [Rust home page](https://www.rust-lang.org/). Another option is to use your package manager of choice, such as Homebrew on OS X:

```sh
$ brew install rust
```

Install TryTLS following the instructions at the TryTLS [project repository page](https://github.com/ouspg/trytls#installation). This requires Python 2.7.9+ or 3.4+:

```sh
$ pip install trytls
```

## Running the Tests

```sh
$ trytls https cargo run --quiet
```
