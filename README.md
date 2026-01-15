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
- **Last updated:** YYYY-MM-DD  
- **Latest digest:** `digests/YYYY-MM-DD.md`
<!-- LATEST:END -->

---

## Topic Navigator

<!-- TOPICS:START -->
| Topic | Latest Update | Papers | Link |
|------|--------------:|------:|------|
| Perception | YYYY-MM-DD | 0 | [Perception](topics/av-perception.md) |
| Prediction | YYYY-MM-DD | 0 | [Prediction](topics/av-prediction.md) |
| Planning & Control | YYYY-MM-DD | 0 | [Planning & Control](topics/av-planning-control.md) |
| BEV & Occupancy | YYYY-MM-DD | 0 | [BEV & Occupancy](topics/av-bev-occupancy.md) |
| Mapping & Localization | YYYY-MM-DD | 0 | [Mapping & Localization](topics/av-mapping-localization.md) |
| V2X & Cooperative Perception | YYYY-MM-DD | 0 | [V2X & Cooperative](topics/av-v2x-cooperative.md) |
| Safety & Robustness | YYYY-MM-DD | 0 | [Safety & Robustness](topics/av-safety-robustness.md) |
| Datasets & Simulation | YYYY-MM-DD | 0 | [Datasets & Simulation](topics/av-datasets-sim.md) |
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

**Last update:** 2026-01-15  
**Daily archive:** `digests/2026-01-15.md`  

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

- **Fast-ThinkAct: Efficient Vision-Language-Action Reasoning via Verbalizable Latent Planning**
  - Authors: Chi-Pin Huang, Yunze Man, Zhiding Yu, Min-Hung Chen, Jan Kautz, Yu-Chiang Frank Wang, Fu-En Yang
  - Published: 2026-01-14 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.09708v1) | [PDF](https://arxiv.org/pdf/2601.09708v1)
- **SAM3-DMS: Decoupled Memory Selection for Multi-target Video Segmentation of SAM3**
  - Authors: Ruiqi Shen, Chang Liu, Henghui Ding
  - Published: 2026-01-14 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.09699v1) | [PDF](https://arxiv.org/pdf/2601.09699v1)
- **COMPOSE: Hypergraph Cover Optimization for Multi-view 3D Human Pose Estimation**
  - Authors: Tony Danjun Wang, Tolga Birdal, Nassir Navab, Lennart Bastian
  - Published: 2026-01-14 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.09698v1) | [PDF](https://arxiv.org/pdf/2601.09698v1)
- _(See full topic page: [Autonomous Driving – Perception (2D/3D Detection, Segmentation)](topics/av-perception.md))_


### Autonomous Driving – Prediction (Trajectories, Intention, Interaction)

- **Value-Aware Numerical Representations for Transformer Language Models**
  - Authors: Andreea Dutulescu, Stefan Ruseti, Mihai Dascalu
  - Published: 2026-01-14 | Category: `cs.CL`
  - Links: [arXiv](https://arxiv.org/abs/2601.09706v1) | [PDF](https://arxiv.org/pdf/2601.09706v1)
- **Contrastive Geometric Learning Unlocks Unified Structure- and Ligand-Based Drug Design**
  - Authors: Lisa Schneckenreiter, Sohvi Luukkonen, Lukas Friedrich, Daniel Kuhn, Günter Klambauer
  - Published: 2026-01-14 | Category: `cs.LG`
  - Links: [arXiv](https://arxiv.org/abs/2601.09693v1) | [PDF](https://arxiv.org/pdf/2601.09693v1)
- **Routing with Generated Data: Annotation-Free LLM Skill Estimation and Expert Selection**
  - Authors: Tianyi Niu, Justin Chih-Yao Chen, Genta Indra Winata, Shi-Xiong Zhang, Supriyo Chakraborty, Sambit Sahu, Yue Zhang, Elias Stengel-Eskin et al.
  - Published: 2026-01-14 | Category: `cs.CL`
  - Links: [arXiv](https://arxiv.org/abs/2601.09692v1) | [PDF](https://arxiv.org/pdf/2601.09692v1)
- _(See full topic page: [Autonomous Driving – Prediction (Trajectories, Intention, Interaction)](topics/av-prediction.md))_


### Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)

- **A Novel $αβ$-Approximation Method Based on Numerical Integration for Discretizing Continuous Systems**
  - Authors: Shen Chen, Chaohou Liu, Wei Yao, Jisong Wang, Shuaipo Guo, Zeng Liu, Jinjun Liu
  - Published: 2026-01-14 | Category: `eess.SY`
  - Links: [arXiv](https://arxiv.org/abs/2601.09549v1) | [PDF](https://arxiv.org/pdf/2601.09549v1)
- **Echo-Side Integrated Sensing and Communication via Space-Time Reconfigurable Intelligent Surfaces**
  - Authors: Marouan Mizmizi, Stefano Tebaldini, Umberto Spagnolini
  - Published: 2026-01-14 | Category: `eess.SP`
  - Links: [arXiv](https://arxiv.org/abs/2601.09484v1) | [PDF](https://arxiv.org/pdf/2601.09484v1)
- **Two-Scale Spatial Deployment for Cost-Effective Wireless Networks via Cooperative IRSs and Movable Antennas**
  - Authors: Ying Gao, Qingqing Wu, Ziyuan Zheng, Yanze Zhu, Wen Chen, Xin Lin, Shanpu Shen
  - Published: 2026-01-14 | Category: `eess.SP`
  - Links: [arXiv](https://arxiv.org/abs/2601.09463v1) | [PDF](https://arxiv.org/pdf/2601.09463v1)
- _(See full topic page: [Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)](topics/av-planning-control.md))_


### BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)

_No matches today._


### Mapping, Localization & HD Maps (AV SLAM / Map Learning)

_No matches today._


### V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)

- **FairShare: Auditable Geographic Fairness for Multi-Operator LEO Spectrum Sharing**
  - Authors: Seyed Bagher Hashemi Natanzi, Hossein Mohammadi, Vuk Marojevic, Bo Tang
  - Published: 2026-01-14 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.09641v1) | [PDF](https://arxiv.org/pdf/2601.09641v1)
- **UAV-enabled Computing Power Networks: Design and Performance Analysis under Energy Constraints**
  - Authors: Yiqin Deng, Zhengru Fang, Senkang Hu, Yanan Ma, Xiaoyu Guo, Haixia Zhang, Yuguang Fang
  - Published: 2026-01-14 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.09493v1) | [PDF](https://arxiv.org/pdf/2601.09493v1)
- _(See full topic page: [V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)](topics/av-v2x-cooperative.md))_


### Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal)

_No matches today._


### Datasets, Benchmarks & Simulation (Driving)

_No matches today._
<!-- END TODAY -->
