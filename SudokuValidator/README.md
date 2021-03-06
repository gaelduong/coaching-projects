# Sudoku validator

## Provided resources

N/A

## Functional requirements

- Given a 2D array which represents a sudoku solution, write a function to validate whether or not it is a valid solution.
- Specifically, write the function `sudokuValidator` which takes in a 2D array `sudokuSolution` as input and returns `true` if it's a valid solution else `false` if it's an invalid solution.
- A sudoku is valid if and only if these 3 conditions are satisfied:
  - Each row must contain the digits 1-9 without repetition.
  - Each column must contain the digits 1-9 without repetition.
  - Each of the nine 3 x 3 sub-boxes of the grid must contain the digits 1-9 without repetition.

```javascript
const sudokuSolution = [
  [1, 2, 3, 4, 5, 6, 7, 8, 9],
  [4, 5, 9, 5, 1, 7, 3, 2, 9],
  [1, 7, 5, 4, 5, 6, 2, 8, 9],
  [4, 5, 9, 5, 1, 7, 3, 2, 9],
  [1, 2, 3, 4, 5, 6, 7, 8, 9],
  [7, 5, 9, 5, 1, 8, 3, 2, 9],
  [1, 3, 6, 7, 4, 8, 5, 9, 2],
  [9, 7, 4, 2, 1, 5, 6, 3, 8],
  [5, 2, 8, 6, 3, 9, 4, 1, 7],
];

const sudokuSolution2 = [
  [7, 9, 2, 1, 5, 4, 3, 8, 6],
  [6, 4, 3, 8, 2, 7, 1, 5, 9],
  [8, 5, 1, 3, 9, 6, 7, 2, 4],
  [2, 6, 5, 9, 7, 3, 8, 4, 1],
  [4, 8, 9, 5, 6, 1, 2, 7, 3],
  [3, 1, 7, 4, 8, 2, 9, 6, 5],
  [1, 3, 6, 7, 4, 8, 5, 9, 2],
  [9, 7, 4, 2, 1, 5, 6, 3, 8],
  [5, 2, 8, 6, 3, 9, 4, 1, 7],
];

sudokuValidator(sudokuSolution); // return false
sudokuValidator(sudokuSolution2); // return true
```

## Visual requirements

N/A

## Project Structure

(Recommended)

```bash
SudokuValidator
├── index.html
├── script.js
└── README.md
```

## Deployment

Deploy and host it on Netlify (hint: google "Netlify Drag and Drop"). Once deployed, include the URL in the Readme.

Link: [xxx].netlify.app

(user can test the code in the Console)

## Version Control

Make sure to use Git and host the source code on your personal Github.

## Skills assessed

### Javascript
