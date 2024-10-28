Using MQ2 to Detect smoke and send alerts through the buzzer.
Objectives
● To detect gas leaks using the MQ2 sensor.
● Promptly alert users with visual and auditory cues in case of a gas leak.
● Continuously monitor gas levels and provide real-time feedback through the
serial
● monitor for user awareness and preventive actions.

Components to Use
1. ESP32
2. Buzzer module
3. MQ-2 gas and smoke sensor
4. On-board LED
5. Jumper cables
6. USB Cable

Project Steps
Follow these simple steps to complete the project
1. Connect the MQ2 smoke sensor to the 4 pin Female-Female jumper cable.
2. Connect the Analog pin (AO) of the MQ2 to pin A3 of the ESP32 board, connect
the VCC pin to the 3.3V pin and the GND pin to the GND pin. The Digital pin
(DO) of the MQ2 should not be connected.
3. Connect the 3 pin Female - Female jumper cable to the Buzzer.
4. Connect the Signal pin (S) of the buzzer to pin A5 of the ESP32 board, connect
the middle pin (VCC) to the 3.3V pin and the GND pin to the GND pin.
5. Connect the USB cable to the ESP32 board and the other end of the cable to
your computer to program it.
6. If the connection is done properly, the MQ2 smoke sensor power LED should
turn on.