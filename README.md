# LedToggle
Toggles Arduino LED using Raspberry Pi3 

This project used Raspberry Pi3 and Arduino Uno.
Demonstrates I2C connection of between two devices.
And controlling IO of the slave device.

Connected using I2C interface.
Pi3 as master and Arduino as slave.

Pi asks the user to choose from numbers 1-3.
Selected number will be sent to Arduino.
Arduino receives this.
And turns on the assigned LED when off or vice versa.
Also displays the selected number on LCD.

Code originally seen here:
http://stackoverflow.com/questions/24807785/raspberrypi-to-arduino-send-and-receive-string

Comments and suggestions to improve the project are highly appreaciated.
