<img width="2075" height="352" alt="REDME_banner" src="https://github.com/user-attachments/assets/04a75c9c-c35f-46af-b2ea-7024a1655b93" />

PNDbotics is committed to building an efficient, end-to-end  humanoid robot platform that streamlines the development, simulation, and deployment processes of AI robots, and further drives breakthroughs in robotics and embodied AI.
As a full-stack developer and manufacturer of humanoid robots, We possess well-developed robotic technologies fused with artificial intelligence technology. The technologies we adopt are shown below:

- Model-Based Robot Gait Planning
- Whole-Body Motion Control Technology
- Embodied Intelligence Algorithms
- Deep Reinforcement Learning (DRL)-based motion control technology

[![Twitter](https://img.shields.io/badge/Twitter-@PNDbotics-1DA1F2?logo=twitter&logoColor=white)](https://x.com/PNDbotics)
[![YouTube](https://img.shields.io/badge/YouTube-ff0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/@PNDbotics)
[![Bilibili](https://img.shields.io/badge/-bilibili-ff69b4?style=flat&labelColor=ff69b4&logo=bilibili&logoColor=white)](https://space.bilibili.com/303744535)

# Open Source Projects
| Title | Description |
|-------|-------------|
| [pnd_models](https://github.com/pndbotics/pnd_models) | This repository contains PNDbotics model files for simulation and control, including URDF/MJCF descriptions, mesh assets, and more. |
| [pnd_teleoperation](https://github.com/pndbotics/pnd_teleoperation) | A ROS2-based motion capture retargeting system that converts human motion data to robot control commands using CasADi optimization. Supports real-time processing from Noitom mocap systems and provides both simulation preview and robot control capabilities for Adam SP/Adam U configurations. |
| [adam_u_deploy](https://github.com/pndbotics/adam_u_deploy) | DDS and ROS2 deployment package for Adam-U control. Provides real-time joint command and state communication for motion retargeting applications, supporting both hand-included and handless configurations of the Adam-U. |
| [pnd_mujoco](https://github.com/pndbotics/pnd_mujoco) | MuJoCo simulation environment, supporting dual data modes (raw for training/simulation, scaled for real-world teleoperation) and integrated with ROS2 Humble for control and configuration. |
| [pnd_sdk_python](https://github.com/pndbotics/pnd_sdk_python) | Python interface for PND SDK |
| [pnd_ros2](https://github.com/pndbotics/pnd_ros2) | The PNDbotics SDK2 implements an easy-to-use robot data communication mechanism based on CycloneDDS, allowing application developers to perform robot data exchange and command control through this interface. Since ROS2 also uses DDS as its communication middleware, Adam’s underlying system is compatible with ROS2. Developers can directly communicate and control the robot using ROS2’s built-in messages, without needing to relay data through the SDK interface. |
| [pnd_rl_gym](https://github.com/pndbotics/pnd_rl_gym) | Public pnd humanoid robot Adam training env based on legged gym |
| [pnd_adam_ros2_publish](https://github.com/pndbotics/pnd_adam_ros2_publish) | ROS2 deployment package for publishing real-time motion commands to Adam. Enables control of body posture, height, upper limbs, and fingers through Xbox-activated data transmission mode. |
| [adam_u_isaac_lab](https://github.com/pndbotics/adam_u_isaac_lab) | This repository provides a minimal example of loading the Adam into Isaac Lab and running simple RL training tasks. It is intended as a starting point for robot manipulation with Isaac Lab — both the RL algorithm and the environment design can (and should) be further extended. |
