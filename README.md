# The Maze Game [![Build Status](https://travis-ci.org/dubzzz/node-maze-game.svg)](https://travis-ci.org/dubzzz/node-maze-game)[![Coverage Status](https://coveralls.io/repos/dubzzz/node-maze-game/badge.svg?branch=master&service=github)](https://coveralls.io/github/dubzzz/node-maze-game?branch=master)

Puzzle-game where the solver as to find a path from departure to end in limited amount of mouvments.

The grid is composed of four types of cells:
- Path: can walk on it
- Wall: cannot walk on it
- Door: need to be opened by reaching their corresponding button. Once reached doors will stay opened for a limited number of round so the player need to move fast. During the last round, if the player moves towards door it will stay open one extra round (door cannot be closed when player is on it)
- Reversed: hidden door that appear when the user push its corresponding button
- Button: a button can open one or several doors. Different buttons can open different sets of doors
