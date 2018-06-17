# DQN-for-FlappyBird
An implementation of DeepMind's Deep-Q-Network agent to play the notorious FlappyBird game.

### Setting up the environment

Here are the steps that you need to follow to train or test the model in action. Just run the following commands:

* First make a python virtual environment

      virtualenv env -p python3

* Install the dependencies as listed in the requirements.txt

      pip install -r requirements.txt
      
* Run the python script `deep_q_network.py`, if you have checkpoints stored in the `saved_networks` directory, the latest checkpoint will be used to play the game.

      python deep_q_network.py
      
### Model used

Here is the model architecture that I used to train the model. The model was conceptualized by Deep Mind for playing ATARI Games. This architecture is based on that.

![Model Architecture](https://raw.githubusercontent.com/rtspeaks360/DQN-for-FlappyBird/master/assets/cnn-arch.png)

### Model in action / Gameplay

<img src="./assets/agent_demo.gif" width="200">

### What just happend?

This gif is a demo of the DQN Agent trained to play this game. To know about the DQNs try following this [blog post](https://ai.intel.com/demystifying-deep-reinforcement-learning/).
