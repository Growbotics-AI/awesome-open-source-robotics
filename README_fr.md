# Robotique Open Source - Sélection

**[English](README.md)** | **[中文](README_zh.md)** | **[日本語](README_ja.md)** | **[Deutsch](README_de.md)** | **[Español](README_es.md)** | **[한국어](README_ko.md)** | **[Português](README_pt.md)**

> Une liste sélectionnée de projets, outils et ressources robotiques open source inspirants et impactants.

Cette liste est intentionnellement **sélective**. Pour la base de données complète avec les nomenclatures, guides d'assemblage et informations détaillées, visitez **[Open Source Robotics](https://robotics.growbotics.ai)**.

---

## Sommaire

- [Projets](#projets)
  - [Bras Robotiques](#bras-robotiques)
  - [Mains Robotiques](#mains-robotiques)
  - [Robots à Pattes](#robots-à-pattes)
  - [Humanoïdes](#humanoïdes)
- [Logiciels et Frameworks](#logiciels-et-frameworks)
- [Modèles de Fondation](#modèles-de-fondation)
- [Simulateurs](#simulateurs)
- [Benchmarks](#benchmarks)
- [Jeux de Données](#jeux-de-données)
- [Recherche](#recherche)
  - [Articles](#articles)
  - [Livres](#livres)
  - [Cours](#cours)
- [Événements](#événements)
- [Personnalités à Suivre](#personnalités-à-suivre)
- [Podcasts](#podcasts)
- [Chaînes YouTube](#chaînes-youtube)
- [Blogs](#blogs)
- [Entreprises Inspirantes](#entreprises-inspirantes)
- [Licence](#licence)

---

## Projets

Une sélection de projets robotiques open source remarquables.

### Bras Robotiques

- **[SO-101 Open Robot Arm](https://github.com/TheRobotStudio/SO-ARM100)**
  Bras robotique 6 axes pour la téléopération et la recherche en robotique IA

- **[BCN3D Moveo](https://github.com/BCN3D/BCN3D-Moveo)**
  Bras robotique imprimé en 3D open source pour l'éducation

- **[OpenArm](https://github.com/enactic/openarm)**
  Bras humanoïde 7 axes pour la recherche en IA physique dans des environnements riches en contacts

### Mains Robotiques

- **[Aero Hand Open](https://github.com/TetherIA/aero-hand-open)**
  Main robotique à tendons : 389g, 314$, 7 DDL avec SDK Python et ROS2

- **[TRLC-DK1](https://github.com/robot-learning-co/trlc-dk1)**
  Plateforme robotique bimanuelle pour la collecte de données humanoïdes avec LeRobot

- **[LEAP Hand](https://github.com/leap-hand/LEAP_Hand_API)**
  Main anthropomorphe à faible coût avec 16 DDL pour l'apprentissage robotique

- **[Delta X Soft Gripper](https://github.com/deltaxrobot/Delta-X-3D-Printed-Parts)**
  Pince souple alimentaire DIY à 10$ utilisant des moules imprimés en 3D et du silicone

- **[DexHand v2.3](https://github.com/TheRobotStudio/V2_DexHand)**
  Conception de main dextre open source de The Robot Studio et NVIDIA

### Robots à Pattes

- **[Solo12](https://github.com/open-dynamic-robot-initiative/open_robot_actuator_hardware)**
  Robot quadrupède léger à 12 DDL pour la recherche en locomotion avec actionneurs à contrôle de couple

- **[Open-Source Leg](https://github.com/neurobionics/opensourceleg)**
  Plateforme de prothèse robotique open source avec designs matériels et SDK Python

### Humanoïdes

- **[Mobile ALOHA](https://github.com/MarkFzp/mobile-aloha)**
  Système de téléopération corps entier à 32k$ pour la manipulation mobile bimanuelle

- **[LeKiwi](https://github.com/SIGRobotics-UIUC/LeKiwi)**
  Manipulateur mobile holonomique à faible coût avec SO-ARM101 et LeRobot

- **[HOPEJr](https://github.com/TheRobotStudio/HOPEJr)**
  Robot humanoïde DIY avec 66 DDL, pièces imprimées en 3D et support LeRobot

## Logiciels et Frameworks

Outils et frameworks essentiels pour le développement robotique.

- **[LeRobot](https://github.com/huggingface/lerobot)**
  Bibliothèque ML HuggingFace pour la robotique réelle en PyTorch

- **[ROS 2](https://github.com/ros2/ros2)**
  Système d'exploitation robotique nouvelle génération pour la robotique de production temps réel

- **[Dora AI](https://github.com/dora-rs/dora)**
  Middleware de flux de données pour applications robotiques IA, construit en Rust

- **[RLinf](https://github.com/RLinf/RLinf)**
  Infrastructure évolutive pour le post-entraînement des modèles de fondation via RL

- **[Extreme Parkour with Legged Robots](https://github.com/chengxuxin/extreme-parkour)**
  Système RL pour le parkour de robots à pattes entraîné en moins de 20 heures

## Modèles de Fondation

Modèles IA pour la robotique et l'intelligence incarnée.

- **[OpenPI](https://github.com/Physical-Intelligence/openpi)**
  Modèles de fondation VLA de Physical Intelligence pour le contrôle robotique général

- **[NVIDIA Isaac GR00T](https://github.com/NVIDIA/Isaac-GR00T)**
  Modèle de fondation ouvert NVIDIA pour le raisonnement et les compétences des robots humanoïdes

- **[OpenVLA](https://github.com/openvla/openvla)**
  Modèle Vision-Langage-Action à 7 milliards de paramètres pour la manipulation robotique

- **[ACT (Action Chunking with Transformers)](https://github.com/tonyzhaozh/act)**
  Apprentissage de politiques basé sur Transformer pour la manipulation bimanuelle

- **[SmolVLA](https://huggingface.co/lerobot/smolvla_base)**
  Modèle VLA à 450M de paramètres fonctionnant sur matériel grand public

## Simulateurs

Simulateurs physiques et environnements virtuels pour le développement et les tests robotiques.

- **[GENESIS](https://github.com/Genesis-Embodied-AI/Genesis)**
  Moteur physique le plus rapide au monde : 43M FPS pour l'apprentissage IA incarnée

- **[MuJoCo](https://github.com/google-deepmind/mujoco)**
  Moteur physique DeepMind pour la recherche en robotique et ML

- **[Isaac Lab](https://github.com/isaac-sim/IsaacLab)**
  Framework d'apprentissage robotique unifié NVIDIA sur Isaac Sim

- **[ManiSkill](https://github.com/haosulab/ManiSkill)**
  Simulation parallélisée GPU pour des compétences de manipulation généralisables

- **[NVIDIA Isaac Sim](https://github.com/isaac-sim/IsaacSim)**
  Application NVIDIA Omniverse pour la simulation et les tests robotiques pilotés par IA

## Benchmarks

Benchmarks standardisés et frameworks d'évaluation pour la recherche robotique.

- **[MetaWorld](https://github.com/Farama-Foundation/Metaworld)**
  Benchmark multi-tâches et méta-RL pour la manipulation robotique

- **[RLBench](https://github.com/stepjam/RLBench)**
  Benchmark de 100+ tâches pour la recherche en manipulation guidée par vision

- **[LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO)**
  Benchmark d'apprentissage robotique continu avec 130 tâches procédurales

- **[CALVIN](https://github.com/mees/calvin)**
  Benchmark de manipulation conditionnée par le langage pour les tâches à long horizon

## Jeux de Données

Jeux de données d'entraînement pour l'apprentissage et la recherche robotique.

- **[Open X-Embodiment (OXE)](https://github.com/google-deepmind/open_x_embodiment)**
  Plus grand jeu de données robotique ouvert : 1M+ épisodes de 22 incarnations

- **[DROID](https://github.com/droid-dataset/droid)**
  76K trajectoires de manipulation robotique de 564 scènes diverses

**[Parcourir tous les projets sur Open Source Robotics](https://robotics.growbotics.ai/projects)**

---

## Recherche

### Articles

- **[Instant Policy: In-Context Imitation Learning via Graph Diffusion](https://arxiv.org/pdf/2411.12633.pdf)** - ICLR 2025 Robot Learning Workshop (Prix du Meilleur Article)

**[Parcourir tous les articles](https://robotics.growbotics.ai/research/papers)**

### Livres

- **[Dancing with Roomba: Cracking the Robot Riddle and Building an Icon](https://www.amazon.com/Dancing-Roomba-Cracking-Riddle-Building/dp/1032889527)** par Joseph L. Jones

- **[Modern Robotics: Mechanics, Planning, and Control](https://www.amazon.com/Modern-Robotics-Mechanics-Planning-Control/dp/1107156300)** par Kevin M. Lynch, Frank C. Park

- **[Probabilistic Robotics](https://www.amazon.com/Probabilistic-Robotics-INTELLIGENT-ROBOTICS-AUTONOMOUS/dp/0262201623)** par Sebastian Thrun, Wolfram Burgard, Dieter Fox

**[Parcourir tous les livres](https://robotics.growbotics.ai/research/books)**

### Cours

- **[Modern Robotics: Mechanics, Planning, and Control Specialization](https://www.coursera.org/specializations/modernrobotics)** sur Coursera

- **[HuggingFace Robotics Course](https://huggingface.co/learn/robotics-course/unit0/1)** sur Hugging Face

**[Parcourir tous les cours](https://robotics.growbotics.ai/research/courses)**

---

## Événements

- **[IEEE International Conference on Robotics and Automation (ICRA)](https://2026.ieee-icra.org/)**

- **[Humanoids Summit](https://humanoidssummit.com/)**

- **[NeurIPS - Neural Information Processing Systems](https://neurips.cc/)**

- **[CoRL - Conference on Robot Learning](https://www.robot-learning.org/)**

**[Voir tous les événements](https://robotics.growbotics.ai/events)**

---

## Personnalités à Suivre

- **[Angela Schoellig](https://twitter.com/angelaschoellig)** (Université de Toronto)

- **[Audrow Nash](https://twitter.com/audrow)**

- **[Chelsea Finn](https://twitter.com/chelseabfinn)** (Université Stanford)

- **[Deepak Pathak](https://twitter.com/pathak2206)** (Carnegie Mellon University)

- **[Pieter Abbeel](https://twitter.com/pabbeel)** (UC Berkeley)

- **[Rémi Cadène](https://twitter.com/RemiCadene)** (UMA - Universal Mechanical Assistant)

**[Découvrir plus de chercheurs et ingénieurs](https://robotics.growbotics.ai/community/people)**

---

## Podcasts

- **[Audrow Nash Podcast](https://open.spotify.com/show/74jWpWiLwsasY2QHtDcl8I)**

- **[RoboPapers](https://open.spotify.com/show/3U0Ed7poaOElItEyUPkuto)**

- **[The Robot Brains Podcast](https://open.spotify.com/show/1oQXUJBjpJoxfUd3JAc0Zt)**

**[Parcourir tous les podcasts](https://robotics.growbotics.ai/community/podcasts)**

---

## Chaînes YouTube

- **[Skyentific](https://www.youtube.com/@skyentific)**

- **[CMU Robotics Institute](https://www.youtube.com/@cmurobotics)**

**[Parcourir toutes les chaînes](https://robotics.growbotics.ai/community/youtube)**

---

## Blogs

Blogs et newsletters robotiques à suivre.

- **[Six Degrees of Robotics](https://sixdegreesofrobotics.substack.com/)** par Christopher Sanchez

- **[State of Robot Learning — Dec 2025](https://vedder.io/misc/state_of_robot_learning_dec_2025.html)** par Kyle Vedder

- **[We All Are Robots](https://ziegler.substack.com)** par Lukas Ziegler

**[Parcourir tous les blogs](https://robotics.growbotics.ai/community/blogs)**

---

## Entreprises Inspirantes

Entreprises et laboratoires de recherche repoussant les limites de la robotique.

- **[1X Technologies](https://www.1x.tech)**
  Développement de robots humanoïdes polyvalents avec automatisation évolutive.

- **[Agility Robotics](https://www.agilityrobotics.com)**
  Créateurs de Digit, un robot bipède pour la logistique réelle.

- **[Apptronik](https://apptronik.com)**
  Innovateurs en robots humanoïdes, dont Apollo.

- **[Boston Dynamics](https://www.bostondynamics.com)**
  Leader de l'industrie en robots dynamiques comme Spot et Atlas.

- **[Enchanted Tools](https://enchanted.tools)**
  Créateurs de Miroka, robots humanoïdes émotionnellement engageants.

- **[Engineered Arts](https://www.engineeredarts.co.uk)**
  Créateurs d'Ameca, robots humanoïdes avancés pour l'interaction humaine.

- **[Hanson Robotics](https://www.hansonrobotics.com)**
  Développeurs de robots humanoïdes réalistes comme Sophia.

- **[Sunday](https://www.sunday.ai)**
  Développement de Memo, un robot domestique entraîné sur 10 millions de tâches ménagères réelles...

**[Explorer toutes les entreprises](https://robotics.growbotics.ai/community/companies)**

---

## Licence

Cette liste est sous licence [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).

---

## Contribuer

Les suggestions sont les bienvenues ! Visitez **[Open Source Robotics](https://robotics.growbotics.ai)** pour suggérer du nouveau contenu ou ouvrez une issue dans ce dépôt.

---

**[Explorer la plateforme complète avec nomenclatures, guides d'assemblage et plus](https://robotics.growbotics.ai)**
