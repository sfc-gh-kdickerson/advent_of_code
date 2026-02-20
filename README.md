# Advent of Code Solutions

My solutions for [Advent of Code](https://adventofcode.com/) programming challenges.

## About Advent of Code

Advent of Code is an annual set of Christmas-themed programming puzzles that runs from December 1st to December 25th. Each day features a two-part problem that tests algorithmic thinking and problem-solving skills.

## Repository Structure

```
.
├── 2024/           # Python solutions
│   ├── day_1/
│   │   ├── main.py or 1.py, 2.py
│   │   └── input.txt
│   ├── day_2/
│   │   └── ...
│   └── ...
└── 2025/           # Rust solutions
    ├── src/
    │   ├── bin/
    │   │   ├── day01.rs
    │   │   ├── day02.rs
    │   │   └── ...
    │   └── lib.rs
    ├── input/
    │   ├── day01
    │   ├── day02
    │   └── ...
    └── Cargo.toml
```

## Progress

### 2024 (Python)

| Day | Part 1 | Part 2 |
|-----|--------|--------|
| 1-25 | ✅ | ✅ |

All 25 days completed!

### 2025 (Rust)

| Day | Part 1 | Part 2 |
|-----|--------|--------|
| 1-12 | ✅ | ✅ |

12 days completed so far.

## Running the Solutions

### Prerequisites

- **Python 3.x** for 2024 solutions
- **Rust** (latest stable) for 2025 solutions

### 2024 (Python)

Navigate to a day's directory and run the solution:

```bash
cd 2024/day_1
python main.py
# or
python 1.py  # Part 1
python 2.py  # Part 2
```

Each day expects an `input.txt` file in the same directory containing your puzzle input.

### 2025 (Rust)

From the `2025` directory:

```bash
cd 2025

# Build all solutions
cargo build --release

# Run a specific day
cargo run --release --bin day01
cargo run --release --bin day02
# etc.
```

Input files are stored in `2025/input/` and are read automatically by each solution.

## Dependencies

### 2024 (Python)

- Python standard library (collections, etc.)

### 2025 (Rust)

- `itertools` - Extended iterator functionality
- `ordered-float` - Orderable floating point types

## Getting Your Puzzle Input

1. Log in to [adventofcode.com](https://adventofcode.com/)
2. Navigate to the puzzle for the day you want to solve
3. Copy your personal puzzle input
4. Save it to the appropriate location:
   - **2024**: `2024/day_X/input.txt`
   - **2025**: `2025/input/dayXX`

## License

This project contains personal solutions to Advent of Code puzzles. Puzzle descriptions and inputs are copyrighted by [Advent of Code](https://adventofcode.com/).

## Acknowledgments

Thanks to [Eric Wastl](http://was.tl/) for creating Advent of Code!
