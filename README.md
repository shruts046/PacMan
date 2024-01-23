# PacMan
**Part 1: Search in Pacman**
Focuses on implementing various search algorithms to guide the Pacman agent through mazes for efficient food collection and goal-reaching. 
Key Components
search.py: Contains all search algorithms.
searchAgents.py: Contains search-based agents.
pacman.py: Main file to run Pacman games.
game.py: Logic behind Pacman world.
util.py: Useful data structures for search algorithms.
Objectives
Implement search algorithms: Depth-First Search, Breadth-First Search, Uniform Cost Search, and A* Search.
Apply these algorithms in various Pacman scenarios.
Develop a heuristic for the CornersProblem and FoodSearchProblem.

**Part 2: Multi-Agent Search**
The Pacman series introduces Multi-Agent Search, where we design agents for the classic version of Pacman, including ghosts. The project involves implementing adversarial search strategies like minimax and expectimax, and crafting evaluation functions for more efficient gameplay.
Key Components
multiAgents.py: Where we will write multi-agent search agents.
Pacman.py: This is the main file for running Pacman games and describing the GameState.
game.py: Contains the logic of the Pacman world.
util.py: Useful data structures for implementing search algorithms.
Objectives
Implement a Reflex Agent that considers both food and ghost locations.
Develop a Minimax agent capable of handling multiple ghosts.
Implement Alpha-Beta Pruning for efficient tree exploration.
Design an Expectimax agent to handle the probabilistic behavior of agents.
Craft a sophisticated evaluation function for game state assessment.

**Part 3: Reinforcement Learning**
Implemented value iteration and Q-learning. Testing agents on Gridworld, a simulated robot controller (Crawler), and Pacman. This project is designed to have hands-on experience with key concepts in reinforcement learning including value iteration, Q-learning, epsilon-greedy strategies, and approximate Q-learning.
Key Components
valueIterationAgents.py: Implementing a value iteration agent for solving known MDPs.
qlearningAgents.py: Developing Q-learning agents for Gridworld, Crawler, and Pacman.
analysis.py: Answering questions provided in the project.
mdp.py: General MDP methods.
learningAgents.py: Base classes for agents.
util.py: Useful utilities including util.Counter.
gridworld.py: Gridworld implementation.
featureExtractors.py: Feature extraction utilities for approximate Q-learning.
Objectives
Implementing a Value Iteration Agent.
Developing a Q-learning agent with update, computeValueFromQValues, getQValue, and computeActionFromQValues methods.
Implementing an epsilon-greedy strategy in your Q-learning agent.
Applying Q-learning to control Pacman in Gridworld.
Implementing an Approximate Q-learning agent that learns weights for features of states.

**Part 4: Ghostbusters**
Designing Pacman agents that use sensors to locate and eat invisible ghosts. This project dives into the world of Bayes Nets, allowing you to explore concepts such as exact and approximate inference in tracking multiple moving ghosts.
Key Components
bustersAgents.py: Containing agents for playing the Ghostbusters variant of Pacman.
inference.py: Coding for tracking ghosts over time using their sounds.
factorOperations.py: Operations to compute new joint or marginalized probability tables.
bayesNet.py: The BayesNet and Factor classes.
Objectives
Implementing Bayes Net structure and understanding the relationships between different variables.
Applying join and elimination operations on factors.
Utilizing variable elimination for probabilistic inference.
Developing methods for exact and approximate inference in dynamic scenarios.
Creating agents capable of tracking and hunting down ghosts based on sensor readings.


