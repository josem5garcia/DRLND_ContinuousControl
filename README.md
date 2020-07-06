# DRLND_ContinuousControl
Second project of the Deep Reinforcement Learning Nano Degree

## Introduction
This repository contains all the files required in the project 'Continuous Control', from the Deep Reinforcement Learning Nano Degree, including all the code to run the model, and a report with the results obtained.

This project make use of the Unity environment, and creates a Deep Deterministic Policy Gradient (DDPG) agent to solve the problem implemented in Python 3 with PyTorch. Two options were proposed in the task, and the one with a single agent is selected, being this task episodic and the agent must get an average score of +30 over 100 consecutive episodes to pass it.

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

## How to run the agent
In order to do this, it is just necesary to run the file 'project.ipynb', or open the Unity ML Agent with the weights included in the repository (already trained agent).

## Install what is required
1. Install Unity (https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md)
2. Download the Unity ML environment and unzip the file (it must be pasted in the root folder).
3. Create Conda Environment with Python 3.6
4. Install Dependencies (python folder)
