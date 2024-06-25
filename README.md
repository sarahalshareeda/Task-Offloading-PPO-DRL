# Intelligent Task Offloading with Cognitive Generative Models for Vehicular Digital Twins
This repository contains the code and resources for implementing cognitive generative intelligent task offloading in digital twins for vehicular networks.
# Abstract
Vehicular Cognitive Digital Twins (DTs) are poised to become a cornerstone of the future metaverse for vehicular networks, facilitating seamless interaction between vehicles and their environments. This repository presents an intelligent Proximal Policy Optimization-Deep Reinforcement Learning (PPO-DRL) approach to evaluate Cloud-Twin, Edge-Twin, and Hybrid-Twin models for latency minimization. The code defines the environment states, task offloading decisions, computational resource allocation, and reward mechanisms to achieve optimal performance.

# Key Features
Cloud, Edge, and Hybrid Deployment Models:
- Evaluate the latency performance of different DT deployment models to find the optimal setup for varying network conditions.
- PPO-DRL Agents: Implement intelligent agents using PPO-DRL to optimize task offloading and resource allocation.
- Simulation and Hyperparameter Tuning: Includes extensive simulations and hyperparameter tuning for convergence and performance evaluation.

# Repository Contents
- src/: Source code for implementing the PPO-DRL models of task offloading algorithms.
- results/: Results from the simulations, including performance metrics and convergence analysis.

# Prerequisites
Python 3.11.3 and PyTorch 2.1.2

# Installation
Open a new terminal

Clone the repository:
- git clone https://github.com/sarahalshareeda/Task-Offloading-PPO-DRL.git. Now you have a folder called "Task-Offloading-PPO-DRL"

If any installation is needed for the imported libraries in the code, use:
- pip install the_lib_name

Running Simulations:
- Jupyter Notebook was used to write the code, so if you prefer to use it, go to https://jupyter.org/install to install Jupyter
- To run the simulations with default settings, then:
  1) change to the created directory: cd Task-Offloading-PPO-DRL
  2) then type: jupyter lab

Once your browser window opens, locate the src folder and click on the related "code" file you want to run. Under the src, these are the included "code" files:
- for obtaining best convergence parameters: cloud-twin-convergence.ipynb, edge-twin-convergence.ipynb, hybrid-twin-convergence.ipynb
- for latency vs network size: cloud-twin-delay_vs_n.ipynb, edge-twin-delay_vs_n.ipynb, hybrid-twin-delay_vs_n.ipynb
- for latency vs task size: cloud-twin-delay_vs_size.ipynb, edge-twin-delay_vs_size.ipynb, hybrid-twin-delay_vs_size.ipynb
- for latency vs data rate: cloud-twin-delay_vs_rate.ipynb, edge-twin-delay_vs_rate.ipynb, hybrid-twin-delay_vs_rate.ipynb

P.S. You can play and choose whatever hyperparameters, network size, task size, and data rates you want to experiment with.

# Author
Sarah Al-Shareeda
CAR-OSU USA
BTS-ITU Turkey
