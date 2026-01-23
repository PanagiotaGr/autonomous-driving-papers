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
- Updated on: **2026-01-23**
- Latest digest: `digests/2026-01-23.md`
<!-- LATEST:END -->

---

## Topic Navigator

<!-- TOPICS:START -->
| Topic | Latest Update | Papers | Link |
|------|--------------:|------:|------|
| Autonomous Driving – Perception (2D/3D Detection, Segmentation) | 2026-01-23 | 60 | [Autonomous Driving – Perception (2D/3D Detection, Segmentation)](topics/av-perception.md) |
| Autonomous Driving – Prediction (Trajectories, Intention, Interaction) | 2026-01-23 | 49 | [Autonomous Driving – Prediction (Trajectories, Intention, Interaction)](topics/av-prediction.md) |
| Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy) | 2026-01-23 | 7 | [Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)](topics/av-planning-control.md) |
| BEV & Occupancy (BEVPerception, Occupancy Networks, 4D) | 2026-01-23 | 0 | [BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)](topics/av-bev-occupancy.md) |
| Mapping, Localization & HD Maps (AV SLAM / Map Learning) | 2026-01-23 | 0 | [Mapping, Localization & HD Maps (AV SLAM / Map Learning)](topics/av-mapping-localization.md) |
| V2X / Cooperative Perception (V2V, V2I, Sensor Sharing) | 2026-01-23 | 3 | [V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)](topics/av-v2x-cooperative.md) |
| Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal) | 2026-01-23 | 0 | [Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal)](topics/av-safety-robustness.md) |
| Datasets, Benchmarks & Simulation (Driving) | 2026-01-23 | 0 | [Datasets, Benchmarks & Simulation (Driving)](topics/av-datasets-sim.md) |
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

**Last update:** 2026-01-23  
**Daily archive:** `digests/2026-01-23.md`  

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

- **CamPilot: Improving Camera Control in Video Diffusion Model with Efficient Camera Reward Feedback**
  - Authors: Wenhang Ge, Guibao Shen, Jiawei Feng, Luozhou Wang, Hao Lu, Xingye Tian, Xin Tao, Ying-Cong Chen
  - Published: 2026-01-22 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.16214v1) | [PDF](https://arxiv.org/pdf/2601.16214v1)
- **Point Bridge: 3D Representations for Cross Domain Policy Learning**
  - Authors: Siddhant Haldar, Lars Johannsmeier, Lerrel Pinto, Abhishek Gupta, Dieter Fox, Yashraj Narang, Ajay Mandlekar
  - Published: 2026-01-22 | Category: `cs.RO`
  - Links: [arXiv](https://arxiv.org/abs/2601.16212v1) | [PDF](https://arxiv.org/pdf/2601.16212v1)
- **Why Can't I Open My Drawer? Mitigating Object-Driven Shortcuts in Zero-Shot Compositional Action Recognition**
  - Authors: Geo Ahn, Inwoong Lee, Taeoh Kim, Minho Shim, Dongyoon Wee, Jinwoo Choi
  - Published: 2026-01-22 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.16211v1) | [PDF](https://arxiv.org/pdf/2601.16211v1)
- _(See full topic page: [Autonomous Driving – Perception (2D/3D Detection, Segmentation)](topics/av-perception.md))_


### Autonomous Driving – Prediction (Trajectories, Intention, Interaction)

- **Counterfactual Training: Teaching Models Plausible and Actionable Explanations**
  - Authors: Patrick Altmeyer, Aleksander Buszydlik, Arie van Deursen, Cynthia C. S. Liem
  - Published: 2026-01-22 | Category: `cs.LG`
  - Links: [arXiv](https://arxiv.org/abs/2601.16205v1) | [PDF](https://arxiv.org/pdf/2601.16205v1)
- **A Rolling-Space Branch-and-Price Algorithm for the Multi-Compartment Vehicle Routing Problem with Multiple Time Windows**
  - Authors: El Mehdi Er Raqabi, Kevin Dalmeijer, Pascal Van Hentenryck
  - Published: 2026-01-22 | Category: `math.OC`
  - Links: [arXiv](https://arxiv.org/abs/2601.16194v1) | [PDF](https://arxiv.org/pdf/2601.16194v1)
- **Learning to Discover at Test Time**
  - Authors: Mert Yuksekgonul, Daniel Koceja, Xinhao Li, Federico Bianchi, Jed McCaleb, Xiaolong Wang, Jan Kautz, Yejin Choi et al.
  - Published: 2026-01-22 | Category: `cs.LG`
  - Links: [arXiv](https://arxiv.org/abs/2601.16175v1) | [PDF](https://arxiv.org/pdf/2601.16175v1)
- _(See full topic page: [Autonomous Driving – Prediction (Trajectories, Intention, Interaction)](topics/av-prediction.md))_


### Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)

- **Stochastic Control Barrier Functions under State Estimation: From Euclidean Space to Lie Groups**
  - Authors: Ruoyu Lin, Magnus Egerstedt
  - Published: 2026-01-22 | Category: `eess.SY`
  - Links: [arXiv](https://arxiv.org/abs/2601.16198v1) | [PDF](https://arxiv.org/pdf/2601.16198v1)
- **Average Unfairness in Routing Games**
  - Authors: Pan-Yang Su, Arwa Alanqary, Bryce L. Ferguson, Manxi Wu, Alexandre M. Bayen, Shankar Sastry
  - Published: 2026-01-22 | Category: `cs.MA`
  - Links: [arXiv](https://arxiv.org/abs/2601.16187v1) | [PDF](https://arxiv.org/pdf/2601.16187v1)
- **Interconnection-based Model Reduction for Linear Hybrid Systems**
  - Authors: Zirui Niu, Giordano Scarciotti, Alessandro Astolfi
  - Published: 2026-01-22 | Category: `eess.SY`
  - Links: [arXiv](https://arxiv.org/abs/2601.16149v1) | [PDF](https://arxiv.org/pdf/2601.16149v1)
- _(See full topic page: [Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)](topics/av-planning-control.md))_


### BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)

_No matches today._


### Mapping, Localization & HD Maps (AV SLAM / Map Learning)

_No matches today._


### V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)

- **Low-altitude Multi-UAV-assisted Data Collection and Semantic Forwarding for Post-Disaster Relief**
  - Authors: Xiaoya Zheng, Geng Sun, Jiahui Li, Jiacheng Wang, Weijie Yuan, Qingqing Wu, Dusit Niyato, Abbas Jamalipour
  - Published: 2026-01-22 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.16146v1) | [PDF](https://arxiv.org/pdf/2601.16146v1)
- **Dynamic Server Allocation Under Stochastic Switchover on Time-Varying Links**
  - Authors: Hossein Mohammadalizadeh, Holger Karl
  - Published: 2026-01-22 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.15904v1) | [PDF](https://arxiv.org/pdf/2601.15904v1)
- **RF Intelligence for Health: Classification of SmartBAN Signals in overcrowded ISM band**
  - Authors: Nicola Gallucci, Giacomo Aragnetti, Matteo Malagrinò, Francesco Linsalata, Maurizio Magarini, Lorenzo Mucchi
  - Published: 2026-01-22 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.15836v1) | [PDF](https://arxiv.org/pdf/2601.15836v1)
- _(See full topic page: [V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)](topics/av-v2x-cooperative.md))_


### Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal)

_No matches today._


### Datasets, Benchmarks & Simulation (Driving)

_No matches today._
<!-- END TODAY -->
