# Science Fair
- Wiki: https://wiki.keyestudio.com/KS0470_Keyestudio_4WD_BT_Robot_Car_V2.0_Kit_for_Arduino

## Wiring
##### Conect all VCC/+5v and GND to VCC (+) and Ground (-) respectiviely.
###### Sonar and Servo
- Connect TRIG to 13
- Connect ECHO to 12
- Connect Servo's Orange wire to 9

###### Bluetooth
- Conect RXD to TX (in UNO)
- Connect TXD to RX (in UNO)
- (**Optionally**, use a resistor)

###### Line Sensor
- Connect the leftmost pin to 11
- Connect the center pin to 7
- Connect the rightmost pin to 8

###### L298N Motor Driver
- Connect the motors to the L298N
- Connect ENA and ENB to VCC (for full speed)
- Connect the "+12V" to 9V Battery
- Connect GND to Ground
- Connect "+5V" to the breadboard's VCC (I'll bring a smol breadboard)

- Connect IN1 to 4
- Connect IN2 to 5
- Connect IN3 to 2
- Connect IN4 to 6

#### Explanation
9V is used to power the motors. The L298N is equipped with circuitry to reduce 9V to 5V. It uses 9V to power the motors and sennds out 5V to power the Arduino and other electronics.
