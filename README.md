# Deep RL Quadcopter Controller
## Project: Udacity Machine Learning Nanodegree - Reinforcement Learning 
## Overview: 
The goal of this project is to train a quadcopter to fly with a deep reinforcement learning algorithm, specifically it is trained how to take-off. For the algorithm, we use a Deep Deterministic Policy Gradient (DDPG).
#### Final Result :
- Final Reward-Episode Plot  :<br>
![Final Reward-Episode Plot](resources/reward_episode.png)
## Contents:
The contents of this repositary are:
Quadcopter_Project.ipynb: This Jupyter notebook provides a part of the code for training the quadcopter and summary of our implementation and results.

Quadcopter_Project.html: HTML export of Quadcopter_Project.ipynb.

task.py: This file defines the task (take-off). Particularly, the reward is defined here.

physics_sim.py: This file introduces a physical simulator for the motion of the quadcopter.

agents/agent.py: This file defines the main part of the DDPG algorithm.

agents/actor_critic_model.py: This file defines the actor model and critic models used for the DDPG algorithm. These models are imported to agent.py.

requirement.txt: A list of the libraries used for this project.

plot.ipy: This Jupyter notebook can be used to check the behavior of the quadcopter when the cell for training DDPG agent in Quadcopter_Project.ipynb is still running.

reward.txt: Final reward, position, orientation, velocity and angular velocity as well as the speeds of the rotors in each episode are recorded here.
