# Collaborative Perception Security

This repository collects recent advances focusing on **defence / adversarial attack** of **collaborative / cooperative / multi-agent perception** for **V2I / V2V / V2X** autonomous driving. 

- **MADE** (MADE: Malicious Agent Detection for Robust Multi-Agent  Collaborative Perception) [[paper](https://arxiv.org/abs/2310.11901)] [~~code~~]
  - Mode: Intermediate Collaboration
  - Dataset: V2X-sim, DAIR-V2X
  - Task: Detection
  - Input: Point Cloud
  - Publication: arxiv 2024
  - Feature: Propose a semi-supervised anomaly detector based on a double-hypothesis test with the Benjamini-Hochberg procedure for false positive control; Propose two novel statistics, _match loss_ and _collaborative reconstruction loss_, to assess the consistency between each putative malicious agent and the ego agent.
 
- **CAD** (On Data Fabrication in Collaborative Vehicular Perception: Attacks and Countermeasures) [[paper](https://www.usenix.org/conference/usenixsecurity24/presentation/zhang-qingzhao)] [[code](https://github.com/zqzqz/AdvCollaborativePerception)]
  - Mode: Intermediate Collaboration
  - Dataset: Adv-OPV2V, Adv-MCity
  - Task: Detection
  - Input: Point Cloud
  - Publication: USENIX 2024
  - Feature: Propose various real-time data fabrication attacks to undermine collaborative perception systems and present a Collaborative Anomaly Detection (CAD) approach for defense.
 
- **V2XP-ASG** (V2XP-ASG: Generating Adversarial Scenes for Vehicle-to-Everything Perception) [[paper](https://arxiv.org/abs/2209.13679)] [[code](https://github.com/XHwind/V2XP-ASG?tab=readme-ov-file)]
  - Mode: Intermediate Collaboration
  - Dataset: OPV2V, Heuristic
  - Task: Detection
  - Input: Point Cloud
  - Publication: ICRA 2023
  - Feature: V2XP-ASG learns to construct an adversarial collaboration graph and simultaneously perturb multiple agents’ poses in an adversarial and plausible manner.

- **ROBOSAC** (Among Us: Adversarially Robust Collaborative Perception by Consensus) [[paper](https://arxiv.org/abs/2303.09495)] [[code](https://github.com/coperception/ROBOSAC)]
  - Mode: Intermediate Collaboration
  - Dataset: V2X-Sim
  - Task: Detection
  - Input: Point Cloud
  - Publication: ICCV 2023
  - Feature: Develop ROBOSAC, a scalable, generalizable, and generally-applicable adversarially robust collaborative perception framework via multi-robot consensus.

- **Adversarial V2V** (Adversarial Attacks On Multi-Agent Communication) [[paper](https://arxiv.org/abs/2101.06560)] [~~code~~]
  - Mode: Intermediate Collaboration
  - Dataset: V2V-Sim (not publicly available)
  - Task: Adversarial Attack
  - Input: Point Cloud
  - Publication: ICCV 2021
  - Feature: The first attack specific to intermediate-fusion collaborative perception, which is an untargeted adversarial attack creating inaccurate detection bounding boxes as many as possible by perturbing feature maps in intermediate-fusion systems.
 
  
