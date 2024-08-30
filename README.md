# Markov Decision Process Simulator

This repository contains a simulator for Markov Decision Processes (MDPs) built using JAX. It leverages features such as Just-In-Time (JIT) compilation and XLA (Accelerated Linear Algebra) to optimize performance and facilitate rapid prototyping.

## Overview

The simulator includes various components for defining, training, and testing reinforcement learning agents within MDP environments. The primary focus is on implementing DQN (Deep Q-Network) algorithms to showcase reinforcement learning techniques.

## Directory Structure

- **dqn_agent.py**: Contains the implementation of the DQN agent.
- **environment.py**: Defines the MDP environment for the agent to interact with.
- **help.txt**: Additional information and resources regarding the project.
- **LICENSE**: The license under which the project is distributed.
- **logs.txt**: Logs generated during the training process for analysis.
- **pyproject.toml**: Project configuration file for dependencies and setup.
- **README.md**: This readme file providing an overview of the project.
- **requirements.txt**: This file contains all pip packages
- **results/**: Directory containing results of experiments and model outputs.
- **run.ipynb**: Jupyter notebook for running simulations and visualizing results.
- **scratch.ipynb**: A notebook for experimentation and prototyping.
- **train.ipynb**: Jupyter notebook for training the DQN agent.
- **train.py**: Script for training the DQN agent.

## Getting Started

To get started with the MDP simulator, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mdp-jax.git
   cd mdp-jax
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the training script:
   ```
   python train.py
   ```

4. Explore the Jupyter notebooks (`run.ipynb`, `train.ipynb`, `scratch.ipynb`) for interactive experimentation and analysis.

## Features

- Just-In-Time Compilation for performance optimization.
- Implementation of the DQN algorithm for reinforcement learning.
- Easy-to-use environment setup for testing different scenarios.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Developed by Tarek

