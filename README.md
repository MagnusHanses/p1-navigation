[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation

### Introduction

In this project, as part of Udacity's Deep Reinforcement Learning Nanodegree, I trained an agent to navigate in a large square-shaped environment. 

![Trained Agent][image1]

In this task, the agent's goal is to collect as many yellow bananas as possible while avoiding blue bananas. The agent is provided with a reward of +1 for collecting a yellow banana and a penalty of -1 for collecting a blue banana. The agent's actions are determined by its current state, which is represented by a 37-dimensional state space that includes the agent's velocity and sensory information about objects in its forward direction. The agent has four possible actions to choose from: moving forward, backward, turning left, or turning right. The task is episodic, and the agent must achieve an average score of +13 over 100 consecutive episodes to successfully solve the environment.

I trained and tested the code on Ubuntu 22.04. To install all necessary dependencies, follow the instructions on https://github.com/udacity/Value-based-methods


### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Place the file in this GitHub repository, and unzip (or decompress) the file. 

### Instructions

Follow the instructions in `Navigation.ipynb` to get started! 

You can use the variable `train` in the first to cell to either train the agent with DQN or to evaluate the agent using the `checkpoint.pth`.


