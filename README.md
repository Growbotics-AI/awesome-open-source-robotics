# Awesome Open Source Robotics

**[中文版 (Chinese)](README_zh.md)**

> A curated list of inspiring and impactful open-source robotics projects, tools, and resources.

This list is intentionally **selective**. For the full database with BOMs, assembly guides, and detailed information, visit **[Open Source Robotics](https://robotics.growbotics.ai)**.

---

## Contents

- [Projects](#projects)
  - [Robotic Arms](#robotic-arms)
  - [Robotic Hands](#robotic-hands)
  - [Humanoids](#humanoids)
- [Software & Frameworks](#software--frameworks)
- [Foundation Models](#foundation-models)
- [Simulators](#simulators)
- [Benchmarks](#benchmarks)
- [Datasets](#datasets)
- [Research](#research)
  - [Papers](#papers)
  - [Books](#books)
  - [Courses](#courses)
- [Events](#events)
- [People to Follow](#people-to-follow)
- [Podcasts](#podcasts)
- [YouTube Channels](#youtube-channels)
- [Blogs](#blogs)
- [Inspiring Companies](#inspiring-companies)
- [License](#license)

---

## Projects

A curated selection of notable open-source robotics projects.

### Robotic Arms

- **[SO-101 Open Robot Arm](https://github.com/TheRobotStudio/SO-ARM100)**  
  6-DOF robot arm for teleoperation and AI robotics research

- **[BCN3D Moveo](https://github.com/BCN3D/BCN3D-Moveo)**  
  Open-source 3D printed robotic arm for education

- **[OpenArm](https://github.com/enactic/openarm)**  
  7DOF humanoid arm for physical AI research in contact-rich environments

### Robotic Hands

- **[Aero Hand Open](https://github.com/TetherIA/aero-hand-open)**  
  Tendon-driven robotic hand: 389g, $314, 7 DOF with Python SDK and ROS2

- **[TRLC-DK1](https://github.com/robot-learning-co/trlc-dk1)**  
  Bimanual robot platform for humanoid data collection with LeRobot

- **[LEAP Hand](https://github.com/leap-hand/LEAP_Hand_API)**  
  Low-cost anthropomorphic hand with 16 DOF for robot learning

- **[Delta X Soft Gripper](https://github.com/deltaxrobot/Delta-X-3D-Printed-Parts)**  
  $10 DIY food-grade soft gripper using 3D-printed molds and silicone

- **[DexHand v2.3](https://github.com/TheRobotStudio/V2_DexHand)**  
  Open-source dexterous hand design from The Robot Studio and NVIDIA

### Humanoids

- **[Mobile ALOHA](https://github.com/MarkFzp/mobile-aloha)**  
  $32k whole-body teleoperation system for bimanual mobile manipulation

- **[LeKiwi](https://github.com/SIGRobotics-UIUC/LeKiwi)**  
  Low-cost holonomic mobile manipulator with SO-ARM101 and LeRobot

- **[HOPEJr](https://github.com/TheRobotStudio/HOPEJr)**  
  DIY humanoid robot with 66 DOF, 3D-printed parts, and LeRobot support

## Software & Frameworks

Essential tools and frameworks for robotics development.

- **[LeRobot](https://github.com/huggingface/lerobot)**  
  HuggingFace ML library for real-world robotics in PyTorch

- **[ROS 2](https://github.com/ros2/ros2)**  
  Next-gen Robot Operating System for real-time production robotics

- **[Dora AI](https://github.com/dora-rs/dora)**  
  Dataflow middleware for AI robotics applications, built in Rust

- **[RLinf](https://github.com/RLinf/RLinf)**  
  Scalable infrastructure for post-training foundation models via RL

- **[Extreme Parkour with Legged Robots](https://github.com/chengxuxin/extreme-parkour)**  
  RL system for legged robot parkour trained in under 20 hours

## Foundation Models

AI models for robotics and embodied intelligence.

- **[OpenPI](https://github.com/Physical-Intelligence/openpi)**  
  Physical Intelligence VLA foundation models for general robot control

- **[NVIDIA Isaac GR00T](https://github.com/NVIDIA/Isaac-GR00T)**  
  NVIDIA open foundation model for humanoid robot reasoning and skills

- **[OpenVLA](https://github.com/openvla/openvla)**  
  7B-parameter Vision-Language-Action model for robotic manipulation

- **[ACT (Action Chunking with Transformers)](https://github.com/tonyzhaozh/act)**  
  Transformer-based policy learning for bimanual manipulation

- **[SmolVLA](https://huggingface.co/lerobot/smolvla_base)**  
  450M parameter VLA model that runs on consumer hardware

## Simulators

Physics simulators and virtual environments for robotics development and testing.

- **[GENESIS](https://github.com/Genesis-Embodied-AI/Genesis)**  
  World's fastest physics engine: 43M FPS for embodied AI learning

- **[MuJoCo](https://github.com/google-deepmind/mujoco)**  
  DeepMind physics engine for robotics and ML research

- **[Isaac Lab](https://github.com/isaac-sim/IsaacLab)**  
  NVIDIA unified robotics learning framework on Isaac Sim

- **[ManiSkill](https://github.com/haosulab/ManiSkill)**  
  GPU-parallelized simulation for generalizable manipulation skills

- **[NVIDIA Isaac Sim](https://github.com/isaac-sim/IsaacSim)**  
  NVIDIA Omniverse app for AI-driven robot simulation and testing

## Benchmarks

Standardized benchmarks and evaluation frameworks for robotics research.

- **[MetaWorld](https://github.com/Farama-Foundation/Metaworld)**  
  Multi-task and meta RL benchmark for robotic manipulation

- **[RLBench](https://github.com/stepjam/RLBench)**  
  100+ task benchmark for vision-guided manipulation research

- **[LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO)**  
  Lifelong robot learning benchmark with 130 procedural tasks

- **[CALVIN](https://github.com/mees/calvin)**  
  Language-conditioned manipulation benchmark for long-horizon tasks

## Datasets

Training datasets for robot learning and research.

- **[Open X-Embodiment (OXE)](https://github.com/google-deepmind/open_x_embodiment)**  
  Largest open robotics dataset: 1M+ episodes from 22 embodiments

- **[DROID](https://github.com/droid-dataset/droid)**  
  76K robot manipulation trajectories from 564 diverse scenes

**[Browse all projects on Open Source Robotics](https://robotics.growbotics.ai/projects)**

---

## Research

### Papers

- **[Instant Policy: In-Context Imitation Learning via Graph Diffusion](https://arxiv.org/pdf/2411.12633.pdf)** - ICLR 2025 Robot Learning Workshop (Best Paper Award)

**[Browse all papers](https://robotics.growbotics.ai/research/papers)**

### Books

- **[Dancing with Roomba: Cracking the Robot Riddle and Building an Icon](https://www.amazon.com/Dancing-Roomba-Cracking-Riddle-Building/dp/1032889527)** by Joseph L. Jones

- **[Modern Robotics: Mechanics, Planning, and Control](https://www.amazon.com/Modern-Robotics-Mechanics-Planning-Control/dp/1107156300)** by Kevin M. Lynch, Frank C. Park

- **[Probabilistic Robotics](https://www.amazon.com/Probabilistic-Robotics-INTELLIGENT-ROBOTICS-AUTONOMOUS/dp/0262201623)** by Sebastian Thrun, Wolfram Burgard, Dieter Fox

**[Browse all books](https://robotics.growbotics.ai/research/books)**

### Courses

- **[Modern Robotics: Mechanics, Planning, and Control Specialization](https://www.coursera.org/specializations/modernrobotics)** on Coursera

- **[HuggingFace Robotics Course](https://huggingface.co/learn/robotics-course/unit0/1)** on Hugging Face

**[Browse all courses](https://robotics.growbotics.ai/research/courses)**

---

## Events

- **[IEEE International Conference on Robotics and Automation (ICRA)](https://2026.ieee-icra.org/)**

- **[Humanoids Summit](https://humanoidssummit.com/)**

- **[NeurIPS - Neural Information Processing Systems](https://neurips.cc/)**

- **[CoRL - Conference on Robot Learning](https://www.robot-learning.org/)**

**[View all events](https://robotics.growbotics.ai/events)**

---

## People to Follow

- **[Angela Schoellig](https://twitter.com/angelaschoellig)** (University of Toronto)

- **[Audrow Nash](https://twitter.com/audrow)**

- **[Chelsea Finn](https://twitter.com/chelseabfinn)** (Stanford University)

- **[Deepak Pathak](https://twitter.com/pathak2206)** (Carnegie Mellon University)

- **[Pieter Abbeel](https://twitter.com/pabbeel)** (UC Berkeley)

- **[Rémi Cadène](https://twitter.com/RemiCadene)** (UMA (Universal Mechanical Assistant))

**[Discover more researchers and engineers](https://robotics.growbotics.ai/community/people)**

---

## Podcasts

- **[Audrow Nash Podcast](https://open.spotify.com/show/74jWpWiLwsasY2QHtDcl8I)**

- **[RoboPapers](https://open.spotify.com/show/3U0Ed7poaOElItEyUPkuto)**

- **[The Robot Brains Podcast](https://open.spotify.com/show/1oQXUJBjpJoxfUd3JAc0Zt)**

**[Browse all podcasts](https://robotics.growbotics.ai/community/podcasts)**

---

## YouTube Channels

- **[Skyentific](https://www.youtube.com/@skyentific)**

- **[CMU Robotics Institute](https://www.youtube.com/@cmurobotics)**

**[Browse all channels](https://robotics.growbotics.ai/community/youtube)**

---

## Blogs

Robotics blogs and newsletters worth following.

- **[Six Degrees of Robotics](https://sixdegreesofrobotics.substack.com/)** by Christopher Sanchez

- **[State of Robot Learning — Dec 2025](https://vedder.io/misc/state_of_robot_learning_dec_2025.html)** by Kyle Vedder

- **[We All Are Robots](https://ziegler.substack.com)** by Lukas Ziegler

**[Browse all blogs](https://robotics.growbotics.ai/community/blogs)**

---

## Inspiring Companies

Robotics companies and research labs pushing the boundaries.

- **[1X Technologies](https://www.1x.tech)**  
  Developing general-purpose humanoid robots with scalable automation.

- **[Agility Robotics](https://www.agilityrobotics.com)**  
  Creators of Digit, a bipedal robot for real-world logistics.

- **[Apptronik](https://apptronik.com)**  
  Innovators in humanoid robots, including Apollo.

- **[Boston Dynamics](https://www.bostondynamics.com)**  
  Industry leader in dynamic robots like Spot and Atlas.

- **[Enchanted Tools](https://enchanted.tools)**  
  Creators of Miroka, emotionally engaging humanoid-like robots.

- **[Engineered Arts](https://www.engineeredarts.co.uk)**  
  Creators of Ameca, advanced humanoid robots for human interaction.

- **[Hanson Robotics](https://www.hansonrobotics.com)**  
  Developers of lifelike humanoid robots like Sophia.

- **[Sunday](https://www.sunday.ai)**  
  Building Memo, a household robot trained on 10 million real-world chores using...

**[Explore all companies](https://robotics.growbotics.ai/community/companies)**

---

## License

This list is licensed under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).

---

## Contributing

Suggestions welcome! Visit **[Open Source Robotics](https://robotics.growbotics.ai)** to suggest new content or open an issue in this repository.

---

**[Explore the full platform with BOMs, assembly guides, and more](https://robotics.growbotics.ai)**
