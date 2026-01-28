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
- Updated on: **2026-01-28**
- Latest digest: `digests/2026-01-28.md`
<!-- LATEST:END -->

---

## Topic Navigator

<!-- TOPICS:START -->
| Topic | Latest Update | Papers | Link |
|------|--------------:|------:|------|
| Autonomous Driving – Perception (2D/3D Detection, Segmentation) | 2026-01-28 | 60 | [Autonomous Driving – Perception (2D/3D Detection, Segmentation)](topics/av-perception.md) |
| Autonomous Driving – Prediction (Trajectories, Intention, Interaction) | 2026-01-28 | 60 | [Autonomous Driving – Prediction (Trajectories, Intention, Interaction)](topics/av-prediction.md) |
| Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy) | 2026-01-28 | 26 | [Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)](topics/av-planning-control.md) |
| BEV & Occupancy (BEVPerception, Occupancy Networks, 4D) | 2026-01-28 | 7 | [BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)](topics/av-bev-occupancy.md) |
| Mapping, Localization & HD Maps (AV SLAM / Map Learning) | 2026-01-28 | 0 | [Mapping, Localization & HD Maps (AV SLAM / Map Learning)](topics/av-mapping-localization.md) |
| V2X / Cooperative Perception (V2V, V2I, Sensor Sharing) | 2026-01-28 | 2 | [V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)](topics/av-v2x-cooperative.md) |
| Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal) | 2026-01-28 | 0 | [Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal)](topics/av-safety-robustness.md) |
| Datasets, Benchmarks & Simulation (Driving) | 2026-01-28 | 0 | [Datasets, Benchmarks & Simulation (Driving)](topics/av-datasets-sim.md) |
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

**Last update:** 2026-01-28  
**Daily archive:** `digests/2026-01-28.md`  

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

- **DuwatBench: Bridging Language and Visual Heritage through an Arabic Calligraphy Benchmark for Multimodal Understanding**
  - Authors: Shubham Patle, Sara Ghaboura, Hania Tariq, Mohammad Usman Khan, Omkar Thawakar, Rao Muhammad Anwer, Salman Khan
  - Published: 2026-01-27 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.19898v1) | [PDF](https://arxiv.org/pdf/2601.19898v1)
- **VGGT-SLAM 2.0: Real time Dense Feed-forward Scene Reconstruction**
  - Authors: Dominic Maggio, Luca Carlone
  - Published: 2026-01-27 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.19887v1) | [PDF](https://arxiv.org/pdf/2601.19887v1)
- **SONIC: Spectral Oriented Neural Invariant Convolutions**
  - Authors: Gijs Joppe Moens, Regina Beets-Tan, Eduardo H. P. Pooch
  - Published: 2026-01-27 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.19884v1) | [PDF](https://arxiv.org/pdf/2601.19884v1)
- _(See full topic page: [Autonomous Driving – Perception (2D/3D Detection, Segmentation)](topics/av-perception.md))_


### Autonomous Driving – Prediction (Trajectories, Intention, Interaction)

- **Self-Distillation Enables Continual Learning**
  - Authors: Idan Shenfeld, Mehul Damani, Jonas Hübotter, Pulkit Agrawal
  - Published: 2026-01-27 | Category: `cs.LG`
  - Links: [arXiv](https://arxiv.org/abs/2601.19897v1) | [PDF](https://arxiv.org/pdf/2601.19897v1)
- **Post-LayerNorm Is Back: Stable, ExpressivE, and Deep**
  - Authors: Chen Chen, Lai Wei
  - Published: 2026-01-27 | Category: `cs.LG`
  - Links: [arXiv](https://arxiv.org/abs/2601.19895v1) | [PDF](https://arxiv.org/pdf/2601.19895v1)
- **M-SGWR: Multiscale Similarity and Geographically Weighted Regression**
  - Authors: M. Naser Lessani, Zhenlong Li, Manzhu Yu, Helen Greatrex, Chan Shen
  - Published: 2026-01-27 | Category: `stat.ME`
  - Links: [arXiv](https://arxiv.org/abs/2601.19888v1) | [PDF](https://arxiv.org/pdf/2601.19888v1)
- _(See full topic page: [Autonomous Driving – Prediction (Trajectories, Intention, Interaction)](topics/av-prediction.md))_


### Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)

- **A Latent Space Framework for Modeling Transient Engine Emissions Using Joint Embedding Predictive Architectures**
  - Authors: Ganesh Sundaram, Tobias Gehra, Jonas Ulmen, Mirjan Heubaum, Daniel Görges, Michael Günthner
  - Published: 2026-01-27 | Category: `eess.SY`
  - Links: [arXiv](https://arxiv.org/abs/2601.19822v1) | [PDF](https://arxiv.org/pdf/2601.19822v1)
- **A refined nonlinear least-squares method for the rational approximation problem**
  - Authors: Michael S. Ackermann, Linus Balicki, Serkan Gugercin, Steffen W. R. Werner
  - Published: 2026-01-27 | Category: `math.NA`
  - Links: [arXiv](https://arxiv.org/abs/2601.19813v1) | [PDF](https://arxiv.org/pdf/2601.19813v1)
- **Frequency Shaping Control for Oscillation Damping in Weakly-Connected Power Network: A Root Locus Method**
  - Authors: Yan Jiang, Wei Chen, Zhaomin Lyu, Xunning Zhang, Dan Wang, Shinji Hara
  - Published: 2026-01-27 | Category: `eess.SY`
  - Links: [arXiv](https://arxiv.org/abs/2601.19665v1) | [PDF](https://arxiv.org/pdf/2601.19665v1)
- _(See full topic page: [Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)](topics/av-planning-control.md))_


### BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)

- **Pareto-Guided Optimization for Uncertainty-Aware Medical Image Segmentation**
  - Authors: Jinming Zhang, Xi Yang, Youpeng Yang, Haosen Shi, Yuyao Yan, Qiufeng Wang, Guangliang Cheng, Kaizhu Huang
  - Published: 2026-01-27 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.19365v1) | [PDF](https://arxiv.org/pdf/2601.19365v1)
- **AMGFormer: Adaptive Multi-Granular Transformer for Brain Tumor Segmentation with Missing Modalities**
  - Authors: Chengxiang Guo, Jian Wang, Junhua Fei, Xiao Li, Chunling Chen, Yun Jin
  - Published: 2026-01-27 | Category: `eess.IV`
  - Links: [arXiv](https://arxiv.org/abs/2601.19349v1) | [PDF](https://arxiv.org/pdf/2601.19349v1)
- **Innovator-VL: A Multimodal Large Language Model for Scientific Discovery**
  - Authors: Zichen Wen, Boxue Yang, Shuang Chen, Yaojie Zhang, Yuhang Han, Junlong Ke, Cong Wang, Yicheng Fu et al.
  - Published: 2026-01-27 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.19325v1) | [PDF](https://arxiv.org/pdf/2601.19325v1)
- _(See full topic page: [BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)](topics/av-bev-occupancy.md))_


### Mapping, Localization & HD Maps (AV SLAM / Map Learning)

_No matches today._


### V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)

- **Quantum Takes Flight: Two-Stage Resilient Topology Optimization for UAV Networks**
  - Authors: Huixiang Zhang, Mahzabeen Emu, Octavia A. Dobre
  - Published: 2026-01-27 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.19724v1) | [PDF](https://arxiv.org/pdf/2601.19724v1)
- **NET4EXA: Pioneering the Future of Interconnects for Supercomputing and AI**
  - Authors: Michele Martinelli, Roberto Ammendola, Andrea Biagioni, Carlotta Chiarini, Ottorino Frezza, Francesca Lo Cicero, Alessandro Lonardo, Pier Stanislao Paolucci et al.
  - Published: 2026-01-27 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.19413v1) | [PDF](https://arxiv.org/pdf/2601.19413v1)
- _(See full topic page: [V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)](topics/av-v2x-cooperative.md))_


### Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal)

_No matches today._


### Datasets, Benchmarks & Simulation (Driving)

_No matches today._
<!-- END TODAY -->
