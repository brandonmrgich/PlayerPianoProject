# Piano Project
Arduino Code for a DIY Player Piano.

See more information about it here: brandonswitzer.squarespace.com/player-piano

Role of each of the Arduinos:

  ESP32:
  
    - Receives and decodes bluetooth message
    
    - Schedules notes
    
    - Handles sustain
    
    - Handles setting changes
    
  Pro Micro:
  
    - Receives data from ESP32 and/or USB
    
    - Activates notes using shift registers
    
  Control Box (Pro Micro):
  
    - Interface for changing settings
    
    - Receives data from USB and sends it to ESP32
    
    - Reset button
    
Required Arduino Libraries:
  - ShiftPWM (Pro Micro)
  - MIDIUSB  (Pro Micro & Control Box)
  - LiquidCrystal_I2C (Control Box)
  - Arduino Core for ESP32 (https://github.com/espressif/arduino-esp32)

DETAILS & DOCUMENTS
  - A video outlining the build process can be viewed on YouTube via the following link: https://youtu.be/S7Bd992k368
  - A document detailing the process of building the player piano can be seen here: https://drive.google.com/file/d/1uUG9_p_ZxxOJA7IN526V5-fykXMjAesL/view?usp=sharing
  - Schematic of the wiring: https://drive.google.com/open?id=13Mw2ipOHaPREzwItvF4orVLiwkJOeLmr
  - C++ Code: https://github.com/bbswitzer/PianoProject
  - Playlist of different songs on the piano: https://www.youtube.com/watch?v=lDdaMBsiQBA&list=PLoJQmZz3MvA6Fd85n4oOz91u7FMfJuI5o
  - Playlist of videos taken during development: https://www.youtube.com/watch?v=O_DePbJAjgY&list=PLoJQmZz3MvA7PK9J5HVHxc-8FWZnZEDiG
