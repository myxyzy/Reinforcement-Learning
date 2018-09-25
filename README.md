# Reinforcement-Learning
**This project implements various reinforcement learning algorithms,
including state-of-art approaches DDPG and D4PG (incomplete), and use them
to solve a challenging balancing task. Moreover, a systematic comparison
among implemented algorithms is given.**

## Implemented algorithms

- Q Learning
- Policy Gradient
- Actor-critic
- Naive DQN (Deep Q-network)
- Prioritized DQN (DQN + Prioritized experience replay)
- Categorical DQN (DQN + Distributional perspective)
- Naive DDPG (Deep Deterministic Policy Gradient)
- Prioritized DDPG (DDPG + Prioritized experience replay)


## Dependency

- Ubuntu 14.04, 16.04
- Python 3.6, 3.5
- PyTorch v0.4.1
- OpenAI Gym (Classic control)
- PyBullet 2.1

## PyBullet task

It is basically a balance task for a 2-wheels robot. However, the robot needs not only to keep balance but also to come down a slope and climb another slope. The simulation is powered by pybullet. You can watch the full video [here](https://youtu.be/oOzKpN154ng).

![alt text](https://github.com/Lucas-ZhipengLiu/Reinforcement-Learning/blob/readme-edits/result%20images/9.gif)

## Results

Test and compare **DQN**, **Prioritized DQN** and **Categorical DQN** on OpenAI Gym CartPole-v1 task. 

![alt text](https://github.com/Lucas-ZhipengLiu/Reinforcement-Learning/blob/master/result%20images/3.png)

Test and compare **DQN**, **DDPG**, **Prioritized DDPG** on PyBullet task.

![alt text](https://github.com/Lucas-ZhipengLiu/Reinforcement-Learning/blob/master/result%20images/4.png)

## References

- [Playing Atari with Deep Reinforcement Learning](https://github.com/Lucas-ZhipengLiu/Reinforcement-Learning/blob/master/references/DQN.pdf)
- [Policy Gradient Methods for Reinforcement Learning with Function Approximation](https://github.com/Lucas-ZhipengLiu/Reinforcement-Learning/blob/master/references/Policy%20Gradient.pdf)
- [Deterministic Policy Gradient Algorithms](https://github.com/Lucas-ZhipengLiu/Reinforcement-Learning/blob/master/references/DPG.pdf)
- [CONTINUOUS CONTROL WITH DEEP REINFORCEMENTLEARNING](https://github.com/Lucas-ZhipengLiu/Reinforcement-Learning/blob/master/references/DDPG.pdf)
- [DISTRIBUTED PRIORITIZED EXPERIENCE REPLAY](https://github.com/Lucas-ZhipengLiu/Reinforcement-Learning/blob/master/references/d3pg.pdf)
- [DISTRIBUTED DISTRIBUTIONAL DETERMINISTIC POLICY GRADIENTS](https://github.com/Lucas-ZhipengLiu/Reinforcement-Learning/blob/master/references/D4PG.pdf)
- [PyBullet Quickstart Guide](https://github.com/Lucas-ZhipengLiu/Reinforcement-Learning/blob/master/references/pybullet%20quickstart%20guide.pdf)
- [DeepMind Control Suite](https://github.com/Lucas-ZhipengLiu/Reinforcement-Learning/blob/master/references/deepmind.pdf)
- [Deep Reinforcement Learning Hands-On](https://github.com/Lucas-ZhipengLiu/Reinforcement-Learning/blob/master/references/deep-reinforcement-learning-hands.pdf)
- [Morvan tutorials](https://morvanzhou.github.io/tutorials/machine-learning/reinforcement-learning/)
