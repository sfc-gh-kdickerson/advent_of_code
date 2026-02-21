# Advent of Code Solutions

Personal solutions for [Advent of Code](https://adventofcode.com/) programming challenges.

## Overview

This repository contains solutions to Advent of Code puzzles:

| Year | Language | Progress |
|------|----------|----------|
| 2024 | Python | 25/25 days |
| 2025 | Rust | 12/25 days |

## Repository Structure

```
.
├── 2024/                    # Python solutions for AoC 2024
│   ├── day_1/
│   │   ├── main.py          # Solution code
│   │   └── input.txt        # Puzzle input
│   ├── day_2/
│   └── ...                  # Days 1-25
│
└── 2025/                    # Rust solutions for AoC 2025
    ├── Cargo.toml           # Rust project configuration
    ├── src/
    │   ├── lib.rs           # Shared utilities (input reading)
    │   └── bin/
    │       ├── day01.rs     # Solution for day 1
    │       ├── day02.rs     # Solution for day 2
    │       └── ...
    └── input/
        ├── day01/
        │   ├── input.txt    # Puzzle input
        │   └── sample.txt   # Sample input for testing
        └── ...
```

## Prerequisites

### Python (2024 Solutions)
- Python 3.8 or higher
- No external dependencies (uses standard library only)

### Rust (2025 Solutions)
- Rust 1.75 or higher (2024 edition)
- Cargo package manager

**Dependencies** (automatically installed via Cargo):
- `itertools` - Extended iterator utilities
- `ordered-float` - Ordered floating-point types

## Getting Started

### Running Python Solutions (2024)

```bash
# Navigate to a specific day
cd 2024/day_1

# Run the solution
python main.py
```

Each day's directory contains:
- `main.py` - The solution code (often with Part 1 and Part 2)
- `input.txt` - The puzzle input

### Running Rust Solutions (2025)

```bash
# Navigate to the 2025 directory
cd 2025

# Build all solutions
cargo build --release

# Run a specific day
cargo run --bin day01
cargo run --bin day02
# ... etc
```

To run with sample input instead of the full input, modify the `InputType` in the solution file:
```rust
let buf = read_input(1, &Sample);  // Use sample input
let buf = read_input(1, &Input);   // Use full input (default)
```

## Solution Approach

Each solution typically includes:
- **Part 1**: Initial puzzle solution
- **Part 2**: Extended/modified puzzle (often commented or separated)

Solutions prioritize:
1. Correctness - Getting the right answer
2. Readability - Clear, understandable code
3. Efficiency - Reasonable runtime for the given inputs

## Adding Your Own Input

Advent of Code provides unique inputs for each user. To use your own inputs:

### For Python (2024)
1. Navigate to the day's directory
2. Replace the contents of `input.txt` with your input

### For Rust (2025)
1. Navigate to `2025/input/dayXX/`
2. Replace `input.txt` with your input
3. Optionally add `sample.txt` for testing

## Resources

- [Advent of Code](https://adventofcode.com/) - Official website
- [Advent of Code Subreddit](https://www.reddit.com/r/adventofcode/) - Community discussion
- [Rust Documentation](https://doc.rust-lang.org/) - Rust language reference
- [Python Documentation](https://docs.python.org/3/) - Python language reference

## License

This repository contains personal solutions to Advent of Code puzzles. Feel free to use them for learning and reference.

**Note**: Puzzle descriptions and inputs are copyrighted by Advent of Code and are not included in this repository's license.
