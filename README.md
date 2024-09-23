# SafeDrive.AI: ML-Based Driver Safety and Monitoring System

## Overview
This project focuses on creating a real-time machine-learning system that monitors driver behavior using computer vision. It detects signs of driver fatigue, yawning, and airbag deployment, providing real-time alerts to reduce road accidents. Built using MobileNet, the system is lightweight and operates with high accuracy, ensuring optimal performance even on resource-limited devices.

### Features
1) Eye Status Detection: Tracks the driver's eye status to detect drowsiness and trigger alarms.
2) Yawn Detection: Detects yawning based on lip distance measurement, alerting the driver to take preventive action.
3) Airbag Detection: Identifies airbag deployment and sends notifications to the driver’s family or friends via the Pushbullet API.

### Tech Stack
1) Frontend: Python with OpenCV and Dlib for facial recognition
2) Backend: Flask, Pushbullet API for notifications
3) Model: MobileNet, Convolutional Neural Networks (CNN)
4) Hardware: Camera for real-time video processing

### Usage
Connect a camera to capture real-time video of the driver.
The system will automatically start monitoring for signs of drowsiness, yawning, or airbag deployment.
Notifications are sent via Pushbullet if an airbag is detected.

### Results
Eye status detection: 95% accuracy
Yawn detection: 90% accuracy
Airbag deployment alerts: 100% success rate
