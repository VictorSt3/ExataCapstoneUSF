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


** NOTE: Script for GNSS is still a work in progress and currently states no signal is found.
