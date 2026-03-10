# Smart Anti-Theft Security System (ESP32)

## Overview

This project is an IoT-based vehicle anti-theft system designed to protect cars and motorcycles from unauthorized access.
The system detects suspicious activity around the vehicle and triggers alarms while allowing the owner to monitor the system remotely.

## Hardware Components

* ESP32
* Ultrasonic Sensor
* Microphone Sensor
* Servo Motor
* Buzzer
* LEDs

## System Features

* Motion detection around the vehicle
* Clap-based authentication for authorized users
* Alarm activation using buzzer and LED indicators
* Servo motor used as a vehicle locking mechanism
* Real-time monitoring through a cloud dashboard

## Communication

The system transmits sensor data using the MQTT protocol to a cloud dashboard built on ThingSpeak for remote monitoring.

## Workflow

1. Ultrasonic sensor detects motion near the vehicle.
2. The microphone sensor listens for a predefined clap pattern.
3. If the correct clap sequence is detected, the servo motor unlocks the vehicle.
4. If unauthorized activity is detected, the buzzer and LED alarm are activated.
5. Sensor data is sent to the cloud dashboard for monitoring.

## Applications

* Vehicle anti-theft systems
* Smart garage security
* IoT-based security solutions

## Future Improvements

* GPS tracking integration
* Camera monitoring
* Biometric authentication (RFID or fingerprint)
