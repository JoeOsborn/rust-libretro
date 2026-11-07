gisst-rust-libretro-sys
=================

Raw bindings to the libretro API (generated with bindgen).

[![libretro.h](https://img.shields.io/badge/libretro.h-9f7d0c7-informational?logo=RetroArch)](https://github.com/libretro/RetroArch/blob/9f7d0c7/libretro-common/include/libretro.h)

[![Build status](https://img.shields.io/github/actions/workflow/status/joeosborn/rust-libretro/main.yaml?branch=master)](https://github.com/joeosborn/rust-libretro/actions)
[![Latest version](https://img.shields.io/crates/v/gisst-rust-libretro-sys.svg)](https://crates.io/crates/gisst-rust-libretro-sys)
[![Documentation](https://docs.rs/gisst-rust-libretro-sys/badge.svg)](https://docs.rs/gisst-rust-libretro-sys)
![License](https://img.shields.io/crates/l/gisst-rust-libretro-sys.svg)

Vulkan Support
==============

This package provides optional support for the Vulkan bindings
provided in [`libretro_vulkan.h`](https://github.com/libretro/RetroArch/blob/master/libretro-common/include/libretro_vulkan.h).
Vulkan supported is gated behind the `vulkan` feature.
