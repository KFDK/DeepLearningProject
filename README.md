# DeepLearningProject
Final project for 02456 Deep Learning at Technical University of Denmark

The title of the project is "GAMING IN 2020: COMPARING REINFORCEMENT LEARNING ALGORITHMS - PPO VS TRULY PPO". The corresponding paper can be downloaded here: . 

The project investigates and compares the two reinforcementlearning algorithms Proximal Policy Optimization (PPO) and an extension of it called Truly PPO on two Procgen atari-likegames, namely Starpilot and Chaser. The foundation of our work is by Y. Wang et al. from https://arxiv.org/abs/1903.07940. 

## Description of Files
**s174466_s174210_tr_ppo_rb.py:** The main script that trains and evaluates the agent. It can be used for both PPO and Truly PPO. All settings in terms of algorithm, environment, hyperparameters etc. are placed at the top of the code.  

**utils_savior.py:** A modified version of utils.py by Nicklas Hansen. It is a bunch of utility functions used for deep RL projects.  
