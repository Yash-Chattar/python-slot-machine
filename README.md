# Python Slot Machine 🎰

A simple terminal-based slot machine game built with Python. The player deposits money, chooses how many lines to bet on, places a bet, and spins the reels to try to win.

## Features

- Deposit money to start playing.
- Choose the number of lines to bet on.
- Set a bet amount for each line.
- Generate random slot machine results.
- Check winning lines automatically.
- Calculate winnings based on symbol values.
- Track your balance after each spin.
- Quit the game whenever you want.

## How It Works

The game generates a 3 × 3 grid of symbols. Each symbol has a different frequency and payout value.

| Symbol | Frequency | Payout Multiplier |
|---|---:|---:|
| A | 2 | 5× |
| B | 4 | 4× |
| C | 6 | 3× |
| D | 8 | 2× |

A winning line contains the same symbol across all three columns. The payout is calculated using the symbol's multiplier and the bet amount per line.

## Requirements

- Python 3.8 or later
- No external libraries required

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/python-slot-machine.git
```

### 2. Navigate to the project directory

```bash
cd python-slot-machine
```

### 3. Run the game

```bash
python main.py
```

If your system uses `python3` instead, run:

```bash
python3 main.py
```

## What I Learned

This project helped me practise:

- Python functions and loops
- Lists and nested lists
- Dictionaries
- Random selection
- Input validation
- Returning multiple values from functions
- Working with `enumerate()`
- Checking winning conditions
- Managing a running balance

## Future Improvements

- Add diagonal winning lines.
- Improve the terminal interface.
- Add a spin animation.
- Write unit tests for the payout logic.

## Disclaimer

This is a learning project intended for local gameplay and Python practice. It does not involve real-money gambling.