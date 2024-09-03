# 🦖 DINO Deep Reinforcement Learning Game

Welcome to the **DINO DRL Game**! This project implements a Deep Q-Network (DQN) using Gymnasium and Stable Baselines3 to train a DINO agent to play a custom game environment. Dive into the world of AI-powered gaming where the DINO learns to survive and thrive through the power of deep reinforcement learning.

## 🌟 Features

- **Custom Environment**: Built using Gymnasium, tailored to provide a unique challenge for the DINO.
- **Deep Q-Network (DQN)**: Utilizes the DQN algorithm from Stable Baselines3 for training the agent.
- **Training Visualization**: Watch as the DINO learns and improves its gameplay skills over time.
- **Modular Design**: Easily customizable environment and agent configurations.

## 🛠️ Installation

To get started with this project, follow the steps below:

### Prerequisites

- Python 3.10+
- Gymnasium
- Stable Baselines3
- OpenCV (for rendering)
- NumPy
- PyDirectInput (for giving updated state to model)
- mss (for screenshots)

### Setup

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/yourusername/dino-drl-game.git
cd dino-drl-game
```

Create a virtual environment and activate it:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## 📊 Results

- **Training Performance**: The training script logs the rewards and losses, which can be visualized using Matplotlib.
- **Gameplay Demo**: Observe how the DINO evolves from random actions to intelligent decisions, navigating the game environment with increasing proficiency.

## 🧩 Customization

- **Environment**: Modify `WebGame Class` to adjust the game mechanics, reward structure, or observation space.
- **Model Parameters**: Tweak the DQN hyperparameters in `dino_game_rl.ipynb` for experimentation and optimization.

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, submit issues, or make pull requests to improve the DINO DRL Game.

## 📞 Contact

For any inquiries, please reach out at ahmedmoiz962@gmail.com or connect via [LinkedIn](https://www.linkedin.com/in/moizahmed25/).
