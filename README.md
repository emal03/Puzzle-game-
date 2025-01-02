# Puzzle-game-
Knights and Knaves Puzzle Solver

This repository holds the Python code for a solver of ‘Knights and Knaves’ problems from a course in logical reasoning. In these puzzles each character in a fictional island is either a Knight-a person who always speaks truth, or a Knave-a person who always lies. The exercise entails finding out the real nature of a character from statements made in particular scenarios.

Code Overview
Logical Rules:
A and B are two characters like two players, they each of which can be either a knight or a knave, but not both.
The relations of puzzling (Implication) and the negations (Not); are used to express the rule for the Across puzzle play and the two characters’ statements.
Knowledge Base:
The knowledge base for each of the puzzles contains all the logical relations and consequences that concern the nature of each of the characters.
Main Functionality:
The main() function goes through a set of given puzzles and checks, which of the TM logical models meet the constraints applied by the model_check() function.
In each case, it determines which of the characters is a knight or knave in compliance with the knowledge base which it has accumulated.
How It Works
Define Rules: The rules for the puzzles are stated by propositions (AKnight, AKnave and so on) and relation Between propositions with the assistance of operations Or, And, Not, Implication.
Solve Puzzles: The script loops through the record of total knowledge base possessed by each puzzle and uses simple models as the parameter to work out for the solution.
Output Results: The solutions are output for each puzzle, denoting the identity of each character: knight or knave.
