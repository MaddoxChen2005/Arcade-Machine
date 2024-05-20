# Arcade Project Plan - Set up for Galaga

## Step 1 (1)
- Download Mame to Raspberry Pi to play games
## Step 2 - Assemble Hardware (3)
Materials: 
- Buttons
  - start with 1 button
  - 6 button layout can play all games
  - 2 more for 1st and 2nd player (not necessary)
  - Could use a breadboard (may not be necessary for one button)
  - code the buttons
- Joystick
  - one for each player (2 total)
  - Code the joysticks
  - attach using breadboard
- Monitor
  - facebook marketplace
  - Connect with HDMI
  - quality doesn't matter
- ~~Raspberry Pi~~
  - ~~2.5 amps for Pi3~~
  - ~~3.0 amps for Pi4~~
  - ~~Micro SD card (at least 8 GB)~~
- ~~Soldering gun~~
  - ~~heat shrink & wires~~
- Speakers
  - connected by the headphone jack
  - potentially connected with Bluetooth (depends on model)
  - Command to send audio to headphone jack: omxplayer /path/to/audio/file.wav
  - Command for python:
```
import pygame
pygame.mixer.init()
pygame.mixer.music.load("myFile.wav")
pygame.mixer.music.play()
while pygame.mixer.music.get_busy() == True:
    continue
```
- Test buttons with RetroPie game
  - Make sure the joystick works how intended
  - Make sure buttons are programmed for the right purpose
  - Find a simple program to test controls
## Step 2 - Build case (5)
- Make measurements
- Trace out cardboard
- box cutter
## Step 3 - Make a game (8)
- learn how to program a simple program using Gadot
- Run Gadot engine on Raspberry Pi
- Potentially use RetroPie
