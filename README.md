# Pong pure C application Cosc345

## Description

A simle Pong application. Install required libraries, then run the application from a console.

## Current features:

> Customizable player paddles
> Changeable difficulties
> Several game-changing power ups

# Developer Documentation and designs/worklogs located in the 'Documents' folder

# Required first time steps:

Go into the SDL2_image2.0.4 and SDL2-2.0.9 .dmg files using an explorer, and move each of the .framework files inside them to your
computer's '/Library/Frameworks/' folder.

# To compile the Beta build:

'gcc pong.c -F/Library/Frameworks/SDL2.framework/Headers -framework SDL2 -F/Library/Frameworks/SDL2_image.framework/Headers -framework SDL2_image -o pong'

from a terminal window open in the 'pong' folder



# To run the Beta build:

In a terminal window that is currently in the 'pong' folder containing the pong.c file:

'./pong/pong' 