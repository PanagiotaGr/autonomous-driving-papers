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
- Updated on: **2026-01-16**
- Latest digest: `digests/2026-01-16.md`
<!-- LATEST:END -->

---

## Topic Navigator

<!-- TOPICS:START -->
| Topic | Latest Update | Papers | Link |
|------|--------------:|------:|------|
| Autonomous Driving – Perception (2D/3D Detection, Segmentation) | 2026-01-16 | 58 | [Autonomous Driving – Perception (2D/3D Detection, Segmentation)](topics/av-perception.md) |
| Autonomous Driving – Prediction (Trajectories, Intention, Interaction) | 2026-01-16 | 60 | [Autonomous Driving – Prediction (Trajectories, Intention, Interaction)](topics/av-prediction.md) |
| Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy) | 2026-01-16 | 7 | [Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)](topics/av-planning-control.md) |
| BEV & Occupancy (BEVPerception, Occupancy Networks, 4D) | 2026-01-16 | 0 | [BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)](topics/av-bev-occupancy.md) |
| Mapping, Localization & HD Maps (AV SLAM / Map Learning) | 2026-01-16 | 0 | [Mapping, Localization & HD Maps (AV SLAM / Map Learning)](topics/av-mapping-localization.md) |
| V2X / Cooperative Perception (V2V, V2I, Sensor Sharing) | 2026-01-16 | 4 | [V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)](topics/av-v2x-cooperative.md) |
| Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal) | 2026-01-16 | 0 | [Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal)](topics/av-safety-robustness.md) |
| Datasets, Benchmarks & Simulation (Driving) | 2026-01-16 | 0 | [Datasets, Benchmarks & Simulation (Driving)](topics/av-datasets-sim.md) |
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

**Last update:** 2026-01-16  
**Daily archive:** `digests/2026-01-16.md`  

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

- **WildRayZer: Self-supervised Large View Synthesis in Dynamic Environments**
  - Authors: Xuweiyi Chen, Wentao Zhou, Zezhou Cheng
  - Published: 2026-01-15 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.10716v1) | [PDF](https://arxiv.org/pdf/2601.10716v1)
- **Alterbute: Editing Intrinsic Attributes of Objects in Images**
  - Authors: Tal Reiss, Daniel Winter, Matan Cohen, Alex Rav-Acha, Yael Pritch, Ariel Shamir, Yedid Hoshen
  - Published: 2026-01-15 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.10714v1) | [PDF](https://arxiv.org/pdf/2601.10714v1)
- **From One-to-One to Many-to-Many: Dynamic Cross-Layer Injection for Deep Vision-Language Fusion**
  - Authors: Cheng Chen, Yuyu Guo, Pengpeng Zeng, Jingkuan Song, Peng Di, Hang Yu, Lianli Gao
  - Published: 2026-01-15 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.10710v1) | [PDF](https://arxiv.org/pdf/2601.10710v1)
- _(See full topic page: [Autonomous Driving – Perception (2D/3D Detection, Segmentation)](topics/av-perception.md))_


### Autonomous Driving – Prediction (Trajectories, Intention, Interaction)

- **DInf-Grid: A Neural Differential Equation Solver with Differentiable Feature Grids**
  - Authors: Navami Kairanda, Shanthika Naik, Marc Habermann, Avinash Sharma, Christian Theobalt, Vladislav Golyanik
  - Published: 2026-01-15 | Category: `cs.LG`
  - Links: [arXiv](https://arxiv.org/abs/2601.10715v1) | [PDF](https://arxiv.org/pdf/2601.10715v1)
- **High-accuracy and dimension-free sampling with diffusions**
  - Authors: Khashayar Gatmiry, Sitan Chen, Adil Salim
  - Published: 2026-01-15 | Category: `cs.LG`
  - Links: [arXiv](https://arxiv.org/abs/2601.10708v1) | [PDF](https://arxiv.org/pdf/2601.10708v1)
- **Distributed Perceptron under Bounded Staleness, Partial Participation, and Noisy Communication**
  - Authors: Keval Jain, Anant Raj, Saurav Prakash, Girish Varma
  - Published: 2026-01-15 | Category: `cs.LG`
  - Links: [arXiv](https://arxiv.org/abs/2601.10705v1) | [PDF](https://arxiv.org/pdf/2601.10705v1)
- _(See full topic page: [Autonomous Driving – Prediction (Trajectories, Intention, Interaction)](topics/av-prediction.md))_


### Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)

- **Safe Trajectory Gradient Flow Control of a Grid-Interfacing Inverter**
  - Authors: Trager Joswig-Jones, Baosen Zhang
  - Published: 2026-01-15 | Category: `eess.SY`
  - Links: [arXiv](https://arxiv.org/abs/2601.10671v1) | [PDF](https://arxiv.org/pdf/2601.10671v1)
- **A user subscription model in mobile radio access networks with network slicing**
  - Authors: José-Ramón Vidal, Luis Guijarro, Vicent Pla
  - Published: 2026-01-15 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.10605v1) | [PDF](https://arxiv.org/pdf/2601.10605v1)
- **Single-Feed Circularly Polarized Super Realized Gain Antenna**
  - Authors: Georgia Psychogiou, Donal P. Lynch, Spyridon N. Daskalakis, Manos M. Tentzeris, George Goussetis, Stylianos D. Asimonis
  - Published: 2026-01-15 | Category: `eess.SY`
  - Links: [arXiv](https://arxiv.org/abs/2601.10292v1) | [PDF](https://arxiv.org/pdf/2601.10292v1)
- _(See full topic page: [Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)](topics/av-planning-control.md))_


### BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)

_No matches today._


### Mapping, Localization & HD Maps (AV SLAM / Map Learning)

_No matches today._


### V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)

- **Breaking the Storage-Bandwidth Tradeoff in Distributed Storage with Quantum Entanglement**
  - Authors: Lei Hu, Mohamed Nomeir, Alptug Aytekin, Sennur Ulukus
  - Published: 2026-01-15 | Category: `cs.IT`
  - Links: [arXiv](https://arxiv.org/abs/2601.10676v1) | [PDF](https://arxiv.org/pdf/2601.10676v1)
- **Enhancing Mobile Ad Hoc Networks (MANETs) with Software-Defined Networking (SDN): A Balanced Approach**
  - Authors: Riccardo Fonti, Andrea Piroddi
  - Published: 2026-01-15 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.10556v1) | [PDF](https://arxiv.org/pdf/2601.10556v1)
- **SDN-Driven Innovations in MANETs and IoT: A Path to Smarter Networks**
  - Authors: Andrea Piroddi, Riccardo Fonti
  - Published: 2026-01-15 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.10544v1) | [PDF](https://arxiv.org/pdf/2601.10544v1)
- _(See full topic page: [V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)](topics/av-v2x-cooperative.md))_


### Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal)

_No matches today._


### Datasets, Benchmarks & Simulation (Driving)

_No matches today._
<!-- END TODAY -->
