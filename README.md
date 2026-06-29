# 🚗 Smart Parking Gate System Using Arduino

> An embedded systems project that automates parking gate access using an Arduino Uno, an HC-SR04 ultrasonic sensor, and a servo motor.

---

## 📖 Overview

The **Smart Parking Gate System** is an embedded systems project developed as part of the **Embedded System Design** course at **Altınbaş University**.

The project simulates an automated parking gate capable of detecting approaching vehicles and controlling a barrier gate without human intervention. An **HC-SR04 ultrasonic sensor** measures the distance to an object, while an **Arduino Uno** processes the sensor data and controls a **servo motor** to open or close the gate automatically.

To improve user interaction, the system provides:

- 🟢 Green LED indicating that the gate is open.
- 🔴 Red LED indicating that the gate is closed.
- 🔊 Buzzer notifications during gate operation.

This project demonstrates how embedded systems integrate sensors, actuators, and microcontrollers to automate a real-world parking system.

---

## ✨ Features

- 🚗 Automatic vehicle detection
- 🚪 Automatic gate opening and closing
-  Real-time distance measurement
-  Servo motor gate control
- 🟢 Green and 🔴 Red LED status indicators
-  Audible buzzer notification
- 🔌 Physical hardware implementation
- 💻 Wokwi simulation

---

## 🛠️ Technologies

### Hardware

- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor
- Breadboard
- Jumper Wires
- LEDs
- 220Ω Resistors
- Buzzer

### Software

- Arduino IDE
- C/C++
- Wokwi Simulator

---

## ⚙️ System Workflow

1. The ultrasonic sensor continuously measures the distance to an approaching object.
2. The Arduino Uno processes the sensor readings.
3. If an object is detected within **15 cm**:
   - The servo motor opens the gate.
   - The green LED turns **ON**.
   - The buzzer is activated.
4. Otherwise:
   - The gate remains closed.
   - The red LED turns **ON**.
   - The buzzer is turned **OFF**.

---

##  System Architecture

```text
                Vehicle
                   │
                   ▼
      HC-SR04 Ultrasonic Sensor
                   │
                   ▼
              Arduino Uno
                   │
            Decision Logic
                   │
      ┌────────────┼────────────┐
      ▼            ▼            ▼
 Servo Motor     LEDs       Buzzer
```
---

### 💻 Wokwi Simulation

> *(Insert a screenshot of your Wokwi simulation.)*



---

##  Future Improvements

- RFID authentication
- LCD display for user messages
- Automatic parking space counter
- Wi-Fi or Bluetooth connectivity
- Mobile application integration
- License plate recognition
- Cloud-based monitoring dashboard
- Finite State Machine (FSM) implementation
- Improved power management

---

## 📚 Concepts Demonstrated

- Embedded Systems
- Arduino Programming
- Sensor Integration
- Servo Motor Control
- Digital Input/Output
- PWM (Pulse Width Modulation)
- Conditional Logic
- Hardware Interfacing
- Automation Systems

---

## 🎥 Demonstration

The project has been successfully tested using both:

- ✅ Physical Arduino hardware
- ✅ Wokwi online simulation
