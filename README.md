# Prototype 1
### camera swapping and player controls
This is the first prototype in a series of 8 that I will be making over the next 32 days.

The purpose of this prototype is to figure out basic movement of 2d characters in a 3d environment
using state machines and user input.

## Goal
Create a working movement system that allows the player to control the character seamlessly
throughtout different camera positions.

## Features

### Character
Main character which moves and is animated in 4 directions. This is done through a sprite3d which is
locked facing the camera. Main character sprite is taken from Chrono Trigger.
### Environment
Everything in the game is modeled to scale with real world proportions. The environment was made in
Blender. Texture assets are taken from Half-Life 2.
### Camera Transitions
Implementing seamless camera transitions took up the most work on this prototype. The main hurdles
to get throught were:
 1. Orientating the player character's walking direction to always face the active camera.
 2. Continuing a the player character's walking direction while transitioning camera angles.
 3. Orientating the player character's sprites to always face the active camera.