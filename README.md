# Deep Deterministic Policy Gradient Project

This project uses a Deep deterministic Policy Gradient to estimating the optimum policy for a double jointed arm trying to keep its hand within a small distance of a moving target.  The agent receives a reward of 0.1 for each timestep that its hand is close to the target.  The goal of the project is to train the agent sufficiently so that it maintains an average score of 30 over 100 episodes.  The simulation is used is the <a href="https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher">Reacher</a> environment provided by <a href="https://github.com/Unity-Technologies/ml-agents">Unity ML-agents</a>.


<br />
<br />
<p align="center"><img src="https://github.com/TheOnceAndFutureSmalltalker/deep_deterministic_policy_gradient/blob/master/images/reacher.gif" width="400px" /> </p>
<p align="center"><b>Double Jointed Arm Agents of Reacher Environment</b></p>



## Installation

It is recommended to follow the Udacity DRL ND dependencies [instructions here](https://github.com/udacity/deep-reinforcement-learning#dependencies) 

This project utilises [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md), [NumPy](http://www.numpy.org/) and [PyTorch](https://pytorch.org/) 

A prebuilt simulator is required in be installed. You need only select the environment that matches your operating system:

### Version 1: One (1) Agent
Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

### Version 2: Twenty (20) Agents
Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

The file needs to placed in the root directory of the repository and unzipped.

Next, before starting the environment utilising the corresponding prebuilt app from Udacity  **Before running the code cell in the notebook**, change the `file_name` parameter to match the location of the Unity environment that you downloaded.

## Usage

Load the Jupyter Notebook file Navigation.ipynb and execute each cell in succession.  The last cell is the model training and may take several minutes to complete.
