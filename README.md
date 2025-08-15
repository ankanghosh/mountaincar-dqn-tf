# mountaincar-dqn-tf
Reinforcement Learning (RL) with Deep Q-Network (DQN) using TensorFlow Agents (TF-Agents) to solve the MountainCar-v0 environment.

# About the project
This is a Google Colab notebook that implements and trains a DQN agent to solve the MountainCar-v0 RL environment using TF-Agents. The underpowered car is trained so that it learns to build momentum by oscillating between hills to reach a flag at the top. Training is performed over 150,000 iterations with periodic evaluation, and the final agent achieves near-optimal performance with an average return of approximately -114.9, consistently reaching the goal in around 115 steps (well below the 200-step limit).

### Key Features:
- **Epsilon-decay scheduling** for balanced exploration-exploitation.
- **Reward shaping** with custom wrapper providing position and velocity bonuses to accelerate learning.
- **Experience replay** using Reverb buffer with 100,000 transitions, uniform sampling, and First-In, First-Out (FIFO) eviction.
- **Dual Q-network architecture** with online and target networks for stable Temporal Difference (TD) learning.
- **Custom epsilon-greedy policy wrapper** for enhanced data collection during training.
- **Comprehensive visualization** with training progress charts and rendered video generation of agent behavior.
- **Hyperparameter optimization** including learning rate tuning, batch sizing, and network architecture design.
- **TensorFlow graph compilation** for optimized training performance.

# Tools Used
Tools and libraries used in this project include TensorFlow, Keras, TF-Agents, OpenAI Gym, Reverb, NumPy, Matplotlib, imageio, PIL, and pyvirtualdisplay.

# Who can benefit from the project?
Anyone can use the project to get started with the basics of RL or DQN using TensorFlow.

# Getting Started
Anyone interested in getting started with Machine Learning, Deep Learning, or Reinforcement Learning, specifically, Deep Q-Networks or classic control problems using TensorFlow and TF-Agents, can clone or download the project to get started.

# References
The most important points of reference for the project are as follows.
1. TensorFlow tutorial about training a DQN agent on the Cartpole environment using TF-Agents. Link [here](https://www.tensorflow.org/agents/tutorials/1_dqn_tutorial).
2. TensorFlow tutorial introducing RL and DQNs. Link [here](https://www.tensorflow.org/agents/tutorials/0_intro_rl).

# Additional Notes
1. The project is a basic one in nature and is not currently being maintained.
3. [Here](https://researchguy.in/reinforcement-learning-with-tensorflow-solving-mountaincar-v0-with-deep-q-network-using-tf-agents/) is the blog post covering this work.
