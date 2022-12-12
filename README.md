# Project 01 For NeXT CS
### Class Period:
### Name0: YOUR NAME HERE
### Name1: OTHER NAME HERE (delete this line if you are working solo)
---


Your mission is to recreate one of these two classic arcade games:
- Breakout/Arkanoid [demo 0](https://elgoog.im/breakout/)  [demo 1](https://www.crazygames.com/game/atari-breakout)
- Space Invaders [demo 0](https://elgoog.im/space-invaders/) [demo 1](https://www.crazygames.com/game/space-invaders)

This project will be completed in phases. The first phase will be to work on this document. Use makrdown formatting. For more markdown help [click here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) or [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)


---

## Phase 0: Game Selection, Analysis & Plan

#### Selected Game: Breakout

### Necessary Features
What are the core features that your game should have? These should be things that __must__ be implemented in order to make the game playable, not extra features that could be added to make the game more fun to play.

Paddle
Ball
Bricks
Ball bounce
Bricks disappear 
Different areas of the paddle bounce differently

### Extra Features
What are some features that are not essential to gameplay, but you would like to see (provided you have time after completing the necessary features.
 
Multiple lives
The paddle breaks
Bricks move in the opposite direction of the paddle


### Controls
How will your game be controlled? If the mouse will be used, explain how. List all keyboard commands as well.

Keyboard Commands:
- Arrow keys move the bricks
- Spacebar start/stop the game

Mouse Conrol:
- Mouse movement: Mouse controls the paddle
- Mouse pressed: Spawn another ball (3x per game)


### Classes
What classes will you be creating for this project? Include the instance variables and methods that you believe you will need. You will be required to create at least 2 different classes. If you are going to use classes similar to those we've made for previous assingments, you will have to add new features to them.

Bricks
- Instance variables: 
  - Brickx, Bricky
  - Brick velocity
  - Brick alive/dead
  - Brick color
  - Brick health
- METHODS
  - reset
  - set color

Ball
- Instance variables:
  - Ballx, Bally
  - Ballxvel, Ballyvol

- METHODS
  - Speed up
  - Change direction
  - Collision check
Paddle
- Instance variables:
  - Paddlex, paddley
  - Paddle width/height
- Methods
  - Paddle move
  - Paddle area collision check
  
  
