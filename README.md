# Python Tic Tac Toe

A first Python learning project developed as a bootcamp milestone exercise.

It explores a two-player Tic Tac Toe game through functions, board state and interactive input. This is an early version with known game-logic and input-handling issues.

## Project contents

```text
Tic_Tac_Toe_Projekt.ipynb   # Step-by-step notebook
Tic_Tac_Toe_Projekt.py     # Python script containing the same exercise
```

Both files contain demonstration code as well as the main game loop. The script retains the notebook's demonstrations and introductory prompts.

## Game interaction

- Two human players choose X and O.
- The starting player is selected randomly.
- Players enter a board position from 1 to 9.
- A replay prompt allows another game.

Board positions follow this layout:

```text
7 | 8 | 9
--+---+--
4 | 5 | 6
--+---+--
1 | 2 | 3
```

## Requirements

- Python 3.
- IPython, used by the board-display function.
- Jupyter Notebook if using the notebook version.

## Open the notebook

The notebook is the original step-by-step format of the exercise.

Install the required packages if needed:

```sh
python -m pip install notebook ipython
```

From the repository root:

```sh
jupyter notebook Tic_Tac_Toe_Projekt.ipynb
```

Run the cells from top to bottom, responding to input prompts as they appear.

## Run the script

The script also requires IPython:

```sh
python -m pip install ipython
python Tic_Tac_Toe_Projekt.py
```

Demonstration output and an initial marker-selection prompt appear before the main game starts. The board uses IPython's output-clearing function, so its display may differ between a notebook and a terminal.

## Learning focus

- Functions and conditional logic.
- Representing a board with a list.
- Alternating turns and updating game state.
- Checking rows, columns and diagonals.
- Interactive input and replay loops.

## Current limitations

- Player two's victory check incorrectly uses player one's marker, so wins may be missed.
- Non-numeric position input can terminate the game.
- The script runs interactive code immediately, including when imported.
- The repository does not currently include automated tests.

These issues are tracked in [issue #1](https://github.com/FuscoJr/python-tic-tac-toe/issues/1).

## Licence

MIT. See [LICENSE](LICENSE).
