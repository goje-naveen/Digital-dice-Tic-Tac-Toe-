# Digital-dice-Tic-Tac-Toe-

Objective:
To create a digital dice using an Arduino Uno and a 7-segment display that simulates the roll of a traditional six-sided die, displaying the result on the 7-segment display when a push button is pressed. A buzzer provides auditory feedback.

Components:

Arduino Uno: Microcontroller used to control the project.
7-Segment Display (Common Anode): Displays the dice number (1-6).
Push Button: Triggers the dice roll.
Buzzer: Provides sound feedback for the dice roll.
100Ω Resistors: Limit current to protect the LEDs in the 7-segment display.
Solderless Breadboard & Jumper Wires: Used for circuit assembly.
Battery Clip & 9V Battery: Power supply for the Arduino.
Circuit Diagram
You'll need to ensure that each component is correctly placed and connected according to the wiring instructions. This includes connecting the 7-segment display to the appropriate digital pins on the Arduino via resistors and ensuring the push button and buzzer are correctly connected.

Assembly Instructions
Mount Components: Arrange the 7-segment display, push button, buzzer, and Arduino on the breadboard.

Wiring:

Connect the segments of the 7-segment display to Arduino pins 2-8 with 100Ω resistors.
Connect the push button to digital pin 9 with a 10kΩ pull-down resistor.
Connect the buzzer to digital pin 10.
Connect power and ground rails to the Arduino.
Power Supply:

Connect the 9V battery to the Arduino’s VIN and GND pins via the battery clip.
Usage Instructions
Operation: Press the push button to roll the dice. The Arduino generates a random number between 1 and 6, which is displayed on the 7-segment display. The buzzer sounds briefly as feedback.
Troubleshooting Guide
Display Issues: Double-check connections, particularly resistors and the common anode to 5V.
Button Issues: Verify connections and test the push button.
Buzzer Issues: Ensure correct wiring and code implementation.
Random Number Issues: Properly use randomSeed() with analogRead() to ensure true randomness.
This project can be a fun and educational way to learn about Arduino, basic electronics, and programming. Let me know if you need further details on the code implementation or specific troubleshooting steps!
