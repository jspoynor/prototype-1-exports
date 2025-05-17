# Prototype 1
### movement-and-interactions-physics
This is the first prototype in a series of 8 that I will be making over the next 32 days.

The purpose of this prototype is to figure out basic movement of 2d characters in a 3d environment
using state machines and user input. 


## Goals
1. Create a working state machine that can perform the same movements on several characters, including 
the player character.
2. The movement system doesn't have to necessarily be intuitive. But it should be satisfying to use 
after a few minutes of gameplay.
3. Have the player able to move through several different rooms (scenes). With minimal loading time.

## Features

### Character
Main character which moves and is animated in 4 directions. This is done through a sprite3d which is
locked facing the camera

### Environment
Everything in the game is modeled to scale with real world proportions. The environment was made in
Blender.