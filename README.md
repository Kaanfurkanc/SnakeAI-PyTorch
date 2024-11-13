# SnakeAI-PyTorch

This repository contains a reinforcement learning project that trains an AI agent to play the classic Snake game autonomously. Using Python, PyTorch, and Pygame, this project demonstrates how reinforcement learning techniques can be applied to train an AI agent to make real-time decisions and improve its gameplay.

## Project Overview

In this project, we use Deep Q-Learning (DQN), a popular reinforcement learning algorithm, to teach the AI agent to play Snake. The goal of the agent is to learn optimal strategies to grow as long as possible without colliding with the game boundaries or its own body.

The training process visualizes the agent's progress in two ways:
1. **Real-time Game Window**: Shows the current state of the game as the AI learns.
2. **Score Plot**: Displays the score and average score trend over the number of games, allowing you to track the agent’s performance improvement.

### Real-time Game Window
![Real-time Game Window](images/game.png)

### Score Plot
![Score Plot](images/plot.png)

## Features

- **Game Environment**: Implemented using Pygame to simulate the classic Snake game.
- **Reinforcement Learning Algorithm**: Uses Deep Q-Learning with experience replay to optimize the agent's performance.
- **Model Training**: The model is trained using PyTorch, leveraging GPU acceleration when available.
- **Dynamic Visualization**: Real-time visualization of the Snake game and agent’s decision-making process.

## Technologies Used

- **Python**: Main programming language used for the project.
- **PyTorch**: Deep learning framework to build and train the DQN model.
- **Pygame**: Library used for game development and visualization.
- **Matplotlib**: Library used for score and mean visualization.
