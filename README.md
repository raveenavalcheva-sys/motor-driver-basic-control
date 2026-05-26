# motor-driver-basic-control
Basic Arduino project demonstrating DC motor wheel movement using a motor driver 
# Arduino Wheel Movement Test

## 🚗 Overview
This project demonstrates basic DC motor wheel movement using an Arduino and motor driver. It was created to test correct wiring and verify motor functionality.

## ⚙️ Components Used
- Arduino UNO
- Motor Driver (L298N)
- DC Motors
- Battery pack
- Jumper wires

## 🔌 Working Principle
The Arduino controls two DC motors using a motor driver through four digital output pins (IN1, IN2, IN3, IN4). Based on the programmed logic, the pins are set HIGH or LOW to define motor rotation direction. In this project, both motors are activated simultaneously to move the wheels in one direction for 3 seconds. After that, all motor inputs are set LOW to stop the motors for 1 second before the cycle repeats. This process demonstrates basic open-loop motor control without sensors or feedback.

## 🎯 Result
The DC motors successfully run in a fixed sequence. The robot moves in one direction for 3 seconds, stops for 1 second, and then repeats the cycle. This confirms correct motor driver wiring and proper Arduino control of motor direction using digital output signals.

## 🎥 Demo Video
https://youtube.com/shorts/fZtTBPt-O8I?si=HJOyflb4twEdu0em

