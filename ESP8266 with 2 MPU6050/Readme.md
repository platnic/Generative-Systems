# ESP8266 connected to 2 MPU6050 sending values to Processing

This repository Give the Code to code to connect 2 MPU6050 to the ESP8266.
The ESP8266 then communicates through its Wifi with Processing on a PC.
All the values of the sensors are then shown on Processing on a graph.
One visual line per input value (6 lines per MPU6050)

XDA from MPU1 connected to D1</br>
SCL1 from MPU1 connected to D2</br>
AD0 from MPU1 connected to 3V3 via resistor</br>
</br>
XDA from MPU2 connected to D1</br>
SCL1 from MPU2 connected to D2</br>
AD0 from MPU2 connected to GND</br>
</br>
GND from MPU1&2 connected to GND</br>
VCC from MPU1&2 connected to 3V3</br>
</br>

![MPU6050-small](https://user-images.githubusercontent.com/12084024/100617118-b6942980-3322-11eb-8960-6051994e92c6.jpg)
</br>

![ESP8266-rotate](https://user-images.githubusercontent.com/12084024/100617123-b85ded00-3322-11eb-8321-f9c5d1beb9e5.jpg)
