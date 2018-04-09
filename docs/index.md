---
layout: default
---
# The Rust Verification working group

This working group is intended to provide a forum for all things formal methods and verification for Rust. We anticipate significant overlap in requirements for tools and want to provide a central repository to exchange ideas and share progress.

## Why Rust?

Most of the benefits of performing verification on Rust programs are directly derived from the guarantees of safe Rust. Unsafe code is significantly more complex, but it may be possible to define contracts that must be upheld at the unsafe boundary. For more information on the differences between safe and unsafe Rust, see the [Rustonomicon](https://doc.rust-lang.org/nomicon/meet-safe-and-unsafe.html).

* No need to reason extensively about the memory model
* Data races are eliminated
* A substantial subset can be transformed into pure functions

## Goals
* Develop formal foundations for the Rust language ([RustBelt](http://plv.mpi-sws.org/rustbelt/)).
* Extract required information from the compiler
* Design methods to formally verify programs written in Rust
* Investigate ways to combine program verification with broader testing frameworks

[More details](goals.html)

## Get Involved

Join our [mailing list](mailto:rust-verification@googlegroups.com), [get in touch with us](mailto:verification@rust-lang.org) or open a pull request to let us know about your Rust verification project.

We follow the [Rust Code of Contact](https://www.rust-lang.org/en-US/conduct.html). Any concerns should be brought to [rust-mods@rust-lang.org](mailto:rust-mods@rust-lang.org)

## License

The output of the verification working group is distributed under the following licenses:

* The code samples are licensed under the terms of both the [MIT License] and the [Apache License v2.0].
* The written prose is licensed under the terms of the Creative Commons [CC-BY-SA v4.0] license.

[MIT License]: ./LICENSE-MIT
[Apache License v2.0]: ./LICENSE-APACHE
[CC-BY-SA v4.0]: ./LICENSE-CC-BY-SA
