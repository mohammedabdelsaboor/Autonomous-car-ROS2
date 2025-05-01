# Autonomous Car with ROS 2 (Without LiDAR)

## Project Description

This repository presents a ROS 2-based autonomous driving system for a low-cost robotic car without relying on LiDAR sensors. The project focuses on mapping and navigation using alternative sensing techniques such as cameras, GPS, and IMU. It is designed for academic research, robotics experimentation, and autonomous systems development in resource-constrained environments.

## Objectives

- Build an autonomous navigation stack in ROS 2 for a small-scale robotic car.
- Perform SLAM 
- Enable autonomous navigation with path planning and obstacle avoidance.
- Utilize camera , GPS, and IMU for localization and environment perception.

## Hardware Setup

- Raspberry Pi 4 or Jetson Nano
- Differential drive or Ackermann-steering robot base
- Camera (e.g., USB webcam or Intel RealSense)
- IMU sensor (MPU6050 )
- GPS module (optional)
- Motor drivers ( L298N )
- ROS 2-compatible microcontroller 
## Software Stack

- ROS 2 
- Nav2: Navigation stack for path planning and control
- SLAM Toolbox or RTAB-Map (if using camera-based SLAM)
- Robot Localization package for sensor fusion (IMU )
- OpenCV for image processing and visual feedback

## Getting Started

1. Install ROS 2 and required packages:
   ```bash
   sudo apt install ros-humble-nav2-bringup ros-humble-slam-toolbox
