<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smart Parking Gate System</title>
</head>

<body>

    <h1>🚗 Smart Parking Gate System Using Arduino</h1>

    <p>
        <em>
            An embedded systems project that automates parking gate access using an Arduino Uno,
            an ultrasonic sensor, and a servo motor.
        </em>
    </p>

    <hr>

    <section>
        <h2>📖 Overview</h2>

        <p>
            The <strong>Smart Parking Gate System</strong> is an embedded systems project
            developed as part of the
            <strong>Embedded System Design</strong> course at
            <strong>Altınbaş University</strong>.
        </p>

        <p>
            The system automatically detects approaching vehicles using an
            <strong>HC-SR04 ultrasonic sensor</strong>. Once a vehicle enters the
            detection range, an <strong>Arduino Uno</strong> processes the sensor
            data and opens the parking gate by rotating a
            <strong>servo motor</strong>. LEDs provide visual feedback, while a
            buzzer alerts users during operation.
        </p>

        <p>
            The project demonstrates how embedded systems can automate real-world
            processes through the interaction of sensors, actuators, and
            microcontrollers.
        </p>
    </section>

    <hr>

    <section>

        <h2>✨ Features</h2>

        <ul>
            <li>Automatic vehicle detection</li>
            <li>Automatic gate opening and closing</li>
            <li>Ultrasonic distance measurement</li>
            <li>Servo motor control</li>
            <li>Green and red LED indicators</li>
            <li>Audible buzzer notification</li>
            <li>Physical hardware implementation</li>
            <li>Wokwi simulation</li>
        </ul>

    </section>

    <hr>

    <section>

        <h2>🛠 Technologies</h2>

        <h3>Hardware</h3>

        <ul>
            <li>Arduino Uno</li>
            <li>HC-SR04 Ultrasonic Sensor</li>
            <li>SG90 Servo Motor</li>
            <li>Breadboard</li>
            <li>Jumper Wires</li>
            <li>LEDs</li>
            <li>Resistors</li>
            <li>Buzzer</li>
        </ul>

        <h3>Software</h3>

        <ul>
            <li>Arduino IDE</li>
            <li>C/C++</li>
            <li>Wokwi Simulator</li>
        </ul>

    </section>

    <hr>

    <section>

        <h2>⚙️ System Workflow</h2>

        <ol>

            <li>The ultrasonic sensor continuously measures the distance.</li>

            <li>Arduino processes the sensor readings.</li>

            <li>
                If an object is detected within <strong>15 cm</strong>:
                <ul>
                    <li>The servo motor opens the gate.</li>
                    <li>The green LED turns ON.</li>
                    <li>The buzzer activates.</li>
                </ul>
            </li>

            <li>
                Otherwise:
                <ul>
                    <li>The gate remains closed.</li>
                    <li>The red LED turns ON.</li>
                    <li>The buzzer is OFF.</li>
                </ul>
            </li>

        </ol>

    </section>

    <hr>

    <section>

        <h2>🏗 System Architecture</h2>

        <pre>
Vehicle
   │
   ▼
Ultrasonic Sensor
   │
   ▼
Arduino Uno
   │
   ▼
Decision Logic
   │
   ▼
Servo Motor + LEDs + Buzzer
        </pre>

    </section>

</body>
</html>

