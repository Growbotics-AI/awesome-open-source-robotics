# Robótica Open Source - Seleção

**[English](README.md)** | **[中文](README_zh.md)** | **[日本語](README_ja.md)** | **[Deutsch](README_de.md)** | **[Español](README_es.md)** | **[Français](README_fr.md)** | **[한국어](README_ko.md)**

> Uma lista selecionada de projetos, ferramentas e recursos de robótica open source inspiradores e impactantes.

Esta lista é intencionalmente **seletiva**. Para o banco de dados completo com BOMs, guias de montagem e informações detalhadas, visite **[Open Source Robotics](https://robotics.growbotics.ai)**.

---

## Índice

- [Projetos](#projetos)
  - [Braços Robóticos](#braços-robóticos)
  - [Mãos Robóticas](#mãos-robóticas)
  - [Robôs com Pernas](#robôs-com-pernas)
  - [Humanoides](#humanoides)
- [Software e Frameworks](#software-e-frameworks)
- [Modelos de Fundação](#modelos-de-fundação)
- [Simuladores](#simuladores)
- [Benchmarks](#benchmarks)
- [Conjuntos de Dados](#conjuntos-de-dados)
- [Pesquisa](#pesquisa)
  - [Artigos](#artigos)
  - [Livros](#livros)
  - [Cursos](#cursos)
- [Eventos](#eventos)
- [Pessoas para Seguir](#pessoas-para-seguir)
- [Podcasts](#podcasts)
- [Canais do YouTube](#canais-do-youtube)
- [Blogs](#blogs)
- [Empresas Inspiradoras](#empresas-inspiradoras)
- [Licença](#licença)

---

## Projetos

Uma seleção de projetos de robótica open source notáveis.

### Braços Robóticos

- **[SO-101 Open Robot Arm](https://github.com/TheRobotStudio/SO-ARM100)**
  Braço robótico de 6 eixos para teleoperação e pesquisa em robótica com IA

- **[BCN3D Moveo](https://github.com/BCN3D/BCN3D-Moveo)**
  Braço robótico impresso em 3D open source para educação

- **[OpenArm](https://github.com/enactic/openarm)**
  Braço humanoide de 7 eixos para pesquisa em IA física em ambientes ricos em contato

### Mãos Robóticas

- **[Aero Hand Open](https://github.com/TetherIA/aero-hand-open)**
  Mão robótica acionada por tendão: 389g, $314, 7 GDL com SDK Python e ROS2

- **[TRLC-DK1](https://github.com/robot-learning-co/trlc-dk1)**
  Plataforma robótica bimanual para coleta de dados humanoides com LeRobot

- **[LEAP Hand](https://github.com/leap-hand/LEAP_Hand_API)**
  Mão antropomórfica de baixo custo com 16 GDL para aprendizado robótico

- **[Delta X Soft Gripper](https://github.com/deltaxrobot/Delta-X-3D-Printed-Parts)**
  Garra macia DIY de $10 para alimentos usando moldes impressos em 3D e silicone

- **[DexHand v2.3](https://github.com/TheRobotStudio/V2_DexHand)**
  Design de mão destra open source do The Robot Studio e NVIDIA

### Robôs com Pernas

- **[Solo12](https://github.com/open-dynamic-robot-initiative/open_robot_actuator_hardware)**
  Robô quadrúpede leve de 12 GDL para pesquisa em locomoção com atuadores controlados por torque

- **[Open-Source Leg](https://github.com/neurobionics/opensourceleg)**
  Plataforma de prótese robótica open source com designs de hardware e SDK Python

### Humanoides

- **[Mobile ALOHA](https://github.com/MarkFzp/mobile-aloha)**
  Sistema de teleoperação de corpo inteiro de $32k para manipulação móvel bimanual

- **[LeKiwi](https://github.com/SIGRobotics-UIUC/LeKiwi)**
  Manipulador móvel holonômico de baixo custo com SO-ARM101 e LeRobot

- **[HOPEJr](https://github.com/TheRobotStudio/HOPEJr)**
  Robô humanoide DIY com 66 GDL, peças impressas em 3D e suporte LeRobot

## Software e Frameworks

Ferramentas e frameworks essenciais para desenvolvimento em robótica.

- **[LeRobot](https://github.com/huggingface/lerobot)**
  Biblioteca ML da HuggingFace para robótica do mundo real em PyTorch

- **[ROS 2](https://github.com/ros2/ros2)**
  Sistema operacional de robôs de próxima geração para robótica de produção em tempo real

- **[Dora AI](https://github.com/dora-rs/dora)**
  Middleware de fluxo de dados para aplicações de robótica com IA, construído em Rust

- **[RLinf](https://github.com/RLinf/RLinf)**
  Infraestrutura escalável para pós-treinamento de modelos de fundação via RL

- **[Extreme Parkour with Legged Robots](https://github.com/chengxuxin/extreme-parkour)**
  Sistema RL para parkour de robôs com pernas treinado em menos de 20 horas

## Modelos de Fundação

Modelos de IA para robótica e inteligência incorporada.

- **[OpenPI](https://github.com/Physical-Intelligence/openpi)**
  Modelos de fundação VLA da Physical Intelligence para controle robótico geral

- **[NVIDIA Isaac GR00T](https://github.com/NVIDIA/Isaac-GR00T)**
  Modelo de fundação aberto da NVIDIA para raciocínio e habilidades de robôs humanoides

- **[OpenVLA](https://github.com/openvla/openvla)**
  Modelo Visão-Linguagem-Ação de 7 bilhões de parâmetros para manipulação robótica

- **[ACT (Action Chunking with Transformers)](https://github.com/tonyzhaozh/act)**
  Aprendizado de políticas baseado em Transformer para manipulação bimanual

- **[SmolVLA](https://huggingface.co/lerobot/smolvla_base)**
  Modelo VLA de 450M de parâmetros que roda em hardware de consumo

## Simuladores

Simuladores de física e ambientes virtuais para desenvolvimento e testes em robótica.

- **[GENESIS](https://github.com/Genesis-Embodied-AI/Genesis)**
  Motor de física mais rápido do mundo: 43M FPS para aprendizado de IA incorporada

- **[MuJoCo](https://github.com/google-deepmind/mujoco)**
  Motor de física da DeepMind para pesquisa em robótica e ML

- **[Isaac Lab](https://github.com/isaac-sim/IsaacLab)**
  Framework unificado de aprendizado em robótica da NVIDIA no Isaac Sim

- **[ManiSkill](https://github.com/haosulab/ManiSkill)**
  Simulação paralela em GPU para habilidades de manipulação generalizáveis

- **[NVIDIA Isaac Sim](https://github.com/isaac-sim/IsaacSim)**
  Aplicativo NVIDIA Omniverse para simulação e testes de robôs com IA

## Benchmarks

Benchmarks padronizados e frameworks de avaliação para pesquisa em robótica.

- **[MetaWorld](https://github.com/Farama-Foundation/Metaworld)**
  Benchmark multi-tarefa e meta-RL para manipulação robótica

- **[RLBench](https://github.com/stepjam/RLBench)**
  Benchmark de 100+ tarefas para pesquisa em manipulação guiada por visão

- **[LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO)**
  Benchmark de aprendizado robótico contínuo com 130 tarefas procedurais

- **[CALVIN](https://github.com/mees/calvin)**
  Benchmark de manipulação condicionada por linguagem para tarefas de longo horizonte

## Conjuntos de Dados

Conjuntos de dados de treinamento para aprendizado e pesquisa em robótica.

- **[Open X-Embodiment (OXE)](https://github.com/google-deepmind/open_x_embodiment)**
  Maior conjunto de dados de robótica aberto: 1M+ episódios de 22 incorporações

- **[DROID](https://github.com/droid-dataset/droid)**
  76K trajetórias de manipulação robótica de 564 cenas diversas

**[Navegue por todos os projetos no Open Source Robotics](https://robotics.growbotics.ai/projects)**

---

## Pesquisa

### Artigos

- **[Instant Policy: In-Context Imitation Learning via Graph Diffusion](https://arxiv.org/pdf/2411.12633.pdf)** - ICLR 2025 Robot Learning Workshop (Prêmio de Melhor Artigo)

**[Navegue por todos os artigos](https://robotics.growbotics.ai/research/papers)**

### Livros

- **[Dancing with Roomba: Cracking the Robot Riddle and Building an Icon](https://www.amazon.com/Dancing-Roomba-Cracking-Riddle-Building/dp/1032889527)** por Joseph L. Jones

- **[Modern Robotics: Mechanics, Planning, and Control](https://www.amazon.com/Modern-Robotics-Mechanics-Planning-Control/dp/1107156300)** por Kevin M. Lynch, Frank C. Park

- **[Probabilistic Robotics](https://www.amazon.com/Probabilistic-Robotics-INTELLIGENT-ROBOTICS-AUTONOMOUS/dp/0262201623)** por Sebastian Thrun, Wolfram Burgard, Dieter Fox

**[Navegue por todos os livros](https://robotics.growbotics.ai/research/books)**

### Cursos

- **[Modern Robotics: Mechanics, Planning, and Control Specialization](https://www.coursera.org/specializations/modernrobotics)** no Coursera

- **[HuggingFace Robotics Course](https://huggingface.co/learn/robotics-course/unit0/1)** no Hugging Face

**[Navegue por todos os cursos](https://robotics.growbotics.ai/research/courses)**

---

## Eventos

- **[IEEE International Conference on Robotics and Automation (ICRA)](https://2026.ieee-icra.org/)**

- **[Humanoids Summit](https://humanoidssummit.com/)**

- **[NeurIPS - Neural Information Processing Systems](https://neurips.cc/)**

- **[CoRL - Conference on Robot Learning](https://www.robot-learning.org/)**

**[Ver todos os eventos](https://robotics.growbotics.ai/events)**

---

## Pessoas para Seguir

- **[Angela Schoellig](https://twitter.com/angelaschoellig)** (Universidade de Toronto)

- **[Audrow Nash](https://twitter.com/audrow)**

- **[Chelsea Finn](https://twitter.com/chelseabfinn)** (Universidade Stanford)

- **[Deepak Pathak](https://twitter.com/pathak2206)** (Carnegie Mellon University)

- **[Pieter Abbeel](https://twitter.com/pabbeel)** (UC Berkeley)

- **[Rémi Cadène](https://twitter.com/RemiCadene)** (UMA - Universal Mechanical Assistant)

**[Descubra mais pesquisadores e engenheiros](https://robotics.growbotics.ai/community/people)**

---

## Podcasts

- **[Audrow Nash Podcast](https://open.spotify.com/show/74jWpWiLwsasY2QHtDcl8I)**

- **[RoboPapers](https://open.spotify.com/show/3U0Ed7poaOElItEyUPkuto)**

- **[The Robot Brains Podcast](https://open.spotify.com/show/1oQXUJBjpJoxfUd3JAc0Zt)**

**[Navegue por todos os podcasts](https://robotics.growbotics.ai/community/podcasts)**

---

## Canais do YouTube

- **[Skyentific](https://www.youtube.com/@skyentific)**

- **[CMU Robotics Institute](https://www.youtube.com/@cmurobotics)**

**[Navegue por todos os canais](https://robotics.growbotics.ai/community/youtube)**

---

## Blogs

Blogs e newsletters de robótica que vale a pena seguir.

- **[Six Degrees of Robotics](https://sixdegreesofrobotics.substack.com/)** por Christopher Sanchez

- **[State of Robot Learning — Dec 2025](https://vedder.io/misc/state_of_robot_learning_dec_2025.html)** por Kyle Vedder

- **[We All Are Robots](https://ziegler.substack.com)** por Lukas Ziegler

**[Navegue por todos os blogs](https://robotics.growbotics.ai/community/blogs)**

---

## Empresas Inspiradoras

Empresas e laboratórios de pesquisa expandindo os limites da robótica.

- **[1X Technologies](https://www.1x.tech)**
  Desenvolvendo robôs humanoides de propósito geral com automação escalável.

- **[Agility Robotics](https://www.agilityrobotics.com)**
  Criadores do Digit, um robô bípede para logística do mundo real.

- **[Apptronik](https://apptronik.com)**
  Inovadores em robôs humanoides, incluindo o Apollo.

- **[Boston Dynamics](https://www.bostondynamics.com)**
  Líder da indústria em robôs dinâmicos como Spot e Atlas.

- **[Enchanted Tools](https://enchanted.tools)**
  Criadores do Miroka, robôs humanoides emocionalmente envolventes.

- **[Engineered Arts](https://www.engineeredarts.co.uk)**
  Criadores do Ameca, robôs humanoides avançados para interação humana.

- **[Hanson Robotics](https://www.hansonrobotics.com)**
  Desenvolvedores de robôs humanoides realistas como Sophia.

- **[Sunday](https://www.sunday.ai)**
  Desenvolvendo o Memo, um robô doméstico treinado em 10 milhões de tarefas domésticas reais...

**[Explore todas as empresas](https://robotics.growbotics.ai/community/companies)**

---

## Licença

Esta lista está licenciada sob [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).

---

## Contribuir

Sugestões são bem-vindas! Visite **[Open Source Robotics](https://robotics.growbotics.ai)** para sugerir novo conteúdo ou abra uma issue neste repositório.

---

**[Explore a plataforma completa com BOMs, guias de montagem e mais](https://robotics.growbotics.ai)**
