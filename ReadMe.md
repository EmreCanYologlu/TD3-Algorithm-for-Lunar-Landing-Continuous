# Building a TD3 Agent for Continuous Control

## Overview

This project implements the **Twin Delayed Deep Deterministic Policy Gradient (TD3)** algorithm to solve the **Lunar Lander Continuous** environment from Gymnasium. TD3, a state-of-the-art reinforcement learning algorithm, is particularly suited for problems involving continuous action spaces. The agent's performance is evaluated by training with multiple random seeds to ensure robustness and reliability.

---

## Features

- **Algorithm:** Twin Delayed Deep Deterministic Policy Gradient (TD3), which addresses overestimation bias in Q-values through:
  - Utilizing two critic networks.
  - Delayed policy updates.
- **Environment:** Lunar Lander Continuous environment from Gymnasium.
  - Goal: Safely land the lunar module on a designated landing pad while avoiding fuel wastage and crashes.
  - Continuous state and action spaces.
- **Evaluation Metrics:**
  - Average reward across multiple episodes and seeds.
  - Robustness and reliability metrics through multiple random seeds.
- **Visualization:**
  - Plots showing reward progression over episodes for each random seed.

---

## Requirements

- **System:** Linux or macOS preferred for compatibility with Gymnasium rendering.

## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```

---

## Usage

1. **Algorithm Training:**
   - Train the TD3 agent on the Lunar Lander Continuous environment.
   - Disable rendering during training to optimize performance.

2. **Multiple Seeds:**
   - Specify different random seeds to test the robustness of the agent.

3. **Output:**
   - Training logs showing episode rewards.
   - Visualization of average rewards over episodes.

---

## Evaluation Criteria

1. **Correctness:**
   - Implementation aligns with the TD3 algorithm.

2. **Performance:**
   - Average reward of 200+ over 100 consecutive episodes.

3. **Robustness:**
   - Consistent performance across six random seeds.

4. **Clarity:**
   - Well-documented and organized code.
   - Detailed analysis of results.

---



## References

1. [TD3 Paper: Fujimoto et al.](https://arxiv.org/abs/1802.09477)
2. [Gymnasium Lunar Lander Documentation](https://gymnasium.farama.org/environments/box2d/lunar_lander/)

---

## Authors
- Names: Emre Can Yologlu
- Course: CS461 - Artificial Intelligence, Fall 2024

---


