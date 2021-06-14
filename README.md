# Tik Tac Toe

This repository holds a very simple implementation of the `Tik Tac Toe` game.

The game has a bug - it does not recognise when it is over and who wins.

### Development

Open the `index.html` file in your browser to see and play the game.

### Task

Your task is is to fix the bug by implementing the `gameWinner` function which is located in the [gameWinner.js](./gameWinner) file.

The input is a matrix with the current game state. Its size is 3x3. In each cell there are only 3 possible values - `0`, `x`
and `o`. `0` means the cell was not used.

The result of the function should be one of the following:

- `x` if the player using the `x` won
- `o` if the player using the `o` won
- `draw` if the game is a draw
- null if there is no winenr and the game is not over yet.
