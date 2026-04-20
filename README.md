# Mehmet Turan Yardimci
**Robot Learning Researcher**

mehmetturanyardimci@hotmail.com | [LinkedIn](https://www.linkedin.com/in/mehmetturanyardimci/) | [GitHub](https://github.com/mturan33)

---

## About Me

Computer Engineering graduate from **Cukurova University** (2025) specializing in robot learning, reinforcement learning, and humanoid control. Building hierarchical control systems that combine vision-language understanding with low-level motor control for humanoid robots.

---

## Featured Projects

### [G1 Vision-Language-Action (VLA)](https://github.com/mturan33/isaac-g1-vla) *(In Progress)*
RL-to-IL-to-VLA pipeline for the G1 humanoid. Collecting expert demonstrations from trained RL policies, then distilling into end-to-end visuomotor policies.

- **Pipeline:** RL expert rollout -> LeRobot v2 dataset -> ACT/Diffusion Policy -> GR00T N1.6
- **Data:** 22-dim joint actions (15 loco + 7 arm), RGB observations from tiled camera
- **Goal:** End-to-end vision-to-action without hand-crafted skill primitives

### [G1 Humanoid Hierarchical Control](https://github.com/mturan33/g1-vlm)
End-to-end hierarchical system for Unitree G1 humanoid: VLM task planning + RL locomotion + arm manipulation + drawer interaction.

- **High-level:** VLM planner (Qwen3-VL) generates skill sequences from natural language tasks
- **Low-level:** PPO-trained locomotion (17k steps/sec) + arm policy (3cm precision)
- **Skills:** Walk, reach, grasp, pull drawer, pick-and-place -- 6/6 drawer, 8/8 pick-place success
- **Stack:** Isaac Lab, RSL-RL, PyTorch, Ollama, CUDA

### [G1 Unitree Locomotion Control (ULC)](https://github.com/mturan33/isaac-g1-ulc)
Multi-stage PPO training pipeline for Unitree G1 whole-body locomotion. Flat walking, velocity tracking, terrain adaptation, torso stabilization, and arm coordination.

- **5-stage curriculum:** Flat -> Velocity -> Terrain -> Torso -> Arm control
- **Performance:** 17k+ steps/sec, 4096 parallel envs, L7 curriculum
- **Stack:** Isaac Lab, RSL-RL, PyTorch, CUDA

### [Isaac Lab Anymal-C Locomotion](https://github.com/mturan33/isaaclab-anymal-locomotion)
PPO from scratch for quadruped locomotion in NVIDIA Isaac Lab. 17k+ steps/sec on RTX 5070 Ti, 4096 parallel envs, domain randomization for sim-to-real.

### [MuJoCo Ant PPO](https://github.com/mturan33/mujoco-ant-ppo)
From-scratch PPO and SAC for MuJoCo Ant-v5. Pure NumPy/PyTorch, custom reward shaping, 2700+ reward in 8M steps.

### [Local Path Planner Benchmark](https://github.com/mturan33/benchmark-local-path-planners-barn-challenge)
Benchmarking ROS navigation planners (TEB, DWA, MPC, Lattice) on BARN dataset. Under publication review.

### [Live Actor-Critic Training](https://github.com/mturan33/my-actor-critic)
Interactive Streamlit app for real-time RL training visualization on CartPole.

---

## Tech Stack

**Robot Learning:** PPO, SAC, GAE, Domain Randomization, Curriculum Learning, Flow Matching, Imitation Learning
**Simulation:** NVIDIA Isaac Lab/Sim, MuJoCo, Gazebo, ROS/ROS2
**AI/ML:** PyTorch, YOLO (v4-8), OpenCV, VLMs (Florence-2, Qwen3-VL)
**Platforms:** Unitree G1, Jetson Nano, Pixhawk
**Languages:** Python, C/C++, CUDA

---

## Experience

**UAV Team Captain** | 1.5 Adana AGM ALKAR (3 years)
- Led 10+ member team for autonomous UAV systems at TEKNOFEST
- YOLOv7 + Jetson Nano + Pixhawk integration for real-time detection

---

Open to research collaborations and R&D opportunities in humanoid robotics and robot learning.
