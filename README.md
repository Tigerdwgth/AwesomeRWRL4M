# Awesome Real-World Reinforcement Learning for Manipulation 🦾

A curated list of research papers on **real-world reinforcement learning for robotic manipulation**, where policies are trained or fine-tuned through **direct interaction with physical manipulators** (e.g., robotic arms, dexterous hands), rather than simulation-only or purely offline learning.

This list focuses on **end-to-end or policy-level reinforcement learning** applied to **real-world manipulation tasks**, including grasping, assembly, deformable object manipulation, and long-horizon dexterous control. Closely related **interactive learning** methods that improve policies from on-robot interaction (e.g., DAgger-style human correction) are also tracked.

Papers within each section are roughly ordered by first release date.

- [Algorithms, Systems & Infrastructure](#algorithms-systems--infrastructure)
- [RL Post-Training of VLAs & Generalist Policies](#rl-post-training-of-vlas--generalist-policies)
- [Residual RL & Policy Steering](#residual-rl--policy-steering)
- [Human-in-the-Loop RL](#human-in-the-loop-rl)
- [DAgger & Human Correction](#dagger--human-correction)
- [World Models & Digital Twins](#world-models--digital-twins)
- [Reward Models for Real-World RL](#reward-models-for-real-world-rl)
- [Dexterous & Contact-Rich Manipulation](#dexterous--contact-rich-manipulation)

---

## Algorithms, Systems & Infrastructure

- **QT-Opt: Scalable Deep Reinforcement Learning for Vision-Based Robotic Manipulation**
  https://arxiv.org/abs/1806.10293

- **SERL: A Software Suite for Sample-Efficient Robotic Reinforcement Learning**
  https://serl-robot.github.io/

- **MENTOR: Mixture-of-Experts Network with Task-Oriented Perturbation for Visual Reinforcement Learning**
  https://arxiv.org/abs/2410.14972

- **SimLauncher: Launching Sample-Efficient Real-world Robotic Reinforcement Learning via Simulation Pre-training**
  https://arxiv.org/abs/2507.04452

- **RLinf: Flexible and Efficient Large-scale Reinforcement Learning via Macro-to-Micro Flow Transformation**
  https://arxiv.org/abs/2509.15965

- **RL-100: Performant Robotic Manipulation with Real-World Reinforcement Learning**
  https://arxiv.org/abs/2510.14830

- **RLinf-USER: A Unified and Extensible System for Real-World Online Policy Learning in Embodied AI**
  https://arxiv.org/pdf/2602.07837

- **One Demonstration Is Enough for Real-World Robotic Reinforcement Learning (AutoSERL)**
  https://arxiv.org/abs/2607.01651

- **Efficient Real-World Online Reinforcement Learning for Robot Manipulation via Centralized Training and Critic Decomposition**
  https://arxiv.org/abs/2608.09762

## RL Post-Training of VLAs & Generalist Policies

- **Policy Agnostic RL: Offline RL and Online RL Fine-Tuning of Any Class and Backbone (PA-RL)**
  https://arxiv.org/abs/2412.06685

- **RLDG: Robotic Generalist Policy Distillation via Reinforcement Learning**
  https://arxiv.org/abs/2412.09858

- **Improving Vision-Language-Action Model with Online Reinforcement Learning (iRe-VLA)**
  https://arxiv.org/abs/2501.16664

- **ConRFT: A Reinforced Fine-tuning Method for Vision-Language-Action Models via Consistency Policy**
  https://arxiv.org/abs/2502.05450

- **SimpleVLA-RL: Scaling VLA Training via Reinforcement Learning**
  https://arxiv.org/abs/2509.09674

- **Self-Improving Embodied Foundation Models**
  https://arxiv.org/abs/2509.15155

- **A Vision-Language-Action-Critic Model for Robotic Real-World Reinforcement Learning (VLAC)**
  https://arxiv.org/abs/2509.15937

- **π\*_0.6: A Vision-Language-Action Model that Learns from Experience**
  https://arxiv.org/abs/2511.14759

- **GR-RL: Going Dexterous and Precise for Long-Horizon Robotic Manipulation**
  https://arxiv.org/abs/2512.01801

- **Precise Manipulation with Efficient Online RL**
  https://www.pi.website/research/rlt

- **SOP: Scaling General-Purpose Robots in the Real World**
  https://agibot.com/research/sop_en

- **Learning While Deploying: Fleet-Scale Reinforcement Learning for Generalist Robot Policies (LWD)**
  https://arxiv.org/abs/2605.00416

- **FlowPRO: Reward-Free Reinforced Fine-Tuning of Flow-Matching VLAs via Proximalized Preference Optimization**
  https://arxiv.org/abs/2606.05468

- **Hierarchical Advantage Weighting for Online RL Fine-Tuning of VLAs from Sparse Episode Outcomes**
  https://arxiv.org/abs/2606.17043

- **FORCE: Efficient VLA Reinforcement Fine-Tuning via Value-Calibrated Warm-up and Self-Distillation**
  https://arxiv.org/abs/2606.26006

- **Adapting Generalist Robot Policies with Semantic Reinforcement Learning (SARL)**
  https://arxiv.org/abs/2606.31958

- **Learning to Act While Waiting: RL Finetuning of Generalist Robot Policies Under Inference Latency**
  https://arxiv.org/abs/2608.23831

- **GRAFT: Grounded and Efficient Online Reinforcement Adaptation for Fine-Grained Robot Manipulation**
  https://arxiv.org/abs/2608.27079

- **Reinforcement Learning for Real-Time Vision-Language-Action Policies**
  https://arxiv.org/abs/2609.18207

- **Stable and Efficient Real-World Online VLA Post-Training via Asynchronous Replay-Anchored Policy Improvement**
  https://arxiv.org/abs/2609.22888

## Residual RL & Policy Steering

- **Steering Your Diffusion Policy with Latent Space Reinforcement Learning (DSRL)**
  https://arxiv.org/abs/2506.15799

- **Residual Off-Policy RL for Finetuning Behavior Cloning Policies (ResFiT)**
  https://arxiv.org/abs/2509.19301

- **Self-Improving Vision-Language-Action Models with Data Generation via Residual RL (PLD)**
  https://arxiv.org/abs/2511.00091

- **From Prior to Pro: Efficient Skill Mastery via Distribution Contractive RL Finetuning (DICE-RL)**
  https://arxiv.org/abs/2603.10263

- **Focus-Then-Contact: Speeding Up Robotic Contact-Rich Task Learning with Affordance-Guided Real-World Residual Reinforcement Learning (FTC, ICML 2026)**
  https://edem-ai.github.io/FTC-website/

- **Beyond Action Residuals: Real-World Robot Policy Steering via Bottleneck Latent Reinforcement Learning**
  https://arxiv.org/abs/2605.19919

- **BORA: Bridging Offline Reinforcement Learning and Online Residual Adaptation for Real-World Dexterous VLA Models**
  https://arxiv.org/abs/2605.30226

- **HiL-ResRL: A Model-Agnostic Finetuning Adapter via Human-in-the-loop Residual Reinforcement Learning**
  https://arxiv.org/abs/2606.22860

- **From Pretraining to Proficiency: Real-World Subtask RL for Long-Horizon Manipulation with Minimal Human Intervention (PARTS)**
  https://arxiv.org/abs/2609.21788

## Human-in-the-Loop RL

- **Precise and Dexterous Robotic Manipulation via Human-in-the-Loop Reinforcement Learning (HIL-SERL)**
  https://arxiv.org/abs/2410.21845

- **Dual-Actor Fine-Tuning of VLA Models: A Talk-and-Tweak Human-in-the-Loop Approach**
  https://arxiv.org/abs/2509.13774

- **Human-in-the-loop Online Rejection Sampling for Robotic Manipulation (Hi-ORS)**
  https://arxiv.org/abs/2510.26406

- **Real-world Reinforcement Learning from Suboptimal Interventions**
  https://arxiv.org/pdf/2512.24288

- **UniSteer: Unified Noise Steering for Efficient Human-Guided VLA Adaptation**
  https://arxiv.org/abs/2605.10821

- **DexPIE: Stable Dexterous Policy Improvement from Real-World Experience**
  https://arxiv.org/abs/2606.09615

- **UniIntervene: Agentic Intervention for Efficient Real-World Reinforcement Learning**
  https://arxiv.org/abs/2606.12372

- **ROVE: Unlocking Human Interventions for Humanoid Manipulation via Reinforcement Learning**
  https://arxiv.org/abs/2606.17011

## DAgger & Human Correction

- **RoboCopilot: Human-in-the-loop Interactive Imitation Learning for Robot Manipulation**
  https://arxiv.org/abs/2503.07771

- **Genie Centurion: Accelerating Scalable Real-World Robot Training with Human Rewind-and-Refine Guidance**
  https://arxiv.org/abs/2505.18793

- **Human-assisted Robotic Policy Refinement via Action Preference Optimization (APO)**
  https://arxiv.org/abs/2506.07127

- **Compliant Residual DAgger: Improving Real-World Contact-Rich Manipulation with Human Corrections (CR-DAgger)**
  https://arxiv.org/abs/2506.16685

- **RaC: Robot Learning for Long-Horizon Tasks by Scaling Recovery and Correction**
  https://arxiv.org/abs/2509.07953

- **FlowCorrect: Efficient Interactive Correction of Generative Flow Policies for Robotic Manipulation**
  https://arxiv.org/abs/2602.22056

- **Force-Aware Residual DAgger via Trajectory Editing for Precision Insertion with Impedance Control**
  https://arxiv.org/abs/2603.04038

- **DexHiL: A Human-in-the-Loop Framework for Vision-Language-Action Model Post-Training in Dexterous Manipulation**
  https://arxiv.org/abs/2603.09121

- **Easy-IIL: Reducing Human Operational Burden in Interactive Imitation Learning via Assistant Experts**
  https://arxiv.org/abs/2603.12769

- **Hand-in-the-Loop: Improving VLA Policies for Dexterous Manipulation via Seamless Hand-Arm Intervention**
  https://arxiv.org/abs/2605.15157

- **FlowDAgger: Human-in-the-Loop Adaptation of Generative Robot Policies in Latent Space**
  https://arxiv.org/abs/2607.08877

- **Towards High-DoF Dexterous Manipulation through VLA Post-Training**
  https://arxiv.org/abs/2609.19666

- **HIL-UMI: Bringing Human-in-the-Loop Post-Training of Vision-Language-Action Models to Universal Manipulation Interface**
  https://arxiv.org/abs/2609.20659

## World Models & Digital Twins

- **WMPO: World Model-based Policy Optimization for Vision-Language-Action Models**
  https://arxiv.org/abs/2511.09515

- **TwinRL: Digital Twin-Driven Reinforcement Learning for Real-World Robotic Manipulation**
  https://arxiv.org/abs/2602.09023

- **GigaBrain-0.5M\*: a VLA That Learns From World Model-Based Reinforcement Learning**
  https://arxiv.org/abs/2602.12099

- **VLAW: Iterative Co-Improvement of Vision-Language-Action Policy and World Model**
  https://arxiv.org/abs/2602.12063

- **Online World Modeling Enables Real-World Inverse Reinforcement Learning from Observation**
  https://arxiv.org/abs/2602.24121

- **RISE: Self-Improving Robot Policy with Compositional World Model（Kai0)**
  https://opendrivelab.com/kai0-rl/

- **WorldSample: Closed-loop Real-robot RL with World Modelling**
  https://arxiv.org/abs/2607.02431

- **How to Learn from What a Human Would Avoid? Intervention-Aware World Models with Real-World RL for Dexterous Manipulation**
  https://arxiv.org/abs/2609.06009

- **Imagine-RL: Residual-Confidence-Guided Cross-Attention for World-Model-Augmented VLA Reinforcement Learning**
  https://arxiv.org/abs/2609.24033

## Reward Models for Real-World RL

- **ReWiND: Language-Guided Rewards Teach Robot Policies without New Demonstrations**
  https://arxiv.org/abs/2505.10911

- **Robo-Dopamine: General Process Reward Modeling for High-Precision Robotic Manipulation**
  https://arxiv.org/abs/2512.23703

- **RoboReward: General-Purpose Vision-Language Reward Models for Robotics**
  https://arxiv.org/abs/2601.00675

- **SOLE-R1: Video-Language Reasoning as the Sole Reward for On-Robot Reinforcement Learning**
  https://arxiv.org/abs/2603.28730

- **RARM: Confidence-Gated Progress Reward Modeling for RL in Manipulation**
  https://arxiv.org/abs/2606.22027

## Dexterous & Contact-Rich Manipulation

- **Dexterous Grasping with Real-World Robotic Reinforcement Learning**
  https://arxiv.org/abs/2503.04014

- **SHaRe-RL: Structured, Interactive Reinforcement Learning for Contact-Rich Industrial Assembly Tasks**
  https://arxiv.org/abs/2509.13949

- **Self-Supervised Multisensory Pretraining for Contact-Rich Robot Reinforcement Learning**
  https://arxiv.org/abs/2511.14427

- **HandelBot: Real-World Piano Playing via Fast Adaptation of Dexterous Robot Policies**
  https://arxiv.org/abs/2603.12243

- **LAMP: Latent Motion Prior-Guided Real-World Learning for Dexterous Hand Manipulation**
  https://arxiv.org/abs/2607.06323

- **Real-World Reinforcement Learning with MPC Scaffolding for Dexterous Manipulation**
  https://arxiv.org/abs/2609.14878

---

Contributions welcome.
