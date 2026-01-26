# 开源机器人精选

**[English](README.md)** | **[日本語](README_ja.md)** | **[Deutsch](README_de.md)** | **[Español](README_es.md)**

> 精选的开源机器人项目、工具和资源列表。

本列表经过**精心筛选**。如需查看完整数据库（包含物料清单、组装指南和详细信息），请访问 **[Open Source Robotics](https://robotics.growbotics.ai)**。

---

## 目录

- [项目](#项目)
  - [机械臂](#机械臂)
  - [机械手](#机械手)
  - [足式机器人](#足式机器人)
  - [人形机器人](#人形机器人)
- [软件与框架](#软件与框架)
- [基础模型](#基础模型)
- [仿真器](#仿真器)
- [基准测试](#基准测试)
- [数据集](#数据集)
- [研究](#研究)
  - [论文](#论文)
  - [书籍](#书籍)
  - [课程](#课程)
- [活动](#活动)
- [值得关注的人](#值得关注的人)
- [播客](#播客)
- [YouTube 频道](#youtube-频道)
- [博客](#博客)
- [优秀公司](#优秀公司)
- [许可证](#许可证)

---

## 项目

精选的开源机器人项目。

### 机械臂

- **[SO-101 Open Robot Arm](https://github.com/TheRobotStudio/SO-ARM100)**
  用于遥操作和AI机器人研究的6自由度机械臂

- **[BCN3D Moveo](https://github.com/BCN3D/BCN3D-Moveo)**
  用于教育的开源3D打印机械臂

- **[OpenArm](https://github.com/enactic/openarm)**
  用于接触丰富环境中物理AI研究的7自由度人形手臂

### 机械手

- **[Aero Hand Open](https://github.com/TetherIA/aero-hand-open)**
  腱驱动机械手：389克，314美元，7自由度，支持Python SDK和ROS2

- **[TRLC-DK1](https://github.com/robot-learning-co/trlc-dk1)**
  用于LeRobot人形数据采集的双臂机器人平台

- **[LEAP Hand](https://github.com/leap-hand/LEAP_Hand_API)**
  用于机器人学习的低成本仿人手，16自由度

- **[Delta X Soft Gripper](https://github.com/deltaxrobot/Delta-X-3D-Printed-Parts)**
  10美元的DIY食品级软体夹爪，使用3D打印模具和硅胶

- **[DexHand v2.3](https://github.com/TheRobotStudio/V2_DexHand)**
  来自The Robot Studio和NVIDIA的开源灵巧手设计

### 足式机器人

- **[Solo12](https://github.com/open-dynamic-robot-initiative/open_robot_actuator_hardware)**
  用于腿式运动研究的轻量级12自由度四足机器人，配备扭矩控制执行器

- **[Open-Source Leg](https://github.com/neurobionics/opensourceleg)**
  开源机器人假肢腿平台，包含硬件设计和Python SDK

### 人形机器人

- **[Mobile ALOHA](https://github.com/MarkFzp/mobile-aloha)**
  3.2万美元的全身遥操作系统，用于双臂移动操作

- **[LeKiwi](https://github.com/SIGRobotics-UIUC/LeKiwi)**
  低成本全向移动操作器，搭载SO-ARM101和LeRobot

- **[HOPEJr](https://github.com/TheRobotStudio/HOPEJr)**
  DIY人形机器人，66自由度，3D打印部件，支持LeRobot

## 软件与框架

机器人开发的必备工具和框架。

- **[LeRobot](https://github.com/huggingface/lerobot)**
  HuggingFace的PyTorch真实世界机器人机器学习库

- **[ROS 2](https://github.com/ros2/ros2)**
  新一代机器人操作系统，用于实时生产机器人

- **[Dora AI](https://github.com/dora-rs/dora)**
  用于AI机器人应用的数据流中间件，用Rust构建

- **[RLinf](https://github.com/RLinf/RLinf)**
  通过强化学习进行基础模型后训练的可扩展基础设施

- **[Extreme Parkour with Legged Robots](https://github.com/chengxuxin/extreme-parkour)**
  在20小时内训练的足式机器人跑酷强化学习系统

## 基础模型

用于机器人和具身智能的AI模型。

- **[OpenPI](https://github.com/Physical-Intelligence/openpi)**
  Physical Intelligence的VLA基础模型，用于通用机器人控制

- **[NVIDIA Isaac GR00T](https://github.com/NVIDIA/Isaac-GR00T)**
  NVIDIA开放基础模型，用于人形机器人推理和技能

- **[OpenVLA](https://github.com/openvla/openvla)**
  70亿参数的视觉-语言-动作模型，用于机器人操作

- **[ACT (Action Chunking with Transformers)](https://github.com/tonyzhaozh/act)**
  基于Transformer的策略学习，用于双臂操作

- **[SmolVLA](https://huggingface.co/lerobot/smolvla_base)**
  4.5亿参数的VLA模型，可在消费级硬件上运行

## 仿真器

用于机器人开发和测试的物理仿真器和虚拟环境。

- **[GENESIS](https://github.com/Genesis-Embodied-AI/Genesis)**
  世界最快物理引擎：4300万FPS，用于具身AI学习

- **[MuJoCo](https://github.com/google-deepmind/mujoco)**
  DeepMind的物理引擎，用于机器人和机器学习研究

- **[Isaac Lab](https://github.com/isaac-sim/IsaacLab)**
  NVIDIA在Isaac Sim上的统一机器人学习框架

- **[ManiSkill](https://github.com/haosulab/ManiSkill)**
  GPU并行仿真，用于可泛化操作技能

- **[NVIDIA Isaac Sim](https://github.com/isaac-sim/IsaacSim)**
  NVIDIA Omniverse应用，用于AI驱动的机器人仿真和测试

## 基准测试

用于机器人研究的标准化基准和评估框架。

- **[MetaWorld](https://github.com/Farama-Foundation/Metaworld)**
  多任务和元强化学习基准，用于机器人操作

- **[RLBench](https://github.com/stepjam/RLBench)**
  100多个任务的基准，用于视觉引导操作研究

- **[LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO)**
  终身机器人学习基准，包含130个程序化任务

- **[CALVIN](https://github.com/mees/calvin)**
  语言条件操作基准，用于长期任务

## 数据集

用于机器人学习和研究的训练数据集。

- **[Open X-Embodiment (OXE)](https://github.com/google-deepmind/open_x_embodiment)**
  最大的开放机器人数据集：来自22种具身形态的100万+轨迹

- **[DROID](https://github.com/droid-dataset/droid)**
  来自564个多样场景的7.6万条机器人操作轨迹

**[在Open Source Robotics浏览所有项目](https://robotics.growbotics.ai/projects)**

---

## 研究

### 论文

- **[Instant Policy: In-Context Imitation Learning via Graph Diffusion](https://arxiv.org/pdf/2411.12633.pdf)** - ICLR 2025机器人学习研讨会（最佳论文奖）

**[浏览所有论文](https://robotics.growbotics.ai/research/papers)**

### 书籍

- **[Dancing with Roomba: Cracking the Robot Riddle and Building an Icon](https://www.amazon.com/Dancing-Roomba-Cracking-Riddle-Building/dp/1032889527)** 作者：Joseph L. Jones

- **[Modern Robotics: Mechanics, Planning, and Control](https://www.amazon.com/Modern-Robotics-Mechanics-Planning-Control/dp/1107156300)** 作者：Kevin M. Lynch, Frank C. Park

- **[Probabilistic Robotics](https://www.amazon.com/Probabilistic-Robotics-INTELLIGENT-ROBOTICS-AUTONOMOUS/dp/0262201623)** 作者：Sebastian Thrun, Wolfram Burgard, Dieter Fox

**[浏览所有书籍](https://robotics.growbotics.ai/research/books)**

### 课程

- **[Modern Robotics: Mechanics, Planning, and Control Specialization](https://www.coursera.org/specializations/modernrobotics)** 在Coursera

- **[HuggingFace Robotics Course](https://huggingface.co/learn/robotics-course/unit0/1)** 在Hugging Face

**[浏览所有课程](https://robotics.growbotics.ai/research/courses)**

---

## 活动

- **[IEEE International Conference on Robotics and Automation (ICRA)](https://2026.ieee-icra.org/)**

- **[Humanoids Summit](https://humanoidssummit.com/)**

- **[NeurIPS - Neural Information Processing Systems](https://neurips.cc/)**

- **[CoRL - Conference on Robot Learning](https://www.robot-learning.org/)**

**[查看所有活动](https://robotics.growbotics.ai/events)**

---

## 值得关注的人

- **[Angela Schoellig](https://twitter.com/angelaschoellig)**（多伦多大学）

- **[Audrow Nash](https://twitter.com/audrow)**

- **[Chelsea Finn](https://twitter.com/chelseabfinn)**（斯坦福大学）

- **[Deepak Pathak](https://twitter.com/pathak2206)**（卡内基梅隆大学）

- **[Pieter Abbeel](https://twitter.com/pabbeel)**（加州大学伯克利分校）

- **[Rémi Cadène](https://twitter.com/RemiCadene)**（UMA通用机械助手）

**[发现更多研究人员和工程师](https://robotics.growbotics.ai/community/people)**

---

## 播客

- **[Audrow Nash Podcast](https://open.spotify.com/show/74jWpWiLwsasY2QHtDcl8I)**

- **[RoboPapers](https://open.spotify.com/show/3U0Ed7poaOElItEyUPkuto)**

- **[The Robot Brains Podcast](https://open.spotify.com/show/1oQXUJBjpJoxfUd3JAc0Zt)**

**[浏览所有播客](https://robotics.growbotics.ai/community/podcasts)**

---

## YouTube 频道

- **[Skyentific](https://www.youtube.com/@skyentific)**

- **[CMU Robotics Institute](https://www.youtube.com/@cmurobotics)**

**[浏览所有频道](https://robotics.growbotics.ai/community/youtube)**

---

## 博客

值得关注的机器人博客和通讯。

- **[Six Degrees of Robotics](https://sixdegreesofrobotics.substack.com/)** 作者：Christopher Sanchez

- **[State of Robot Learning — Dec 2025](https://vedder.io/misc/state_of_robot_learning_dec_2025.html)** 作者：Kyle Vedder

- **[We All Are Robots](https://ziegler.substack.com)** 作者：Lukas Ziegler

**[浏览所有博客](https://robotics.growbotics.ai/community/blogs)**

---

## 优秀公司

推动机器人技术边界的公司和研究实验室。

- **[1X Technologies](https://www.1x.tech)**
  开发具有可扩展自动化能力的通用人形机器人。

- **[Agility Robotics](https://www.agilityrobotics.com)**
  Digit的创造者，用于现实世界物流的双足机器人。

- **[Apptronik](https://apptronik.com)**
  人形机器人创新者，包括Apollo。

- **[Boston Dynamics](https://www.bostondynamics.com)**
  动态机器人行业领导者，如Spot和Atlas。

- **[Enchanted Tools](https://enchanted.tools)**
  Miroka的创造者，情感互动的类人形机器人。

- **[Engineered Arts](https://www.engineeredarts.co.uk)**
  Ameca的创造者，用于人机交互的先进人形机器人。

- **[Hanson Robotics](https://www.hansonrobotics.com)**
  仿真人形机器人开发商，如Sophia。

- **[Sunday](https://www.sunday.ai)**
  开发Memo，一款家用机器人，使用1000万个真实世界家务数据训练...

**[探索所有公司](https://robotics.growbotics.ai/community/companies)**

---

## 许可证

本列表采用 [CC0 1.0 通用](https://creativecommons.org/publicdomain/zero/1.0/) 许可。

---

## 贡献

欢迎提出建议！请访问 **[Open Source Robotics](https://robotics.growbotics.ai)** 提交新内容，或在本仓库提交issue。

---

**[探索完整平台，包含物料清单、组装指南等](https://robotics.growbotics.ai)**
