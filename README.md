# air_quality_monitoring
 A compact air quality monitoring system using an ESP32 microcontroller.

*Description* 

The air quality monitoring system utilizes an ESP32 microcontroller for data processing and 
communication. Sensors are connected to measure key environmental factors: 
**• MQ135 Gas Sensor**: Detects pollutants like CO2, ammonia, benzene, and more, 
providing an air quality index based on Analog readings. 
**• DHT11 Sensor**: Monitors temperature and humidity, contributing to more 
comprehensive environmental data. 
**• LCD Display with I2C Converter**: Displays real-time sensor data locally.

The system sends data to the Blynk IoT platform, allowing remote monitoring via mobile 
devices. Users can set alerts for hazardous air quality thresholds and receive notifications 
through Blynk’s notification system.

*Hardware*: 
1. ESP32 Microcontroller 
2. MQ135 Air Quality Sensor 
3. DHT11 Temperature and Humidity Sensor 
4. LCD Display (16x2) 
5. I2C Converter 
6. Jumper Wires and Breadboard
   
*Software*: 
1. Arduino IDE  
2. Blynk Library for IoT Connectivity 
3. DHT and LiquidCrystal_I2C Libraries for sensor interfacing
