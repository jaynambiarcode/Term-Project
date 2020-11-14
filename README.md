# Term-Project
The main goal here is to create a “guess the word” game. It has certain key things one needs to note.   The user needs to be able to input letter guesses. A limit should also be set on how many guesses they can use. Keep notifying the user of the remaining turns.



The main function is been defined, that intializes global count, global display, global word, global already_guessed, global length and global play_game.

They can be used in the other parts as functions too.
Words_to_guess, Contains all the Hangman words we want the user to guess in the game.
We use the random module in this variable to randomly choose the word from words_to_guess in the game.


Already_guessed: This would contain the string indices of the correctly guessed words. The play_loop function takes in the argument of play_game.

The Play_game, argument is used to either continue the game after it is played once or end it according to what the user suggests.


The While loop is used to execute the play_game argument. It takes the parameter, y=yes and n=no. If the user gives an input of something else other than y/n, it asks the question again for the appropriate answer. If the user inputs “y”, the game restarts, otherwise the game ends.


