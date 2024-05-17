# Arcade Project Plan - Set up for Galaga

## Step 1 - Assemble Hardware
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
- Raspberry Pi
  - 2.5 amps for Pi3
  - 3.0 amps for Pi4
  - Micro SD card (at least 8 GB)
- Soldering gun
  - heatshrink & wires
- Speakers
  - connected by the headphone jack
  - potentially connected with bluetooth (depends on model)
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
## Step 2 - Build case
- Make measurements
- Trace out cardboard
- box cutter
## Step 3 - Make a game
- learn how to program a simple program using Gadot
- Run Gadot engine on Raspberry Pi
- Potentially use RetroPie
## Step 4 
- Download Mame to Raspberry Pi to play games
