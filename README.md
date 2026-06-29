# smart-parking-gate-system
Arduino-based smart parking gate system using an ultrasonic sensor and servo motor for automated vehicle detection and gate control.

##Overview
The Smart Parking Gate System is an embedded systems project developed as part of the Embedded System Design course at Altınbaş University.
The system automatically detects approaching vehicles using an HC-SR04 ultrasonic sensor. Once a vehicle enters the detection range, an Arduino Uno processes the sensor data and opens the parking gate by rotating a servo motor. LEDs provide visual feedback, while a buzzer alerts users during operation.
The project demonstrates how embedded systems can automate real-world processes through the interaction of sensors, actuators, and microcontrollers.

##Features
Automatic vehicle detection
Automatic gate opening and closing
Ultrasonic distance measurement
Servo motor control
Green and red LED indicators
Audible buzzer notification
Physical hardware implementation
Wokwi simulation

##🛠 Technologies
Hardware
Arduino Uno
HC-SR04 Ultrasonic Sensor
SG90 Servo Motor
Breadboard
Jumper Wires
LEDs
Resistors
Buzzer
Software
Arduino IDE
C/C++
Wokwi Simulator

##⚙️ System Workflow
The ultrasonic sensor continuously measures the distance.
Arduino processes the sensor readings.
If an object is detected within 15 cm:
The servo motor opens the gate.
The green LED turns ON.
The buzzer activates.
Otherwise:
The gate remains closed.
The red LED turns ON.
The buzzer is OFF.

##🏗 System Architecture
Vehicle
↓
Ultrasonic Sensor
↓
Arduino Uno
↓
Decision Logic
↓
Servo Motor + LEDs + Buzzer

