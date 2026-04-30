# Yeachan Kim

**Undergraduate @ HYU ERICA | Robotics · SLAM · Navigation · ROS2**

I build and experiment with robotic navigation systems — focusing on reproducible evaluation, sensor fusion, and real-world robustness.
Currently expanding from LiDAR-based navigation toward 3D vision and perception-driven autonomy.

---

## About

- B.E. candidate in Mechanical Engineering, Hanyang University ERICA
- Research interest: autonomous mobile robots, 2D/3D SLAM, local planner optimization, 3D perception
- Building toward graduate research in robot navigation and perception

---

## Current Work

**[navigation_stack_lab](https://github.com/jack2148/navigation_stack_lab)**
— ROS2-based platform for controlled comparison of mobile robot navigation algorithms

| Focus | Details |
|---|---|
| SLAM | LiDAR-only / LiDAR + Wheel Encoder fusion |
| Planner Benchmark | DWB vs MPPI under Nav2 |
| Evaluation Metrics | Time-to-goal, collision rate, trajectory smoothness, CPU load |
| Robustness | Injected sensor noise and latency experiments |

---

## Selected Projects

**[Kaist-ROS2_path-tracking](https://github.com/jack2148/Kaist-ROS2_path-tracking)**
— KAIST Mobility Challenge
- Implemented and compared Pure Pursuit and Stanley lateral control algorithms
- Tuned parameters for stable path tracking under varying driving conditions

**[Lidar_drive_competition](https://github.com/jack2148/Lidar_drive_competition)**
— LiDAR-based Obstacle Avoidance
- Cone and obstacle detection using 2D LiDAR
- Reactive control logic for real-time avoidance
- Documented sensor limitations and failure cases

---

## Perception Expansion

Extending toward camera-based perception to enable richer scene understanding beyond LiDAR geometry.

- RGB-D camera integration, point cloud processing
- Camera-robot calibration, object detection, 6D pose estimation
- Perception-to-action pipeline for navigation and manipulation

---

## Stack

```
ROS2 (Nav2)   |   C / C++ / Python   |   Gazebo   |   LiDAR / IMU / Wheel Encoder / RGB-D
```

---

## Direction

- **Now** — Reproducible 2D navigation benchmark (DWB vs MPPI, quantitative metrics)
- **Next** — RGB-D perception integration, 3D navigation in cluttered environments
- **Later** — Perception-driven autonomous navigation, learning-based SLAM and planning

---

📫 yeachan4842@gmail.com
