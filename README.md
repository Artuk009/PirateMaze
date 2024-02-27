# Q-Learning Pirate Maze

### What code were you given?
* I was given two .py files which contained one class, TreasureMaze.py, to represent the environment which includes a maze object defined as a matrix and a second class, GameExperience.py, that stores all of the states that come between the initial state and the terminal state. The provided .ipynb file contains all the code for setting up the parameters of the game such as the actions that can be taken by the agent, the structure of the maze matrix, and the code for the neural network layer model. The notebook file also provides an environment for testing the completed logic behind the Q-training algorithm code created by outputting the maze and the final path of the agent to the target cell.
  
### What code did you create yourself?
* I created the Q-learning implementation for finding the best possible navigation sequence that results in reaching the treasure cell while maximizing the reward. The implementation determines the optimal number of epochs to achieve a 100% win rate which turns out to be approximately epoch number 219 in my experiment. Additionally, I implement an update condition to reduce the epsilon or learning rate value as the model progresses through the iterations so that the agent can transition from random exploratory actions to value-based exploitation actions as the Q-values improve.

### What do computer scientists do and why does it matter?
* Computer Scientists use the most relevant technologies and mathematical methods to create simple solutions to complex problems. This matters because there are many different questions in the world that have yet to be answered due to a lack of technological advances or computational capabilities regarding large-scale problems. For instance, big data only became recently accessible to humans because machine learning and data analytics techniques resulted in methods for parsing through and analyzing datasets with millions of entries with relative ease. Beforehand, the human eye could not make sense of data on such a large scale.

### How do I approach a problem as a computer scientist?
* I approach the problem first by establishing what that problem is and how it can be broken down into specific use cases. Then I reason out a theoretical solution to that problem that might cover the basis for all of the defined use cases. Next, I would establish a base case for which this theoretical solution could solve the problem (i.e. solve an example of the problem on a relatively small scale). Once the base case has proven successful using the proposed solution, we can then begin testing the solution on a case-by-case basis, try to find a contradiction to the proposed solution, or devise some sort of inductive process for continuous/infinite cases. Finally, our solution to the problem has either proven successful or requires reevaluation.

### What are my ethical responsibilities to the end user and the organization?
*
