# Mountain Car Reinforcement Learning with Q-Learning

This project was developed as part of an Artificial Intelligence course at the University of Tehran.

The project focuses on solving the **MountainCar-v0** environment using **Q-Learning**, a model-free Reinforcement Learning algorithm. A tabular Q-Learning agent is implemented from scratch, trained using different exploration strategies, and evaluated under multiple state discretization settings.

---

## Topics Covered

* Reinforcement Learning
* Markov Decision Process (MDP)
* Q-Learning
* Q-Table implementation
* State discretization
* Epsilon-Greedy policy
* Exploration vs Exploitation
* Epsilon decay strategies
* Agent training
* Agent evaluation
* Reward visualization
* Hyperparameter comparison

---

## Algorithm

* Tabular Q-Learning

---

## Libraries

* Python
* Gym
* NumPy
* Matplotlib
* Pygame

---

## Environment

**MountainCar-v0**

The agent learns to drive an underpowered car up a steep hill by building momentum through repeated interactions with the environment.

---

## Experiments

The project compares different exploration strategies:

* Constant Epsilon
* Linear Decay
* Logarithmic Decay
* Exponential Decay

It also investigates the impact of different state discretization granularities:

* 5 × 5 Buckets
* 40 × 40 Buckets
* 100 × 100 Buckets

---

## Results

The trained agent successfully solved the environment after approximately **336,494 training episodes**, achieving:

* **Average Evaluation Reward:** -109.19
* **Best Reward:** -102
* **Worst Reward:** -116

The project also includes reward curves, moving-average performance plots, epsilon decay visualization, and comparisons between different exploration strategies and discretization settings.

---

## Skills Practiced

* Reinforcement Learning
* Q-Learning
* Dynamic Programming Concepts
* Epsilon-Greedy Exploration
* Hyperparameter Tuning
* State Space Discretization
* Performance Evaluation
* Data Visualization

---

## Repository Structure

```text
03-Reinforcement-Learning
│
├── Reinforcement_Learning.ipynb
└── README.md
```
