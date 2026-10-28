# Sudoku Solver

A Sudoku solver written in Python, using a backtracking algorithm.

## About The Project

The Sudoku Solver can solve any grid. The grid is typed manually as a list of lists. It uses a backtracking method, selecting the first valid option for every cell and moving to the next one. When a cell has no valid option, the program goes back to the previous cell until a valid option is found, then moves forward again.

### Built With

- Python 3

## Getting Started

Run the solver with Python 3:

```sh
python sudoku-solver.py
```

The grid is defined directly in the script as a list of lists.

## Notes

The following notes are from the original README:

- This was the author's first Python project, written three days after starting to learn programming. It was written without any external libraries.
- An update (02/05/2020) reworked the project into a more efficient and more pythonic version. The old version, which includes a detailed Jupyter Notebook, is available on the `archive` branch.

## Status

Completed (per the original README).

## License

No license file is present in this repository.
