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
- Updated on: **2026-01-21**
- Latest digest: `digests/2026-01-21.md`
<!-- LATEST:END -->

---

## Topic Navigator

<!-- TOPICS:START -->
| Topic | Latest Update | Papers | Link |
|------|--------------:|------:|------|
| Autonomous Driving – Perception (2D/3D Detection, Segmentation) | 2026-01-21 | 60 | [Autonomous Driving – Perception (2D/3D Detection, Segmentation)](topics/av-perception.md) |
| Autonomous Driving – Prediction (Trajectories, Intention, Interaction) | 2026-01-21 | 60 | [Autonomous Driving – Prediction (Trajectories, Intention, Interaction)](topics/av-prediction.md) |
| Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy) | 2026-01-21 | 23 | [Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)](topics/av-planning-control.md) |
| BEV & Occupancy (BEVPerception, Occupancy Networks, 4D) | 2026-01-21 | 8 | [BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)](topics/av-bev-occupancy.md) |
| Mapping, Localization & HD Maps (AV SLAM / Map Learning) | 2026-01-21 | 0 | [Mapping, Localization & HD Maps (AV SLAM / Map Learning)](topics/av-mapping-localization.md) |
| V2X / Cooperative Perception (V2V, V2I, Sensor Sharing) | 2026-01-21 | 9 | [V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)](topics/av-v2x-cooperative.md) |
| Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal) | 2026-01-21 | 0 | [Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal)](topics/av-safety-robustness.md) |
| Datasets, Benchmarks & Simulation (Driving) | 2026-01-21 | 0 | [Datasets, Benchmarks & Simulation (Driving)](topics/av-datasets-sim.md) |
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

**Last update:** 2026-01-21  
**Daily archive:** `digests/2026-01-21.md`  

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

- **Implicit Neural Representation Facilitates Unified Universal Vision Encoding**
  - Authors: Matthew Gwilliam, Xiao Wang, Xuefeng Hu, Zhenheng Yang
  - Published: 2026-01-20 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.14256v1) | [PDF](https://arxiv.org/pdf/2601.14256v1)
- **VideoMaMa: Mask-Guided Video Matting via Generative Prior**
  - Authors: Sangbeom Lim, Seoung Wug Oh, Jiahui Huang, Heeji Yoon, Seungryong Kim, Joon-Young Lee
  - Published: 2026-01-20 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.14255v1) | [PDF](https://arxiv.org/pdf/2601.14255v1)
- **Motion 3-to-4: 3D Motion Reconstruction for 4D Synthesis**
  - Authors: Hongyuan Chen, Xingyu Chen, Youjia Zhang, Zexiang Xu, Anpei Chen
  - Published: 2026-01-20 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.14253v1) | [PDF](https://arxiv.org/pdf/2601.14253v1)
- _(See full topic page: [Autonomous Driving – Perception (2D/3D Detection, Segmentation)](topics/av-perception.md))_


### Autonomous Driving – Prediction (Trajectories, Intention, Interaction)

- **Jet-RL: Enabling On-Policy FP8 Reinforcement Learning with Unified Training and Rollout Precision Flow**
  - Authors: Haocheng Xi, Charlie Ruan, Peiyuan Liao, Yujun Lin, Han Cai, Yilong Zhao, Shuo Yang, Kurt Keutzer et al.
  - Published: 2026-01-20 | Category: `cs.LG`
  - Links: [arXiv](https://arxiv.org/abs/2601.14243v1) | [PDF](https://arxiv.org/pdf/2601.14243v1)
- **APEX-Agents**
  - Authors: Bertie Vidgen, Austin Mann, Abby Fennelly, John Wright Stanly, Lucas Rothman, Marco Burstein, Julien Benchek, David Ostrofsky et al.
  - Published: 2026-01-20 | Category: `cs.CL`
  - Links: [arXiv](https://arxiv.org/abs/2601.14242v1) | [PDF](https://arxiv.org/pdf/2601.14242v1)
- **Spatiotemporal Wildfire Prediction and Reinforcement Learning for Helitack Suppression**
  - Authors: Shaurya Mathur, Shreyas Bellary Manjunath, Nitin Kulkarni, Alina Vereshchaka
  - Published: 2026-01-20 | Category: `cs.LG`
  - Links: [arXiv](https://arxiv.org/abs/2601.14238v1) | [PDF](https://arxiv.org/pdf/2601.14238v1)
- _(See full topic page: [Autonomous Driving – Prediction (Trajectories, Intention, Interaction)](topics/av-prediction.md))_


### Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)

- **The Impact of Interference Cognition on the Reliability and Capacity of Industrial Wireless Communications**
  - Authors: Yichen Guo, Tao Peng, Yujie Zhao, Yijing Niu, Wenbo Wang
  - Published: 2026-01-20 | Category: `eess.SY`
  - Links: [arXiv](https://arxiv.org/abs/2601.14164v1) | [PDF](https://arxiv.org/pdf/2601.14164v1)
- **A flexible language model-assisted electronic design automation framework**
  - Authors: Cristian Sestito, Panagiota Kontou, Pratibha Verma, Atish Dixit, Alexandros D. Keros, Michael O'Boyle, Christos-Savvas Bouganis, Themis Prodromakis
  - Published: 2026-01-20 | Category: `eess.SY`
  - Links: [arXiv](https://arxiv.org/abs/2601.14098v1) | [PDF](https://arxiv.org/pdf/2601.14098v1)
- **Data-Driven Safe Output Regulation of Strict-Feedback Linear Systems with Input Delay**
  - Authors: Zhenxu Zhao, Ji Wang, Weiyao Lan
  - Published: 2026-01-20 | Category: `eess.SY`
  - Links: [arXiv](https://arxiv.org/abs/2601.14089v1) | [PDF](https://arxiv.org/pdf/2601.14089v1)
- _(See full topic page: [Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)](topics/av-planning-control.md))_


### BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)

- **Facial Spatiotemporal Graphs: Leveraging the 3D Facial Surface for Remote Physiological Measurement**
  - Authors: Sam Cantrill, David Ahmedt-Aristizabal, Lars Petersson, Hanna Suominen, Mohammad Ali Armin
  - Published: 2026-01-20 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.13724v1) | [PDF](https://arxiv.org/pdf/2601.13724v1)
- **Hierarchical Long Video Understanding with Audiovisual Entity Cohesion and Agentic Search**
  - Authors: Xinlei Yin, Xiulian Peng, Xiao Li, Zhiwei Xiong, Yan Lu
  - Published: 2026-01-20 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.13719v1) | [PDF](https://arxiv.org/pdf/2601.13719v1)
- **MVGD-Net: A Novel Motion-aware Video Glass Surface Detection Network**
  - Authors: Yiwei Lu, Hao Huang, Tao Yan
  - Published: 2026-01-20 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.13715v1) | [PDF](https://arxiv.org/pdf/2601.13715v1)
- _(See full topic page: [BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)](topics/av-bev-occupancy.md))_


### Mapping, Localization & HD Maps (AV SLAM / Map Learning)

_No matches today._


### V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)

- **Storage-Rate Trade-off in A-XPIR**
  - Authors: Mohamed Nomeir, Sennur Ulukus
  - Published: 2026-01-20 | Category: `cs.IT`
  - Links: [arXiv](https://arxiv.org/abs/2601.14202v1) | [PDF](https://arxiv.org/pdf/2601.14202v1)
- **Communication Technologies for Intelligent Transportation Systems: From Railways to UAVs and Beyond**
  - Authors: Shrief Rizkalla, Adrian Kliks, Nila Bagheri, Miguel A. Bellido-Manganell, Aniruddha Chandra, Anja Dakic, Laura Finarelli, Davy Gaillot et al.
  - Published: 2026-01-20 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.14106v1) | [PDF](https://arxiv.org/pdf/2601.14106v1)
- **MANATEE: A DevOps Platform for xApp Lifecycle Management and Testing in Open RAN**
  - Authors: Sofia Montebugnoli, Leonardo Bonati, Andrea Sabbioni, Luca Foschini, Paolo Bellavista, Salvatore D'Oro, Michele Polese, Tommaso Melodia
  - Published: 2026-01-20 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.14009v1) | [PDF](https://arxiv.org/pdf/2601.14009v1)
- _(See full topic page: [V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)](topics/av-v2x-cooperative.md))_


### Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal)

_No matches today._


### Datasets, Benchmarks & Simulation (Driving)

_No matches today._
<!-- END TODAY -->
