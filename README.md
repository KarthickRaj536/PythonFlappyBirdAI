## Python Flappy Bird AI
An AI which plays Flappy Bird, that finds the perfect way to get the maximum score.

![1](https://github.com/user-attachments/assets/67c435c8-7577-4b3d-ae4d-f027e11d659f)

## How to Play
1) First, download/fork the github on your PC.
2) Make sure all the files are extracted at the same place.
3) Open the main.py file and all dependencies/libraries mentioned in the program.
4) Now run the program

## Description
The objective in this game is to navigate the bird through gaps between pipes without colliding with them. The game utilizes the NEAT (NeuroEvolution of Augmenting Topologies) algorithm to train a neural network to control the bird automatically. The model used in this script is a feedforward neural network with a simple architecture that takes in four input features: the bird's x-coordinate, y-coordinate, velocity, and distance to the next pipe. The network consists of a single hidden layer with 10 neurons using sigmoid activation functions, and an output layer with 2 neurons also using sigmoid activation functions. The model is trained using the NEAT algorithm, which employs evolutionary principles to optimize the weights and connections between neurons. During training, each genome (neural network) is evaluated by simulating a game and calculating its fitness score based on its performance. The top-performing genomes are then selected for reproduction, and new offspring are generated through crossover and mutation to introduce diversity and improve performance. The process is repeated for multiple generations until a stopping criterion is reached, resulting in the fittest genome being used to play the game. This model uses a combination of evolutionary principles and machine learning techniques to train a neural network that can play Flappy Bird by making decisions based on the game state. 
