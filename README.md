# Q-Learning for Trading
Advanced Machine Learning – Lab 2

## Project Overview
This repository contains the work carried out for Lab 2 of the Advanced Machine Learning course.
The objective of this project is to apply Q-Learning, a reinforcement learning algorithm, to a simplified
trading environment in order to analyze agent behavior, learning dynamics, and decision-making performance.

The entire project is implemented and documented in a Jupyter Notebook.

## 🎯Objectives
- Implement the Q-Learning algorithm from scratch
- Model a trading environment using reinforcement learning concepts
- Define states, actions, and reward functions
- Train a learning agent through interaction with the environment
- Analyze and visualize learning performance and results

## 🧪Methodology
This project is based on reinforcement learning, where an agent learns an optimal policy by interacting
with an environment and maximizing cumulative rewards.

Key elements include:
- State space representing market conditions
- Action space (e.g., buy, sell, hold)
- Reward function based on trading outcomes
- Q-table updated using the Bellman equation
- Exploration vs exploitation strategy using an epsilon-greedy policy

## 📁Project Structure
q-learning-trading-lab/
- notebooks/
  - Advanced_ML_Lab2.ipynb
- requirements.txt
- .gitignore
- README.md

## ⚙️Requirements
- Python 3.9 or higher
- Jupyter Notebook

Install the required dependencies using:
pip install -r requirements.txt

## ⚙️Running the Project
Start Jupyter Notebook by running:
jupyter notebook

Then open the following file:
Advanced_ML_Lab2.ipynb

Execute the cells sequentially to reproduce the experiments and results.

## 🧪Experiments and Results
The notebook includes:
- Training of the Q-Learning agent
- Visualization of cumulative rewards
- Analysis of agent decisions over time
- Discussion of convergence behavior
- Interpretation of results and observed limitations

## Limitations
- The trading environment is highly simplified
- Transaction costs, slippage, and market impact are not modeled
- Results depend on hyperparameter selection
- This project is intended for academic and educational purposes only

## 🚀Future Work
Possible improvements include:
- Deep Q-Learning using neural networks
- More realistic market simulations
- Risk-aware reward functions
- Hyperparameter optimization
- Multi-asset trading environments

## Academic Context
This project was completed as part of the Advanced Machine Learning course.
It is intended solely for educational and evaluation purposes.
