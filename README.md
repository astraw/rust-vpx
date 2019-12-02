# env-libvpx-sys

![](https://github.com/astraw/env-libvpx-sys/workflows/Build%20and%20Run/badge.svg)

Rust bindings to libvpx.

Allows encoding of VP9 video frames, and together with
[WebM](https://crates.io/crates/webm-native), creation of WebM video files.

Supports system-wide installations of libvpx. Includes bundled FFI for a few
versions of libvpx. You can also enable `generate` feature of this crate to
generate FFI on the fly for a custom version of libvpx.
