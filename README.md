# 🤖 ROS Robot Navigator

This project is a ROS-based navigation setup for an autonomous mobile robot. It focuses on getting a robot to understand its surroundings, build a map, and move to a target location safely — even when the environment isn’t static.

---

## 🚀 What it does

The system uses LiDAR and odometry data to create a map of the environment (SLAM) and figure out where the robot is at any given time. From there, it plans a path to a goal and adjusts in real time to avoid obstacles along the way.

---

## 🛠️ Tech Stack

- **Framework:** ROS (Noetic / Melodic)  
- **Languages:** Python 3, C++  
- **Simulation & Visualization:** Gazebo, RViz  

### Key ROS packages:
- `gmapping` → for SLAM  
- `amcl` → for localization  
- `move_base` → for navigation  
- `map_server` → for map handling  

---

## 🧩 Features

- **Autonomous Navigation**  
  Uses path planning algorithms like Dijkstra and A* to find efficient routes.

- **Obstacle Avoidance**  
  Applies the Dynamic Window Approach (DWA) to react to obstacles in real time.

- **Sensor Fusion**  
  Combines IMU and encoder data (EKF) to improve localization accuracy.

- **Configurable Setup**  
  Uses YAML files to tweak things like robot footprint, inflation radius, and speed limits.

---

## 🖼️ Gallery

 RViz      
| :---: |  

<img width="997" height="721" alt="image" src="https://github.com/user-attachments/assets/08c14dcb-5af3-4911-912f-0aebd4d64126" />

Gazebo
| :---: | 

<img width="989" height="721" alt="image" src="https://github.com/user-attachments/assets/27eb2487-ba03-449a-8c51-e09ec5167c9b" />

---

## Notes

This project is mainly aimed at understanding how different parts of the ROS navigation stack come together — from mapping and localization to planning and control.


