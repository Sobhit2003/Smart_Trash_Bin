# Smart_Trash_Bin
📌 Overview
This project aims to develop an intelligent, modular smart trash bin capable of detecting user presence, measuring trash fill levels in multiple zones, and alerting users when the bin is full. It integrates environmental sensing, real-time status indication, serial logging, and optional IoT expansion.

🎯 Objectives
Detect user presence with an ultrasonic sensor.

Automatically open/close the bin lid using a servo motor.

Monitor trash levels across dual zones.

Display status using RGB LEDs and buzzer.

Log sensor readings every 5 seconds in JSON format.

Support future expansion to ESP8266/LoRa IoT modules.

🔌 Key Features
Auto-Lid System: Opens when a user is detected (<30 cm) and auto-closes after 5 seconds with debounce logic.

Multi-Zone Fill Detection: Uses two ultrasonic sensors to categorize trash levels as Empty, Mid, or Full.

Alerts & Indicators: RGB LED and buzzer provide real-time feedback.

Serial Monitoring: Outputs structured logs for each reading (timestamp, level, sensor data).

IoT Ready: UART/SoftwareSerial ports available for wireless modules.

🔩 Hardware Used
Arduino Uno/Nano

3x HC-SR04 Ultrasonic Sensors

Servo Motor

RGB LED

Buzzer

Breadboard & Resistors
✅ Conclusion
The system meets all functional goals and is optimized for future upgrades like IoT connectivity. It provides a smart, scalable solution for waste management in smart city applications.

Simulation Link 
https://www.tinkercad.com/things/5232fqeJkVJ-mighty-jofo 
