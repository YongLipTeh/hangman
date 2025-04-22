<div align = "center">
  
![C++man](https://github.com/user-attachments/assets/a791b4a2-6c3c-4ac6-8b3a-3d847a834522)
  
A classic children word guessing game implemented in C++
</div>

## Platform
This code has been compiled into many platforms depending on what OS you use.

### Windows, macOS
For Windows and Mac, you can play the game by simply running, as long as the platform matches the file.

Intel Macs only support intel compiled programs while Apple Silicon Macs can only run M chips compiled program, please download the correct file.

### Linux
The program is compiled with Intel chip in Arch Linux. To run the program, open terminal, change the directory
```sh
$ cd ~/Downloads
```
Run it.
```sh
$ ./C++manLinux
```

## How to Play this Game?
If you have not played this game, here are the rules for it.

### High Level
- The program will pick a word at random based on the database. Each word will be masked under an underscore.
- The player wins if they can uncover all the alphabets and guess the word. 
- The player loses if they run out of life.
### Each turn
- The player will guess a single letter, there is no limit how many letters they can guess, but they are limited by the amount of life they have.
- If the player has already guessed the letter, it doesn't count. The player continues with the next letter.
- If any of the input matches the underscore, the underscores will be replace with that letter, the play continues.
- If none of the undersocres represent the letter, the player uses up one of its lifes.
### Status
- The player will be shown how many lifes they have left (represented by '+').
- The player will be shown which letter they have guessed incorectly.
- There will be an internal list to keep track which letters the player have guessed.

### Error Input
- This program is also robust enough to account for invalid inputs.
- If more characters are keyed in, it will also be ignored.

## Gameplay
The welcome screen so the player keyed in a letter.

![488-c++manpart5_m0DvbWffj7](https://github.com/user-attachments/assets/5c848426-d6aa-4f3c-add1-a8b105cba4bc)

The player picked a wrong letter.

![488-c++manpart5_H2kLp3o8ib](https://github.com/user-attachments/assets/4da5e483-ca12-44f1-92f2-cf8b4760633b)

The character is not a valid letter.


![488-c++manpart5_AeLPCl2z1Q](https://github.com/user-attachments/assets/4853039d-d44a-491f-8af4-5567b4174100)

The player has figured out all the letters

![Kd4vmZqOeq](https://github.com/user-attachments/assets/ae603bf8-0a0b-473a-9907-3bf1a9ebd609)


## Credits
This project is a solution to a guided problem provided in [learncpp](https://www.learncpp.com/cpp-tutorial/chapter-16-summary-and-quiz/).

The random number generator is part of the tutorial written by Alex. The code is fully written by me, although I was guided by the tutorial.
