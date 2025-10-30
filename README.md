# Smart-Irrigation-System-Arduino
🌾 Smart Irrigation System (Automation Using Arduino Uno)

🔍 Project Overview

This project is a basic real-time Smart Irrigation System designed to automate the watering process for crops or plants based on soil moisture levels.
It uses a Soil Moisture Sensor to detect soil conditions and a Relay Module to control a water pump (motor) automatically.
A Buzzer is used to indicate different moisture levels for better monitoring.


---

🎯 Objective

To design a low-cost, automatic irrigation system that saves water and reduces the need for manual monitoring by farmers or gardeners.


---

⚙️ Components Used

Component	Description

Arduino Uno	Microcontroller board controlling the system
Soil Moisture Sensor	Detects moisture level in the soil
Relay Module	Controls the water pump automatically
Water Pump (Motor)	Pumps water to the plants
Buzzer	Gives alert for low/high moisture
Jumper Wires & Breadboard	For connections and prototyping
Power Supply	5V–12V (depending on motor requirements)



---

🔌 Circuit Connections

Soil Moisture Sensor → Digital Pin 6 of Arduino

Relay Module (IN Pin) → Digital Pin 3 of Arduino

Buzzer (optional) → Digital Pin 8 of Arduino

VCC and GND connected accordingly to Arduino 5V and GND.

Relay Output connected to the motor and power supply for switching.



---

🧠 Working Principle

1. The soil moisture sensor reads the moisture level.


2. When soil is dry, sensor output becomes HIGH, triggering the relay to turn ON the motor.


3. When soil has sufficient moisture, sensor output becomes LOW, turning OFF the motor.


4. The buzzer alerts when moisture is low or sufficient (optional).


5. The Serial Monitor displays live sensor readings for debugging.


---

🧾 Applications

Smart Agriculture Systems

Home Garden Automation

Water Conservation Projects

IoT or AI-based future extensions



---

🚀 Future Scope

Add IoT integration (Blynk or ThingSpeak) for remote monitoring.

Use AI models to predict irrigation needs based on temperature and soil history.

Expand for multi-zone irrigation systems.



---

📷 Project Output

(Add images of your circuit and working setup here)
Example:



---

🧑‍💻 Developed By

Ravi Kumar Bandi
B.Tech (3rd Year) | Smart Automation Enthusiast
📅 Year: 2025
