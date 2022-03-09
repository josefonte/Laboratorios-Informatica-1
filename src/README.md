# Source Code

The code is divided in 5 parts:

## Tarefas & Supporting Scripts 
The Haskell scripts `Tarefa1.hs`,`Tarefa2.hs`,`Tarefa3.hs`,`Tarefa4.hs`,`Tarefa5.hs`,`Tarefa6.hs`,`Types.hs`,`FileUtils.hs`,`Main.hs`, `StatesModoNormal.hs` & `KillPacman.hs` are the backbone of the game. They are responsable for the following:

- Tarefa1.hs : Maze creator.
- Tarefa2.hs : Pacman & Ghost movement, interactions with foods, walls & tunnel.
- Tarefa3.hs : Compiling a map into instructions.
---
- Tarefa4.hs : React to time with ncurses library.
- Tarefa5.hs : Ghosts BOT, Escape and Chase Mode.
- Tarefa6.hs : Pacman BOT, Escape and Chase Mode.
---
- FileUtils.hs, Main.hs, Types.hs & StatesModeNormal.hs : Supporting scripts to the Tarefa_.hs scripts.
---
## Maps 
The file `Maps` contains the different `maps.txt` in available to play in the game.

## Visual Interface using Gloss
The Haskell script `Gamecomplete.hs` turnes the previous scripts into a visual interface using the Gloss library.

## Images used in the Visual Interface
The file `ImagensParaPacman` contains all the images used to generate the visual interface on the `GamesCompleted.hs` script.  

## Documentation on Haddock
The file `doc/html` contains the html compiled code from documentation made using Haddock. 
