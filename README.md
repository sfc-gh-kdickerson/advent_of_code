# Advent of Code Solutions

Solutions for [Advent of Code](https://adventofcode.com/) challenges in Python (2024) and Rust (2025).

## Project Structure

```
.
├── 2024/                    # Python solutions for AoC 2024
│   └── day_N/               # Each day's directory (day_1 through day_25)
│       ├── main.py          # Solution (or 1.py/2.py for parts)
│       ├── input.txt        # Puzzle input
│       └── sample.txt       # Sample input for testing
│
├── 2025/                    # Rust solutions for AoC 2025
│   ├── Cargo.toml           # Rust project manifest
│   ├── src/
│   │   ├── lib.rs           # Shared utilities
│   │   └── bin/             # Binary for each day (day01.rs - day12.rs)
│   └── input/
│       └── dayNN/           # Input files for each day
│           ├── input.txt
│           └── sample.txt
```

## Prerequisites

### 2024 (Python)
- Python 3.x
- No external dependencies (uses only standard library)

### 2025 (Rust)
- Rust toolchain (install via [rustup](https://rustup.rs/))
- Dependencies (managed automatically by Cargo):
  - `itertools` - Functional iteration utilities
  - `ordered-float` - Floating-point comparison support

## Running the Solutions

### 2024 Python Solutions

Navigate to a day's directory and run the Python script:

```bash
cd 2024/day_1
python main.py
```

Some days have separate files for Part 1 and Part 2:
```bash
python 1.py  # Part 1
python 2.py  # Part 2
```

### 2025 Rust Solutions

From the `2025/` directory:

```bash
cd 2025

# Build all solutions
cargo build --release

# Run a specific day
cargo run --release --bin day01

# Run tests
cargo test
```

## Input Files

Each solution expects an `input.txt` file in its respective input directory:
- **2024**: Place input in `2024/day_N/input.txt`
- **2025**: Place input in `2025/input/dayNN/input.txt`

Sample inputs for testing are provided in `sample.txt` files.

## Progress

| Year | Language | Days Completed |
|------|----------|----------------|
| 2024 | Python   | 25/25          |
| 2025 | Rust     | 12/25          |