# Yea Chan Kim

**Robotics · Robot Learning · Manipulation**

Robotics Engineering undergraduate at Hanyang University ERICA and undergraduate research intern at KITECH since July 2026. Current work focuses on teleoperation-based manipulation demonstrations, imitation learning, and data-efficient demonstration collection. Interested in hybrid robot-learning approaches that combine data-driven policies with robot kinematics and structured control.

[Email](mailto:yeachan4842@gmail.com)

## Current Research

### 1. Teleoperation & Manipulation Learning

**[OMY_FRANKA_TELEOP](https://github.com/jack2148/OMY_FRANKA_TELEOP)**

Built a teleoperation pipeline from a physical OMY-L100 leader to a Franka FR3 in MuJoCo, including Cartesian pose retargeting, 6D-to-7DoF damped least-squares inverse kinematics, and null-space control. This is a simulation-stage FR3 system; deployment to physical FR3 hardware is not claimed.

### 2. Imitation Learning & Policy Analysis

**[dp-act-policy-study](https://github.com/jack2148/dp-act-policy-study)**

Studying ACT and Diffusion Policy in LeRobot-based manipulation tasks, including Push-T analysis and FR3 MuJoCo experiments using teleoperation demonstrations. Current work investigates how execution strategy, investigates the relationship between execution strategy, trajectory coverage, demonstration distribution, and policy behavior

The Push-T study includes exploratory 50-episode comparisons of ACT execution configurations.

## Research Interests

My broader research interest is in robotic manipulation architectures that separate learning-based decision making from kinematics- and control-based execution, combining data-driven policies with structured robot control.

## Supporting Robotics Systems Work

**[rgbd-object-pose-estimation](https://github.com/jack2148/rgbd-object-pose-estimation)** — RGB-D manipulation perception using an Intel RealSense D455, YOLOv8-seg, CAD meshes, and FoundationPose. The verified mean mask mAP50 is **0.929** across three industrial-part classes; this is a segmentation metric, not 6D-pose accuracy.

**[navigation_stack_lab](https://github.com/jack2148/navigation_stack_lab)** — Real-hardware ROS 2 navigation and system integration with SLAM, EKF sensor fusion, Nav2, DWB/MPPI experiments, and person-following logic. MPPI computation and parameters were optimized to improve the control loop from approximately 5–6 Hz to a stable 20 Hz.

## Selected Achievements

- 1st Place — 2026 Creative Comprehensive Design Competition
- Bronze Award — College of Engineering Capstone Design Competition
- Final — KAIST Mobility Challenge 2025
- Undergraduate Paper Award — ICROS 2026

## Publications / Presentations

- “Performance Comparison of DWB and MPPI Local Planners in ROS 2 Nav2 Environment” — ICROS 2026, poster, first author
- “Multimodal Perception and Monitoring System for Indoor Security Patrol Robots” — ICROS 2026, poster, Undergraduate Paper Award

## Technical Areas

`ROS 2 · MuJoCo · LeRobot · ACT · Diffusion Policy · Python · C/C++ · Nav2 · SLAM · MPPI · DWB · RGB-D · YOLOv8 · FoundationPose`
