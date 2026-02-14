# Yechan Kim
HYU ERICA Robotics | SLAM | Navigation | ROS2

I design and implement reproducible robotic navigation systems.  
My focus is on SLAM, local planner optimization, and robust navigation under real-world uncertainty.

---

## 🔬 Current Focus

- 2D LiDAR + Wheel Encoder SLAM
- ROS2 Nav2 local planner benchmarking (DWA vs TEB vs MPPI)
- Quantitative evaluation of navigation performance
- Robustness under sensor noise and latency

---

## 🧪 Main Project

### navigation_stack_lab

A ROS2-based navigation research platform built for controlled experimental comparison.

**Scope**
- LiDAR-only SLAM
- LiDAR + Wheel Odometry SLAM
- Nav2 Local Planner Comparison
- Parameter tuning & failure case analysis

**Evaluation Metrics**
- Time-to-goal (sec)
- Collision rate (%)
- Trajectory smoothness (Σ|Δθ|)
- CPU load (%)
- Stability under injected noise

**Goal**
Build a reproducible benchmark framework for 2D navigation and extend it toward 3D perception-based planning.

---

## 🏁 Selected Work

- Pure Pursuit vs Stanley Controller comparison (autonomous driving competition)
- Parameter sensitivity experiments
- Failure case documentation with rosbag-based analysis

---

## 🛠 Technical Stack

- ROS2 (Nav2)
- C++ / Python
- Gazebo Simulation
- LiDAR, IMU, Wheel Encoder
- Experimental design & system-level debugging

---

## 🎯 Research Direction

Short-term:
- High-robustness 2D navigation benchmark platform

Mid-term:
- Depth-based 3D mapping
- 3D navigation in cluttered environments

Long-term:
- Learning-based SLAM and planning integration

---

📫 Contact: yeachan4842@gmail.com
