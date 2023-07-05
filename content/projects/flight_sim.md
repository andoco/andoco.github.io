+++
title = "Flight simulation using Rust and Bevy"
date = 2023-07-02

[taxonomies]
tags = ["rust", "bevy", "game"]

[extra]
thumbnail = "flight-sim-bevy-rust.png"
+++

A basic flight simulation written using the [Bevy](https://bevyengine.org/) game engine in [Rust](https://www.rust-lang.org/).

The simulation features an airplane that can take off and navigate an endless cityscape. Flight dynamics are modelled using wing lift coefficient curves.

<!-- more -->

{{ image(path="flight-sim-bevy-rust.png") }}

It is compiled to WASM and available to play online in your browser.

{{ button(label="Launch flight sim", url="/flight-sim-bevy-rust") }}
