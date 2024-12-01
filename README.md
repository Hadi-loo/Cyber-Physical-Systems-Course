# Cyber-Physical Systems Course Projects

This repository serves as an overview and central hub for the projects developed as part of the Cyber-Physical Systems course at the University of Tehran. Each project explores innovative applications of cyber-physical systems in diverse domains.

## Projects Overview
### IoT Entrance Control System

This project is the implementation of a cloud-based entrance control system. The system consists of a cloud server and a client. The client is a microcontroller that is connected to a RFID reader and a DC motor. The server is a cloud server that is responsible for authenticating the users and controlling the entrance. The server is also responsible for monitoring the entrance and keeping the entrance history. Key features include:

-   RFID Integration: Enables secure and automated entrance management.
-   Real-time Monitoring: A web application for tracking and managing access logs.
-   Technology Stack: Developed with Arduino, Qt, and web technologies.

### Motion-Based Authentication System

This project aims to develop an Android application that uses the accelerometer and gyroscope sensors to authenticate users based on their motion patterns. The user can move the phone in two directions (parallel to the x-axis or y-axis) and rotate the phone around the z-axis to record a pattern. The application has three buttons: Calibrate, Record New Pattern, and Authenticate Pattern. Calibration is done by taking the average of the sensor readings for the first 20 data readings from the sensors. The user can record a new pattern by pressing the record button, and the pattern consists of a list of paths with x position, y position, and rotation degree. The app compares the recorded pattern with the pattern that the user recorded before to authenticate the user. The backend part of the application is implemented in C++, and the frontend part is implemented in QML. The application uses the accelerometer sensor to read acceleration in two directions (x-axis and y-axis) and calculate the position and speed of the phone. The gyroscope sensor is used to read speed in the z-axis and calculate the rotation degree of the phone. The data rate is set to 20 in both accelerometer and gyroscope sensors. The application uses Perfetto for tracing and profiling the app.
