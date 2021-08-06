# CS50's Introduction to Artificial Intelligence with Python

## :warning: Important

This repository contains solutions to the CS50 AI projects. If you intend to take this course in the future, please read the [Academic Honesty policy](https://cs50.harvard.edu/ai/2020/honesty/) before viewing the solutions.

## Testcases

Each project contains a `test.py` and `unit_test.py` file which I've written while solving the problems. Feel free to use it and test your own solutions!

## Table of Contents

| Week                                           | Lecture                                     | Concept                                                                                  | Name                                           | Description                                                                                                                                       |
| ---------------------------------------------- | ------------------------------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| [0](https://cs50.harvard.edu/ai/2020/weeks/0/) | [Search](https://youtu.be/WbzNRTTrX0g)      | [BFS](https://cs50.harvard.edu/ai/2020/notes/0/#breadth-first-search)                    | [Degrees](lec0/degrees/degrees.py)             | [Determine how many “degrees of separation” apart two actors are.](https://cs50.harvard.edu/ai/2020/projects/0/degrees/)                          |
| [0](https://cs50.harvard.edu/ai/2020/weeks/0/) | [Search](https://youtu.be/WbzNRTTrX0g)      | [Minimax](https://cs50.harvard.edu/ai/2020/notes/0/#minimax)                             | [Tic-Tac-Toe](lec0/tictactoe/tictactoe.py)     | [Implement an AI to play Tic-Tac-Toe optimally.](https://cs50.harvard.edu/ai/2020/projects/0/tictactoe/)                                          |
| [1](https://cs50.harvard.edu/ai/2020/weeks/1/) | [Knowledge](https://youtu.be/HWQLez87vqM)   | [Model Checking](https://cs50.harvard.edu/ai/2020/notes/1/#inference)                    | [Knights](lec1/knights/puzzle.py)              | [Solve the "Knights and Knaves" puzzles using AI.](https://cs50.harvard.edu/ai/2020/projects/1/knights/)                                          |
| [1](https://cs50.harvard.edu/ai/2020/weeks/1/) | [Knowledge](https://youtu.be/HWQLez87vqM)   | [Knowledge Engineering](https://cs50.harvard.edu/ai/2020/notes/1/#knowledge-engineering) | [Minesweeper](lec1/minesweeper/minesweeper.py) | [Implement an AI to play Minesweeper optimally.](https://cs50.harvard.edu/ai/2020/projects/1/minesweeper/)                                        |
| [2](https://cs50.harvard.edu/ai/2020/weeks/2/) | [Uncertainty](https://youtu.be/D8RRq3TbtHU) | [Bayesian Networks](https://cs50.harvard.edu/ai/2020/notes/2/#bayesian-networks)         | [Heredity](lec2/heredity/heredity.py)          | [Write an AI to assess the likelihood that a person will have a particular genetic trait.](https://cs50.harvard.edu/ai/2020/projects/2/heredity/) |
| [2](https://cs50.harvard.edu/ai/2020/weeks/2/) | [Uncertainty](https://youtu.be/D8RRq3TbtHU) | [Markov Models](https://cs50.harvard.edu/ai/2020/notes/2/#markov-models)                 | [PageRank](lec2/pagerank/pagerank.py)          | [Write an AI to rank web pages by importance.](https://cs50.harvard.edu/ai/2020/projects/2/pagerank/)                                             |

## How to Run Tests

1. Make sure you have [Python3](https://www.python.org/downloads/) installed in your machine.
    - (My version: `Python 3.9.5`, but anything above `Python 3.4` should work too.)
2. Install `pytest` by running `pip install pytest` in a terminal.
    - More information about `pip` [here](https://realpython.com/what-is-pip/).
3. Make a copy of the test file and paste it in the same folder as the project that you want to test.
    - For example, if you want to test your code for `degrees.py`, make a copy of `degrees_test.py` in the same folder as your `degrees.py` and other files that came along with the project, like `util.py`, `large/` and `small/`.
4. From your terminal, navigate to the project folder and run `pytest` or `pytest <project>_test.py`.
    - For example, navigate to `degrees/` and run `pytest` or `pytest degrees_test.py`.

## Useful pytest Flags

- Run `pytest -s` to show print statements in the console
- Run `pytest -vv` for verbose mode
- Install `pyrepeat` with `pip` and then run `pytest --count n` to repeat the test for n times
