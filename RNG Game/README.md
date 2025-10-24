# RNG Game

## Overview
A lightweight **Rust** console game where you guess a secret number between 1 and 100.  
The program gives “too high” / “too low” hints, counts your attempts, and lets you play again.

## Features
- Secure random generation with the `rand` crate (`ThreadRng`).
- Robust input parsing with detailed error messages.
- Clear hint system.
- Replay loop.
- Minimal, idiomatic Rust code.

## Requirements
- Rust 1.56+ (`rustc`, `cargo`)

## Quick Start
```bash
git clone https://github.com/elmoxbt/TurbinePB_Q425_elmoxbt.git
cd TurbinePB_Q425_elmoxbt/RNG\ Game
cargo run --release

# Project Structure

RNG Game/
├── Cargo.toml      # Dependencies (rand)
├── src/
│   └── main.rs     # Game logic: RNG, input loop, replay
└── README.md

# Build and Run Manually

cargo build --release
./target/release/rng_game   # (or rng_game.exe on Windows)

# Contributing
Fork → improve → open a PR.
Ideas: difficulty tiers, guess history, GUI with crossterm.

#License
MIT
