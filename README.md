## Hi there 👋, my name is Athmajan.

## 🙋🏽‍♂️ About Me
I am from Sri Lanka 🇱🇰, currently living in Oulu Finland 🇫🇮.  
I am an engineer with over 7 years of experience developing automation and digitization solutions in the telecommunications industry.  
  
I will soon receive a Master's Degree in Wireless Communications Engineering from the University of Oulu, where I have been exploring and studying applications of AI, RL and DL in Wireless Communications Networks.  
  
When I am not building dreams or volunteering to teach kids, you'll find me running outdoors 🏃🏽 - rain, shine, or snow!,  📺 Binge-watching Netflix's finest, and spending quality time with my beautiful wife Jero 🩵.

## 👨🏽‍💻 I am currently working on

[Adaptive multi-agent systems by modeling other agents' communications and actions.](https://github.com/ICONgroupCWC/chase-and-capture)  
- Discrete State/Action Spaces

<div style="display: flex; justify-content: space-around; align-items: center;" style="margin: 30px 0;">
    <img src="https://github.com/Athmajan/athmajan/raw/main/bert_marl.gif" alt="Adaptive Multi-Agent Systems" width="45%">
    <img src="https://github.com/Athmajan/athmajan/blob/main/30_15_30_Adapt.gif" alt="Adaptive Multi-Agent Systems" width="45%">
</div>  
_  

- Continuous State/Action Spaces
This is a work in Progress - I am extending the discrete results to continuous state and action spaces using the MPE gym environment.
On the left - Base Policy. On the right - Sequential Rollout.
<div style="display: flex; justify-content: space-around; align-items: center;" style="margin: 30px 0;">
    <img src="https://github.com/Athmajan/athmajan/blob/main/cont_action.gif" alt="Adaptive Multi-Agent Systems Continuous" width="45%">
</div> 

## 📚 I am currently learning
- [NVIDIA Sionna](https://nvlabs.github.io/sionna/index.html)
  ![NVIDIA](https://img.shields.io/badge/NVIDIA-Sionna-76B900?style=flat&logo=nvidia&logoColor=white)
  ![MATLAB](https://img.shields.io/badge/MATLAB-Channel%20Estimation-blue?style=flat&logo=mathworks&logoColor=white)  
  As a part of the coursework for 521322S Telecommunication Engineering Project, I am leveraging Sionna from NVIDIA Labs - the open-source library to simulate the physical layer of wireless systems.
  Specifically, I am attempting to implement OFDM signal with sync and explore channel and data estimation comparing results with implementations on MATLAB.

- [Building RAG Agents with LLMs](https://learn.nvidia.com/)
  ![NVIDIA](https://img.shields.io/badge/NVIDIA-Learning-76B900?style=flat&logo=nvidia&logoColor=white)


## Table of Contents
Here is a summary of my project compilation.
- [Python Automation Projects](#python-automation)
- RL, DL and ML
  - [Reinforcement Learning](#reinforcement-learning)
    - [World Models](#world-models)
    - [Multi Robot Repair](#multi-robot-repair)
    - [CartPole](#cartpole)
    - [Cleanup and Harvest - PPO Agents in MARL](#cleanup-and-harvest---ppo-agents-in-marl)
    - [DM Walker - Vanilla Policy Gradient Agent for Base Policy](#dm-walker---vanilla-policy-gradient-agent-for-base-policy)
    - [DM Walker - MPC on MPPI Agent with TD3](#dm-walker---mpc-on-mppi-agent-with-td3)
  - [Deep Learning](#deep-learning)
  - [Machine Learning](#machine-learning)

- Communication Networks
  - [Signal Processing](#signal-processing)
  - [Signal Detection and Estimation](#signal-detection-and-estimation)
  - [L1 Simulations](#l1-simulations)
  - [Network Virtualization and Containerization](#network-virtualization-and-containerization)
  - [Antenna Design](#antenna-design)

## Python Automation
- [Automated base station classifier/controller and email alerts](https://github.com/Athmajan/troposphere)
    <div style="display: flex; justify-content: space-around; align-items: center;" style="margin: 50px 0;">
    <img src="https://github.com/Athmajan/athmajan/blob/main/tropospheric.gif" alt="tropospheric prediction" width="70%">
    </div>
  
## Reinforcement Learning
- [World Models](https://github.com/ICONgroupCWC/worldmodels-ARM)  
  ![Python](https://img.shields.io/badge/Python-World_Models-blue?style=flat&logo=python&logoColor=white)
  ![Pytorch](https://img.shields.io/badge/PyTorch-VAE-orange?style=flat&logo=pytorch&logoColor=white)  

  Original implementation by [ctallec](https://github.com/ctallec/world-models)  
  My contribution is the compatibility with Apple Silicon processors.  
  
  Pytorch implementation of the "World Models" for ARM processors (Apple Silicon).
  I reimplemented the Paper: Ha and Schmidhuber, [World Models](https://doi.org/10.5281/zenodo.1207631) compatible with Apple Silicon processors.
  On the right, you can see the agent's regenerated dream of the real observation (left) by using the VAE.  
  <img src="https://github.com/Athmajan/athmajan/blob/main/VAE%20WM.gif" alt="Adaptive Multi-Agent Systems" width="500" style="margin: 20px 0;">

- [Multi Robot Repair](https://github.com/Athmajan/multi-robot-repair)  
  ![Python](https://img.shields.io/badge/Python-POMDP-blue?style=flat&logo=python&logoColor=white)  
  This is a work in progress. I am developing the simulator described in the [paper](https://arxiv.org/abs/2011.04222) - Multiagent Rollout and Policy Iteration for POMDP with Application to Multi-Robot Repair Problems.
  <br></br>
  <img src="https://github.com/Athmajan/multi-robot-repair/blob/main/robot-repair-simulator.gif" alt="robot repair" width="500" style="margin: 20px 0;">

- CartPole  
  ![AC](https://img.shields.io/badge/RL-AC-green?style=flat&logo=python&logoColor=white)
  ![DQN](https://img.shields.io/badge/RL-DQN-yellow?style=flat)  

  - [DQN Agent](https://github.com/Athmajan/dqn-cartpole)
    This is an attempt to understand how a DQN agent can be trained for a cartpole game.
  - [Vanilla Actor-Critic and PPO](https://github.com/Athmajan/actor-critic-methods)
    This is my attempt to understand how to train a vanilla actor-critic and PPO agent for a cartpole game.
  <br></br>  
  <div style="display: flex; justify-content: space-around; align-items: center;" style="margin: 50px 0;">
    <img src="https://github.com/Athmajan/athmajan/blob/main/cartpoleDQN.png" alt="DQN Cartpole" width="45%">
    <img src="https://github.com/Athmajan/athmajan/blob/main/AC_PPO_cartpole.png" alt="Adaptive Multi-Agent Systems" alt="AC and PPO Cartpole" width="45%">
  </div>

- [Cleanup and Harvest - PPO Agents in MARL](https://github.com/Athmajan/cleanup)  
  ![MARL](https://img.shields.io/badge/RL-MultiAgent-yellow?style=flat)  
  This is a self-study exploration of how to train PPO agents in a multi-agent setting.
  On the left you can see the PPO agents at work and on the right side compares to random actions.
  <br></br>
  <div style="display: flex; justify-content: space-around; align-items: center;" style="margin: 50px 0;">
    <img src="https://github.com/Athmajan/athmajan/blob/main/clearnup_PPO.gif" alt="PPO cleanup" width="500">
  </div>
  
- [DM Walker - Vanilla Policy Gradient Agent for Base Policy](https://github.com/Athmajan/walker-stand)  
  ![Google](https://img.shields.io/badge/DeepMind-PolicyGradient-yellow?style=flat)  
  This is a self-study of how to train a vanilla policy gradient agent that can be used as a base policy for running MPC later on.
  
- [DM Walker - MPC on MPPI Agent with TD3](https://github.com/Athmajan/walker-stand-mpc)  
  ![Pytorch](https://img.shields.io/badge/MPC-MPPI-orange?style=flat&logo=pytorch&logoColor=white)  
  This is a self-study of how to learn physics dynamics and a policy for walker-stand using TD3 and MPC based on MPPI.  
  Left - Vanilla PG Agent | Right - MPC Agent  
  <div style="display: flex; justify-content: space-around; align-items: center;" style="margin: 30px 0;">
    <img src="https://github.com/Athmajan/athmajan/blob/main/VanilaPG.gif" alt="Vanilla PG walker stand" width="45%">
    <img src="https://github.com/Athmajan/athmajan/blob/main/walkerMPC.gif" alt="MPC walker stand" alt="AC and PPO Cartpole" width="45%">
  </div>


## Machine Learning
- [Multi-Modal Physical Exercise Classification](https://github.com/Athmajan/MMDF)
  Decision-level fusion for multimodal classification. Feature extraction. Feature-level fusion.

## Deep Learning
- [Transfer Learning](https://github.com/Athmajan/DL-Transfer-Learning)
  A group project on transfer learning-based image classification for the course Deep Learning 2023.
  Collaborators :
  - Suranga Wengappuli Arachchige : suranga.wengappuliarachchige@student.oulu.fi
  - Madhusanka, Manimel Wadu : madhusanka.manimelwadu@oulu.fi
 
- [Linear Regression](https://github.com/Athmajan/DL-Linear-Regression)
  Load data and create a train/test split. Build a Pytorch model for a simple linear regression problem. Training the model with gradient descent algorithm in Pytorch.
  
- [Fashion-MNIST classification](https://github.com/Athmajan/DL-NN)
  Neural Network, Deep Neural Network, Loss Function and Optimization. Building a simple NN using numpy to understand the backpropagation. Gradient check using finite-difference approximation. Stochastic Gradient Descent (SGD). Regularization and simple hype-parameters tuning methods to improve NN performance.

- [CNN](https://github.com/Athmajan/DL-CNN)
- [Generative Adversarial Network](https://github.com/Athmajan/DL-GAN)

- [Neural Network from scratch](https://github.com/Athmajan/NN-simpl)
  An interesting approach to explaining neurons, layers, and how weights and biases work using basic principles. [YOUTUBE](https://www.youtube.com/playlist?list=PLQVvvaa0QuDcjD5BAw2DxE6OF2tius3V3)
  

  

## Signal Processing
- [Optimal Wiener Filter](https://github.com/Athmajan/SSP2-HW1)
- [Kalman Filter](https://github.com/Athmajan/SSP2-HW2)
- [Extended Kalman Filter](https://github.com/Athmajan/SSP2-HW3)
- [LMS Algorithm for Channel Equalizations](https://github.com/Athmajan/SSP2-HW4)
- [RLS Algorithm](https://github.com/Athmajan/SSP2-HW5)
- [Estimator Correlator](https://github.com/Athmajan/SSP2-HW6)
  
## Signal Detection and Estimation  
- [Efficient Signal Estimator by Monte Carlo Simulation](https://github.com/Athmajan/SSP1-HW1)
- [Maximum likelihood estimator. Linear Estimator](https://github.com/Athmajan/SSP1-HW3)
- [MLE and LSE Estimators](https://github.com/Athmajan/SSP1-HW4)
- [LMMSE Estimator. Signal Detection](https://github.com/Athmajan/SSP1-HW5)
- [Linear algebra, Probabilities, Multivariate densities, and Matrices](https://github.com/Athmajan/SSP1-HW2)

## L1 Simulations
- [Simulation of AWGN Channel](https://github.com/Athmajan/L1-AWGN)
- [BER Simulations on AWGN with BPSK](https://github.com/Athmajan/L1-BER)
- [Gray and Binary Coding with QPSK on AWGN](https://github.com/Athmajan/L1-Gray-Binary-Coding)
- [Adaptive Gain Controller for LTE20 Signal](https://github.com/Athmajan/L1-Adaptive-Controller-LTE20)
- [Ray Tracing](https://github.com/Athmajan/WC1-Lab/tree/main/Ray%20Tracing)
- [MPSK in AWGN Channel](https://github.com/Athmajan/WC1-Lab/tree/main/MPSK%20in%20AWGN%20Channel)
- [DPSK in Rayleigh Fading Channel](https://github.com/Athmajan/WC1-Lab/tree/main/DPSK%20in%20Rayleigh%20Fading%20Channel)
- [Maximal Ratio Combining for Diversity](https://github.com/Athmajan/WC1-Lab/tree/main/Maximal%20Ratio%20Combining%20for%20Diversity)
- [Channel Coding](https://github.com/Athmajan/WC1-Lab/tree/main/Channel%20Coding)
- [Convolutional Encoder and Decoder](https://github.com/Athmajan/WC1-Lab/tree/main/Convolutional%20Encoder%20and%20Decoder)
  
## Network Virtualization and Containerization
- [CoAP | IoT | Hypervisor](https://github.com/Athmajan/CN1-Lab)
- [Mininet](https://github.com/Athmajan/CN2-Lab)
  
## Antenna Design
- [Single Element Antenna and Antenna Array Design](https://github.com/Athmajan/antenna-design)

