# Publications — Hongjin Fu

Robot learning for legged and wheeled-bipedal locomotion: reinforcement learning, teacher–student distillation, and sim-to-real deployment.

All three papers are **accepted and not yet published in the proceedings**. The PDFs here are the authors' final camera-ready versions. Links to the published versions will be added once they are available.

## 2026

**ViT-Enhanced Critic for Terrain-Adaptive Bipedal Locomotion via Teacher-Student Reinforcement Learning**
**Hongjin Fu**, Yang Liufu, Jianqin Lin, Zhengcheng Pan, Xinyu Xie†, Zhenyu Hou†
*IEEE International Conference on Advanced Robotics and Mechatronics (ICARM 2026)*, accepted, to appear · First author
[PDF](papers/2026_ICARM_ViT-Enhanced-Critic.pdf)

> A lightweight Vision Transformer replaces the MLP/MoE terrain encoder in the critic. It tokenizes a 12×12 local heightmap into patches and aggregates them with a [CLS] token, and is trained with PPO in a teacher–student pipeline. Across five simulated terrain types it reduces velocity-tracking error by 5.0% and height-tracking error by 8.5% compared with the VMTS baseline. Real-world stair climbing and multi-terrain traversal were validated on a LimX Dynamics P1 biped.

**BiCross-UNet: Hierarchical Bidirectional Cross-Conditioning and Privileged Denoising Distillation for Robust Perceptive Locomotion**
Senming Tan\*, Fuyang Liu\*, **Hongjin Fu**, Qijing Xiao, Sicong Wang, Senyu Li, Jie Tan, Zhenyu Hou†
*IEEE International Conference on Advanced Robotics and Mechatronics (ICARM 2026)*, accepted, to appear
[PDF](papers/2026_ICARM_BiCross-UNet.pdf)

> A two-stream perceptive locomotion policy for humanoids that couples proprioceptive history and terrain observations through hierarchical bidirectional cross-conditioning and global cross-attention. A teacher-guided terrain reconstruction objective and a stable distillation pipeline (DAgger-style action mixing, replay, staged training, structured corruption curriculum) give robustness to noisy terrain perception.

**FROST: Fast Reflex-Like On-Stall Training for Blind Narrow-Stair Climbing in Wheeled-Bipedal Robots**
Jie Tan, Senyu Li, Yuanming Luo, **Hongjin Fu**, JianQin Lin, Rui Ling
*International Conference on Control, Automation, Robotics and Vision (ICARCV 2026)*, accepted, to appear
[PDF](papers/2026_ICARCV_FROST.pdf)

> Event-triggered RL rewards for blind stair climbing on a wheeled biped. A training-time stall-and-posture trigger activates rewards for body lifting, sequential leg swings, and recovery. The deployed policy uses only proprioception. It reaches 88% success on 200 mm steps in simulation, compared with 0–2% for the ablations. Prototype demonstrations cover narrow stairs with risers up to 200 mm.

\* equal contribution · † corresponding author

---

Copyright of each paper will belong to its publisher once published. These copies are shared for personal and academic reference only.
