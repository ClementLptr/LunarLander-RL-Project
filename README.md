# Autonomous Lunar Landing

## Course: Reinforcement Learning

## Project Objective
The goal of this project is to train an autonomous agent using Reinforcement Learning (RL) to land a spacecraft safely on the Moon in the OpenAI Gym Lunar Lander environment. The agent must learn to:
- Stabilize the lander
- Minimize fuel consumption
- Land smoothly while dealing with gravity, inertia, and dynamic uncertainties

<div align="center">
  <img src="figures/env.gif" alt="TFB Agent" height="200"/>
</div>

## Motivation for Choosing Lunar Lander
- **Complex problem**: The agent must optimize multiple constraints (fuel efficiency, stability, and precision) in a complex, partially observable environment.
- **Strong foundation for RL applications**: The project offers an opportunity to apply key RL concepts such as policy learning, reward shaping, and the exploration-exploitation tradeoff.

## Implemented RL Agents
This project will implement and compare different RL algorithms:
- **DQN (Deep Q-Network)**: Discrete action control with experience replay.
- **PPO (Proximal Policy Optimization)**: Policy gradient method for better stability.

## Expected Results & Challenges
### Expected Outcomes
- A trained RL agent capable of landing safely with a high success rate.
- Performance comparison of **DQN vs PPO vs SAC** (learning speed, stability, final reward).
- Graphs and visualizations of training curves, landing attempts, and agent improvements.

### Challenges
- **Exploration vs Exploitation**: The agent must balance random actions with optimizing learned strategies.
- **Reward Shaping**: Proper tuning of the reward function is crucial for efficient learning.

## Conclusion
This project will demonstrate the power of Deep RL for autonomous spacecraft landing. The results could be extended to drone landings, robotic control, or real-world aerospace applications.

---
**Author:** Clément Leprêtre, Cyrielle Théobald

**Repository:** [GitHub - LunarLander-RL-Project](https://github.com/ClementLptr/LunarLander-RL-Project)

