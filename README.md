# Yeachan Kim

**Undergraduate @ HYU ERICA | Robotics · 3D Perception · Navigation · ROS2**

I build robotic systems that connect perception, navigation, and control.  
My current focus is ROS2-based mobile robot navigation and RGB-D perception for object understanding in real-world robotic systems.

---

## About

- B.E. candidate in Robotics Engineering, Hanyang University ERICA
- Research interests: 3D perception, RGB-D vision, object pose estimation, perception-driven navigation, autonomous mobile robots
- Building toward robust robot autonomy through perception-control integration

---

## Current Work

**[navigation_stack_lab](https://github.com/jack2148/navigation_stack_lab)**  
— ROS2-based platform for controlled comparison of mobile robot navigation algorithms

| Focus | Details |
|---|---|
| SLAM | 2D LiDAR-based mapping and localization |
| Sensor Fusion | LiDAR + Wheel Encoder-based navigation |
| Planner Benchmark | DWB vs MPPI under ROS2 Nav2 |
| Evaluation Metrics | Time-to-goal, collision rate, trajectory smoothness, CPU load |
| Robustness | Sensor noise and latency experiments |

---

## Selected Projects

**[rgbd-object-pose-estimation](https://github.com/jack2148/rgbd-object-pose-estimation)**  
— RGB-D based object position and orientation estimation for robotic perception
- Performed instance segmentation using YOLOv8n-seg on a custom industrial object dataset
- Estimated 3D object position via depth-based back-projection using Intel RealSense D455
- Approximated object orientation using contour-based geometric analysis
- Integrated as a ROS2 perception module publishing object pose data at 10 Hz

**[Kaist-ROS2_path-tracking](https://github.com/jack2148/Kaist-ROS2_path-tracking)**  
— KAIST Mobility Challenge
- Implemented Pure Pursuit and Stanley lateral control algorithms for path tracking
- Tuned parameters for stable path tracking under varying driving conditions
- Integrated ROS2-based path tracking components for autonomous driving scenarios

**[Lidar_drive_competition](https://github.com/jack2148/Lidar_drive_competition)**  
— LiDAR-based Obstacle Avoidance
- Implemented cone and obstacle detection using 2D LiDAR
- Developed reactive control logic for real-time obstacle avoidance
- Documented sensor limitations and failure cases from real-world testing

---

## 3D Perception Expansion

I am expanding from LiDAR-based navigation toward RGB-D based robot perception to enable richer scene understanding beyond 2D geometry.

- RGB-D camera integration and depth-based 3D position estimation
- Object detection and instance segmentation for industrial objects
- Point cloud processing and camera-robot calibration
- Perception modules for robot manipulation and autonomous navigation pipelines

---

## Stack

Programming: C / C++ / Python 
Frameworks Tools: ROS 2 / Nav2 / GitHub
Sensors: LiDAR / IMU / RGB-D / Wheel Encoder


---

## Direction

- **Now** — ROS2-based 2D navigation benchmark with quantitative evaluation
- **Next** — RGB-D perception integration and point cloud-based object understanding
- **Later** — Perception-driven autonomous navigation in cluttered and dynamic environments

---

## Contact

📫 yeachan4842@gmail.com
