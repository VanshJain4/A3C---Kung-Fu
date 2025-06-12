# 🥋 A3C Agent for Kung Fu Master (Atari)

This project implements an Asynchronous Advantage Actor-Critic (A3C) agent to play the Atari game **Kung Fu Master** using PyTorch and Gymnasium. The model learns from raw pixel input using convolutional layers and parallel environments for efficient training.

### 🚀 Highlights

- Preprocessing raw Atari frames (42x42 grayscale, 4-frame stacks)
- Deep CNN-based shared policy and value network
- Trained with A3C using 10 parallel environments
- Achieved 1000+ average reward within 3K training steps
- Real-time gameplay rendering after training

### 🧠 Tech Stack

- Python, PyTorch
- Gymnasium (`KungFuMasterDeterministic-v0`)
- OpenCV, ImageIO
- A3C architecture (actor-critic, entropy regularization)

