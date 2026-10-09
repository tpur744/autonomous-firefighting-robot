# Autonomous Firefighting Robot

An autonomous Mecanum-wheel mobile robot designed to navigate its environment, detect fire sources, and extinguish them using onboard sensors and control algorithms.

Developed as part of a university mechatronics engineering project.

## Project Overview

The robot combines omnidirectional movement, sensor-based navigation, and closed-loop control to autonomously locate and respond to fire sources.

### Key Features

- **Mecanum-Wheel Drive:** Four-wheel omnidirectional movement, enabling translation and rotation independently.
- **PID Heading Control:** Gyroscope feedback used to maintain and correct the robot's orientation during movement.
- **Autonomous Navigation:** Ultrasonic and infrared sensors used for obstacle detection and navigation.
- **Fire Detection:** Phototransistor sensors used to detect and locate a light source representing a fire.
- **Finite State Machine (FSM):** Coordinates navigation, fire detection, approach, and extinguishing behaviours.

## Control System

The robot uses a finite state machine to coordinate autonomous operation, transitioning between behaviours based on sensor feedback.

A PID controller processes gyroscope measurements to calculate heading corrections, allowing the robot to maintain its intended orientation.

The Mecanum-wheel drivetrain enables omnidirectional movement without conventional steering, providing flexibility when navigating around obstacles and approaching fire sources.

## Technologies Used

- C/C++
- Embedded Systems
- PID Control
- Finite State Machines (FSM)
- Mecanum-Wheel Kinematics
- Gyroscope Feedback
- Ultrasonic and Infrared Sensors
- Phototransistor-Based Fire Detection
