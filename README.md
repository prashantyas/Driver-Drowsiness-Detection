Driver Drowsiness Detection

Overview
Driver fatigue is a leading cause of road accidents. This project is a real-time Driver Drowsiness Detection System built using Python. It monitors the driver’s facial landmarks, detects signs of drowsiness by analyzing the Eye Aspect Ratio (EAR) using Euclidean distance, and provides audible alerts to prevent accidents.

Features
Real-time Detection: Monitors the driver’s eyes using a webcam feed.
Alert System: Triggers a warning sound when drowsiness is detected.
Lightweight and Efficient: Implements fast algorithms for immediate feedback.
Customizable Thresholds: Adjust sensitivity to suit different conditions.

Tech Stack
Python
OpenCV: For video stream handling and facial feature detection.
dlib: For detecting facial landmarks.
imutils: For streamlining image processing tasks.
pygame: For playing audio alerts.

How It Works
Captures live video feed using a webcam.
Detects facial landmarks (eyes) using dlib.
Calculates the Eye Aspect Ratio (EAR) using Euclidean distance between eye landmarks.
If the EAR drops below a predefined threshold for a specific duration, it triggers an alert sound using pygame.

Requirements
Python 3.x
Webcam for live video feed
Libraries: opencv-python, dlib, imutils, pygame

Future Improvements
Integrating a mobile app for remote alerts.
Adding support for additional signs of drowsiness (e.g., yawning).
Optimizing for edge devices like Raspberry Pi.
