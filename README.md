# Carrot Swap Game

Engage in a simple yet intriguing game of bluffing and decision-making with the Carrot Swap Game. This two-player game features boxes, each potentially containing a "carrot." As players, you'll exercise your wits to determine whether to stick with your box or swap it in the hopes of claiming the elusive "carrot." The game's ASCII graphics add a unique touch to the experience.

## How to Play

1. Run the program in a compatible environment.
2. Players take turns being the first and second player.
3. The first player looks into their box and decides whether to bluff or reveal the "carrot."
4. The second player, based on the first player's statement, decides whether to swap boxes or stay.
5. Reveal the contents of the boxes and determine the winner!

## Features

- A beginner-friendly game with simple rules and minimal loops.
- ASCII graphics enhance the gameplay experience.
- Encourages strategic thinking and bluffing.

## Instructions

1. Open a terminal or command prompt.
2. Navigate to the program's directory.
3. Run the program using `python carrot_swap_game.py`.
4. Follow the on-screen prompts to play the game.

## ASCII Graphics

Closed boxes:
```
  __________     __________
 /         /|   /         /|
+---------+ |  +---------+ |
|   RED   | |  |   GOLD  | |
|   BOX   | /  |   BOX   | /
+---------+/   +---------+/
```

An open, empty box:
```
   _________
  |         |
  |         |
  |_________|    __________
 /         /|   /         /|
+---------+ |  +---------+ |
|   RED   | |  |   GOLD  | |
|   BOX   | /  |   BOX   | /
+---------+/   +---------+/
```

An open box of carrots:
```
   ___VV____
  |   VV    |
  |   VV    |
  |___||____|    __________
 /    ||   /|   /         /|
+---------+ |  +---------+ |
|   RED   | |  |   GOLD  | |
|   BOX   | /  |   BOX   | /
+---------+/   +---------+/
```