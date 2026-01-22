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
- Updated on: **2026-01-22**
- Latest digest: `digests/2026-01-22.md`
<!-- LATEST:END -->

---

## Topic Navigator

<!-- TOPICS:START -->
| Topic | Latest Update | Papers | Link |
|------|--------------:|------:|------|
| Autonomous Driving – Perception (2D/3D Detection, Segmentation) | 2026-01-22 | 60 | [Autonomous Driving – Perception (2D/3D Detection, Segmentation)](topics/av-perception.md) |
| Autonomous Driving – Prediction (Trajectories, Intention, Interaction) | 2026-01-22 | 60 | [Autonomous Driving – Prediction (Trajectories, Intention, Interaction)](topics/av-prediction.md) |
| Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy) | 2026-01-22 | 16 | [Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)](topics/av-planning-control.md) |
| BEV & Occupancy (BEVPerception, Occupancy Networks, 4D) | 2026-01-22 | 2 | [BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)](topics/av-bev-occupancy.md) |
| Mapping, Localization & HD Maps (AV SLAM / Map Learning) | 2026-01-22 | 0 | [Mapping, Localization & HD Maps (AV SLAM / Map Learning)](topics/av-mapping-localization.md) |
| V2X / Cooperative Perception (V2V, V2I, Sensor Sharing) | 2026-01-22 | 2 | [V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)](topics/av-v2x-cooperative.md) |
| Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal) | 2026-01-22 | 0 | [Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal)](topics/av-safety-robustness.md) |
| Datasets, Benchmarks & Simulation (Driving) | 2026-01-22 | 0 | [Datasets, Benchmarks & Simulation (Driving)](topics/av-datasets-sim.md) |
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

**Last update:** 2026-01-22  
**Daily archive:** `digests/2026-01-22.md`  

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

- **APPLE: Attribute-Preserving Pseudo-Labeling for Diffusion-Based Face Swapping**
  - Authors: Jiwon Kang, Yeji Choi, JoungBin Lee, Wooseok Jang, Jinhyeok Choi, Taekeun Kang, Yongjae Park, Myungin Kim et al.
  - Published: 2026-01-21 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.15288v1) | [PDF](https://arxiv.org/pdf/2601.15288v1)
- **Towards Understanding Best Practices for Quantization of Vision-Language Models**
  - Authors: Gautom Das, Vincent La, Ethan Lau, Abhinav Shrivastava, Matthew Gwilliam
  - Published: 2026-01-21 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.15287v1) | [PDF](https://arxiv.org/pdf/2601.15287v1)
- **Iterative Refinement Improves Compositional Image Generation**
  - Authors: Shantanu Jaiswal, Mihir Prabhudesai, Nikash Bhardwaj, Zheyang Qin, Amir Zadeh, Chuan Li, Katerina Fragkiadaki, Deepak Pathak
  - Published: 2026-01-21 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.15286v1) | [PDF](https://arxiv.org/pdf/2601.15286v1)
- _(See full topic page: [Autonomous Driving – Perception (2D/3D Detection, Segmentation)](topics/av-perception.md))_


### Autonomous Driving – Prediction (Trajectories, Intention, Interaction)

- **MolecularIQ: Characterizing Chemical Reasoning Capabilities Through Symbolic Verification on Molecular Graphs**
  - Authors: Christoph Bartmann, Johannes Schimunek, Mykyta Ielanskyi, Philipp Seidl, Günter Klambauer, Sohvi Luukkonen
  - Published: 2026-01-21 | Category: `cs.LG`
  - Links: [arXiv](https://arxiv.org/abs/2601.15279v1) | [PDF](https://arxiv.org/pdf/2601.15279v1)
- **Many Experiments, Few Repetitions, Unpaired Data, and Sparse Effects: Is Causal Inference Possible?**
  - Authors: Felix Schur, Niklas Pfister, Peng Ding, Sach Mukherjee, Jonas Peters
  - Published: 2026-01-21 | Category: `stat.ML`
  - Links: [arXiv](https://arxiv.org/abs/2601.15254v1) | [PDF](https://arxiv.org/pdf/2601.15254v1)
- **Recommending Best Paper Awards for ML/AI Conferences via the Isotonic Mechanism**
  - Authors: Garrett G. Wen, Buxin Su, Natalie Collina, Zhun Deng, Weijie Su
  - Published: 2026-01-21 | Category: `cs.LG`
  - Links: [arXiv](https://arxiv.org/abs/2601.15249v1) | [PDF](https://arxiv.org/pdf/2601.15249v1)
- _(See full topic page: [Autonomous Driving – Prediction (Trajectories, Intention, Interaction)](topics/av-prediction.md))_


### Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)

- **TTCBF: A Truncated Taylor Control Barrier Function for High-Order Safety Constraints**
  - Authors: Jianye Xu, Bassam Alrifaee
  - Published: 2026-01-21 | Category: `eess.SY`
  - Links: [arXiv](https://arxiv.org/abs/2601.15196v1) | [PDF](https://arxiv.org/pdf/2601.15196v1)
- **Stochastic EMS for Optimal 24/7 Carbon-Free Energy Operations**
  - Authors: Natanon Tongamrak, Kannapha Amaruchkul, Wijarn Wangdee, Jitkomut Songsiri
  - Published: 2026-01-21 | Category: `eess.SY`
  - Links: [arXiv](https://arxiv.org/abs/2601.15135v1) | [PDF](https://arxiv.org/pdf/2601.15135v1)
- **Instantaneous Frequency in Power Systems using the Teager-Kaiser Energy Operator**
  - Authors: A. Vaca, J. Gutierrez Florensa, F. Milano
  - Published: 2026-01-21 | Category: `eess.SY`
  - Links: [arXiv](https://arxiv.org/abs/2601.15099v1) | [PDF](https://arxiv.org/pdf/2601.15099v1)
- _(See full topic page: [Autonomous Driving – Planning & Control (Motion Planning, MPC, Policy)](topics/av-planning-control.md))_


### BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)

- **HERMES: KV Cache as Hierarchical Memory for Efficient Streaming Video Understanding**
  - Authors: Haowei Zhang, Shudong Yang, Jinlan Fu, See-Kiong Ng, Xipeng Qiu
  - Published: 2026-01-21 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.14724v1) | [PDF](https://arxiv.org/pdf/2601.14724v1)
- **Context Patch Fusion With Class Token Enhancement for Weakly Supervised Semantic Segmentation**
  - Authors: Yiyang Fu, Hui Li, Wangyu Wu
  - Published: 2026-01-21 | Category: `cs.CV`
  - Links: [arXiv](https://arxiv.org/abs/2601.14718v1) | [PDF](https://arxiv.org/pdf/2601.14718v1)
- _(See full topic page: [BEV & Occupancy (BEVPerception, Occupancy Networks, 4D)](topics/av-bev-occupancy.md))_


### Mapping, Localization & HD Maps (AV SLAM / Map Learning)

_No matches today._


### V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)

- **Economic feasibility of virtual operators in 5G via network slicing**
  - Authors: Erwin J. Sacoto-Cabrera, Luis Guijarro, Jose R. Vidal, Vicent Pla
  - Published: 2026-01-21 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.15103v1) | [PDF](https://arxiv.org/pdf/2601.15103v1)
- **5G NR Non-Terrestrial Networks: Open Challenges for Full-Stack Protocol Design**
  - Authors: Francesco Rossato, Mattia Figaro, Alessandro Traspadini, Takayuki Shimizu, Chinmay Mahabal, Sanjeewa Herath, Chunghan Lee, Dogan Kutay Pekcan et al.
  - Published: 2026-01-21 | Category: `cs.NI`
  - Links: [arXiv](https://arxiv.org/abs/2601.14883v1) | [PDF](https://arxiv.org/pdf/2601.14883v1)
- _(See full topic page: [V2X / Cooperative Perception (V2V, V2I, Sensor Sharing)](topics/av-v2x-cooperative.md))_


### Safety, Robustness & Verification (Uncertainty, OOD, Adversarial, Formal)

_No matches today._


### Datasets, Benchmarks & Simulation (Driving)

_No matches today._
<!-- END TODAY -->
