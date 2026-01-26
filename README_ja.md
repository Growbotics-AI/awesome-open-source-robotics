# オープンソースロボティクス精選リスト

**[English](README.md)** | **[中文](README_zh.md)** | **[Deutsch](README_de.md)** | **[Español](README_es.md)**

> 優れたオープンソースロボティクスプロジェクト、ツール、リソースの厳選リスト。

このリストは意図的に**厳選**されています。BOM、組立ガイド、詳細情報を含む完全なデータベースは **[Open Source Robotics](https://robotics.growbotics.ai)** をご覧ください。

---

## 目次

- [プロジェクト](#プロジェクト)
  - [ロボットアーム](#ロボットアーム)
  - [ロボットハンド](#ロボットハンド)
  - [脚式ロボット](#脚式ロボット)
  - [ヒューマノイド](#ヒューマノイド)
- [ソフトウェア・フレームワーク](#ソフトウェアフレームワーク)
- [基盤モデル](#基盤モデル)
- [シミュレータ](#シミュレータ)
- [ベンチマーク](#ベンチマーク)
- [データセット](#データセット)
- [研究](#研究)
  - [論文](#論文)
  - [書籍](#書籍)
  - [コース](#コース)
- [イベント](#イベント)
- [注目すべき人物](#注目すべき人物)
- [ポッドキャスト](#ポッドキャスト)
- [YouTubeチャンネル](#youtubeチャンネル)
- [ブログ](#ブログ)
- [注目企業](#注目企業)
- [ライセンス](#ライセンス)

---

## プロジェクト

注目のオープンソースロボティクスプロジェクト厳選。

### ロボットアーム

- **[SO-101 Open Robot Arm](https://github.com/TheRobotStudio/SO-ARM100)**
  遠隔操作とAIロボティクス研究用の6自由度ロボットアーム

- **[BCN3D Moveo](https://github.com/BCN3D/BCN3D-Moveo)**
  教育用オープンソース3Dプリントロボットアーム

- **[OpenArm](https://github.com/enactic/openarm)**
  接触が多い環境での物理AI研究用7自由度ヒューマノイドアーム

### ロボットハンド

- **[Aero Hand Open](https://github.com/TetherIA/aero-hand-open)**
  腱駆動ロボットハンド：389g、314ドル、7自由度、Python SDKとROS2対応

- **[TRLC-DK1](https://github.com/robot-learning-co/trlc-dk1)**
  LeRobotを使用したヒューマノイドデータ収集用双腕ロボットプラットフォーム

- **[LEAP Hand](https://github.com/leap-hand/LEAP_Hand_API)**
  ロボット学習用16自由度低コスト人間型ハンド

- **[Delta X Soft Gripper](https://github.com/deltaxrobot/Delta-X-3D-Printed-Parts)**
  3Dプリント金型とシリコンを使用した10ドルDIY食品グレードソフトグリッパー

- **[DexHand v2.3](https://github.com/TheRobotStudio/V2_DexHand)**
  The Robot StudioとNVIDIAによるオープンソース巧緻ハンド設計

### 脚式ロボット

- **[Solo12](https://github.com/open-dynamic-robot-initiative/open_robot_actuator_hardware)**
  トルク制御アクチュエータを搭載した歩行研究用12自由度軽量四足ロボット

- **[Open-Source Leg](https://github.com/neurobionics/opensourceleg)**
  ハードウェア設計とPython SDKを備えたオープンソースロボット義足プラットフォーム

### ヒューマノイド

- **[Mobile ALOHA](https://github.com/MarkFzp/mobile-aloha)**
  双腕移動マニピュレーション用32,000ドル全身遠隔操作システム

- **[LeKiwi](https://github.com/SIGRobotics-UIUC/LeKiwi)**
  SO-ARM101とLeRobotを搭載した低コスト全方向移動マニピュレータ

- **[HOPEJr](https://github.com/TheRobotStudio/HOPEJr)**
  66自由度、3Dプリント部品、LeRobot対応DIYヒューマノイドロボット

## ソフトウェア・フレームワーク

ロボティクス開発に必須のツールとフレームワーク。

- **[LeRobot](https://github.com/huggingface/lerobot)**
  PyTorchによる実世界ロボティクス用HuggingFace MLライブラリ

- **[ROS 2](https://github.com/ros2/ros2)**
  リアルタイム本番ロボティクス用次世代ロボットオペレーティングシステム

- **[Dora AI](https://github.com/dora-rs/dora)**
  Rustで構築されたAIロボティクスアプリケーション用データフローミドルウェア

- **[RLinf](https://github.com/RLinf/RLinf)**
  強化学習による基盤モデルの事後訓練用スケーラブルインフラストラクチャ

- **[Extreme Parkour with Legged Robots](https://github.com/chengxuxin/extreme-parkour)**
  20時間以内に訓練された脚式ロボットパルクール用RLシステム

## 基盤モデル

ロボティクスと身体化知能のためのAIモデル。

- **[OpenPI](https://github.com/Physical-Intelligence/openpi)**
  汎用ロボット制御用Physical Intelligence VLA基盤モデル

- **[NVIDIA Isaac GR00T](https://github.com/NVIDIA/Isaac-GR00T)**
  ヒューマノイドロボットの推論とスキル用NVIDIAオープン基盤モデル

- **[OpenVLA](https://github.com/openvla/openvla)**
  ロボットマニピュレーション用70億パラメータVision-Language-Actionモデル

- **[ACT (Action Chunking with Transformers)](https://github.com/tonyzhaozh/act)**
  双腕マニピュレーション用Transformerベースポリシー学習

- **[SmolVLA](https://huggingface.co/lerobot/smolvla_base)**
  消費者向けハードウェアで動作する4億5000万パラメータVLAモデル

## シミュレータ

ロボティクス開発とテスト用物理シミュレータと仮想環境。

- **[GENESIS](https://github.com/Genesis-Embodied-AI/Genesis)**
  世界最速の物理エンジン：身体化AI学習用4300万FPS

- **[MuJoCo](https://github.com/google-deepmind/mujoco)**
  ロボティクスとML研究用DeepMind物理エンジン

- **[Isaac Lab](https://github.com/isaac-sim/IsaacLab)**
  Isaac Sim上のNVIDIA統合ロボティクス学習フレームワーク

- **[ManiSkill](https://github.com/haosulab/ManiSkill)**
  汎化可能なマニピュレーションスキル用GPU並列シミュレーション

- **[NVIDIA Isaac Sim](https://github.com/isaac-sim/IsaacSim)**
  AI駆動ロボットシミュレーションとテスト用NVIDIA Omniverseアプリ

## ベンチマーク

ロボティクス研究用標準化ベンチマークと評価フレームワーク。

- **[MetaWorld](https://github.com/Farama-Foundation/Metaworld)**
  ロボットマニピュレーション用マルチタスク・メタRLベンチマーク

- **[RLBench](https://github.com/stepjam/RLBench)**
  視覚誘導マニピュレーション研究用100以上のタスクベンチマーク

- **[LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO)**
  130の手続き的タスクを含む生涯ロボット学習ベンチマーク

- **[CALVIN](https://github.com/mees/calvin)**
  長期タスク用言語条件付きマニピュレーションベンチマーク

## データセット

ロボット学習と研究用訓練データセット。

- **[Open X-Embodiment (OXE)](https://github.com/google-deepmind/open_x_embodiment)**
  最大のオープンロボティクスデータセット：22の身体形態から100万以上のエピソード

- **[DROID](https://github.com/droid-dataset/droid)**
  564の多様なシーンからの76,000ロボットマニピュレーション軌跡

**[Open Source Roboticsで全プロジェクトを閲覧](https://robotics.growbotics.ai/projects)**

---

## 研究

### 論文

- **[Instant Policy: In-Context Imitation Learning via Graph Diffusion](https://arxiv.org/pdf/2411.12633.pdf)** - ICLR 2025ロボット学習ワークショップ（最優秀論文賞）

**[全論文を閲覧](https://robotics.growbotics.ai/research/papers)**

### 書籍

- **[Dancing with Roomba: Cracking the Robot Riddle and Building an Icon](https://www.amazon.com/Dancing-Roomba-Cracking-Riddle-Building/dp/1032889527)** 著：Joseph L. Jones

- **[Modern Robotics: Mechanics, Planning, and Control](https://www.amazon.com/Modern-Robotics-Mechanics-Planning-Control/dp/1107156300)** 著：Kevin M. Lynch, Frank C. Park

- **[Probabilistic Robotics](https://www.amazon.com/Probabilistic-Robotics-INTELLIGENT-ROBOTICS-AUTONOMOUS/dp/0262201623)** 著：Sebastian Thrun, Wolfram Burgard, Dieter Fox

**[全書籍を閲覧](https://robotics.growbotics.ai/research/books)**

### コース

- **[Modern Robotics: Mechanics, Planning, and Control Specialization](https://www.coursera.org/specializations/modernrobotics)** Coursera

- **[HuggingFace Robotics Course](https://huggingface.co/learn/robotics-course/unit0/1)** Hugging Face

**[全コースを閲覧](https://robotics.growbotics.ai/research/courses)**

---

## イベント

- **[IEEE International Conference on Robotics and Automation (ICRA)](https://2026.ieee-icra.org/)**

- **[Humanoids Summit](https://humanoidssummit.com/)**

- **[NeurIPS - Neural Information Processing Systems](https://neurips.cc/)**

- **[CoRL - Conference on Robot Learning](https://www.robot-learning.org/)**

**[全イベントを表示](https://robotics.growbotics.ai/events)**

---

## 注目すべき人物

- **[Angela Schoellig](https://twitter.com/angelaschoellig)**（トロント大学）

- **[Audrow Nash](https://twitter.com/audrow)**

- **[Chelsea Finn](https://twitter.com/chelseabfinn)**（スタンフォード大学）

- **[Deepak Pathak](https://twitter.com/pathak2206)**（カーネギーメロン大学）

- **[Pieter Abbeel](https://twitter.com/pabbeel)**（UCバークレー）

- **[Rémi Cadène](https://twitter.com/RemiCadene)**（UMA（Universal Mechanical Assistant））

**[より多くの研究者とエンジニアを発見](https://robotics.growbotics.ai/community/people)**

---

## ポッドキャスト

- **[Audrow Nash Podcast](https://open.spotify.com/show/74jWpWiLwsasY2QHtDcl8I)**

- **[RoboPapers](https://open.spotify.com/show/3U0Ed7poaOElItEyUPkuto)**

- **[The Robot Brains Podcast](https://open.spotify.com/show/1oQXUJBjpJoxfUd3JAc0Zt)**

**[全ポッドキャストを閲覧](https://robotics.growbotics.ai/community/podcasts)**

---

## YouTubeチャンネル

- **[Skyentific](https://www.youtube.com/@skyentific)**

- **[CMU Robotics Institute](https://www.youtube.com/@cmurobotics)**

**[全チャンネルを閲覧](https://robotics.growbotics.ai/community/youtube)**

---

## ブログ

フォローすべきロボティクスブログとニュースレター。

- **[Six Degrees of Robotics](https://sixdegreesofrobotics.substack.com/)** 著：Christopher Sanchez

- **[State of Robot Learning — Dec 2025](https://vedder.io/misc/state_of_robot_learning_dec_2025.html)** 著：Kyle Vedder

- **[We All Are Robots](https://ziegler.substack.com)** 著：Lukas Ziegler

**[全ブログを閲覧](https://robotics.growbotics.ai/community/blogs)**

---

## 注目企業

境界を押し広げるロボティクス企業と研究機関。

- **[1X Technologies](https://www.1x.tech)**
  スケーラブルな自動化機能を持つ汎用ヒューマノイドロボットを開発。

- **[Agility Robotics](https://www.agilityrobotics.com)**
  実世界の物流用二足歩行ロボットDigitの開発者。

- **[Apptronik](https://apptronik.com)**
  Apolloを含むヒューマノイドロボットのイノベーター。

- **[Boston Dynamics](https://www.bostondynamics.com)**
  SpotやAtlasなど動的ロボットの業界リーダー。

- **[Enchanted Tools](https://enchanted.tools)**
  感情的に魅力的なヒューマノイド型ロボットMirokaの開発者。

- **[Engineered Arts](https://www.engineeredarts.co.uk)**
  人間とのインタラクション用先進ヒューマノイドロボットAmecaの開発者。

- **[Hanson Robotics](https://www.hansonrobotics.com)**
  Sophiaのような生命感あふれるヒューマノイドロボットの開発者。

- **[Sunday](https://www.sunday.ai)**
  1000万の実世界家事データで訓練された家庭用ロボットMemoを構築中...

**[全企業を探索](https://robotics.growbotics.ai/community/companies)**

---

## ライセンス

このリストは[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)ライセンスの下で公開されています。

---

## 貢献

提案を歓迎します！新しいコンテンツを提案するには **[Open Source Robotics](https://robotics.growbotics.ai)** にアクセスするか、このリポジトリでissueを開いてください。

---

**[BOM、組立ガイドなどを含む完全なプラットフォームを探索](https://robotics.growbotics.ai)**
