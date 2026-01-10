# Mehmet Turan Yardımcı
**Robot Learning Researcher | Hierarchical VLM-RL for Humanoid Control**

mehmetturanyardimci@hotmail.com | [LinkedIn](https://www.linkedin.com/in/mehmetturanyardimci/) | [GitHub](https://github.com/mturan33)

---

## 👋 About Me

I'm a Computer Engineering graduate from **Çukurova University** (2025) specializing in **robot learning, reinforcement learning, and humanoid control**. My research focuses on **hierarchical VLM-RL systems** that combine vision-language understanding with low-level motor control for humanoid robots.

**Current Research:** Developing a hierarchical control system for the **Unitree G1 humanoid robot** in NVIDIA Isaac Lab, combining PPO-based locomotion with Flow Matching manipulation policies.

---

## 🔬 Research Focus

**Hierarchical VLM-RL for Humanoid Manipulation**
- High-level: Vision-Language Models (Florence-2/Molmo2) for semantic scene understanding
- Mid-level: Flow Matching for bimanual manipulation planning  
- Low-level: PPO policies for whole-body locomotion control
- Achieved **17,000+ steps/second** training speed with 4096 parallel environments

---

## 🛠 Tech Stack

**Robot Learning:** PPO, SAC, Actor-Critic, GAE, Domain Randomization, Curriculum Learning  
**Simulation:** NVIDIA Isaac Lab, Isaac Sim, MuJoCo, Gazebo, ROS/ROS2  
**AI/ML:** PyTorch, TensorBoard, YOLO (v4-8), OpenCV, Flow Matching  
**Platforms:** Unitree G1, Jetson Nano, Pixhawk  
**Languages:** Python, C/C++, CUDA

---

## 🚀 Featured Projects

### [G1 Humanoid Hierarchical VLM-RL](https://github.com/mturan33/g1-vlm-rl) *(In Progress)*
Hierarchical control system for Unitree G1 humanoid robot combining VLM planning with RL execution.

**Architecture:**
- Stage 1-2: Locomotion policy (velocity tracking, terrain adaptation)
- Stage 3: Torso control (pitch/roll/yaw tracking while walking) — **24.69 reward**
- Stage 4: Arm control with residual actions (77 obs dim, 22 actions) — **28.81 reward**
- Stage 5+: VLM integration for language-conditioned manipulation

**Technologies:** Isaac Lab 2.3.1, RSL-RL, PyTorch, CUDA, TensorBoard

---

### [Isaac Lab Anymal-C Locomotion](https://github.com/mturan33/isaaclab-anymal-locomotion)
PPO implementation from scratch for quadruped locomotion in NVIDIA Isaac Lab.

**Highlights:**
- 17,000+ steps/second on single RTX 5070 Ti GPU
- Domain randomization for sim-to-real transfer
- Vectorized environments with 4096 parallel instances

---

### [MuJoCo Ant PPO](https://github.com/mturan33/mujoco-ant-ppo)
From-scratch PPO & SAC implementation for MuJoCo Ant-v5 environment.

**Key Features:**
- Pure NumPy & PyTorch
- Custom reward shaping to eliminate hopping behavior
- **2700+ reward** achieved in 8M steps
- GAE (λ=0.95), learning rate annealing, exploration decay

---

### [Local Path Planner Benchmark](https://github.com/mturan33/benchmark-local-path-planners-barn-challenge)
Benchmarking framework for ROS navigation planners using BARN dataset.

**Planners Tested:** TEB, DWA, MPC, Lattice  
**Status:** Under publication review at Çukurova University Engineering Journal

---

### [Live Actor-Critic Training](https://github.com/mturan33/my-actor-critic)
Interactive Streamlit app demonstrating real-time RL training on CartPole.
- Watch the agent learn live in browser
- Adjustable hyperparameters for educational purposes

---

## 💼 Experience

**UAV Team Captain** | 1.5 Adana AGM ALKAR (3 years)
- Led 10+ member team designing autonomous UAV systems
- Integrated YOLOv7 + Jetson Nano + Pixhawk for TEKNOFEST competitions
- Developed real-time object detection for fixed-wing UAVs

---

## 📚 Currently Exploring

- **Hierarchical Control:** Whole-body humanoid manipulation with PPO + Flow Matching
- **VLM Integration:** Florence-2/Molmo2 for semantic scene understanding and task planning
- **Sim-to-Real:** Domain randomization and teacher-student distillation for G1 deployment

---

## 📫 Let's Connect!

Open to **research collaborations** and **R&D opportunities** in humanoid robotics and robot learning.

📧 mehmetturanyardimci@hotmail.com
