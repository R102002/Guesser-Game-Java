# Guesser-Game-Java
Created guesser game in java


This Java code is for a guessing game. It has three classes: Guesser, Player, and Umpire.

The Guesser class takes a guess from the guesser and returns it.

The Player class takes a guess from the player and returns it.

The Umpire class collects the guesses from the guesser and three players, compares them, and outputs the result of the game. It has three methods: collectNumFromGuesser(), collectNumFromPlayers(), and compare().

The collectNumFromGuesser() method creates an object of the Guesser class, calls the guessingNumber() method to get the guess from the guesser, and stores it in the numFromGuesser variable.

The collectNumFromPlayers() method creates three objects of the Player class, calls the guessingNumber() method to get the guesses from three players, and stores them in the numFromPlayer1, numFromPlayer2, and numFromPlayer3 variables.

The compare() method compares the guesses from the guesser and the three players and outputs the result of the game based on the following conditions:

If the guess from the guesser is equal to the guess from player1 and player2 and player3, then all the players and the guesser are winners.
If the guess from the guesser is equal to the guess from player1 and player2, then player1 and player2 are the winners.
If the guess from the guesser is equal to the guess from player1 and player3, then player1 and player3 are the winners.
If the guess from the guesser is equal to the guess from player2 and player3, then player2 and player3 are the winners.
If the guess from the guesser is equal to the guess from player1, then player1 is the winner.
If the guess from the guesser is equal to the guess from player2, then player2 is the winner.
If the guess from the guesser is equal to the guess from player3, then player3 is the winner.
If the guess from the guesser is not equal to any of the guesses from the players, then all the guesses are incorrect and the players and the guesser have lost the game.

The LaunchGame class is the main class that runs the game. It creates an object of the Umpire class, calls the collectNumFromGuesser() method, the collectNumFromPlayers() method, and the compare() method to run the game, and outputs the result of the game.
