# Bevy Rust-GPU

A suite of crates designed to bridge the `rust-gpu` SPIR-V compiler into the `bevy` engine.

See [`bevy-rust-gpu`](https://github.com/Bevy-Rust-GPU/bevy-rust-gpu) for top-level project documentation.

## Other repositories of note

### [`t-funk`](https://github.com/Bevy-Rust-GPU/t-funk)

Type-level programming toolkit. Abuses Rust's trait system to encode static, composable type-level computation.
Implements data structures, type classes, and a significant chunk of the Haskell standard library - all statically.

Pros: Rich expression of static type-level computing.
Cons: Verbose. Terrible compile times.


### Elysian Series

[`V1`](https://github.com/Bevy-Rust-GPU/elysian-legacy)
[`V2`](https://github.com/Bevy-Rust-GPU/elysian-legacy-2)
[`V3`](https://github.com/Bevy-Rust-GPU/elysian-legacy-3)

Iterative attempts at refining a practical, cross-domain implicit surface compiler.
A full mission statement is available in the [`V1`](https://github.com/Bevy-Rust-GPU/elysian-legacy) README.
V1 is free-standing, and included here for posterity, while V2 and V3 each depend on other crates in this organization.
