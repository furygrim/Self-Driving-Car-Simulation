# 🏎️ Self-Driving Car Simulation with DQN and CNN

This project simulates a self-driving car using a Deep Q-Network (DQN) combined with a Convolutional Neural Network (CNN) in the `CarRacing-v0` environment from OpenAI Gym. The agent learns to navigate a simulated track autonomously by leveraging reinforcement learning techniques to optimize its driving behavior.

## 🚀 Project Overview

The self-driving agent receives visual input from the environment and learns optimal actions—left, right, and straight—to stay on the track and maximize rewards. The DQN model uses a CNN to process the environment's pixel data, extract relevant features, and determine the best driving actions through trial and error.

## 📂 Project Structure

```plaintext
├── car_racing_dqn.ipynb       # Jupyter Notebook with complete code
├── README.md                  # Project documentation
└── dqn_car_racing.h5          # Saved model weights after training
