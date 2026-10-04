# Chass

The website is organized into three files:

- `index.html` contains the page structure.
- `styles.css` contains the layout and visual styles.
- `game.js` contains the game rules, engine, and interface behavior.

Use **Save game** to download a JSON save file. Use **Load game** to restore it later; saves include the current position, move history, mode, and undo history.

En voyant is a one-turn capture opportunity created when a bought pawn is placed horizontally beside an opposing pawn. The adjacent pawn captures diagonally forward beyond it and removes the bought pawn.
