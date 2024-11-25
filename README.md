 Dynamic Face Tracking and Route Prediction Across Distributed Camera Network

Overview

This project presents a framework for enhancing surveillance systems through real-time face recognition and pedestrian trajectory prediction. By integrating MobileFaceNet for face identification and a Partial Trajectory Matching Algorithm, the system facilitates the prediction of individual movements across a distributed camera network.

Objectives

Develop a real-time face recognition system.
Predict pedestrian routes based on historical trajectory data.
Improve security monitoring and situational awareness.
Key Features

Face Recognition:
Uses MobileFaceNet for high accuracy and fast processing.
Matches live video feed faces against a database of known individuals.
Route Prediction:
Predicts future movement paths using historical trajectory data.
Employs Partial Trajectory Matching for efficient prediction.
Performance Metrics:
Achieves 87.5% accuracy in face recognition.
Trajectory prediction reaches 80% accuracy with improvements observed by incorporating additional historical nodes.
Implementation

Tools and Technologies
Frameworks: MobileFaceNet for face recognition, Partial Trajectory Matching for path prediction.
Hardware:
4 Logitech C920 HD webcams for video feed.
Intel Core i5, 16GB RAM, NVIDIA GeForce GTX 1660 GPU for processing.
Software: Python and OpenCV libraries.
Workflow
Face Recognition:
Detects and identifies faces in video feeds.
Matches detected faces against a database of known embeddings.
Trajectory Prediction:
Segments real-time paths into smaller components.
Matches these segments against historical data to predict future movements.
Results

Face Recognition:
Precision: 87.5%
Recall: 77.8%
F1 Score: 82.3%
Trajectory Prediction:
Achieves 80% accuracy using historical data.
Improved to 100% with additional trajectory nodes.
Applications

Security and Surveillance:
Crime prevention through proactive monitoring.
Enhanced situational awareness for law enforcement agencies.
Traffic Management:
Pedestrian flow analysis and management.
Public Safety:
Real-time monitoring in high-security zones.
Future Work

Integrating larger datasets and CCTV networks.
Incorporating additional waypoints for improved trajectory prediction accuracy.
Enhancing camera deployment strategies to minimize recognition errors.
Access Information

This work is published and available for detailed review on the IEEE Xplore website. You can view the abstract and full paper at the following link:
https://ieeexplore.ieee.org/abstract/document/10730825
