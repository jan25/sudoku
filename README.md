# sūdoku

Sudoku puzzle written using React and Python for pregenerated puzzles.

The goal of Sudoku is to fill a 9×9 grid with numbers so that each row, column and 3×3 section contain all of the digits between 1 and 9.

Click here to solve puzzles 👉👉👉[jan25/sūdoku](https://jan25.github.io/sudoku) 👈👈👈 

<p align="center">
    <img src="demo.png" width="300" height="400">
</p>

## Develop

```bash
# Fork and clone repo
git clone https://github.com/jan25/sudoku.git
cd path/to/sudoku

# Local development
npm install
npm start

# Production build and test
npm run predeploy && <serve-build-assets-with-favorite-tool>

# Deploy to github pages
npm run deploy
```

## Coming up

- ~~Remove '0' number from empty cells~~
- ~~Highlight cell when dragging to drop~~
- ~~end of game: blinking numbers with 'Well Done' message. Also, with 'new game' button~~
- ~~Put numbers strip on all 4 sides of grid~~
- ~~Info dialog~~ fix console errors
- Deploy to gh pages on custom /sudoku folder
- Implement custom puzzle generator logic (e.g. https://dlbeer.co.nz/articles/sudoku.html)
- Mobile site support
- Add emojis around Well done message. or anywhere else
- Group puzzles in difficulty levels. And add chooser in UI
