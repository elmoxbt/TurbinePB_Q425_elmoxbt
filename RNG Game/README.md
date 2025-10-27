# RNG Game

This directory contains early Rust learning projects focused on basic game logic, user input, and Rust fundamentals.

## Projects

### 1) hello-cargo
Minimal "Hello, World!" app demonstrating Cargo basics.
- Create/build/run with Cargo
- Project layout and `Cargo.toml`

Run:
```bash
cd "RNG Game"/hello-cargo
cargo run
```

### 2) Rust-Guessing-Game
Console-based number guessing game (1–100) using the `rand` crate.
- Random number generation
- Input parsing and error handling
- Hints: "too high" / "too low"
- Replay loop

Run:
```bash
cd "RNG Game"/Rust-Guessing-Game
cargo run --release
```

### 3) counter
Simple counting game showcasing loops and conditionals.

Run:
```bash
cd "RNG Game"/counter
cargo run
```

## Requirements
- Rust 1.56+ (`rustc`, `cargo`)

## Structure
```
RNG Game/
├── hello-cargo/
├── Rust-Guessing-Game/
└── counter/
```

## Contributing
Fork → improve → open a PR.
Ideas: difficulty tiers, guess history, GUI with `crossterm`.

## License
MIT
