# Slytherin-Game-using-Genetic-Algorithm

## AIM
Snake game have been around from the time when people started using mobile phones. People enjoyed playing it since the controls were only the four directional keys and the only objective was to collect the fruit to grow the snake’s length without colliding the snake's head with its body. Reinforcement learning though around from some time has started to find its application in tasks which try to computer to perform human capabilities. I thought the snake game would help us learn how to use reinforcement learning concepts and make the computer play the game by itself and try to beat a normal human score.

## SCOPE 
The scope of this project is to investigate the powers residing within genetic algorithms that can on its own solve complex problems. From simple games such as snake or tic-tac-toe to many complex applications like self-driving cars or AI-driven robots, genetic algorithms have the ability to reproduce human-like results or even better. It can work wonders with many problems  because it does not require any type  of training dataset, just a set of rules can help us solve the problem over a number of iterations. To implement the project it is essential to know the in’s and out’s of python through which we will code.

## PROJECT FLOW STRUCTURE
![project-flow](https://github.com/anshulp2912/Slytherin-Game-using-Genetic-Algorithm/blob/master/workflow_slytherin.png?raw=true)

### HUMAN Playable Game:
Library used:
- Pygame : pip install pygame
- Tkinter

  Just run the snake_pygame.py under Source/Human_game
  
### AI-Game using Genetic Algorithm:
Description of the working of each file under Source/AI_game:
- main.py -  to start training snake game using genetic algorithm
- Snake_Game.py  -  contains logic of creating snake game using pygame
- Run_Game.py  -  play snake game using predicted directions from genetic algorithm
- Genetic_Algorithm.py  -  contains genetic algorithm functions like crossover, mutation etc
- Feed_Forward_Neural_Network.py  -  contains the functions for calculating the output from feed forward neural network

Reference Blog: https://theailearner.com/2018/11/09/snake-game-with-genetic-algorithm/

## LIMITATIONS
- One of the major limitations, in the case of Machine Learning is the amount of time that it requires to train the model. The speed of other object oriented programming languages such as C++. Training over a large number of epochs makes a near perfect model. Nevertheless, a large number of epochs means more time to complete the learning process. 
- Another limitation is that the machine learning model is dependent on the fact that the device on which the model is being trained has a GPU or not. GPU embedded machines tend to have good performance while taking minimal training time. However, in the case of machines without GPU and only utilising CPU while other processes are active, the learning process could last as long as a day for even a less demanding model.
- Python is not a very good language for mobile development. In the snake game we are implementing, naturally, it would only make sense to deploy such a model in mobile phones or similar devices. This limitation of python hinders making better and efficient games.

