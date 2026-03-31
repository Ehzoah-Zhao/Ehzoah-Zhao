# Haozhe Zhao

Student Researcher & Developer | **Fudan University**

**Research Focus:** Embodied AI, Robotics, and Spatial Awareness.

## Featured Work

* **G1-MotionFlow: Natural Language-Driven Humanoid Motion Generation**
  * Engineered a 3-stage pipeline (VQ-VAE, T5-Base, PPO) mapping semantic instructions to physical actuation for the 29-DoF Unitree G1.
  * Resolved cumulative "zero-drift" errors via an active over-redundancy strategy (fusing joint angles and spatial positions).
  * Achieved <1s end-to-end latency for zero-shot text-to-motion execution in MuJoCo simulations.

* **ROS Multi-Agent SLAM: Multi-Sensor Fusion Localization & Mapping**
  * Developed distributed spatial awareness pipelines integrating UWB, LiDAR, IMU, and odometry data for wheeled robots.
  * Optimized complex `tf` tree transforms and inter-node communication synchronization across multiple operating agents.

## Tech Stack

* **Frameworks/Simulators:** ROS 1 / ROS 2, MuJoCo, Unitree SDK
* **AI/Deep Learning:** PyTorch, Reinforcement Learning (PPO), LLMs, VQ-VAE
* **Languages:** C++, Python
