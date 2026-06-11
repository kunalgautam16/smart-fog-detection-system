# Smart Fog Detection System

An IoT-integrated hybrid deep learning system for real-time fog detection, vehicle detection, and intelligent speed recommendation in low-visibility environments.

## Overview

This project combines Computer Vision and IoT technologies to improve road safety during foggy weather conditions. The system analyzes road images, detects vehicles using a hybrid deep learning approach, estimates fog density, and recommends safe vehicle speeds in real time.

## Key Features

- Hybrid object detection using YOLOv8 and Faster R-CNN
- Real-time fog density estimation
- Intelligent vehicle speed recommendation
- ThingSpeak IoT cloud integration
- ESP32 deployment simulation using Wokwi
- Annotated visualization of detected vehicles
- Automated cloud-based monitoring

## Technologies Used

- YOLOv8
- Faster R-CNN
- Python
- OpenCV
- PyTorch
- NumPy
- Matplotlib
- ThingSpeak IoT
- ESP32
- Wokwi Simulator

## System Workflow

Input Road Image
→ Vehicle Detection (YOLOv8 + Faster R-CNN)
→ Prediction Fusion
→ Fog Density Estimation
→ Speed Recommendation
→ ThingSpeak Cloud Monitoring

## Performance

- Achieved 94.2% accuracy in fog detection
- Real-time vehicle detection and analysis
- Dynamic speed recommendation based on visibility conditions
- Successful IoT integration using ThingSpeak

## Project Outcomes

- Estimated fog density from road images
- Recommended safe vehicle speeds in real time
- Uploaded speed data to ThingSpeak cloud platform
- Simulated ESP32 deployment using Wokwi

## Repository Structure

```text
.
├── speed_in_fog.ipynb
├── README.md
├── requirements.txt
├── screenshots/
└── outputs/
```

## Future Improvements

- Real-time CCTV/Camera integration
- Advanced fog estimation models
- Traffic density analysis
- Edge deployment on physical ESP32 hardware
- Mobile dashboard integration

## Author

Kunal Gautam
