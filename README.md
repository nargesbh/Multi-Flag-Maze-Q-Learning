# Q-Learning Navigation in a Grid-World Maze

- [Overview](#overview)
  - [How It Works](#how-it-works)
- [Usage](#usage)
- [Requirements](#requirements)
- [Contact](#contact)

## Overview

This repository contains a Python implementation of Q-Learning for grid-world maze navigation. The goal is to train an agent to collect flags while avoiding obstacles. 

### How It Works

1. **Q-Table Initialization**: A Q-table is initialized with zeros, where rows represent actions (up, down, left, right), and columns represent states.

2. **Training**: In each epoch, the agent starts at the initial state and selects actions based on the Q-table. Actions are chosen randomly (exploration) with a given exploration rate or based on the highest Q-value (exploitation).

3. **Q-Table Update**: After taking an action, the agent moves to the next state, receives a reward, and updates the Q-value for the current state-action pair using the Q-Learning formula.

4. **Repeat Until Done**: Training continues until all flags are collected or a maximum number of epochs is reached.

5. **Display Q-Table**: Optionally, the final Q-table can be displayed if `show_q_table` is set to True.

## Usage

To use this implementation:

1. Clone the repository.
2. Adjust the maze, flags, hyperparameters, and other settings in the provided code to match your problem.
3. Run the code to train the agent and find the optimal policy.

## Requirements

Ensure you have the required packages installed:

```
pip install numpy networkx matplotlib
```




## Contact

For questions or feedback, contact [Narges Babaahmadi](mailto:nargesbabaahmadi7@gmail.com).


