# Chat Bot

This Kotlin program simulates a basic chatbot interaction, where the bot greets the user, guesses their age based on remainders, counts to a specified number, conducts a programming knowledge test, and ends the conversation.

## Features

- **Greeting**: The chatbot greets the user and provides information about itself.
- **Guess Age**: The bot asks the user for remainders when dividing their age by 3, 5, and 7, and then calculates their age using the Chinese Remainder Theorem.
- **Counting**: The bot counts to a specified number provided by the user.
- **Programming Knowledge Test**: The bot asks the user a multiple-choice question about programming methods and provides feedback on the answer.
- **Conclusion**: The bot ends the conversation with a congratulatory message.

## Usage

1. Run the program.
2. Follow the prompts to interact with the chatbot:
   - Enter your name when prompted.
   - Provide remainders when asked to guess your age.
   - Enter a number when prompted to count.
   - Answer the programming knowledge test question.

## Example

Hello! My name is Chat Bot.
I was created in 2023.
And what is your name?
John
Nice to meet you, John!
Do you like tricks?? Let me guess your age.
Enter remainders of dividing your age by 3, 5, and 7:
1
2
1
Your age is 22; that's a good time to start programming!
Now I will prove to you that I can count to any number you want.
5
0!
1!
2!
3!
4!
5!
Let's test your programming knowledge.
Why do we use methods?

To repeat a statement multiple times.
To decompose a program into several small subroutines.
To determine the execution time of a program.
To interrupt the execution of a program.
2
Congratulations, have a nice day!
markdown
Copy code

## Notes

- The chatbot program is implemented in Kotlin.
- Interaction with the chatbot occurs through console input and output.
- The program utilizes mathematical operations, loops, and conditional statements to simulate conversation and perform tasks.
- ------------------------------------------------

The following knowledge and concepts were utilized in writing this program:

Input/Output Handling: Interaction with the user occurs through console input/output, utilizing the Scanner class for input.

Functions: The program is divided into multiple functions, each responsible for a specific task such as greeting the user, guessing age, counting, conducting a test, and ending the conversation.

Mathematical Operations: Mathematical operations are used to guess the user's age based on remainders and to count numbers up to a given input.

Looping: The program utilizes loops, specifically a for loop, to count numbers up to a given input.

Conditional Statements: A while loop is used for the test section, where the program continues to prompt the user until the correct answer is provided.

Functionality Decomposition: The program decomposes its functionality into smaller, more manageable functions, enhancing code readability and maintainability.

These knowledge areas and concepts contribute to the functionality and interactivity of the chatbot program.
