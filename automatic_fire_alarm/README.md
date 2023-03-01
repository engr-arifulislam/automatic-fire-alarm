# project_automatic_fire_alarm_sensor
Project Automatic Fire detection and Alerting system, helps in detecting fire by taking inputs from several sensors and help in alerting the concerned people with the GPS coordinates of the fire that has taken place. DIVE into the project for learning how GPS and GSM modules communicate with each other and the Arduino's function in it. 


Components Used in this Project:
1. Arduino Uno
2. Smoke Detector Sensor (MQ2)
3. Temperature and Humidity Sensor (DHT 11)
4. Flame Sensor
5. LCD Panel 
6. Buzzer
7. 10kΩ POT

Modules Used:
1. GSM Module
2. GPS Module

Working: When a fire or high temperature or smoke is detected by the sensor, it firsts requests the GPS module to send the data of the longitute and latitute of the position where it is present, then routing it through the Arduino, message is sent to the concerned person regarding the fire alert with the corresponding coordinates. 


Procedure: 

Initially, all the sensors are tested and the pins are connected to the pins of the arduino as described in the code. 

Connections: 

GPS TX -----------> Arduino RX Pin 0,

GSM TX -----------> Arduino Pin 8,

GSM RX -----------> Arduino Pin 9,

MQ2 --------------> Arduino A0 Pin for analog,

LCD Panel --------> Pin 4,5,6,7,11,12,

Flame Sensor -----> Pin 2,

Buzzer -----------> Pin 13,

DHT 11 -----------> Pin 3


Attach the sensors and upload the code, you can get the project running. 

JUST A SMALL GLIMPSE OF MY PROJECT

![Image 2](https://user-images.githubusercontent.com/47684759/87859062-1e3b7080-c950-11ea-946b-5763eb576a69.jpg)

![Image 1](https://user-images.githubusercontent.com/47684759/87859083-3dd29900-c950-11ea-93ca-34bec8b1e2a1.jpg)


FOr any queries mail me. 












