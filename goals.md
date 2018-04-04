# Verification WG Goals

## Short Term
Extract required information from the compiler
* trait impls
* MIR
* types

Determine a way to write specifications
* create a set of example
* subset of rust
* extensible

## Areas of interest
* Functional correctness
* Taint Tracing
* Reachability
* Constant time execution

## Long term
Formalize semantics of the Rust language itself
* make the semantic model more faithful to the language
* reason about the memory model (in particular, relaxed memory)
* create a valgrind plugin?

Perform verification directly on Rust programs
* Eventually, also be able to verify unsafe code

Integrate verification with testing
