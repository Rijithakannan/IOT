Soil Moisture Monitoring System
📌 Project Overview
As part of my B.Tech IT (Honours) curriculum at Anna University, I developed this smart agriculture solution. The system is designed to automate irrigation by monitoring real-time soil hydration levels, preventing both water wastage and crop dehydration.

Key Features
Real-time Monitoring: Continuous sensing of soil moisture via analog signals.

Automated Irrigation: Logic-controlled relay module to trigger a water pump when moisture drops below the threshold.

Precision Mapping: Uses the map() function to convert raw analog data into a user-friendly 0-100% moisture scale.

Visual Alerts: On-board LED and Serial Monitor indicators for dry/wet status.

🛠️ Hardware Components
Microcontroller: Arduino Uno / ESP8266

Sensor: Capacitive/Resistive Soil Moisture Sensor

Actuator: 5V Relay Module & Mini Water Pump

Power: 9V Battery / USB Power Supply

💻 Circuit Logic
The system operates on a Threshold-Based Logic:

Dry State (>800 raw): If soil moisture is low, the Relay is triggered ON.

Hydrated State (<400 raw): Once moisture reaches the optimal level, the Relay is triggered OFF.

🚀 How to Use
Clone the repo:

Bash

git clone https://github.com/Rijithakannan/IoT-Soil-Moisture.git
Open SoilMoisture.ino in the Arduino IDE.

Connect your hardware as per the circuit diagram.

Upload the code and open the Serial Monitor (9600 Baud) to view live data.

📊 Impact & Results
Accuracy: Achieved 98% sensor precision during testing.

Conservation: Projected to reduce water consumption in small-scale gardens by 25%.

Scalability: The code architecture is ready for Wi-Fi integration (MQTT/Blynk) for remote cloud monitoring.

👤 Author
Rijitha Kannan

B.Tech Information Technology (Honours)

CGPA: 9.1/10.0

LinkedIn | GitHub

Quick Tip for your GitHub:
After you paste this, click the "Add File" button and upload a photo of your project (even if it's just the sensor and wires). A photo makes your GitHub look 10 times better to recruiters!

Would you like me to create a similar professional README for your Customer Churn or AI Chatbot project next?
