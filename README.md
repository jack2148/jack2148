# Yeachan Kim

**Undergraduate @ HYU ERICA | Robotics · Manipulation · Perception · ROS2**

I build robotic systems that bridge perception and control — from navigation benchmarks to manipulation pipelines.
Focused on AI-based robot control, environment recognition, and learning-based approaches toward real-world task execution.

---

## About

- B.E. candidate in Robotics Engineering, Hanyang University ERICA
- Research interests: perception-driven navigation, learning-based robot control, object pose estimation, autonomous mobile robots
- Building toward robust robot autonomy through perception-control integration

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

**[rgbd-object-pose-estimation](https://github.com/jack2148/rgbd-object-pose-estimation)**
— RGB-D based object position and orientation estimation for robotic manipulation
- Performed instance segmentation using YOLOv8n-seg on custom industrial object dataset
- Estimated 3D object position via depth-based back-projection using Intel RealSense D455
- Approximated object orientation using contour-based geometric analysis
- Integrated as a ROS2 perception module publishing object pose data at 10 Hz

---

## Perception Expansion

Extending toward camera-based perception to enable richer scene understanding beyond LiDAR geometry.

- RGB-D camera integration, point cloud processing
- Camera-robot calibration, object detection, 6D pose estimation
- Interested in perception-to-manipulation pipelines and learning-based robot control

---

## Stack

```
ROS2 (Nav2 / MoveIt2)   |   C / C++ / Python   |   Gazebo   |   LiDAR / IMU / RGB-D / Wheel Encoder
```

---

## Direction

- **Now** — Reproducible 2D navigation benchmark (DWB vs MPPI, quantitative metrics)
- **Next** — RGB-D perception integration, 3D navigation in cluttered environments
- **Later** — Perception-driven manipulation, imitation learning for robot control

---

📫 yeachan4842@gmail.com
