# RL_Blackjack_MiniProject
===========================

A Q-learning agent trained to play Blackjack using the Gym environment.

**Table of Contents**
--------------------

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Results](#results)
5. [Evaluation](#evaluation)
6. [References](#references)

**Introduction**
--------------

This project implements a Q-learning agent to play Blackjack, a popular card game. The agent uses the Q-learning algorithm to learn the optimal policy for playing the game.

**Installation**
--------------

No installation required! This project is a Python script that can be run directly.

**Usage**
------

To run the agent, simply execute the `blackjack_qlearning.py` script:
```bash
python blackjack_qlearning.py
```
This will train the agent for 50,000 episodes and evaluate its performance.

**Results**
---------

Here's a plot showing the average rewards earned by the agent over time:

![Average Rewards](./results/average_rewards.png)

**Evaluation**
------------

The agent was evaluated by playing 1,000 episodes and recording the number of wins, losses, and draws:

| Metric | Value |
| --- | --- |
| Wins | 420 |
| Losses | 280 |
| Draws | 300 |

**References**
------------

* [Gym: A Toolkit for Reinforcement Learning](https://gym.openai.com/)
* [Q-Learning Algorithm](https://en.wikipedia.org/wiki/Q-learning)
* [Blackjack Rules](https://en.wikipedia.org/wiki/Blackjack)

**License**
---------

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

**Author**
--------

[Your Name]
```
You can copy-paste this into your README file and customize it to fit your project's needs.
