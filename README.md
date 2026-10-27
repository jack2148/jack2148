# Yea Chan Kim

**Robotics · Robot Learning · Manipulation**

Robotics Engineering undergraduate at Hanyang University ERICA and research intern at the Korea Institute of Industrial Technology (KITECH). My work connects robot systems, teleoperation, human demonstrations, imitation learning, and fixed-condition evaluation with failure analysis.

[Email](mailto:yeachan4842@gmail.com)

## Current Focus

Building manipulation workflows from Geomagic Touch teleoperation to demonstrations, LeRobot datasets, ACT and Diffusion Policy training, and spatial analysis of fixed evaluation results on a MuJoCo-simulated Franka FR3.

## Featured Research

### Franka Teleoperation

[franka-teleoperation](https://github.com/jack2148/franka-teleoperation) — Geomagic Touch teleoperation for a **MuJoCo-simulated Franka FR3**, including Cartesian mapping, damped least-squares inverse kinematics, null-space control, clutching, command conditioning, and haptic software validation.

Historical OMY-L100 work has a separate validation scope; this repository does not claim physical Franka deployment or exact reconstruction of the original OMY executable environment.

### Franka Imitation Learning

[franka-imitation-learning](https://github.com/jack2148/franka-imitation-learning) — Geomagic Touch demonstrations → LeRobot dataset → ACT / Diffusion Policy → frozen TEST50 → spatial and failure analysis.

The dataset contains **50 demonstrations and 48,272 frames** of operator and wrist RGB at **20 Hz**.

On the **same frozen TEST50**, ACT 300k succeeded in **27/50 (54%)** trials and Diffusion Policy 480k in **43/50 (86%)**. These results describe the specified checkpoints and configurations, not algorithm-wide superiority.

## Supporting Robotics Systems

### RGB-D Object Pose Estimation

[rgbd-object-pose-estimation](https://github.com/jack2148/rgbd-object-pose-estimation) — Intel RealSense D455, YOLOv8 segmentation, FoundationPose integration, and ROS 2 outputs for manipulation perception.

Mean mask mAP50 is approximately **0.929**; this is a **segmentation metric, not 6D pose accuracy**.

### ROS 2 Navigation

[navigation_stack_lab](https://github.com/jack2148/navigation_stack_lab) — Real-robot ROS 2 system integration across sensors and TF, SLAM, EKF / AMCL localization, Nav2, and DWB / MPPI navigation.

Additional supporting work: [DWB vs MPPI Experiment](https://github.com/jack2148/ROS2_MPPI_DWB_Experiment_ICROS) · [KAIST Path Tracking](https://github.com/jack2148/Kaist-ROS2_path-tracking)

## Selected Research Outputs

- “Performance Comparison of DWB and MPPI Local Planners in ROS 2 Nav2 Environment” — ICROS 2026 poster, first author
- “Multimodal Perception and Monitoring System for Indoor Security Patrol Robots” — ICROS 2026 poster

## Selected Awards

- 1st Place — 2026 Creative Comprehensive Design Competition
- Bronze Award — College of Engineering Capstone Design Competition
- Finalist — KAIST Mobility Challenge 2025
- Undergraduate Paper Award — ICROS 2026

## Technical Stack

`ROS 2 · MuJoCo · LeRobot · ACT · Diffusion Policy · Python · C/C++ · PyTorch · Nav2 · SLAM · YOLOv8 · FoundationPose`
