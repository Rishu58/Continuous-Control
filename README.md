# Continuous-Control
This project is part of the Deep Reinforcement Learning Nanodegree Program, by Udacity.
The goal in this project is to create and train an agent to navigate and collect bananas in a large, square world.


# Understanding the environment
This environment has been built using the Unity Machine Learning Agents Toolkit (ML-Agents), which is an open-source Unity plugin that enables games and simulations to serve as environments for training intelligent agents. You can read more about ML-Agents by perusing the GitHub repository.

The project environment provided by Udacity is similar to, but not identical to the Banana Collector environment on the Unity ML-Agents GitHub page.

In this environment, an Agent navigates a large, square world collecting bananas. Each episode of this task is limited to 300 steps. A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of the agent is to collect as many yellow bananas as possible, avoiding the blue ones.

# The state-space has 37 dimensions and contains the agent's velocity, along with the ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

0 - move forward
1 - move backward
2 - turn left
3 - turn right
Solving the environment
To solve the environment, the Agent must obtain an average score of +13 over 100 consecutive episodes.

Here is the result.

