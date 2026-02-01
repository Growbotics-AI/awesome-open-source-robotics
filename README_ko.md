# 오픈소스 로보틱스 엄선 목록

**[English](README.md)** | **[中文](README_zh.md)** | **[日本語](README_ja.md)** | **[Deutsch](README_de.md)** | **[Español](README_es.md)** | **[Français](README_fr.md)** | **[Português](README_pt.md)**

> 영감을 주고 영향력 있는 오픈소스 로보틱스 프로젝트, 도구, 리소스의 엄선된 목록입니다.

이 목록은 의도적으로 **선별**되었습니다. BOM, 조립 가이드, 상세 정보가 포함된 전체 데이터베이스는 **[Open Source Robotics](https://robotics.growbotics.ai)**를 방문하세요.

---

## 목차

- [프로젝트](#프로젝트)
  - [로봇 팔](#로봇-팔)
  - [로봇 손](#로봇-손)
  - [다리 로봇](#다리-로봇)
  - [휴머노이드](#휴머노이드)
- [소프트웨어 및 프레임워크](#소프트웨어-및-프레임워크)
- [파운데이션 모델](#파운데이션-모델)
- [시뮬레이터](#시뮬레이터)
- [벤치마크](#벤치마크)
- [데이터셋](#데이터셋)
- [연구](#연구)
  - [논문](#논문)
  - [도서](#도서)
  - [강좌](#강좌)
- [이벤트](#이벤트)
- [팔로우할 인물](#팔로우할-인물)
- [팟캐스트](#팟캐스트)
- [YouTube 채널](#youtube-채널)
- [블로그](#블로그)
- [영감을 주는 기업](#영감을-주는-기업)
- [라이선스](#라이선스)

---

## 프로젝트

주목할 만한 오픈소스 로보틱스 프로젝트 선별 목록입니다.

### 로봇 팔

- **[SO-101 Open Robot Arm](https://github.com/TheRobotStudio/SO-ARM100)**
  원격 조작 및 AI 로보틱스 연구를 위한 6-DOF 로봇 팔

- **[BCN3D Moveo](https://github.com/BCN3D/BCN3D-Moveo)**
  교육용 오픈소스 3D 프린팅 로봇 팔

- **[OpenArm](https://github.com/enactic/openarm)**
  접촉이 풍부한 환경에서 물리적 AI 연구를 위한 7DOF 휴머노이드 팔

### 로봇 손

- **[Aero Hand Open](https://github.com/TetherIA/aero-hand-open)**
  텐던 구동 로봇 손: 389g, $314, 7 DOF, Python SDK 및 ROS2 지원

- **[TRLC-DK1](https://github.com/robot-learning-co/trlc-dk1)**
  LeRobot을 이용한 휴머노이드 데이터 수집용 양팔 로봇 플랫폼

- **[LEAP Hand](https://github.com/leap-hand/LEAP_Hand_API)**
  로봇 학습을 위한 저비용 인간형 손, 16 DOF

- **[Delta X Soft Gripper](https://github.com/deltaxrobot/Delta-X-3D-Printed-Parts)**
  3D 프린팅 몰드와 실리콘을 사용한 $10 DIY 식품용 소프트 그리퍼

- **[DexHand v2.3](https://github.com/TheRobotStudio/V2_DexHand)**
  The Robot Studio와 NVIDIA의 오픈소스 정교한 손 디자인

### 다리 로봇

- **[Solo12](https://github.com/open-dynamic-robot-initiative/open_robot_actuator_hardware)**
  토크 제어 액추에이터를 갖춘 보행 연구용 경량 12-DOF 사족보행 로봇

- **[Open-Source Leg](https://github.com/neurobionics/opensourceleg)**
  하드웨어 설계와 Python SDK를 포함한 오픈소스 로봇 의족 플랫폼

### 휴머노이드

- **[Mobile ALOHA](https://github.com/MarkFzp/mobile-aloha)**
  양팔 이동 매니퓰레이션을 위한 $32k 전신 원격 조작 시스템

- **[LeKiwi](https://github.com/SIGRobotics-UIUC/LeKiwi)**
  SO-ARM101 및 LeRobot을 탑재한 저비용 홀로노믹 이동 매니퓰레이터

- **[HOPEJr](https://github.com/TheRobotStudio/HOPEJr)**
  66 DOF, 3D 프린팅 부품, LeRobot 지원을 갖춘 DIY 휴머노이드 로봇

## 소프트웨어 및 프레임워크

로보틱스 개발을 위한 필수 도구와 프레임워크입니다.

- **[LeRobot](https://github.com/huggingface/lerobot)**
  PyTorch 기반 실제 로보틱스를 위한 HuggingFace ML 라이브러리

- **[ROS 2](https://github.com/ros2/ros2)**
  실시간 프로덕션 로보틱스를 위한 차세대 로봇 운영 체제

- **[Dora AI](https://github.com/dora-rs/dora)**
  Rust로 구축된 AI 로보틱스 애플리케이션용 데이터플로우 미들웨어

- **[RLinf](https://github.com/RLinf/RLinf)**
  RL을 통한 파운데이션 모델 사후 훈련을 위한 확장 가능한 인프라

- **[Extreme Parkour with Legged Robots](https://github.com/chengxuxin/extreme-parkour)**
  20시간 이내에 훈련된 다리 로봇 파쿠르 RL 시스템

## 파운데이션 모델

로보틱스 및 구현된 지능을 위한 AI 모델입니다.

- **[OpenPI](https://github.com/Physical-Intelligence/openpi)**
  범용 로봇 제어를 위한 Physical Intelligence VLA 파운데이션 모델

- **[NVIDIA Isaac GR00T](https://github.com/NVIDIA/Isaac-GR00T)**
  휴머노이드 로봇 추론 및 기술을 위한 NVIDIA 오픈 파운데이션 모델

- **[OpenVLA](https://github.com/openvla/openvla)**
  로봇 매니퓰레이션을 위한 70억 파라미터 Vision-Language-Action 모델

- **[ACT (Action Chunking with Transformers)](https://github.com/tonyzhaozh/act)**
  양팔 매니퓰레이션을 위한 트랜스포머 기반 정책 학습

- **[SmolVLA](https://huggingface.co/lerobot/smolvla_base)**
  소비자용 하드웨어에서 실행되는 4억 5천만 파라미터 VLA 모델

## 시뮬레이터

로보틱스 개발 및 테스트를 위한 물리 시뮬레이터 및 가상 환경입니다.

- **[GENESIS](https://github.com/Genesis-Embodied-AI/Genesis)**
  세계 최고 속도의 물리 엔진: 구현된 AI 학습을 위한 4300만 FPS

- **[MuJoCo](https://github.com/google-deepmind/mujoco)**
  로보틱스 및 ML 연구를 위한 DeepMind 물리 엔진

- **[Isaac Lab](https://github.com/isaac-sim/IsaacLab)**
  Isaac Sim 기반 NVIDIA 통합 로보틱스 학습 프레임워크

- **[ManiSkill](https://github.com/haosulab/ManiSkill)**
  일반화 가능한 매니퓰레이션 기술을 위한 GPU 병렬 시뮬레이션

- **[NVIDIA Isaac Sim](https://github.com/isaac-sim/IsaacSim)**
  AI 기반 로봇 시뮬레이션 및 테스트를 위한 NVIDIA Omniverse 앱

## 벤치마크

로보틱스 연구를 위한 표준화된 벤치마크 및 평가 프레임워크입니다.

- **[MetaWorld](https://github.com/Farama-Foundation/Metaworld)**
  로봇 매니퓰레이션을 위한 다중 작업 및 메타 RL 벤치마크

- **[RLBench](https://github.com/stepjam/RLBench)**
  비전 기반 매니퓰레이션 연구를 위한 100개 이상 작업 벤치마크

- **[LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO)**
  130개 절차적 작업을 포함한 평생 로봇 학습 벤치마크

- **[CALVIN](https://github.com/mees/calvin)**
  장기 작업을 위한 언어 조건부 매니퓰레이션 벤치마크

## 데이터셋

로봇 학습 및 연구를 위한 훈련 데이터셋입니다.

- **[Open X-Embodiment (OXE)](https://github.com/google-deepmind/open_x_embodiment)**
  최대 규모의 오픈 로보틱스 데이터셋: 22개 구현체에서 100만+ 에피소드

- **[DROID](https://github.com/droid-dataset/droid)**
  564개 다양한 장면에서 76K 로봇 매니퓰레이션 궤적

**[Open Source Robotics에서 모든 프로젝트 찾아보기](https://robotics.growbotics.ai/projects)**

---

## 연구

### 논문

- **[Instant Policy: In-Context Imitation Learning via Graph Diffusion](https://arxiv.org/pdf/2411.12633.pdf)** - ICLR 2025 Robot Learning Workshop (최우수 논문상)

**[모든 논문 찾아보기](https://robotics.growbotics.ai/research/papers)**

### 도서

- **[Dancing with Roomba: Cracking the Robot Riddle and Building an Icon](https://www.amazon.com/Dancing-Roomba-Cracking-Riddle-Building/dp/1032889527)** 저자: Joseph L. Jones

- **[Modern Robotics: Mechanics, Planning, and Control](https://www.amazon.com/Modern-Robotics-Mechanics-Planning-Control/dp/1107156300)** 저자: Kevin M. Lynch, Frank C. Park

- **[Probabilistic Robotics](https://www.amazon.com/Probabilistic-Robotics-INTELLIGENT-ROBOTICS-AUTONOMOUS/dp/0262201623)** 저자: Sebastian Thrun, Wolfram Burgard, Dieter Fox

**[모든 도서 찾아보기](https://robotics.growbotics.ai/research/books)**

### 강좌

- **[Modern Robotics: Mechanics, Planning, and Control Specialization](https://www.coursera.org/specializations/modernrobotics)** Coursera

- **[HuggingFace Robotics Course](https://huggingface.co/learn/robotics-course/unit0/1)** Hugging Face

**[모든 강좌 찾아보기](https://robotics.growbotics.ai/research/courses)**

---

## 이벤트

- **[IEEE International Conference on Robotics and Automation (ICRA)](https://2026.ieee-icra.org/)**

- **[Humanoids Summit](https://humanoidssummit.com/)**

- **[NeurIPS - Neural Information Processing Systems](https://neurips.cc/)**

- **[CoRL - Conference on Robot Learning](https://www.robot-learning.org/)**

**[모든 이벤트 보기](https://robotics.growbotics.ai/events)**

---

## 팔로우할 인물

- **[Angela Schoellig](https://twitter.com/angelaschoellig)** (토론토 대학교)

- **[Audrow Nash](https://twitter.com/audrow)**

- **[Chelsea Finn](https://twitter.com/chelseabfinn)** (스탠퍼드 대학교)

- **[Deepak Pathak](https://twitter.com/pathak2206)** (카네기 멜론 대학교)

- **[Pieter Abbeel](https://twitter.com/pabbeel)** (UC 버클리)

- **[Rémi Cadène](https://twitter.com/RemiCadene)** (UMA - Universal Mechanical Assistant)

**[더 많은 연구자 및 엔지니어 찾아보기](https://robotics.growbotics.ai/community/people)**

---

## 팟캐스트

- **[Audrow Nash Podcast](https://open.spotify.com/show/74jWpWiLwsasY2QHtDcl8I)**

- **[RoboPapers](https://open.spotify.com/show/3U0Ed7poaOElItEyUPkuto)**

- **[The Robot Brains Podcast](https://open.spotify.com/show/1oQXUJBjpJoxfUd3JAc0Zt)**

**[모든 팟캐스트 찾아보기](https://robotics.growbotics.ai/community/podcasts)**

---

## YouTube 채널

- **[Skyentific](https://www.youtube.com/@skyentific)**

- **[CMU Robotics Institute](https://www.youtube.com/@cmurobotics)**

**[모든 채널 찾아보기](https://robotics.growbotics.ai/community/youtube)**

---

## 블로그

팔로우할 가치가 있는 로보틱스 블로그 및 뉴스레터입니다.

- **[Six Degrees of Robotics](https://sixdegreesofrobotics.substack.com/)** 저자: Christopher Sanchez

- **[State of Robot Learning — Dec 2025](https://vedder.io/misc/state_of_robot_learning_dec_2025.html)** 저자: Kyle Vedder

- **[We All Are Robots](https://ziegler.substack.com)** 저자: Lukas Ziegler

**[모든 블로그 찾아보기](https://robotics.growbotics.ai/community/blogs)**

---

## 영감을 주는 기업

로보틱스의 경계를 넓히는 기업 및 연구소입니다.

- **[1X Technologies](https://www.1x.tech)**
  확장 가능한 자동화를 갖춘 범용 휴머노이드 로봇 개발.

- **[Agility Robotics](https://www.agilityrobotics.com)**
  실제 물류를 위한 이족보행 로봇 Digit의 창시자.

- **[Apptronik](https://apptronik.com)**
  Apollo를 포함한 휴머노이드 로봇 혁신 기업.

- **[Boston Dynamics](https://www.bostondynamics.com)**
  Spot과 Atlas 같은 역동적 로봇 분야의 업계 리더.

- **[Enchanted Tools](https://enchanted.tools)**
  감정적으로 매력적인 휴머노이드형 로봇 Miroka의 창시자.

- **[Engineered Arts](https://www.engineeredarts.co.uk)**
  인간 상호작용을 위한 첨단 휴머노이드 로봇 Ameca의 창시자.

- **[Hanson Robotics](https://www.hansonrobotics.com)**
  Sophia 같은 실제 같은 휴머노이드 로봇 개발사.

- **[Sunday](https://www.sunday.ai)**
  1천만 개의 실제 가사 작업으로 훈련된 가정용 로봇 Memo 개발...

**[모든 기업 탐색하기](https://robotics.growbotics.ai/community/companies)**

---

## 라이선스

이 목록은 [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) 라이선스입니다.

---

## 기여

제안을 환영합니다! 새 콘텐츠를 제안하려면 **[Open Source Robotics](https://robotics.growbotics.ai)**를 방문하거나 이 저장소에 이슈를 등록하세요.

---

**[BOM, 조립 가이드 등이 포함된 전체 플랫폼 탐색하기](https://robotics.growbotics.ai)**
