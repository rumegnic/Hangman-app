# Hangman-app
Built a hangman game app in order to practice Collections framework(ArrayLists focused), exceptions,how handle errors and file handling.

-Pretty straight forward project that uses a .txt file with a few words for the hangman game

-Uses 2 functions: one that takes the words from the .txt file and another that stores one of the random words.

-start() function uses two char arrays:*one for the randomWord that is being converted to character array through .toCharArray() method
                                       *and another for storing '_' instead of characters, that will be replaced with the correct char when the user types it.
-using and infinite while loop to ask the user for input  for every single character
*if user loses -> numberOfChances-- and a message that informs the user that he/she ran out of chances and prints the word that was not guessed. 
*if user wins -> the _ in the guessingArray will be replaced with the correct character until the word is completed, thus user getting a congratulatoins message.
- the main method only has an object of type GameService(the class with all the necessary functions for the game) which calls the .start() method in order for the game to run, thus applying the Clean Code Principles in Java.
