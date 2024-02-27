# Q-Learning Pirate Maze

### What code were you given?
* I was given two .py files which contained one class, TreasureMaze.py, to represent the environment which includes a maze object defined as a matrix and a second class, GameExperience.py, that stores all of the states that come between the initial state and the terminal state. The provided .ipynb file contains all the code for setting up the parameters of the game such as the actions that can be taken by the agent, the structure of the maze matrix, and the code for the neural network layer model. The notebook file also provides an environment for testing the completed logic behind the Q-training algorithm code created by outputting the maze and the final path of the agent to the target cell.
  
### What code did you create yourself?
* I created the Q-learning implementation for finding the best possible navigation sequence that results in reaching the treasure cell while maximizing the reward. The implementation determines the optimal number of epochs to achieve a 100% win rate which turns out to be approximately epoch number 219 in my experiment. Additionally, I implement an update condition to reduce the epsilon or learning rate value as the model progresses through the iterations so that the agent can transition from random exploratory actions to value-based exploitation actions as the Q-values improve.

### What do computer scientists do and why does it matter?
*

### How do I approach a problem as a computer scientist?
*

### What are my ethical responsibilities to the end user and the organization?
*
