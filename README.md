# Deep Deterministic Policy Gradient Project

This project uses a Deep deterministic Policy Gradient to estimating the optimum policy for a double jointed arm trying to keep its hand within a small distance of a moving target.  The agent receives a reward of 0.1 for each timestep that its hand is close to the target.  The goal of the project is to train the agent sufficiently so that it maintains an average score of 30 over 100 episodes.  The simulation is used is the <a href="https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher">Reacher</a> environment provided by <a href="https://github.com/Unity-Technologies/ml-agents">Unity ML-agents</a>.


<br />
<br />
<p align="center"><img src="https://github.com/TheOnceAndFutureSmalltalker/deep_deterministic_policy_gradient/blob/master/images/reacher.gif" width="400px" /> </p>
<p align="center"><b>Double Jointed Arm Agents of Reacher Environment</b></p>



## Dependencies

To run this code, you must have Python 3.6, Jupyter, PyTorch, NumPy, and Matplotlib installed.  You must also have the 

## Instructions

Load the Jupyter Notebook file Navigation.ipynb and execute each cell in succession.  The last cell is the model training and may take several minutes to complete.
