# CartPole Reinforcement Learning Project

## Overview
This project implements and analyzes the **CartPole** environment using Reinforcement Learning techniques. The goal of CartPole is to balance a pole on a moving cart by applying left or right forces, maximizing the episode reward by keeping the pole upright for as long as possible.

The project explores training behavior, performance variability, and reproducibility when using learning based agents.

---

## Environment
- **Environment:** OpenAI Gym / Gymnasium `CartPole-v1`
- **Observation Space:** Cart position, cart velocity, pole angle, pole angular velocity
- **Action Space:** Left or Right force
- **Reward:** +1 for every timestep the pole remains balanced

---

## Project Objectives
- Train an agent to solve the CartPole task
- Analyze score variability across runs
- Understand reproducibility challenges in RL
- Evaluate the impact of randomness and hyperparameters

---

## Project Roles & Responsibilities

| Role        | Name               | Responsibilities |
|-------------|--------------------|------------------|
| **Runner** | Mark Young | Executes training runs, manages experiment execution |
| **Maintainer** | Drashti Patel | Maintains codebase, handles structure, version control, and fixes |
| **Analyst** | Andrea Churchwell | Analyzes results, evaluates performance trends, documents findings |
| **Reviewer** | Tashoy Miller | Reviews code, validates results, ensures clarity and correctness |

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cartpole-project.git
   cd cartpole-project
````

2. Create and activate a virtual environment (optional but recommended)

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the training script:

   ```bash
   python train.py
   ```

---
