MINI:

Libraries:
- Tools -> Manage Libraries 
  - Adafruit TinyUSB
    -  Might be included inside the Seeeduino package
  - Sensirion I2C SHT4x (with Sensirion Core dependency)
    - Might be included inside the Seeeduino package


For T/H and 3-axis accelerometer:

Set baud rate to 115200 in the serial monitor

Add Seed studio board manager
- Files -> Preferences (Mac: Arduino IDE -> Settings)
  - `https://files.seeedstudio.com/arduino/package_seeeduino_boards_index.json`

Download and select board type under board manager
- Seed nRF52 Boards
  - Seed Wio Tracker 1110

Make sure to update firmware for the board found here: https://wiki.seeedstudio.com/Get_Started_with_Wio-Trakcer_1110/#flash-firmware

** NOTE: Script for GNSS is still a work in progress and currently states no signal is found.

HUB:
- Video to help setting up PI: https://www.youtube.com/watch?v=rVym1624Xig
** Newset version was having some issues, so an older version (0.7.1) of rak OS was used
