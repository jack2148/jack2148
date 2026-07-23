# Yeachan Kim

**Robotics undergraduate building real-robot systems and controlled experiments — now developing teleoperation-based data collection and imitation learning for manipulation.**

## About

Robotics Engineering undergraduate at Hanyang University ERICA, graduating in August 2027. I build and evaluate real-robot systems—from sensor fusion and navigation to RGB-D perception—and am extending that systems experience into teleoperation-based data collection and imitation learning with ACT and Diffusion Policy for manipulation.

## Current Work

**[OMY_FRANKA_TELEOP](https://github.com/jack2148/OMY_FRANKA_TELEOP)** — **Status: Ongoing.** A cross-embodiment Cartesian teleoperation pipeline that transfers a real OMY-L100 leader arm to a Franka FR3 in MuJoCo. OMY-to-MuJoCo synchronization is complete; FR3 Cartesian retargeting is in progress.

**[dp-act-policy-study](https://github.com/jack2148/dp-act-policy-study)** — Controlled Push-T imitation-learning experiments in LeRobot. Diffusion Policy reached **24%** success, compared with **2%** for the baseline ACT configuration and **12%** for ACT with the temporal-ensembling execution strategy removed.

## Selected Projects

**[navigation_stack_lab](https://github.com/jack2148/navigation_stack_lab)** — Real-hardware ROS2 patrol robot: SLAM, EKF sensor fusion, Nav2, MPPI tuning, and person-following logic. The linked experiment repository reports controlled DWB–MPPI comparisons.

**[rgbd-object-pose-estimation](https://github.com/jack2148/rgbd-object-pose-estimation)** — RealSense D455 RGB-D perception with YOLOv8 segmentation and a FoundationPose-based 6D-pose path published as ROS2 messages; mean Mask mAP50: **0.9290**.

**[Kaist-ROS2_path-tracking](https://github.com/jack2148/Kaist-ROS2_path-tracking)** — Compared and tuned Pure Pursuit and Stanley lateral controllers for KAIST Mobility Challenge path tracking.

**[Lidar_drive_competition](https://github.com/jack2148/Lidar_drive_competition)** — 2D LiDAR obstacle/cone detection and reactive avoidance, including sensor limitations and failure cases.

## Direction

- **Now** — Teleoperation-based data collection and ACT/Diffusion Policy comparison experiments.
- **Next** — Sim-to-real transfer to a real FR3: collect real demonstrations and train and run policies.
- **Later** — Extend manipulation work to the RBY-1 humanoid.

📫 yeachan4842@gmail.com

## Stack

`ROS2 · Nav2 · MoveIt2 · PyTorch · LeRobot · Python · C/C++ · MuJoCo · Gazebo · LiDAR · IMU · RGB-D · Wheel Encoder`
