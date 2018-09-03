
# Project 1: Navigation

### Introduction

This is the first project in the Udacity Deep Reinforcement Learning Nanodegree program.    You may duplicate the project results by following instructions stated below.

The learning objective of this project is to train an agent to collect bananas by using Deep Q network.       A trained agent should navigate its environment as shown in the image below.

!![Trained Agent]()

The goal is to collect as many yellow bananas as possible while avoid blue bananas.  A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

### Getting Started

1. Firstly, clone this repository to your local PC.

2. Next you need to download the environment from one of the links below depending on your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

3. Extract all the files from the downloaded zip file and place them in a sub-folder (just create one and name it anything) inside this repository folder.

### Training Instructions

1. Follow the instructions in `Navigation.ipynb` to get started with training your own agent!  

2. You should achieve at least a score of 13 if the agent is properly trained.

3. After training the agent,  run the agent and view the pop-up window for a view of how the agent is navigating the environment and picking up bananas !