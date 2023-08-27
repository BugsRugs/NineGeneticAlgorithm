# NineGeneticAlgorithm
Genetic algorithm designed to play the malaysian card game nine. 
The inspiration for this algorithm stemmed from the fact that there does not exists any information regarding odds charts or game theory relating to Nine. After thorough online research, it seemed the only way to know which strategies would be optimal for this game, was to use the brilliance of AI along with Google Collaboratory's GPUs to simulate games. The algorithm uses a random single gene crossover with random mutation for its "players", who are assigned random genes(traits) from their inception. Once players are initialized they play against a dealer, whose strategy is preset, with the aim of making the most "money" possible over hundreds of hands. The top two performers of each population are used to repopulate the next generation in order to repeat the process hundreds of thousands of times. After all games are simulated, the top performers genes are outputted as well as the amount of money they made against the dealer. 

## Code Structure
Imports and Initial Setup
Importing necessary libraries and setting up the initial environment.

Fitness Calculation
Defining the function to calculate the fitness score of a genome based on simulated card game hands.

Scoring Hands
Implementing the logic to score hands in the card game, considering different conditions and values.

Dealer's Strategy
Defining the dealer's strategy for hitting in the card game.

Player's Hit
Defining the logic for a player's hit action in the game.

Setting Hand Features
Setting up features for a player's hand to be used in the fitness calculation.

Dealing Cards
Implementing the card dealing process for both the player and the dealer.

Deck Generation
Generating a deck of cards with different suits and values.

Genome Initialization
Initializing random genomes for the population at the start of the genetic algorithm.

Reproduction and New Population
Defining the process of reproducing genomes and generating a new population.

Simulations and Algorithm
Running simulations using the genetic algorithm to optimize the strategy for playing the card game.

Main Execution
Generating a deck of cards and running the simulations using the defined functions and algorithm.
