# Advent of Code Solutions

My solutions for [Advent of Code](https://adventofcode.com/) puzzles.

## Structure

### 2024 (Python)

Solutions implemented in Python. Each day has its own directory with solution files.

```
2024/
  day_X/
    main.py or 1.py/2.py  - Solution code
    input.txt             - Puzzle input
    sample.txt            - Sample input for testing
```

### 2025 (Rust)

Solutions implemented in Rust using Cargo workspace.

```
2025/
  src/bin/dayXX.rs        - Day solutions
  input/dayXX/            - Inputs (input.txt, sample.txt)
  Cargo.toml              - Package configuration
```

Run a specific day:
```bash
cd 2025
cargo run --bin day01
```

### 2026 (Rust)

Solutions for 2026 using the same Rust structure as 2025.

```
2026/
  src/bin/dayXX.rs        - Day solutions
  input/dayXX/            - Inputs (input.txt, sample.txt)
  Cargo.toml              - Package configuration
```

Run a specific day:
```bash
cd 2026
cargo run --bin day01
```