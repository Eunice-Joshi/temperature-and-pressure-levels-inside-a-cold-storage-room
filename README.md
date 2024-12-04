# temperature-levels-inside-a-cold-storage-room

This project demonstrates a simple temperature and pressure monitoring system for a cold storage room using an Arduino, a TMP36 temperature sensor, and an Adafruit 16x2 LCD screen.


Features:
*Real-Time Monitoring: Displays live temperature in Celsius and a simulated pressure value on an LCD screen.
*Ease of Use: Minimal hardware setup with straightforward coding.
*Customization: Adaptable for additional sensors and features.

**Hardware Requirements**
Arduino Uno (or any compatible microcontroller).
TMP36 temperature sensor.
Adafruit 16x2 LCD screen with I2C backpack.
Breadboard and jumper wires.

** Software Requirements**
Arduino IDE (latest version).
Adafruit LCD library (Adafruit_LiquidCrystal).

** How to Set Up**
Connect the Hardware:
Connect the TMP36 sensor output pin to A0 on the Arduino.
Attach the Adafruit LCD to the I2C pins on the Arduino.
Install Required Libraries:
In the Arduino IDE, go to Sketch > Include Library > Manage Libraries.
Search for and install Adafruit_LiquidCrystal.

Upload the Code:
This is available as a file in the repository
Copy the provided code into the Arduino IDE.
Upload the code to your Arduino board.

View Readings:

The LCD will display the current temperature in Celsius and a simulated pressure value.
**Code Overview**
Temperature Measurement:
Analog readings from the TMP36 sensor are converted to voltage, then calculated into Celsius.

Formula:

Temperature=(Voltage−0.5)×100.0
Simulated Pressure:

Pressure values are randomly generated for demonstration purposes using the random() function.
LCD Display:

First line: Temperature in Celsius.
Second line: Simulated pressure in Pascals.

**Applications**
Monitoring temperature in cold storage rooms.
Educational projects to learn about sensors and displays.
Extensible to include humidity sensors or wireless data transmission. This project demonstrates a simple temperature and pressure monitoring system for a cold storage room using an Arduino, a TMP36 temperature sensor, and an Adafruit 16x2 LCD screen.
