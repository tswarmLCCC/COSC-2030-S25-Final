# COSC-2030-S25-Final

nstructions
Final Introduction VideoLinks to an external site.

C++ Object-Oriented Programming Assignment: Poker Hand Simulator

Objective: The goal of this assignment is to familiarize you with object-oriented programming in C++. You will be implementing classes for a card, deck, and hand. The program will simulate drawing a hand of cards and evaluate the hand for common poker hands. It will then run a simulation of 500 draws and compute the odds of each hand.

Detailed Description:

Part 1: Card Class Create a Card class that represents a standard playing card. Each card has a rank (2-10, Jack, Queen, King, Ace) and a suit (Hearts, Diamonds, Clubs, Spades).
Part 2: Deck Class Create a Deck class that represents a deck of cards. The deck should contain 52 Card objects, one for each rank-suit combination. Implement a method to shuffle the deck and a method to draw a card from the deck.
Part 3: Hand Class Create a Hand class that represents a hand of cards. A hand is simply a collection of cards drawn from a deck. Implement a method to draw a hand of five cards from a deck.
Part 4: Poker Hand Evaluation Implement a method in the Hand class to evaluate the hand for the common poker hands (High Card, Pair, Two Pair, Three of a Kind, Straight, Flush, Full House, Four of a Kind, Straight Flush).
Part 5: Simulation
Write a main program that uses these classes to simulate drawing 500 hands. Compute and print the odds of each type of hand.

Deliverables:

Source code files for your classes and main program.
The source and output will be in your Final Project Replit
Grading Criteria: Correctness of the card, deck, and hand classes (60%) Correctness of the poker hand evaluation (20%) Correctness of the simulation and odds computation (20%)

 

Poker Hands Odds Table

| Poker Hand	   |  No. Ways	| Probability	| Odds against
| --------       | -------    | --------     | ------- |
 
| Royal Flush	| 4	| 0.00%	 |  649,739 to 1 |
| Straight Flush	| 40	| 0.00%	 |  72,192 to 1 |
| Four-of-a-Kind	| 624	| 0.02%	 |  4,165 to 1 |
| Full House	| 3,744	| 0.14%	   |  694 to 1 |
| Flush	| 5,108	| 0.20%	   |  509 to 1 |
| Straight	| 10,200	| 0.39%	   |  255 to 1 |
| Three-of-a-Kind	| 54,912	| 2.11%	   |  46 to 1 |
| Two Pair	| 123,552	| 4.75%	   |  20 to 1 |
| One Pair	| 1,098,240	| 42.26%	 |  1.37 to 1 |
| No pair/Highcard | 	1,302,540	| 50.12%	  | roughly 1 to 1 |
