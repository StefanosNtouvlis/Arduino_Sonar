# Sonar Project

## Overview

Welcome to the repository for the Sonar project! In this project, we've repurposed components from the previous "smart" automated trashcan project to create a sonar system. By reusing components, we uphold principles of sustainability while exploring new applications for existing hardware.

## Components

The main components utilized in this project are similar to those used in the smart bin project:
- **Arduino Uno Microcontroller**
- **Servo Mini 9g Motor**
- **Ultrasonic Sensor**
- **Jumper Cables**
- **USB-B Cable**

Additionally, we've incorporated:
- **Breadboard:** Used to facilitate multiple connections required for the project.
- **Glue Gun:** Utilized to secure the sensor onto the motor for stable operation.

## Code

The code for this project consists of two parts:

### Arduino Code
The first part is written in the Arduino IDE and uploaded to the Arduino Uno microcontroller. You can experiment with it by downloading the `radar_ultrasonic.ino` file. This code controls the interaction between the ultrasonic sensor and the servo motor.

### Processing Code
The second part is written in Processing, a programming language and IDE specifically designed for visual arts and interactive graphics. You can play with it by downloading the `radar_ultrasonic.pde` file. This code creates a visual representation of the sonar data received from the Arduino, displaying it on the monitor with a red color indication.

## Functionality

The sonar system functions similarly to a traditional sonar device. The servo motor turns indefinitely, continuously scanning the surroundings. When an object enters the active radius of the ultrasonic sensor (adjustable within the sensor's capabilities), a signal is sent to the controller. The Arduino reads this signal and passes it to Processing, where it appears on the monitor as a visual representation in red color, indicating the presence of an object.

Feel free to explore the code, suggest improvements, or adapt the project to suit your needs! If you have any questions or encounter issues, don't hesitate to reach out. Enjoy experimenting with sonar technology!
