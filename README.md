<div align = "center">
![Image](https://github.com/user-attachments/assets/1ead9739-d694-4ab3-ba58-b5819492f4f6)

  
A classic children word guessing game implemented in C++
</div>

## Platform
This code has been compiled into many platforms depending on what OS you use.

### Windows
For Windows users, just run the executable and aterminal window will pop up.

### macOS
### Linux

## How to Play this Game?
If you have not played this game, here are the rules for it.

### High Level
- The program will pick a word at random based on the database. Each word will be masked under an underscore.
- The player wins if they can uncover all the alphabets and guess the word. 
- The player loses if they run out of life.
### Gameplay
- The player will guess a single letter, there is not limit of how many letters they can guess, but they are limited by the amount of life they have.
- If the player has already guessed the letter, it doesn't count. The player continues with the next letter.
- If any of the input matches the underscore, the underscores will be replace with that letter, the play continues.
- If none of the undersocres represent the letter, the player uses up one of its wrong guesses.
### Status
- The player will be shown how many lifes they have left (represented by '+').
- The player will be shown which letter they have guessed incorectly.
- There will be an internal list to keep track which letters the player have guessed.

### Error Input
- This program is also robust enough to account for invalid inputs.
- If more characters are keyed in, it will also be ignored.


