# Q learning for simple atari game

This is a simple example of a type of [reinforcement learning](https://en.wikipedia.org/wiki/Reinforcement_learning)
called [Q learning](https://en.wikipedia.org/wiki/Q-learning). 

## Overview

We are building simple game and using Q-learning algorithm we built the bot which can able to will this simple game

	● Rules: The agent (yellow box) has to reach one of the goals to end the game 
	         (green or red cell).
	
	● Rewards: Each step gives a negative reward of -0.04. 
	           The red cell gives a negative reward of -1. 
	           The green one gives a positive reward of +1.
	           
	● States: Each cell is a state the agent can be.
	● Actions: There are only 4 actions. Up, Down, Right, Left.

## Dependencies

- Python 2.7
- tkinter

## Installation
- To install tkinter You need to execute this command: ```$ sudo apt-get install python-tk```

## Usage

Run `python Learner.py` in terminal to see the the bot in action. It'll find the optimal strategy pretty fast (like in 15 seconds)

## Credits

The credits for this code go to [PhillipeMorere](https://github.com/PhilippeMorere) and [joongwha](https://github.com/joongwha). I've merely created a wrapper to get people started.
