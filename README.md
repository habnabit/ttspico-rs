# ttspico-rs
[![Docs for ttspico](https://docs.rs/ttspico/badge.svg)](https://docs.rs/ttspico)

Rust bindings for Pico TTS, an open source ([Apache 2.0](LICENSE)) text-to-speech engine.

## Crates in this repo
- [`ttspico_sys`](ttspico-sys/): Low-level (C FFI) Rust bindings to Pico.  
  Links to a system `libttspico`.
- [`ttspico`](ttspico/): High-level, idiomatic Rust bindings to Pico.  
  Built on top of `ttspico_sys`.

## Getting started
See [ttspico/examples/make_wav.rs](ttspico/examples/make_wav.rs).

## Platforms
Pico was [originally part of Android](https://android.googlesource.com/platform/external/svox/+/refs/heads/master/pico/),
but it is written in portable C99 and works great on many other operating systems and platforms.

## License
Both Pico and the Rust bindings are licensed under the [Apache 2.0 license](LICENSE).
