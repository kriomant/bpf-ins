# bpf-ins
[![Build Status](https://github.com/arcjustin/bpf-ins/workflows/build/badge.svg)](https://github.com/arcjustin/bpf-ins/actions?query=workflow%3Abuild)
[![crates.io](https://img.shields.io/crates/v/bpf-ins.svg)](https://crates.io/crates/bpf-ins)
[![mio](https://docs.rs/bpf-ins/badge.svg)](https://docs.rs/bpf-ins/)
[![Lines of Code](https://tokei.rs/b1/github/arcjustin/bpf-ins?category=code)](https://tokei.rs/b1/github/arcjustin/bpf-ins?category=code)


## Description
Library for encoding and decoding eBPF instructions.

## Usage
```rust
/*
 * return 0
 */
let instructions = [ 
    Instruction::mov32(Register::R0, 0), // mov r0, 0
    Instruction::exit(),                 // exit
];
```

## TODO
- Replace `anyhow` with own Result/Error definitions.
