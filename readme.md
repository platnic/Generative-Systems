This repository Give the Code to code to connect 2 MPU6050 to the ESP8266.
The ESP then communicates through its Wifi with Processing on a PC.
All the values of the sensors are then shown on Processing on a graph.
One visual line per input value (6 lines per MPU6050)

XDA from MPU1 connected to D1
SCL1 from MPU1 connected to D2
AD0 from MPU1 connected to 3V3 via resistor

XDA from MPU2 connected to D1
SCL1 from MPU2 connected to D2
AD0 from MPU2 connected to GND

GND from MPU1&2 connected to GND
VCC from MPU1&2 connected to 3V3

![MPU6050-small](https://user-images.githubusercontent.com/12084024/100617118-b6942980-3322-11eb-8960-6051994e92c6.jpg)

![ESP8266-rotate](https://user-images.githubusercontent.com/12084024/100617123-b85ded00-3322-11eb-8321-f9c5d1beb9e5.jpg)
