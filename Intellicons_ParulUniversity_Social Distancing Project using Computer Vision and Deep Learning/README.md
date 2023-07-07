## Overview

In the wake of the COVID-19 pandemic, maintaining social distancing has become crucial for public health and safety. This project aims to develop a robust solution that can automatically detect and monitor social distancing violations in real-time using computer vision and deep learning.
## Features

- Detection and tracking of people in a given scene using computer vision algorithms.
- Calculation of the distance between individuals based on their spatial relationships.
- Identification and visualization of social distancing violations.
- Real-time monitoring of social distancing measures.
- Integration with Intel's OpenVINO toolkit for optimized inference on Intel hardware.

## Key Components

1. Data Collection: The project provides scripts and utilities to collect and prepare training data, including annotated images or videos containing people.
2. Model Training: We used Intel's Pre-Trained models for getting better accuracy in the person detection.
3. Distance Calculation: Spatial relationships between detected individuals are analyzed to determine the distance between them.
4. Violation Detection: A set of rules or thresholds is defined to identify social distancing violations based on the calculated distances.
5. Visualization: The violations are highlighted and visualized on the original scene, providing a clear indication of where social distancing measures are not being followed.
6. Real-time Monitoring: The system is capable of processing live video streams, enabling real-time monitoring of social distancing compliance.
7. OpenVINO Integration: The project demonstrates the utilization of Intel's OpenVINO toolkit to optimize and accelerate deep learning inference on Intel hardware.
