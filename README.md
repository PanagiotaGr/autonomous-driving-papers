# Autonomous Driving arXiv Daily

A lightweight, automatically updated daily arXiv digest focused on **Autonomous Driving research**.

This repository is designed to support:
- literature review
- state-of-the-art tracking
- thesis / research work in autonomous vehicles

The digest covers the full autonomous driving stack, from perception to planning and safety.

---

## Scope

The following research areas are tracked daily:

- **Perception**
  - 2D / 3D object detection
  - Semantic & panoptic segmentation
  - Multi-modal sensor fusion (camera, LiDAR, radar)
  - Lane, drivable area & traffic signal understanding

- **Prediction**
  - Trajectory & motion prediction
  - Intention and behavior prediction
  - Interaction-aware & multi-agent models
  - VRU prediction (pedestrians, cyclists)
  - Risk, uncertainty & collision prediction

- **Planning & Control**
  - Motion & behavior planning
  - Trajectory optimization
  - Model Predictive Control (MPC)
  - Learning-based planning (IL / RL)
  - Safe and risk-aware planning

- **BEV & Occupancy**
  - Bird’s-Eye View (BEV) perception
  - Occupancy grids & occupancy networks
  - Spatio-temporal & 4D occupancy forecasting

- **Mapping & Localization**
  - SLAM & odometry (visual / LiDAR)
  - HD maps & semantic mapping
  - Localization & map learning

- **V2X & Cooperative Perception**
  - V2V / V2I / V2X
  - Collaborative & cooperative perception
  - Multi-vehicle sensor sharing

- **Safety & Robustness**
  - Uncertainty estimation & calibration
  - Out-of-distribution (OOD) detection
  - Adversarial robustness
  - Formal verification & runtime assurance
  - Scenario generation & corner cases

- **Datasets, Benchmarks & Simulation**
  - Driving datasets & benchmarks
  - Simulation environments
  - Scenario-based evaluation

---

## Latest Update

<!-- LATEST:START -->
- Updated on: **2026-01-27**
- Latest digest: `digests/2026-01-27.md`
<!-- LATEST:END -->

---

## Topic Navigator

<!-- TOPICS:START -->
| Topic | Latest Update | Papers | Link |
|------|--------------:|------:|------|
| Autonomous Driving – Perception (2D/3D Detection, Segmentation) | 2026-01-27 | 60 | [Autonomous Driving – Perception (2D/3D Detection, Segmentation)](topics/av-perception.md) |
| Autonomous Driving – Prediction (Trajectories, Intention, Interaction) | 2026-01-27 | 60 | [Autonomous Driving – Prediction (Trajectories, Intention, Interaction)](topics/av-prediction.md) |
| Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy) | 2026-01-27 | 32 | [Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)](topics/av-planning-control.md) |
| BEV & Occupancy (BEVPerception, Occupancy Networks, 4D) | 2026-01-27 | 3 | [BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)](topics/av-bev-occupancy.md) |
| Mapping, Localization & HD Maps (AV SLAM / Map Learning) | 2026-01-27 | 0 | [Mapping, Localization & HD Maps (AV SLAM / Map Learning)](topics/av-mapping-localization.md) |
| V2X / Cooperative Perception (V2V, V2I, Sensor Sharing) | 2026-01-27 | 7 | [V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)](topics/av-v2x-cooperative.md) |
| Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal) | 2026-01-27 | 0 | [Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal)](topics/av-safety-robustness.md) |
| Datasets, Benchmarks & Simulation (Driving) | 2026-01-27 | 0 | [Datasets, Benchmarks & Simulation (Driving)](topics/av-datasets-sim.md) |
<!-- TOPICS:END -->

---

## How It Works

The repository is updated automatically via **GitHub Actions**.

Every day:
1. arXiv is queried using broad category-based queries.
2. Papers are filtered using **domain-specific keywords** (title + abstract).
3. Results are organized into:
   - `digests/YYYY-MM-DD.md` — daily archive
   - `topics/<topic>.md` — rolling topic-based collections
4. The README is updated with the latest digest and topic statistics.

The configuration is fully customizable via `config.yml`.

---

## Configuration

You can edit `config.yml` to modify:
- arXiv categories
- topic definitions
- keyword lists (include / exclude)
- number of days back
- maximum papers per topic

This makes the repository adaptable to:
- general state-of-the-art tracking
- focused thesis research
- long-term literature monitoring

---

## Recommended Usage

- Use **daily digests** for quick scanning.
- Use **topic pages** as a rolling literature review.
- Optionally add personal notes or annotations directly to topic pages for thesis writing.

---

## License

Apache-2.0

<!-- BEGIN TODAY -->
## ✅ Today

**Last update:** 2026-01-27  
**Daily archive:** `digests/2026-01-27.md`  

_Auto-generated. Edit `config.yml` to change topics/queries/filters._

### Browse by topic (links)

- **[Autonomous Driving – Perception (2D/3D Detection, Segmentation)](topics/av-perception.md)**
- **[Autonomous Driving – Prediction (Trajectories, Intention, Interaction)](topics/av-prediction.md)**
- **[Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)](topics/av-planning-control.md)**
- **[BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)](topics/av-bev-occupancy.md)**
- **[Mapping, Localization & HD Maps (AV SLAM / Map Learning)](topics/av-mapping-localization.md)**
- **[V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)](topics/av-v2x-cooperative.md)**
- **[Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal)](topics/av-safety-robustness.md)**
- **[Datasets, Benchmarks & Simulation (Driving)](topics/av-datasets-sim.md)**

### Autonomous Driving – Perception (2D/3D Detection, Segmentation)

- **Goal-oriented Communication for Fast and Robust Robotic Fault Detection and Recovery**
  - Authors: Shutong Chen, Adnan Aijaz, Yansha Deng
  - Published: 2026-01-26 | Category: `cs.RO`
  - Links: [arXiv](https://arxiv.org/abs/2601.18765v1) | [PDF](https://arxiv.org/pdf/2601.18765v1)
- **SeNeDiF-OOD: Semantic Nested Dichotomy Fusion for Out-of-Distribution Detection Methodology in Open-World Classification. A Case Study on Monument Style Classification**
  - Authors: Ignacio Antequera-Sánchez, Juan Luis Suárez-Díaz, Rosana Montes, Francisco Herrera
  - Published: 2026-01-26 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.18739v1) | [PDF](https://arxiv.org/pdf/2601.18739v1)
- **Advances and Innovations in the Multi-Agent Robotic System (MARS) Challenge**
  - Authors: Li Kang, Heng Zhou, Xiufeng Song, Rui Li, Bruno N. Y. Chen, Ziye Wang, Ximeng Meng, Stone Tao et al.
  - Published: 2026-01-26 | Category: `cs.RO`
  - Links: [arXiv](https://arxiv.org/abs/2601.18733v1) | [PDF](https://arxiv.org/pdf/2601.18733v1)
- _(See full topic page: [Autonomous Driving – Perception (2D/3D Detection, Segmentation)](topics/av-perception.md))_


### Autonomous Driving – Prediction (Trajectories, Intention, Interaction)

- **ctELM: Decoding and Manipulating Embeddings of Clinical Trials with Embedding Language Models**
  - Authors: Brian Ondov, Chia-Hsuan Chang, Yujia Zhou, Mauro Giuffrè, Hua Xu
  - Published: 2026-01-26 | Category: `cs.CL`
  - Links: [arXiv](https://arxiv.org/abs/2601.18796v1) | [PDF](https://arxiv.org/pdf/2601.18796v1)
- **Reuse your FLOPs: Scaling RL on Hard Problems by Conditioning on Very Off-Policy Prefixes**
  - Authors: Amrith Setlur, Zijian Wang, Andrew Cohen, Paria Rashidinejad, Sang Michael Xie
  - Published: 2026-01-26 | Category: `cs.LG`
  - Links: [arXiv](https://arxiv.org/abs/2601.18795v1) | [PDF](https://arxiv.org/pdf/2601.18795v1)
- **MEGnifying Emotion: Sentiment Analysis from Annotated Brain Data**
  - Authors: Brian Liu, Oiwi Parker Jones
  - Published: 2026-01-26 | Category: `cs.HC`
  - Links: [arXiv](https://arxiv.org/abs/2601.18792v1) | [PDF](https://arxiv.org/pdf/2601.18792v1)
- _(See full topic page: [Autonomous Driving – Prediction (Trajectories, Intention, Interaction)](topics/av-prediction.md))_


### Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)

- **AI-Driven Fuzzing for Vulnerability Assessment of 5G Traffic Steering Algorithms**
  - Authors: Seyed Bagher Hashemi Natanzi, Hossein Mohammadi, Bo Tang, Vuk Marojevic
  - Published: 2026-01-26 | Category: `eess.SP`
  - Links: [arXiv](https://arxiv.org/abs/2601.18690v1) | [PDF](https://arxiv.org/pdf/2601.18690v1)
- **Synchronization and Localization in Ad-Hoc ICAS Networks Using a Two-Stage Kuramoto Method**
  - Authors: Dominik Neudert-Schulz, Thomas Dallmann
  - Published: 2026-01-26 | Category: `eess.SP`
  - Links: [arXiv](https://arxiv.org/abs/2601.18643v1) | [PDF](https://arxiv.org/pdf/2601.18643v1)
- **Experimental Characterization of ISAC Channel Mapping and Environment Awareness**
  - Authors: Zhuangzhuang Cui, Rizqi Hersyandika, Haoqiu Xiong, Sofie Pollin
  - Published: 2026-01-26 | Category: `eess.SY`
  - Links: [arXiv](https://arxiv.org/abs/2601.18558v1) | [PDF](https://arxiv.org/pdf/2601.18558v1)
- _(See full topic page: [Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)](topics/av-planning-control.md))_


### BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)

- **Vision-Language-Model-Guided Differentiable Ray Tracing for Fast and Accurate Multi-Material RF Parameter Estimation**
  - Authors: Zerui Kang, Yishen Lim, Zhouyou Gu, Seung-Woo Ko, Tony Q. S. Quek, Jihong Park
  - Published: 2026-01-26 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.18242v1) | [PDF](https://arxiv.org/pdf/2601.18242v1)
- **V-Loop: Visual Logical Loop Verification for Hallucination Detection in Medical Visual Question Answering**
  - Authors: Mengyuan Jin, Zehui Liao, Yong Xia
  - Published: 2026-01-26 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.18240v1) | [PDF](https://arxiv.org/pdf/2601.18240v1)
- **HomoFM: Deep Homography Estimation with Flow Matching**
  - Authors: Mengfan He, Liangzheng Sun, Chunyu Li, Ziyang Meng
  - Published: 2026-01-26 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.18222v1) | [PDF](https://arxiv.org/pdf/2601.18222v1)
- _(See full topic page: [BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)](topics/av-bev-occupancy.md))_


### Mapping, Localization & HD Maps (AV SLAM / Map Learning)

_No matches today._


### V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)

- **An ISAC-ready Full-Duplex Backscatter Architecture for the mmWave IoT**
  - Authors: Skanda Harisha, Jimmy G. D. Hester, Aline Eid
  - Published: 2026-01-26 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.18727v1) | [PDF](https://arxiv.org/pdf/2601.18727v1)
- **COMETS: Coordinated Multi-Destination Video Transmission with In-Network Rate Adaptation**
  - Authors: Yulong Zhang, Ying Cui, Zili Meng, Abhishek Kumar, Dirk Kutscher
  - Published: 2026-01-26 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.18670v1) | [PDF](https://arxiv.org/pdf/2601.18670v1)
- **An LLM-Agent-Based Framework for Age of Information Optimization in Heterogeneous Random Access Networks**
  - Authors: Fang Liu, Erchao Zhu, Jiedan Tan, Jingwen Tong, Taotao Wang, Shengli Zhang
  - Published: 2026-01-26 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.18563v1) | [PDF](https://arxiv.org/pdf/2601.18563v1)
- _(See full topic page: [V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)](topics/av-v2x-cooperative.md))_


### Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal)

_No matches today._


### Datasets, Benchmarks & Simulation (Driving)

_No matches today._
<!-- END TODAY -->
