[//]: # (Image References)

# About this project


This repository of DeepRL source code is work of 1st "Project" in 
**[Udacity Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893)**
The project goal is to implement smart agent walking around game simulator (using DQN algorithm)
which is created by using Unity ML-Agents([github repository](https://github.com/Unity-Technologies/ml-agents))

# Project Details
![Trained Agent][image1]

In the simulator, there are two types of bananas, yellow ones and blue ones.
If he catches yellow one, he gets positive reward (+1). But if he catches blue one,
he gets negative reward (-1). Thus, the goal of the agent is to collect
as many yellow bananas as possible while avoiding blue bananas.

Students need to implement DeepRL agent using Python and Pytorch.

The simulation contains a single agent that navigates a large environment.
At each time step, it has four actions at its disposal:

- `0` - walk forward
- `1` - walk backward
- `2` - turn left
- `3` - turn right

The state space has `37` dimensions and contains the agent's velocity,
along with ray-based perception of objects around agent's forward direction.

The task is episodic, and in order to solve the environment, the agent must
get an average score of +13 over 100 consecutive episodes.

# Getting Started
First create an environment from [Environment](./environment.yaml) then follow the instructions.

# Instructions
To train the agent, start jupyter notebook, open `NavigationProject.ipynb`
and execute! For more information, please check instructions
inside the notebook.

# Additional informations
- [Report](./Report.pdf) : Result report of training score
when using Double-DQN as agent.

You can watch the training agent and trained agent videos at below links; 

Training :  https://youtu.be/J3B5zx8BLB8
Trained Agent: https://youtu.be/yNvRt8H9X1s


