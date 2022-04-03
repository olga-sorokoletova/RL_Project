# RL-2020/21: Markov Decision Processes

This is the homework of the RL 2020/21 course at Sapienza University of Rome.

## Task Assignment

1. **Implement the OpenAI Gym Atari environment** [MsPacman-v0](https://gym.openai.com/envs/MsPacman-v0/) (with static ghosts) using the same [interface as the one in Gym](https://gym.openai.com/docs/#environments) in Python according to the following specifications:

  * The environment is FULLY observable
  * No graphical rendering is needed
  * ONLY discrete states (i.e., instead of images, the real environment state are returned as observation)
  * A reduced state space (e.g., the state of the grid should is small - at most 10x10, the number of ghosts is adapted accordingly)
  * ONLY discrete actions
  * Except the agent (i.e., the player) everything is STATIC
  * A simple test program where an instance of the environment is created and a sequence of at least 5 random actions is executed while printing out the    observation

2. **Expose the transition model** from the environment to the agent, **implement the policy iteration algorithm** and run it on the environment.

## Implementation

The Jupiter Notebook with implementation is attached as [code.ipynb](https://github.com/olga-sorokoletova/Reinforcement-Learning/blob/main/Homework/code.ipynb).

## Author
- Olga Sorokoletova - 1937430
