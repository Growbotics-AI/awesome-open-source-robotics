# Awesome Open Source Robotik

**[English](README.md)** | **[中文](README_zh.md)** | **[日本語](README_ja.md)** | **[Español](README_es.md)**

> Eine kuratierte Liste inspirierender und wirkungsvoller Open-Source-Robotikprojekte, Tools und Ressourcen.

Diese Liste ist bewusst **selektiv**. Für die vollständige Datenbank mit Stücklisten, Montageanleitungen und detaillierten Informationen besuchen Sie **[Open Source Robotics](https://robotics.growbotics.ai)**.

---

## Inhalt

- [Projekte](#projekte)
  - [Roboterarme](#roboterarme)
  - [Roboterhände](#roboterhände)
  - [Humanoide](#humanoide)
- [Software & Frameworks](#software--frameworks)
- [Foundation Models](#foundation-models)
- [Simulatoren](#simulatoren)
- [Benchmarks](#benchmarks)
- [Datensätze](#datensätze)
- [Forschung](#forschung)
  - [Paper](#paper)
  - [Bücher](#bücher)
  - [Kurse](#kurse)
- [Veranstaltungen](#veranstaltungen)
- [Persönlichkeiten](#persönlichkeiten)
- [Podcasts](#podcasts)
- [YouTube-Kanäle](#youtube-kanäle)
- [Blogs](#blogs)
- [Inspirierende Unternehmen](#inspirierende-unternehmen)
- [Lizenz](#lizenz)

---

## Projekte

Eine kuratierte Auswahl bemerkenswerter Open-Source-Robotikprojekte.

### Roboterarme

- **[SO-101 Open Robot Arm](https://github.com/TheRobotStudio/SO-ARM100)**
  6-DOF-Roboterarm für Teleoperation und KI-Robotikforschung

- **[BCN3D Moveo](https://github.com/BCN3D/BCN3D-Moveo)**
  Open-Source 3D-gedruckter Roboterarm für Bildungszwecke

- **[OpenArm](https://github.com/enactic/openarm)**
  7-DOF humanoider Arm für physische KI-Forschung in kontaktreichen Umgebungen

### Roboterhände

- **[Aero Hand Open](https://github.com/TetherIA/aero-hand-open)**
  Sehnengetriebene Roboterhand: 389g, 314$, 7 DOF mit Python SDK und ROS2

- **[TRLC-DK1](https://github.com/robot-learning-co/trlc-dk1)**
  Bimanuale Roboterplattform für humanoide Datenerfassung mit LeRobot

- **[LEAP Hand](https://github.com/leap-hand/LEAP_Hand_API)**
  Kostengünstige anthropomorphe Hand mit 16 DOF für Roboterlernen

- **[Delta X Soft Gripper](https://github.com/deltaxrobot/Delta-X-3D-Printed-Parts)**
  10$ DIY lebensmittelechter Soft-Gripper mit 3D-gedruckten Formen und Silikon

- **[DexHand v2.3](https://github.com/TheRobotStudio/V2_DexHand)**
  Open-Source geschickte Hand-Design von The Robot Studio und NVIDIA

### Humanoide

- **[Mobile ALOHA](https://github.com/MarkFzp/mobile-aloha)**
  32.000$ Ganzkörper-Teleoperationssystem für bimanuale mobile Manipulation

- **[LeKiwi](https://github.com/SIGRobotics-UIUC/LeKiwi)**
  Kostengünstiger holonomer mobiler Manipulator mit SO-ARM101 und LeRobot

- **[HOPEJr](https://github.com/TheRobotStudio/HOPEJr)**
  DIY humanoider Roboter mit 66 DOF, 3D-gedruckten Teilen und LeRobot-Unterstützung

## Software & Frameworks

Wesentliche Tools und Frameworks für die Robotikentwicklung.

- **[LeRobot](https://github.com/huggingface/lerobot)**
  HuggingFace ML-Bibliothek für reale Robotik in PyTorch

- **[ROS 2](https://github.com/ros2/ros2)**
  Roboter-Betriebssystem der nächsten Generation für Echtzeit-Produktionsrobotik

- **[Dora AI](https://github.com/dora-rs/dora)**
  Dataflow-Middleware für KI-Robotikanwendungen, entwickelt in Rust

- **[RLinf](https://github.com/RLinf/RLinf)**
  Skalierbare Infrastruktur für Post-Training von Foundation Models via RL

- **[Extreme Parkour with Legged Robots](https://github.com/chengxuxin/extreme-parkour)**
  RL-System für Roboter-Parkour mit Beinen, trainiert in unter 20 Stunden

## Foundation Models

KI-Modelle für Robotik und verkörperte Intelligenz.

- **[OpenPI](https://github.com/Physical-Intelligence/openpi)**
  Physical Intelligence VLA Foundation Models für allgemeine Robotersteuerung

- **[NVIDIA Isaac GR00T](https://github.com/NVIDIA/Isaac-GR00T)**
  NVIDIA Open Foundation Model für humanoide Roboter-Reasoning und -Fähigkeiten

- **[OpenVLA](https://github.com/openvla/openvla)**
  7B-Parameter Vision-Language-Action Modell für Robotermanipulation

- **[ACT (Action Chunking with Transformers)](https://github.com/tonyzhaozh/act)**
  Transformer-basiertes Policy-Learning für bimanuale Manipulation

- **[SmolVLA](https://huggingface.co/lerobot/smolvla_base)**
  450M Parameter VLA-Modell, das auf Consumer-Hardware läuft

## Simulatoren

Physik-Simulatoren und virtuelle Umgebungen für Robotikentwicklung und -tests.

- **[GENESIS](https://github.com/Genesis-Embodied-AI/Genesis)**
  Weltweit schnellste Physik-Engine: 43M FPS für verkörpertes KI-Lernen

- **[MuJoCo](https://github.com/google-deepmind/mujoco)**
  DeepMind Physik-Engine für Robotik- und ML-Forschung

- **[Isaac Lab](https://github.com/isaac-sim/IsaacLab)**
  NVIDIA einheitliches Robotik-Lernframework auf Isaac Sim

- **[ManiSkill](https://github.com/haosulab/ManiSkill)**
  GPU-parallelisierte Simulation für generalisierbare Manipulationsfähigkeiten

- **[NVIDIA Isaac Sim](https://github.com/isaac-sim/IsaacSim)**
  NVIDIA Omniverse App für KI-gesteuerte Robotersimulation und -tests

## Benchmarks

Standardisierte Benchmarks und Evaluierungsframeworks für Robotikforschung.

- **[MetaWorld](https://github.com/Farama-Foundation/Metaworld)**
  Multi-Task und Meta-RL Benchmark für Robotermanipulation

- **[RLBench](https://github.com/stepjam/RLBench)**
  100+ Aufgaben-Benchmark für visionsgesteuerte Manipulationsforschung

- **[LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO)**
  Lebenslanges Roboterlernen-Benchmark mit 130 prozeduralen Aufgaben

- **[CALVIN](https://github.com/mees/calvin)**
  Sprachkonditionierter Manipulations-Benchmark für Langzeithorizont-Aufgaben

## Datensätze

Trainingsdatensätze für Roboterlernen und Forschung.

- **[Open X-Embodiment (OXE)](https://github.com/google-deepmind/open_x_embodiment)**
  Größter offener Robotik-Datensatz: 1M+ Episoden von 22 Verkörperungen

- **[DROID](https://github.com/droid-dataset/droid)**
  76K Robotermanipulations-Trajektorien aus 564 verschiedenen Szenen

**[Alle Projekte auf Open Source Robotics durchsuchen](https://robotics.growbotics.ai/projects)**

---

## Forschung

### Paper

- **[Instant Policy: In-Context Imitation Learning via Graph Diffusion](https://arxiv.org/pdf/2411.12633.pdf)** - ICLR 2025 Robot Learning Workshop (Best Paper Award)

**[Alle Paper durchsuchen](https://robotics.growbotics.ai/research/papers)**

### Bücher

- **[Dancing with Roomba: Cracking the Robot Riddle and Building an Icon](https://www.amazon.com/Dancing-Roomba-Cracking-Riddle-Building/dp/1032889527)** von Joseph L. Jones

- **[Modern Robotics: Mechanics, Planning, and Control](https://www.amazon.com/Modern-Robotics-Mechanics-Planning-Control/dp/1107156300)** von Kevin M. Lynch, Frank C. Park

- **[Probabilistic Robotics](https://www.amazon.com/Probabilistic-Robotics-INTELLIGENT-ROBOTICS-AUTONOMOUS/dp/0262201623)** von Sebastian Thrun, Wolfram Burgard, Dieter Fox

**[Alle Bücher durchsuchen](https://robotics.growbotics.ai/research/books)**

### Kurse

- **[Modern Robotics: Mechanics, Planning, and Control Specialization](https://www.coursera.org/specializations/modernrobotics)** auf Coursera

- **[HuggingFace Robotics Course](https://huggingface.co/learn/robotics-course/unit0/1)** auf Hugging Face

**[Alle Kurse durchsuchen](https://robotics.growbotics.ai/research/courses)**

---

## Veranstaltungen

- **[IEEE International Conference on Robotics and Automation (ICRA)](https://2026.ieee-icra.org/)**

- **[Humanoids Summit](https://humanoidssummit.com/)**

- **[NeurIPS - Neural Information Processing Systems](https://neurips.cc/)**

- **[CoRL - Conference on Robot Learning](https://www.robot-learning.org/)**

**[Alle Veranstaltungen anzeigen](https://robotics.growbotics.ai/events)**

---

## Persönlichkeiten

- **[Angela Schoellig](https://twitter.com/angelaschoellig)** (University of Toronto)

- **[Audrow Nash](https://twitter.com/audrow)**

- **[Chelsea Finn](https://twitter.com/chelseabfinn)** (Stanford University)

- **[Deepak Pathak](https://twitter.com/pathak2206)** (Carnegie Mellon University)

- **[Pieter Abbeel](https://twitter.com/pabbeel)** (UC Berkeley)

- **[Rémi Cadène](https://twitter.com/RemiCadene)** (UMA (Universal Mechanical Assistant))

**[Mehr Forscher und Ingenieure entdecken](https://robotics.growbotics.ai/community/people)**

---

## Podcasts

- **[Audrow Nash Podcast](https://open.spotify.com/show/74jWpWiLwsasY2QHtDcl8I)**

- **[RoboPapers](https://open.spotify.com/show/3U0Ed7poaOElItEyUPkuto)**

- **[The Robot Brains Podcast](https://open.spotify.com/show/1oQXUJBjpJoxfUd3JAc0Zt)**

**[Alle Podcasts durchsuchen](https://robotics.growbotics.ai/community/podcasts)**

---

## YouTube-Kanäle

- **[Skyentific](https://www.youtube.com/@skyentific)**

- **[CMU Robotics Institute](https://www.youtube.com/@cmurobotics)**

**[Alle Kanäle durchsuchen](https://robotics.growbotics.ai/community/youtube)**

---

## Blogs

Robotik-Blogs und Newsletter, die es wert sind, verfolgt zu werden.

- **[Six Degrees of Robotics](https://sixdegreesofrobotics.substack.com/)** von Christopher Sanchez

- **[State of Robot Learning — Dec 2025](https://vedder.io/misc/state_of_robot_learning_dec_2025.html)** von Kyle Vedder

- **[We All Are Robots](https://ziegler.substack.com)** von Lukas Ziegler

**[Alle Blogs durchsuchen](https://robotics.growbotics.ai/community/blogs)**

---

## Inspirierende Unternehmen

Robotik-Unternehmen und Forschungslabore, die Grenzen verschieben.

- **[1X Technologies](https://www.1x.tech)**
  Entwickelt universelle humanoide Roboter mit skalierbarer Automatisierung.

- **[Agility Robotics](https://www.agilityrobotics.com)**
  Schöpfer von Digit, einem zweibeinigen Roboter für reale Logistik.

- **[Apptronik](https://apptronik.com)**
  Innovatoren bei humanoiden Robotern, einschließlich Apollo.

- **[Boston Dynamics](https://www.bostondynamics.com)**
  Branchenführer bei dynamischen Robotern wie Spot und Atlas.

- **[Enchanted Tools](https://enchanted.tools)**
  Schöpfer von Miroka, emotional ansprechenden humanoidartigen Robotern.

- **[Engineered Arts](https://www.engineeredarts.co.uk)**
  Schöpfer von Ameca, fortschrittlichen humanoiden Robotern für menschliche Interaktion.

- **[Hanson Robotics](https://www.hansonrobotics.com)**
  Entwickler lebensechter humanoider Roboter wie Sophia.

- **[Sunday](https://www.sunday.ai)**
  Baut Memo, einen Haushaltsroboter, trainiert mit 10 Millionen realen Hausarbeiten...

**[Alle Unternehmen erkunden](https://robotics.growbotics.ai/community/companies)**

---

## Lizenz

Diese Liste ist lizenziert unter [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).

---

## Mitwirken

Vorschläge willkommen! Besuchen Sie **[Open Source Robotics](https://robotics.growbotics.ai)** um neue Inhalte vorzuschlagen oder öffnen Sie ein Issue in diesem Repository.

---

**[Erkunden Sie die vollständige Plattform mit Stücklisten, Montageanleitungen und mehr](https://robotics.growbotics.ai)**
