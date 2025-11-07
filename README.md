# 🐍 Reinforcement Learning Snake Game

This project trains an AI agent to play the classic Snake game using **Reinforcement Learning**.

<p align="center">
  <img src="Demo%20Learning.gif" alt="Project Demo" width="600">
</p>

## 🤖 How It Works

This project uses a **Deep Q-Learning (DQN)** model to teach the AI (agent) how to play.

* **State Prediction:** The agent analyzes the current game state (e.g., snake's position, food location, and obstacles) to predict the best move.
* **Reward System:** The agent learns by receiving rewards. For example, it gets a positive reward for eating food and a negative reward (penalty) for hitting a wall or itself.
* **Experience Replay:** The agent stores its past experiences (state, action, reward, next state) in a memory buffer. During training, it samples random batches from this memory. This process helps the agent learn from a diverse set of experiences, leading to more stable and effective training.

## 🛠️ Tech Stack

* Python
* Pygame (for the game environment)
* PyTorch / TensorFlow (for the Deep Q-Network)
* NumPy
* Matplotlib (for plotting results)

*(Note: Please update this section with the specific libraries you used.)*

## 🚀 How to Run

### 1. Prerequisites

Make sure you have Python 3.x installed.

### 2. Clone the Repository

```bash
git clone [https://github.com/Jontybr18211/Reinforcement-Learning-Snake-Game.git](https://github.com/Jontybr18211/Reinforcement-Learning-Snake-Game.git)
cd Reinforcement-Learning-Snake-Game
