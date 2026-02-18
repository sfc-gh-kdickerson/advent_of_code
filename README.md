# Advent of Code Solutions

Personal solutions for [Advent of Code](https://adventofcode.com/) challenges.

## Project Structure

```
.
├── 2024/                    # Year 2024 solutions (Python/Go)
│   ├── day_1/
│   │   ├── main.py          # Solution (early days use main.py)
│   │   ├── input.txt        # Puzzle input
│   │   └── sample.txt       # Sample test case
│   ├── day_6/
│   │   ├── 1.py             # Part 1 solution (later days use numbered files)
│   │   ├── 2.py             # Part 2 solution
│   │   ├── input.txt
│   │   └── test.py          # Tests
│   └── ...                  # Days 1-25
│
├── 2025/                    # Year 2025 solutions (Rust)
│   ├── Cargo.toml           # Rust package manifest
│   ├── src/
│   │   ├── lib.rs           # Shared utilities (input reading, etc.)
│   │   └── bin/
│   │       ├── day01.rs     # Day 1 solution
│   │       ├── day02.rs     # Day 2 solution
│   │       └── ...          # Additional days
│   └── input/
│       ├── day01/
│       │   ├── input.txt    # Puzzle input
│       │   └── sample.txt   # Sample test case
│       └── ...              # Input for each day
│
├── __init__.py              # Python package indicator
└── README.md
```

### Organization

**By Year:** Each year has its own directory with solutions for all 25 days.

**2024 (Python/Go):**
- Each day is a separate directory (`day_1`, `day_2`, etc.)
- Solutions are Python scripts (`main.py` or `1.py`/`2.py` for parts 1 and 2)
- Some days include Go implementations
- Input and sample files are stored alongside solutions

**2025 (Rust):**
- Structured as a Cargo project
- Solutions are binary crates in `src/bin/` (e.g., `day01.rs`)
- Shared utilities in `src/lib.rs`
- Input files are centralized in the `input/` directory
- Run solutions with `cargo run --bin dayXX`