+++
title = "Trevi - a slightly overengineered plant watering device"
template = "page.html"
date = 2024-04-05T17:38:00Z
[taxonomies]
tags = ["projects", "embeded", "rust", "esp32"]
[extra]
summary = "A personal project of mine - a device that allows maintaing constaint soil moisture for a plant. Including a small OLED screen, web interface, persistent storage. Built in Rust on top of ESP32 platform using an excellent embasy suite."
mathjax = "tex-mml"
cover_image = "images/post-1/cover.jpg"
+++

# Background

It has all started with my first bonsai tree dying :(. It was not only my first bonsai tree, but actually the first plant I've truly attempted to take under my care every. Turns out that a sweet plum grown in a bonsai style can substantialy deteriorate when not watered for only a couple of days(for me it happened when I was on cross-country skiing vacation).

# The idea

I've wanted to get more into embedded programming for quite some time. I've completed a course that includeded embedded programming as part of my mechatronics degree, and built some projects back then, but that was a long time ago. On top of that I really wanted to explore the possibility of utilizing my favorite programming language - Rust - in this domain.

# The cheapest computer I've ever owned - ESP32 DevkitC

My platform of choice, that I've landed on by exploring Amazon listings and cross-referencing with Rust target support tables, came to be the ESP32 by Espressif. It has lots of IO pins, built in bluetooth(including BLE), WiFi and lots of other peripherals(clocks, ADCs etc.) I've bough a 3-pack of ESP32 DevKitC's manufactured by a German company called AZDelivery. The company maintains an extensive stock of various electonics equipment and components that it sells either directly through their website or through Amazon. I've chosen to go through Amazon for my purchase.
LINK TO AMAZON HERE AND MENTION THE PRICE

# no_std Rust on espressif ESP32 fork

I've mentioned going through Rust target support tables when looking for a platform for the project, but in reality Rust does not actually provide support for Xtensa architecture that the regular ESP32 is based on. How are we able to compile Rust code for ES32 then? The answer is a fork maintained by the microcontroller manufacturer - Espressif. The source code can be found on GitHub GITHUB LINK

# espup and other tools

# Bare metal vs IDF

# Eploring embassy

# Pump it up

```rust
fn main() {
  println!("test");
}
```

# Back to the physical world - interference

# esp32-hal or esp-hal and the bugs

# audio

# web gui

# development server for faster iteration

# persistent storage - my crate

# OLED display

# UI and state

# WiFI scanner and selection

# EDE design

# PCB design

# Physical PCB
