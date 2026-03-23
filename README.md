# 🤖 ROS Robot Navigator

This repository contains a specialized **ROS-based navigation stack** designed for an autonomous mobile robot. The project focuses on the integration of sensor data to achieve precise **SLAM (Simultaneous Localization and Mapping)** and reliable path planning in dynamic environments.

## 🚀 Project Overview
The navigator utilizes a combination of Laser Scan data (LiDAR) and Odometry to build a high-fidelity map of its surroundings. It calculates the most efficient path to a designated goal while performing real-time obstacle avoidance.

## 🛠️ Tech Stack
* **Framework:** ROS (Robot Operating System) Noetic/Melodic
* **Languages:** Python 3, C++ (CMake)
* **Simulators:** Gazebo (Physics Engine) & RViz (Visualization)
* **Key Packages:** `gmapping`, `amcl`, `move_base`, `map_server`

## 🧩 Key Features
* **Autonomous Path Planning:** Implements Dijkstra and A* algorithms for global trajectory calculation.
* **Dynamic Obstacle Avoidance:** Uses the **Dynamic Window Approach (DWA)** for local costmap updates and agile maneuvers.
* **Sensor Fusion:** Merges IMU and Encoder data to maintain accurate robot localization (EKF).
* **Modular Configuration:** YAML-based tuning for inflation layers, footprint padding, and velocity limits.

## 🖼️ Gallery

 RViz      
| :---: |  

<img width="997" height="721" alt="image" src="https://github.com/user-attachments/assets/08c14dcb-5af3-4911-912f-0aebd4d64126" />

Gazebo
| :---: | 

<img width="989" height="721" alt="image" src="https://github.com/user-attachments/assets/27eb2487-ba03-449a-8c51-e09ec5167c9b" />


## 🏁 Getting Started

### 1. Prerequisites
Ensure you have a ROS environment installed (Noetic recommended).
```bash
sudo apt-get install ros-noetic-navigation
sudo apt-get install ros-noetic-gmapping


