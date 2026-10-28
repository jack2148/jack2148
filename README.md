# Yea Chan Kim

**Robotics · Robot Learning · Manipulation**

Robotics Engineering undergraduate at Hanyang University ERICA and research intern at the Korea Institute of Industrial Technology (KITECH). My work spans robot systems, teleoperation, human demonstrations, imitation learning, and controlled policy evaluation.

[Email](mailto:yeachan4842@gmail.com)

## Current Focus

Building manipulation workflows from Geomagic Touch teleoperation to demonstrations, LeRobot datasets, ACT and Diffusion Policy training, and controlled evaluation on a MuJoCo-simulated Franka FR3.

## Featured Research

### Franka Teleoperation

[franka-teleoperation](https://github.com/jack2148/franka-teleoperation) — Geomagic Touch teleoperation for a **MuJoCo-simulated Franka FR3**, including Cartesian mapping, damped least-squares inverse kinematics, null-space control, clutching, command conditioning, and haptic software validation.

The teleoperation stack also supports OMY-L100 leader input.

### Franka Imitation Learning

[franka-imitation-learning](https://github.com/jack2148/franka-imitation-learning) — Geomagic Touch demonstrations → LeRobot dataset → ACT / Diffusion Policy training → frozen TEST50 evaluation.

The dataset contains **50 demonstrations and 48,272 frames** of operator and wrist RGB at **20 Hz**.

ACT and Diffusion Policy were evaluated on the **same frozen TEST50 of 50 different initial states**, with **27/50** and **43/50** successful rollouts respectively. These results describe the evaluated checkpoints under the same test protocol and do not establish general algorithm superiority.

At KITECH, I also collected teleoperation demonstrations on physical Franka FR3 and UR5 systems using Sigma / Omega leader devices.

## Supporting Robotics Systems

### RGB-D Object Pose Estimation

[rgbd-object-pose-estimation](https://github.com/jack2148/rgbd-object-pose-estimation) — Intel RealSense D455, YOLOv8 segmentation, FoundationPose integration, and ROS 2 outputs for manipulation perception.

Mean mask mAP50 is approximately **0.929**; this is a **segmentation metric, not 6D pose accuracy**.

### ROS 2 Navigation

[navigation_stack_lab](https://github.com/jack2148/navigation_stack_lab) — Real-robot ROS 2 system integration across sensors and TF, SLAM, EKF / AMCL localization, Nav2, and DWB / MPPI navigation.

In the ICROS planner study, DWB and MPPI were evaluated across **2 scenarios × 5 runs per planner**, for **20 physical-robot runs** under the same map, waypoint, and costmap conditions.

- Static obstacle: MPPI **5/5 successful runs**, DWB **0/5 successful runs**
- Narrow turn: both planners **5/5**, with MPPI achieving **1.77× lower position error**

Additional supporting work: [DWB vs MPPI Experiment](https://github.com/jack2148/ROS2_MPPI_DWB_Experiment_ICROS) · [KAIST Path Tracking](https://github.com/jack2148/Kaist-ROS2_path-tracking)

## Selected Research Outputs

- “Performance Comparison of DWB and MPPI Local Planners in ROS 2 Nav2 Environment” — ICROS 2026 poster, **First Author**
- “Multimodal Perception and Monitoring System for Indoor Security Patrol Robots” — ICROS 2026 poster, **Co-Author · Undergraduate Paper Award**

## Selected Awards

- Bronze Award — College of Engineering Capstone Design Competition, 2026.09
- Undergraduate Paper Award — ICROS 2026, 2026.07
- 1st Place — Creative Comprehensive Design Competition, 2026.06
- Finalist — KAIST Mobility Challenge 2025, 2026.02

## Technical Stack

`ROS 2 · MuJoCo · LeRobot · Teleoperation · Imitation Learning (ACT, Diffusion Policy) · Python · C/C++ · PyTorch · Nav2 · SLAM`
