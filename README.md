# Slot Machine Game

A Python-based slot machine game with betting, spinning, and winning detection features.

## Features

- **Deposit System**: Start with a deposit of any amount
- **Multiple Betting Lines**: Choose to bet on 1-3 lines
- **Flexible Betting**: Bet between $1-$100 per line
- **Symbol System**: 4 different symbols (A, B, C, D) with varying frequencies and values
- **Visual Display**: See your slot machine results in a grid format
- **Winning Detection**: Automatic detection of winning combinations
- **Balance Tracking**: Keep track of your money throughout the game
- **Game Loop**: Continue playing until you quit or run out of money

## Symbol Values

| Symbol | Frequency | Value (Bet Multiplier) |
|--------|-----------|------------------------|
| A      | 2         | 5x                     |
| B      | 4         | 4x                     |
| C      | 6         | 3x                     |
| D      | 8         | 2x                     |

## How to Play

1. **Start the Game**: Run `python main.py`
2. **Deposit Money**: Enter the amount you want to start with
3. **Choose Lines**: Select how many lines to bet on (1-3)
4. **Set Bet**: Choose your bet amount per line ($1-$100)
5. **Spin**: Watch the slot machine spin and see your results
6. **Collect Winnings**: If you get matching symbols across a line, you win!
7. **Continue or Quit**: Keep playing or quit when ready

## Winning Rules

- Match the same symbol across all columns in a line to win
- Winnings = Symbol Value × Bet Amount
- You can win on multiple lines simultaneously
- Example: Betting $10 on line 1 and getting three A's = $50 win (5×$10)

## Requirements

- Python 3.6 or higher
- No additional dependencies required (uses only built-in Python modules)

## Installation

1. Clone or download this repository
2. Navigate to the project directory
3. Run the game: `python main.py`

## Game Controls

- **Enter**: Spin the slot machine
- **q**: Quit the game
- **Any other key**: Continue playing

## Example Game Session

```
How much would you like to deposit? $100
Enter the number of lines to bet on (1-3)? 2
What would you like to bet on each line? $5

You are betting $5 on 2 lines. Total bet is equal to: $10

A | B | C
D | A | B
C | D | A

You won $25!
You won on lines: 1

Current balance is $115
Press enter to play (q to quit).
```

Enjoy playing the slot machine game! 