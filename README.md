🌱📡 IoT-BASED PLANT MONITORING SYSTEM USING NODEMCU ESP8266 + THINGSPEAK
System Overview

This project is designed to monitor temperature, humidity, soil moisture, and rain status using sensors connected to a NodeMCU ESP8266 microcontroller.
The system sends real-time data to ThingSpeak, allowing for remote observation and analysis.

Key Features

* Live Monitoring: Temperature and humidity monitoring using DHT11 sensor
*  Soil Moisture Sensing: Assessing irrigation needs using soil moisture sensor
* Rain Detection: Digital rain sensor for detecting rainfall
* Cloud Visualization: Sending data to ThingSpeak for visualization and analysis
* Continuous Updates: Data updates every few seconds

Hardware Components

*  NodeMCU ESP8266: Wi-Fi enabled microcontroller
* DHT11 Sensor: Temperature and humidity sensor
* Soil Moisture Sensor: Measures soil water content (Analog)
* Rain Sensor Module: Detects rainfall (Digital)
* Breadboard & Jumper Wires: Circuit connections
* USB Cable: Power and programming interface
* Wi-Fi Network: Internet access for data upload

ThingSpeak Setup

To set up ThingSpeak, you'll need to:
1. Create a free account on ThingSpeak
2. Create a new channel with fields for temperature, humidity, and soil moisture
3. Copy the Write API Key from the channel settings

How it Works

The system works as follows:
1. NodeMCU reads data from sensors (DHT11, soil moisture, and rain sensor)
2. Sensor data is mapped and formatted
3. NodeMCU connects to Wi-Fi and pushes data to ThingSpeak
4. You can remotely view sensor data on your ThingSpeak dashboard

Divya Dharsini Dhanaraj 
Electronics And Communication Engineering
