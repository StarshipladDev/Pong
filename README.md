# Pong pure C application Cosc345

## Description

A simle Pong application. Install required libraries, then run the application from a console.

## Current features:

> Customizable player paddles

> Changeable difficulties

> Several game-changing power ups

> Two game modes - normal and 'doubles'

> Several funky background tracks

> Useful hotkeys (See 'info' screen on homepage)

# Developer Documentation and designs/worklogs located in the 'Documents' folder

# Required first time steps:

Uncompress all the files in the 'sounds' folder back into the 'sounds'folder as their uncompressed versions

Go into the SDL2_image2.0.4 ,SDL2_mixer-2.0.4 and SDL2-2.0.9 .dmg files using an explorer, and move each of the .framework files inside them to your
computer's '/Library/Frameworks/' folder.

# To compile the Final build:

'gcc pong.c -F/Library/Frameworks/SDL2.framework/Headers -framework SDL2 -F/Library/Frameworks/SDL2_image.framework/Headers -framework SDL2_image -F/Library/Frameworks/SDL2.framework/Headers -framework SDL2_mixer -o pong'

from a terminal window open in the 'pong' folder



# To run the Final build:

In a terminal window that is currently in the 'pong' folder containing the pong.c file:

'./pong' 