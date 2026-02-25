# epsilon-greedy-bandit-simulation
Simulation study of the epsilon-greedy strategy in the multi-armed bandit problem, analysing exploration–exploitation trade-offs.
## Project Overview

This project explores the epsilon-greedy strategy in the multi-armed bandit problem.  
The goal is to study how different epsilon values affect the balance between exploration and exploitation.

Through simulation experiments, we compare how agents perform under different levels of randomness and analyze their learning behavior over time.

---

## Problem Description

The multi-armed bandit problem is a classic reinforcement learning task.  
An agent repeatedly selects one action from multiple options (arms), each with an unknown reward distribution.

The challenge is to:

- Explore different actions to gather information
- Exploit the best-known action to maximize reward

The epsilon-greedy strategy addresses this trade-off by:

- Choosing a random action with probability ε (exploration)
- Choosing the best current action with probability 1 - ε (exploitation)

---

## Methodology

- Simulated a k-armed bandit environment
- Implemented the epsilon-greedy algorithm
- Compared performance under different epsilon values
- Evaluated:
  - Average reward over time
  - Optimal action selection rate

---

## Results

The experiments show that:
![Average Reward Comparison](images/average_reward.png)
![Optimal_Action Comparison](images/optimal_action.png)
- Small epsilon values allow more stable long-term performance
- Larger epsilon values increase exploration but may reduce short-term reward
- A proper balance between exploration and exploitation is critical for learning efficiency

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

---

## File Structure
