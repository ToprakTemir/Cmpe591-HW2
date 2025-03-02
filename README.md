 # Cmpe591 Deep Learning for Robotics Project 2: 

# How to run:

HW2.py is the actual implementation of the homework, homework2.py is just the environment file. 

An example of creating a DQN, optionally loading already trained model, creating environment and plotting rewards is given in the __main__ block of the HW2.py.

train() function in the DQNAgent class automatically creates the necessary environment and trains a new model. test() function creates the environment in GUI mode and runs the trained model.

**Note:** I used high level state for observations, and used 50 step per episode.

Reward Plot:

![smoothed_reward_plot](https://github.com/user-attachments/assets/a8044eb9-1cbe-410f-8dfc-20100c5b3377)

RPS plot:

![smoothed_rps_plot](https://github.com/user-attachments/assets/d8bfcbb1-9667-40bd-9240-5de5c9b4a79e)

## Installation & Dependencies
I used a conda virtual environment for the project, exact environment details are given in the environment.yml file. 
For installing the virtual environment:

    conda env create -f environment.yml
