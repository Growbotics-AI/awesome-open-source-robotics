# Awesome Robótica de Código Abierto

**[English](README.md)** | **[中文](README_zh.md)** | **[日本語](README_ja.md)** | **[Deutsch](README_de.md)**

> Una lista curada de proyectos, herramientas y recursos de robótica de código abierto inspiradores e impactantes.

Esta lista es intencionalmente **selectiva**. Para la base de datos completa con listas de materiales, guías de ensamblaje e información detallada, visita **[Open Source Robotics](https://robotics.growbotics.ai)**.

---

## Contenido

- [Proyectos](#proyectos)
  - [Brazos Robóticos](#brazos-robóticos)
  - [Manos Robóticas](#manos-robóticas)
  - [Humanoides](#humanoides)
- [Software y Frameworks](#software-y-frameworks)
- [Modelos Fundacionales](#modelos-fundacionales)
- [Simuladores](#simuladores)
- [Benchmarks](#benchmarks)
- [Conjuntos de Datos](#conjuntos-de-datos)
- [Investigación](#investigación)
  - [Artículos](#artículos)
  - [Libros](#libros)
  - [Cursos](#cursos)
- [Eventos](#eventos)
- [Personas a Seguir](#personas-a-seguir)
- [Podcasts](#podcasts)
- [Canales de YouTube](#canales-de-youtube)
- [Blogs](#blogs)
- [Empresas Inspiradoras](#empresas-inspiradoras)
- [Licencia](#licencia)

---

## Proyectos

Una selección curada de proyectos notables de robótica de código abierto.

### Brazos Robóticos

- **[SO-101 Open Robot Arm](https://github.com/TheRobotStudio/SO-ARM100)**
  Brazo robótico de 6 DOF para teleoperación e investigación en robótica con IA

- **[BCN3D Moveo](https://github.com/BCN3D/BCN3D-Moveo)**
  Brazo robótico impreso en 3D de código abierto para educación

- **[OpenArm](https://github.com/enactic/openarm)**
  Brazo humanoide de 7 DOF para investigación de IA física en entornos con mucho contacto

### Manos Robóticas

- **[Aero Hand Open](https://github.com/TetherIA/aero-hand-open)**
  Mano robótica accionada por tendones: 389g, $314, 7 DOF con SDK de Python y ROS2

- **[TRLC-DK1](https://github.com/robot-learning-co/trlc-dk1)**
  Plataforma robótica bimanual para recolección de datos humanoides con LeRobot

- **[LEAP Hand](https://github.com/leap-hand/LEAP_Hand_API)**
  Mano antropomórfica de bajo costo con 16 DOF para aprendizaje robótico

- **[Delta X Soft Gripper](https://github.com/deltaxrobot/Delta-X-3D-Printed-Parts)**
  Pinza suave de grado alimenticio DIY de $10 usando moldes impresos en 3D y silicona

- **[DexHand v2.3](https://github.com/TheRobotStudio/V2_DexHand)**
  Diseño de mano diestra de código abierto de The Robot Studio y NVIDIA

### Humanoides

- **[Mobile ALOHA](https://github.com/MarkFzp/mobile-aloha)**
  Sistema de teleoperación de cuerpo completo de $32k para manipulación móvil bimanual

- **[LeKiwi](https://github.com/SIGRobotics-UIUC/LeKiwi)**
  Manipulador móvil holonómico de bajo costo con SO-ARM101 y LeRobot

- **[HOPEJr](https://github.com/TheRobotStudio/HOPEJr)**
  Robot humanoide DIY con 66 DOF, piezas impresas en 3D y soporte para LeRobot

## Software y Frameworks

Herramientas y frameworks esenciales para el desarrollo de robótica.

- **[LeRobot](https://github.com/huggingface/lerobot)**
  Biblioteca de ML de HuggingFace para robótica del mundo real en PyTorch

- **[ROS 2](https://github.com/ros2/ros2)**
  Sistema operativo de robots de nueva generación para robótica de producción en tiempo real

- **[Dora AI](https://github.com/dora-rs/dora)**
  Middleware de flujo de datos para aplicaciones de robótica con IA, construido en Rust

- **[RLinf](https://github.com/RLinf/RLinf)**
  Infraestructura escalable para post-entrenamiento de modelos fundacionales vía RL

- **[Extreme Parkour with Legged Robots](https://github.com/chengxuxin/extreme-parkour)**
  Sistema de RL para parkour de robots con patas entrenado en menos de 20 horas

## Modelos Fundacionales

Modelos de IA para robótica e inteligencia encarnada.

- **[OpenPI](https://github.com/Physical-Intelligence/openpi)**
  Modelos fundacionales VLA de Physical Intelligence para control general de robots

- **[NVIDIA Isaac GR00T](https://github.com/NVIDIA/Isaac-GR00T)**
  Modelo fundacional abierto de NVIDIA para razonamiento y habilidades de robots humanoides

- **[OpenVLA](https://github.com/openvla/openvla)**
  Modelo Vision-Language-Action de 7B parámetros para manipulación robótica

- **[ACT (Action Chunking with Transformers)](https://github.com/tonyzhaozh/act)**
  Aprendizaje de políticas basado en Transformers para manipulación bimanual

- **[SmolVLA](https://huggingface.co/lerobot/smolvla_base)**
  Modelo VLA de 450M parámetros que funciona en hardware de consumo

## Simuladores

Simuladores de física y entornos virtuales para desarrollo y pruebas de robótica.

- **[GENESIS](https://github.com/Genesis-Embodied-AI/Genesis)**
  Motor de física más rápido del mundo: 43M FPS para aprendizaje de IA encarnada

- **[MuJoCo](https://github.com/google-deepmind/mujoco)**
  Motor de física de DeepMind para investigación en robótica y ML

- **[Isaac Lab](https://github.com/isaac-sim/IsaacLab)**
  Framework unificado de aprendizaje robótico de NVIDIA en Isaac Sim

- **[ManiSkill](https://github.com/haosulab/ManiSkill)**
  Simulación paralelizada en GPU para habilidades de manipulación generalizables

- **[NVIDIA Isaac Sim](https://github.com/isaac-sim/IsaacSim)**
  Aplicación NVIDIA Omniverse para simulación y pruebas de robots impulsados por IA

## Benchmarks

Benchmarks estandarizados y frameworks de evaluación para investigación en robótica.

- **[MetaWorld](https://github.com/Farama-Foundation/Metaworld)**
  Benchmark de RL multi-tarea y meta para manipulación robótica

- **[RLBench](https://github.com/stepjam/RLBench)**
  Benchmark de más de 100 tareas para investigación de manipulación guiada por visión

- **[LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO)**
  Benchmark de aprendizaje robótico de por vida con 130 tareas procedurales

- **[CALVIN](https://github.com/mees/calvin)**
  Benchmark de manipulación condicionado por lenguaje para tareas de largo horizonte

## Conjuntos de Datos

Conjuntos de datos de entrenamiento para aprendizaje e investigación robótica.

- **[Open X-Embodiment (OXE)](https://github.com/google-deepmind/open_x_embodiment)**
  El mayor conjunto de datos de robótica abierto: 1M+ episodios de 22 encarnaciones

- **[DROID](https://github.com/droid-dataset/droid)**
  76K trayectorias de manipulación robótica de 564 escenas diversas

**[Explorar todos los proyectos en Open Source Robotics](https://robotics.growbotics.ai/projects)**

---

## Investigación

### Artículos

- **[Instant Policy: In-Context Imitation Learning via Graph Diffusion](https://arxiv.org/pdf/2411.12633.pdf)** - ICLR 2025 Robot Learning Workshop (Premio al Mejor Artículo)

**[Explorar todos los artículos](https://robotics.growbotics.ai/research/papers)**

### Libros

- **[Dancing with Roomba: Cracking the Robot Riddle and Building an Icon](https://www.amazon.com/Dancing-Roomba-Cracking-Riddle-Building/dp/1032889527)** por Joseph L. Jones

- **[Modern Robotics: Mechanics, Planning, and Control](https://www.amazon.com/Modern-Robotics-Mechanics-Planning-Control/dp/1107156300)** por Kevin M. Lynch, Frank C. Park

- **[Probabilistic Robotics](https://www.amazon.com/Probabilistic-Robotics-INTELLIGENT-ROBOTICS-AUTONOMOUS/dp/0262201623)** por Sebastian Thrun, Wolfram Burgard, Dieter Fox

**[Explorar todos los libros](https://robotics.growbotics.ai/research/books)**

### Cursos

- **[Modern Robotics: Mechanics, Planning, and Control Specialization](https://www.coursera.org/specializations/modernrobotics)** en Coursera

- **[HuggingFace Robotics Course](https://huggingface.co/learn/robotics-course/unit0/1)** en Hugging Face

**[Explorar todos los cursos](https://robotics.growbotics.ai/research/courses)**

---

## Eventos

- **[IEEE International Conference on Robotics and Automation (ICRA)](https://2026.ieee-icra.org/)**

- **[Humanoids Summit](https://humanoidssummit.com/)**

- **[NeurIPS - Neural Information Processing Systems](https://neurips.cc/)**

- **[CoRL - Conference on Robot Learning](https://www.robot-learning.org/)**

**[Ver todos los eventos](https://robotics.growbotics.ai/events)**

---

## Personas a Seguir

- **[Angela Schoellig](https://twitter.com/angelaschoellig)** (University of Toronto)

- **[Audrow Nash](https://twitter.com/audrow)**

- **[Chelsea Finn](https://twitter.com/chelseabfinn)** (Stanford University)

- **[Deepak Pathak](https://twitter.com/pathak2206)** (Carnegie Mellon University)

- **[Pieter Abbeel](https://twitter.com/pabbeel)** (UC Berkeley)

- **[Rémi Cadène](https://twitter.com/RemiCadene)** (UMA (Universal Mechanical Assistant))

**[Descubrir más investigadores e ingenieros](https://robotics.growbotics.ai/community/people)**

---

## Podcasts

- **[Audrow Nash Podcast](https://open.spotify.com/show/74jWpWiLwsasY2QHtDcl8I)**

- **[RoboPapers](https://open.spotify.com/show/3U0Ed7poaOElItEyUPkuto)**

- **[The Robot Brains Podcast](https://open.spotify.com/show/1oQXUJBjpJoxfUd3JAc0Zt)**

**[Explorar todos los podcasts](https://robotics.growbotics.ai/community/podcasts)**

---

## Canales de YouTube

- **[Skyentific](https://www.youtube.com/@skyentific)**

- **[CMU Robotics Institute](https://www.youtube.com/@cmurobotics)**

**[Explorar todos los canales](https://robotics.growbotics.ai/community/youtube)**

---

## Blogs

Blogs y boletines de robótica que vale la pena seguir.

- **[Six Degrees of Robotics](https://sixdegreesofrobotics.substack.com/)** por Christopher Sanchez

- **[State of Robot Learning — Dec 2025](https://vedder.io/misc/state_of_robot_learning_dec_2025.html)** por Kyle Vedder

- **[We All Are Robots](https://ziegler.substack.com)** por Lukas Ziegler

**[Explorar todos los blogs](https://robotics.growbotics.ai/community/blogs)**

---

## Empresas Inspiradoras

Empresas de robótica y laboratorios de investigación que empujan los límites.

- **[1X Technologies](https://www.1x.tech)**
  Desarrollando robots humanoides de propósito general con automatización escalable.

- **[Agility Robotics](https://www.agilityrobotics.com)**
  Creadores de Digit, un robot bípedo para logística del mundo real.

- **[Apptronik](https://apptronik.com)**
  Innovadores en robots humanoides, incluyendo Apollo.

- **[Boston Dynamics](https://www.bostondynamics.com)**
  Líder de la industria en robots dinámicos como Spot y Atlas.

- **[Enchanted Tools](https://enchanted.tools)**
  Creadores de Miroka, robots tipo humanoide emocionalmente atractivos.

- **[Engineered Arts](https://www.engineeredarts.co.uk)**
  Creadores de Ameca, robots humanoides avanzados para interacción humana.

- **[Hanson Robotics](https://www.hansonrobotics.com)**
  Desarrolladores de robots humanoides realistas como Sophia.

- **[Sunday](https://www.sunday.ai)**
  Construyendo Memo, un robot doméstico entrenado con 10 millones de tareas del mundo real...

**[Explorar todas las empresas](https://robotics.growbotics.ai/community/companies)**

---

## Licencia

Esta lista está licenciada bajo [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).

---

## Contribuir

¡Sugerencias bienvenidas! Visita **[Open Source Robotics](https://robotics.growbotics.ai)** para sugerir nuevo contenido o abre un issue en este repositorio.

---

**[Explora la plataforma completa con listas de materiales, guías de ensamblaje y más](https://robotics.growbotics.ai)**
