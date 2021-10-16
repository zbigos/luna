# Luna is a board used to get kids into STEM fields.
This board is specifically designed to use standard JLC process, and mostly THT components

Still waiting for a fab run, this design is **NOT** proven.

<img src="https://github.com/zbigos/luna/blob/master/image.jpg" width="378" height="394">

# Features
Main feature of Luna is a circular cutout that is split into 10, separately controllable zones (to make a moon phase simulation-thing).
To make it respond to real time, there is a standard DS3231 RTC chip connected to the I2C bus.
There is also a gpio expander that matrix-drives HH:MM:SS clock in 3x16 configuration.

RPpico has been used as the microcontroller, and to preserve its fragile USB connector an external power only usb-c has been added.
Since the external usb is power only, and board has no place for buttons, the setting of time has to be done via RPpico usb.

# Contributing
don't
