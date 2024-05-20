# Arcade Project Plan - Set up for Galaga

## Step 1 - Download Emulator (1)
- Download Mame to Raspberry Pi to play games
- Time: 1 Hour
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
Link for Buttons & Joysick: https://odseven.com/products/odseven-2-player-arcade-buttons-and-joystick-diy-controller-kit-wholesale?pr_prod_strat=e5_desc&pr_rec_id=9213122a7&pr_rec_pid=1442703441975&pr_ref_pid=1442707013687&pr_seq=uniform
- Monitor
  - Facebook Marketplace
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
    - Link for speakers: https://www.logitech.com/en-us/products/speakers/s120-slim-lightweight-stereo.980-000012.html
    - Test sound
- Test buttons with RetroPie game
  - Make sure the joystick works how intended
  - Make sure buttons are programmed for the right purpose
  - Find a simple program to test controls
  - 
## Step 3 - Build case (5)
- Make measurements
- Trace out cardboard
- box cutter
## Step 4 - Make a game (8)
### Step 4a - Gadot Tutorial
- https://www.youtube.com/watch?v=LOhfqjmasi0
### Step 4b - Own program
- learn how to program a simple program using Gadot
- Run Gadot engine on Raspberry Pi
- Potentially use RetroPie
