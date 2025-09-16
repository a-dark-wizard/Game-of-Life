# Game-of-Life
## A Python implementation of John Conway's classic cellular automaton Game of Life

This code implements game of life with variable start patterns and update speed.

The rules for the Game of Life are as follows,

For a cell that is alive:
- Any cell with one or no neighbors dies - Isolation.
- Any cell with four or more neighbors dies - Overpopulation.
- Any cell with two or three neighbors survives - Survival.

For a cell that is dead:
- Any cell with three neighbors becomes alive - Reproduction.

### Dependencies (pip install)
```
pygame
pygame-menu==1.96.1
```
### Usage

```
python3 game_of_life.py
```

#### Main Menu

The Main Menu allows the players to navigate to Play Menu and the Help and About Menus. The Help Menu details the game controls while About Menu lists game information.

<p align="center">
  <img width="640" height="480" src="https://raw.githubusercontent.com/a-dark-wizard/Game-of-Life/master/Images/Main_Menu.png" alt="Main Menu">
</p>

#### Play Menu

In the Play Menu, players can change start pattern and the game update delay. Start patterns that can be chosen are 'Glider', 'Beacon', 'Toad','Blinker', 'Tetromino', 'Pulsar', 'Light Weight Spaceship', 'Copperhead Spaceship', 'Weekender', 'Gosper Glider Gun' and 'Random'. The game update delay is given in ms with smaller values causing the game to update faster. 

<p align="center">
  <img width="640" height="480" src="https://raw.githubusercontent.com/a-dark-wizard/Game-of-Life/master/Images/Play_Menu.png" alt="Play Menu">
</p>

#### In-Game Screenshot

Pulsar

<p align="center">
  <img width="640" height="480" src="https://raw.githubusercontent.com/a-dark-wizard/Game-of-Life/master/Images/Pulsar.png" alt="Pulsar">
</p>

Gosper Glider Gun

<p align="center">
  <img width="640" height="480" src="https://raw.githubusercontent.com/a-dark-wizard/Game-of-Life/master/Images/Glider_Gun.png" alt="Glider Gun">
</p>
