# Birthday Paradox Analysis

**Note:** This is a learning project for exploring and analyzing the birthday paradox phenomenon.

## Overview

The [birthday paradox](https://en.wikipedia.org/wiki/Birthday_problem) is a fascinating probability concept that demonstrates how likely it is for at least two people in a group to share the same birthday. Despite intuition suggesting this would be rare, it actually occurs with surprisingly high probability in relatively small groups (e.g., ~50% chance with just 23 people).

This project explores the birthday paradox through data analysis and visualization using Python, featuring:

- **Sample data simulations** across various group sizes
- **Analysis of shared birthday occurrences** in different population sizes
- **Probability exploration** through empirical data

## Project Structure

```
├── analysis.ipynb                    # Main Jupyter notebook for analysis
├── data/
│   └── birthday_paradox_sample.csv  # Sample data from simulated trials
├── pyproject.toml                   # Project configuration
└── README.md                        # This file
```

## Data Description

The `birthday_paradox_sample.csv` contains simulation results with the following fields:

- **trial**: Trial number
- **group_size**: Number of people in the group
- **birthdays**: List of birthday values (day of year) for each person in the group
- **shared_birthday**: Binary indicator (1 if at least two people shared a birthday, 0 otherwise)
- **shared_day**: The day of the year where the birthday was shared (if applicable)

## Getting Started

### Requirements

- Python >= 3.11

### Installation

```bash
# Install dependencies with uv
uv sync
```

## Learning Objectives

This project is designed to practice:

- Data analysis with Python
- Working with probability and statistics
- Jupyter notebook workflows
- CSV data handling and exploration
- Visualization of statistical findings

## References

- [Birthday Problem - Wikipedia](https://en.wikipedia.org/wiki/Birthday_problem)
- [The Birthday Paradox Explained](https://www.britannica.com/story/what-is-the-birthday-paradox)
