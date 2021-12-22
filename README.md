# Lab04 Guide
## Getting Started
[Lab Introduction Video](https://youtu.be/O3VsbYU8ye0)

- Please clone the [Mod04 Code Examples](https://github.com/lhindman/cs121-mod04-examples.git).
- Please watch the [Activity 1 Walkthough Videos](https://www.youtube.com/playlist?list=PLbxWwkW_BhyAyktCxjjiuAu-hi5f3AFIh).  


### Code Style Requirements
Please review the [CS121 Style Guide](https://docs.google.com/document/d/1LWbGQBKkApnNAzzgwOSvRM03DmhYWx5yEfecT2WXfjI/edit?usp=sharing) and apply it in all lab activities and projects this semester. Coding Style will assessed as part of your lab and project grades.

### Code Quality Requirements
- Code must compile without warnings using openjdk11
- Code must run without errors or warnings on safe-path and edge test cases
- More to come as we learn about input validation and exception handling
## Activity 1 - LeapChecker
### Problem Description
Design and implement an application that reads an integer value representing a year from the user.  The purpose of the program is to determine whether the year is a leap year (and therefore has 29 days in February) in the Gregorian calendar.  A year is a leap year if it is divisible by 4, unless it is also divisible by 100 but not 400.  For example, the year 2003 is not a leap year, but 2004 is.  The year 1900 is not a leap year because it is divisible by 100, but the year 2000 is a leap year because even though it is divisible by 100, it is also divisible by 400. Produce an error message for any input value less than 1582 (the year the Gregorian calendar was adopted).

#### Sample Output
```
Enter a year: 1980
1980 is a leap year

Enter a year: 2020
2020 is a leap year

Enter a year: 1900
1900 is not a leap year

Enter a year: 2019
2019 is not a leap year
```
### Implementation Guide
1. Expand the folder named A1-LeapChecker and create a new file named LeapChecker.java
2. Design a program to satisfy the requirements in the Problem Description and enter the program code in LeapChecker.java
3. Test the program using the run link above the main method
4. Commit the changes to your local repository with a message stating that Activity 1 is completed.
5. Push the changes from your local repository to the github classroom repository.

## Activity 2 - EvenNumberSum
### Problem Description
Design and implement an application that reads an integer value and prints the sum of all even integers between 2 and the input value, inclusive. Print an error message if the input value is less than 2. Prompt accordingly.

#### Sample Output
```
Enter a positive integer: 100
The sum of the even integers from 2 to 100 is 2550

Enter a positive integer: 101
The sum of the even integers from 2 to 101 is 2550

Enter a positive integer: 2
The sum of the even integers from 2 to 2 is 2

Enter a positive integer: 1
The value must be greater than two.
```

### Implementation Guide
1. Expand the folder named A2-EvenNumberSum and create a new file named EvenNumberSum.java
2. Design a program to satisfy the requirements in the Problem Description and enter the program code in EvenNumberSum.java
3. Test the program using the run link above the main method. Carefully think about each of the different cases you'll need to test for to verify that the application is functioning properly.
4. Commit the changes to your local repository with a message stating that Activity 2 is completed.
5. Push the changes from your local repository to the github classroom repository.

## Activity 3 - HigherLower Game
### Problem Description
Design and implement an application that plays the Higher / Lower guessing game with numbers. The details for this activity are in the guide below:

[HigherLower Activity Guide](https://docs.google.com/document/d/1V6xuHAUCOLSEpzxm5OF1Vh3zcdgl2m78AIo3S-NFY_U/edit?usp=sharing)

### Impementation Guide
1. Expand the folder named A3-HigherLower and open the file named HigherLower.java
2. Modify the existing HigherLower.java program as specified in the HigherLower Activity Guide
3. Test the program using the run link above the main method
4. Commit the changes to your local repository with a message stating that Activity 3 is completed.
5. Push the changes from your local repository to the github classroom repository.


## Activity 4 - VowelCounter
### Problem Description
Design and implement an application that reads a string from the user and then determines and prints how many of each lowercase vowel (a,e,i,o, and u) appear in the entire string. Have a separate counter for each vowel. Also count and print the number of nonvowel characters.

#### Sample Output
```
Enter a string of characters:
Mississippi River

Number of each lowercase vowel in the string:
a: 0
e: 1
i: 5
o: 0
u: 0
other characters: 11


Enter a string of characters:
Life is like a box of chocolates, you never know what you're gonna get...

Number of each lowercase vowel in the string:
a: 4
e: 7
i: 3
o: 8
u: 2
other characters: 49
```
### Implementation Guide
1. Expand the folder named A4-VowelCounter and create a new file named VowelCounter.java
2. Design a program to satisfy the requirements in the Problem Description and enter the program code in VowelCounter.java
3. Test the program using the run link above the main method. Carefully think about each of the different cases you'll need to test for to verify that the application is functioning properly.
4. Commit the changes to your local repository with a message stating that Activity 4 is completed.
5. Push the changes from your local repository to the github classroom repository.

## Activity 5 - RockPaperScissors
### Problem Description
Design and implement an application that plays the Rock-Paper-Scissors game against the computer. When played between two people, each person picks one of three options (usually shown by a hand gesture) at the same time, and a winner is determined. In the game, Rock beats Scissors, Scissors beats Paper, and Paper beats Rock. 

The program should randomely choose one of the three options (without revealing it) and then prompt for the user's selection. At that point, the program reveals both choices and prints a statement indicating whether the user won, the computer won, or it was a tie. Continue playing until the user chooses to stop. Then print the number of user wins, losses, and ties.

#### Sample Output
```
Enter your choice - 1 for Rock, 2 for Paper, and 3 for Scissors: 2
My choice was Rock.
You win!

Play again (y/n)? y 

Enter your choice - 1 for Rock, 2 for Paper, and 3 for Scissors: 3
My choice was Rock.
I win!

Play again (y/n)? y

Enter your choice - 1 for Rock, 2 for Paper, and 3 for Scissors: 2
My choice was Scissors.
I win!

Play again (y/n)? y

Enter your choice - 1 for Rock, 2 for Paper, and 3 for Scissors: 1
My choice was Paper.
I win!

Play again (y/n)? n

You won 1 times.
You lost 3 times.
We tied 0 times.
```

### Implementation Guide
1. Expand the folder named A5-RockPaperScissors and create a new file named RockPaperScissors.java
2. Design a program to satisfy the requirements in the Problem Description and enter the program code in RockPaperScissors.java
3. Test the program using the run link above the main method. Carefully think about each of the different cases you'll need to test for to verify that the application is functioning properly.
4. Commit the changes to your local repository with a message stating that Activity 5 is completed.
5. Push the changes from your local repository to the github classroom repository.
