# wheel_of_random-
A Python game that generates numbers 1-100 in a random, non-repeating sequence using either a GUI button (tkinter) or command-line input, cycling through all numbers before restarting with a new random order.

# Random Number Sequence Game

A Python game that generates numbers from 1 to 100 in a random, non-repeating sequence. Available in two versions: GUI (tkinter) and command-line.

## Features
- Generates numbers 1-100 in a random order
- Ensures all numbers are used before repeating
- Two interfaces:
  - GUI version: Click a button to see the next number
  - CLI version: Enter 'n' for next number, 'q' to quit

## Requirements
- Python 3.x
- tkinter (usually included with Python) for GUI version

## How to Run
1. Clone the repository
2. Run either:
   - `python number_game_gui.py` for GUI version
   - `python number_game_cli.py` for command-line version

## Usage
- GUI: Click "Generate Number" button
- CLI: Type 'n' for next number, 'q' to exit
- Sequence resets with a new random order after all 100 numbers are used

## Files
- `number_game_gui.py`: GUI version with button interface
- `number_game_cli.py`: Command-line version with text input
