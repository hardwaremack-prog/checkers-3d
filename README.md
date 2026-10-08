# Checkers 3D

Checkers on a 3D tabletop: a walnut and maple board, cream and onyx pieces, and a computer opponent that never keeps you waiting. Built with three.js.

![Checkers 3D screenshot](<Checkers 3D - screenshot.png>)

## How to play

You play cream; the walnut side moves on its own a moment after your turn.

1. Click one of your pieces. Its legal moves light up with green rings.
2. Click a lit square to move there.

| Mouse | Action |
|---|---|
| Drag | Orbit the camera around the table |
| Scroll | Move closer or farther |
| Click | Select a piece or make a move |

## Rules the game enforces

- Standard American checkers, and illegal moves are blocked
- Captures are mandatory, and multi-jumps must be finished with the same piece
- Pieces that reach the far row are crowned and move in all four diagonals
- Win by taking every enemy piece or leaving the other side with no legal move

## Run it

Download `checkers-3d.html` and open it in your web browser. No install, no account, nothing to set up.

The full guide is in `checkers-3d-manual.pdf`.

---
Made by hardwaremack.
