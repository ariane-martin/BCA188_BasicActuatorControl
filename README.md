# Laboratory Activity 6: Basic Actuator Control

**Student:** Ariane L. Martin
**Course:** BCA188

## Description

This laboratory demonstrates basic DC motor control using an ESP32, L298N motor driver, and push button. When the button is pressed, the motor rotates. When the button is released, the motor coasts to a stop.

## Objectives

- Control a DC motor using an ESP32 and motor driver.
- Demonstrate button-controlled run/coast behavior.
- Understand the functions of motor driver pins.
- Identify the motor and driver specifications.

## Materials and Components

- ESP32 Development Board
- L298N Motor Driver
- RF-300CA-12400 DC Motor
- Push Button
- Breadboard and Jumper Wires
- External Motor Power Supply
- USB Cable and Laptop

## Results and Observations

| Button Condition               | Observed Result          |
| ------------------------------ | ------------------------ |
| Button released                | Motor stopped            |
| Button pressed                 | Motor rotated            |
| Button held                    | Motor continued rotating |
| Button released after pressing | Motor coasted to a stop  |

All required functional tests were successful.

## Laboratory Report

[View Laboratory 6 Report](Martin_Laboratory6_Report.pdf)

## Video Documentation

[https://drive.google.com/file/d/1S6PspRNAYud4NpF6JbZwoRldjSRxq8pZ/view?usp=drive_link](https://drive.google.com/file/d/1S6PspRNAYud4NpF6JbZwoRldjSRxq8pZ/view?usp=drive_link)

## Conclusion

The laboratory successfully demonstrated basic actuator control using an ESP32 and L298N motor driver. The motor responded correctly to the push button, demonstrating how digital input signals can control a DC motor through a motor driver.
