# rusty_simd

> **This repository has moved.** `rusty_simd` now lives at
> [`crates/rusty_simd`](https://github.com/Rusty-Mill/rusty_mill/tree/main/crates/rusty_simd)
> in the [`rusty_mill`](https://github.com/Rusty-Mill/rusty_mill) monorepo, with full commit
> history preserved. This repository is kept for historical reference and is no longer
> developed; please open issues and pull requests against `rusty_mill` instead.

[![CI](https://github.com/baileyrd/rusty_simd/actions/workflows/ci.yml/badge.svg)](https://github.com/baileyrd/rusty_simd/actions/workflows/ci.yml)

A zero-dependency SIMD (AVX2/NEON/FMA) accelerated block dequantization kernel library for LLM and Whisper inference in Rust.

`rusty_simd` provides `dequantize_q4_0`, `f16_to_f32`, and SIMD dot product kernels for `rusty_llama` and `rusty_whisper`.

## License

Licensed under either of [Apache License, Version 2.0](./LICENSE-APACHE) or [MIT license](./LICENSE-MIT) at your option.
