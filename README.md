# Robotic_Arm
This project is a WiFi-controlled robot arm using an ESP32, programmed in C++ for real-time control via a web interface. Technologies: ESP32, C++, WebSockets, Servo Motors, HTML/CSS, JavaScript.

#Project Members
1.SHAIKH HANIYA ASAD [Team Leader]
2.NAIK SALIMA IRSHAD
3.SHAIKH IQRA BANO
4.NADANKAR SAKSHI TANAJI

#Project Guide 
1.Prof.DHANASHREE KANGANE [Professor]

### Subject Details
- Class : TE (ECS) Div A - 2024-2025
- Subject : Mini project - 2A (MP-2A)
- Project Type : Mini Project

### Deployment Steps for Smartphone-Controlled Robotic Arm Using ESP32

Please follow the below steps to run this project:
links:
1. 👉 ESP32 board URL:
https://dl.espressif.com/dl/package_e
2.👉 AsyncTCP Library:
https://github.com/me-no-dev/AsyncTCP
3.👉 ESPAsyncWebServer Library:
https://github.com/me-no-dev/ESPAsync

1. Hardware Setup
Assemble the Robotic Arm: Put together the robotic arm components, including servomotors, sensors, and structural parts.

ESP32 Connection: Securely connect the ESP32 microcontroller to the robotic arm’s control elements.

Power Supply: Ensure a stable power supply is connected to the ESP32 and the servomotors to avoid interruptions.

2. Software Development
ESP32 Programming: Write and upload the firmware to the ESP32 using Arduino IDE or PlatformIO, which handles motor control and wireless communication.

Smartphone App Development: Develop a smartphone application to send control commands to the ESP32. The app can use Wi-Fi or Bluetooth for communication.
3. Integration
System Integration: Integrate the hardware and software components. Ensure the ESP32 can receive commands from the smartphone and control the robotic arm accordingly.

Network Setup: Configure the Wi-Fi network settings for the ESP32 to ensure it can communicate with the smartphone.

4. Testing
Unit Testing: Test individual components, like each servomotor, to ensure they function correctly.

Integration Testing: Conduct tests to ensure that all components work seamlessly together.

User Acceptance Testing: Have users test the system to ensure it meets their needs and functions as expected.

5. Installation
Physical Setup: Install the robotic arm in the desired location, ensuring it is securely mounted.

Connectivity Check: Verify that the ESP32 is connected to the power supply and can communicate with the smartphone app.


##Data Generated and Processed:

#Control Commands
Details: Commands sent from the smartphone app to the ESP32. Examples include move, stop, rotate, etc.
Purpose: These commands dictate the actions the robotic arm takes.

#Feedback Data
Details: Data sent back from the ESP32 to the smartphone app, such as current position, status updates, and error messages.
Purpose: Provides real-time feedback to the user on the status and position of the robotic arm.

#Position Data
Details: Information about the positions of the servomotors, usually in terms of angles.
Purpose: Ensures accurate movement and positioning of the robotic arm.

#Sensor Data (If Applicable)
Details: Data from any sensors attached to the robotic arm, such as position sensors or accelerometers.
Purpose: Used for feedback and control to ensure precise and stable operation.

#Test Data
Details: Data from various test scenarios, including sequences of commands and the corresponding outcomes.
Purpose: Validate the functionality and performance of the robotic arm during the testing phase.

#Log Data
Details: Logs of operations performed by the robotic arm, including timestamps and actions taken.
Purpose: Useful for debugging and performance analysis.

##References

#IJRASET Journal - "Robotic Arm using ESP32 and Smartphone"
This paper discusses the design and implementation of a robotic arm controlled using WebSockets for communication between the arm and the mobile device.

#IoT Design Pro - "Web controlled IoT based Robotic Arm using ESP32"
This article provides details on controlling a robotic arm wirelessly using a microcontroller ESP32 and a webpage for control.

#IJSR - "Real Time Control of Robotic Arm Using Bluetooth Low Energy & Wi-Fi with ESP32 and Android Application"
This paper explores real-time control of a robotic arm using Bluetooth Low Energy and Wi-Fi with the ESP32 module and an Android application.

#GitHub Repository - "RobotArm"
This repository contains code and diagrams for a robot arm controlled using a smartphone and the ESP32.

#Academia.edu - "ROBOT ARM WITH SMARTPHONE CONTROL"
This document provides insights into the construction and control of a robotic arm using a smartphone.

