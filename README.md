# Sonar Project

## Overview

Welcome to the repository for the Sonar project! In this project, we've repurposed components from the previous "smart" automated trashcan project to create a sonar system. By reusing components, we uphold principles of sustainability while exploring new applications for existing hardware.
![IMG_20240120_010335](https://github.com/StefanosNtouvlis/Arduino_Sonar/assets/81410555/67548858-88d3-49c1-a6bf-bd3900273d01)
![Screenshot 2024-01-20 at 1 06 00 AM](https://github.com/StefanosNtouvlis/Arduino_Sonar/assets/81410555/5b2ddc9d-a99d-4307-acf1-2d528c67bef8)


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

![IMG_20240120_003204](https://github.com/StefanosNtouvlis/Arduino_Sonar/assets/81410555/6d9903a1-157a-4602-a494-dfcf9c5d9575)
![IMG_20240120_003120](https://github.com/StefanosNtouvlis/Arduino_Sonar/assets/81410555/69b41ec7-cd1b-4b95-aef3-fb0eec185d74)

## Code

The code for this project consists of two parts:

### Arduino Code
The first part is written in the Arduino IDE and uploaded to the Arduino Uno microcontroller. You can experiment with it by downloading the `radar_ultrasonic.ino` file. This code controls the interaction between the ultrasonic sensor and the servo motor.

### Processing Code
The second part is written in Processing, a programming language and IDE specifically designed for visual arts and interactive graphics. You can play with it by downloading the `radar_ultrasonic.pde` file. This code creates a visual representation of the sonar data received from the Arduino, displaying it on the monitor with a red color indication.

## Functionality

The sonar system functions similarly to a traditional sonar device. The servo motor turns indefinitely, continuously scanning the surroundings. When an object enters the active radius of the ultrasonic sensor (adjustable within the sensor's capabilities), a signal is sent to the controller. The Arduino reads this signal and passes it to Processing, where it appears on the monitor as a visual representation in red color, indicating the presence of an object.

Feel free to explore the code, suggest improvements, or adapt the project to suit your needs! If you have any questions or encounter issues, don't hesitate to reach out. Enjoy experimenting with sonar technology!
