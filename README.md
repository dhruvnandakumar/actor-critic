# actor-critic
A DDPG Actor-Critic network model

## 1.0 Project Details
This project aims to solve Unity Reacher environment, a double jointed arm that can move to target locations. The rewards is +0.1 for every time the arm is at the right location. Thus, the goal of the game is to maximise how much time the arm spends at the tarrget.

The game is considered complete when the arm exceeds 30 points in a single training episode. 

## 2 Getting started with the repository
This repository requires some dependencies to be installed, particulary the Unity Gym. 
Follow these links to install the right dependencies: 
1. Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip
2. Mac OSX: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip\
3. Windows 32bit: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip
4. Windows 64bit: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip
5. No monitor linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip

You will also have to install some python depencies:
1. First, please follow the setup on this url to get your python virtual environment set up: https://github.com/udacity/deep-reinforcement-learning#dependencies
2. Open a terminal window at the root of this repository and run the following command: pip -q install ./python

## 3 Instructions 

Place the download in this repository in the root folder, and follow along with the continuois_control.ipynb Jupyter Notebook. 
