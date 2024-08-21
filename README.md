
# 🐍 Python Projects Collection

## 📧 Email Slicer
This Python script is a simple tool to slice an email address into its username and domain parts. The script takes an email address as input and splits it using the "@" symbol, returning the username and domain separately.

**How It Works:**
- The `slice_email` function takes an email address as an argument.
- It uses the `split()` method to divide the email into two parts: the username and the domain.
- The script then prints the extracted username and domain in a formatted output.

**Usage:**
- Run the script.
- Enter the email address when prompted.
- The script will output the username and domain separately.

**Example:**
Enter your email address: example@domain.com
Username: example
Domain: domain.com

---

## 🔄 Palindrome Checker
This Python script checks whether a given word or phrase is a palindrome. A palindrome is a sequence of characters that reads the same forward and backward, ignoring spaces and case.

**How It Works:**
- The `is_palindrome` function takes a string as input.
- It removes any spaces and converts the string to lowercase for a uniform comparison.
- The function then checks if the string is equal to its reverse using Python's slicing feature.
- Based on this check, the script will print whether the input is a palindrome or not.

**Usage:**
- Run the script.
- Enter a word or phrase when prompted.
- The script will determine if it's a palindrome and display the appropriate message.

**Example:**
Enter a word or phrase: A man a plan a canal Panama
It's a palindrome!

---

## ❓ Quiz Game
This Python script is a simple quiz game that tests your knowledge on various topics. The game presents a series of questions to the user and evaluates their answers, keeping track of the score.

**How It Works:**
- The quiz consists of a list of dictionaries, where each dictionary contains a question and its corresponding answer.
- The script iterates through each question, prompting the user to enter their answer.
- The user's input is compared to the correct answer (case-insensitive).
- The script provides feedback on whether the user's answer is correct and updates the score accordingly.
- At the end of the quiz, the total score is displayed.

**Usage:**
- Run the script.
- Answer each question when prompted.
- The script will inform you if your answer is correct and keep track of your score.

**Example:**
What is the largest planet in our solar system?
Enter your answer: Jupiter
Correct!

Who painted the famous artwork 'The Starry Night'?
Enter your answer: Van Gogh
Correct!

What is the chemical symbol for gold?
Enter your answer: Ag
Sorry, the correct answer was Au

**Features:**
- Case-insensitive answer checking.
- Instant feedback after each question.
- Score tracking to see how well you performed.

---

## 🔐 Secret Message Encryption and Decryption Tool
This Python project offers a simple yet effective way to encrypt and decrypt messages. It uses a character-shifting technique, where each character in the message is shifted by a user-specified key to create an encrypted version. The same key is used to decrypt the message, returning it to its original form.

**How It Works:**
- **Encryption:**
  - The `encrypt` function shifts each character in the message by the key value using its ASCII code.
  - The result is a scrambled (encrypted) message that can only be deciphered by knowing the key.

- **Decryption:**
  - The `decrypt` function reverses the encryption process by shifting each character back by the key value.
  - The output is the original message.

**Usage:**
- **Encryption:**
  - Run the encryption script.
  - Input the message you wish to encrypt.
  - Choose a secret number as the key for encryption.
  - The script will output the encrypted message.
Write your secret message: Hello World
Choose a secret number: 3
Encrypted message: Khoor#Zruog

- **Decryption:**
  - Run the decryption script.
  - Input the encrypted message.
  - Enter the same key used during encryption.
  - The script will output the decrypted (original) message.
Write your encrypted message: Khoor#Zruog
Enter your secret number again: 3
Decrypted message: Hello World

**Features:**
- **Custom Encryption Key:** Allows users to select their own key for message encryption.
- **Simple Decryption Process:** Users can decrypt the message using the same key, restoring the original message.
- **Educational Tool:** This project is an excellent introduction to basic encryption techniques, ideal for beginners learning about Python and cryptography.

---

## 🔢 Fibonacci Sequence Generator
This Python script generates a sequence of Fibonacci numbers. The Fibonacci sequence is a series of numbers in which each number (after the first two) is the sum of the two preceding ones, typically starting with 0 and 1.

**How It Works:**
- The `fibonacci` function takes an integer `n` as input, representing the number of Fibonacci numbers to generate.
- It initializes a list with the first two Fibonacci numbers: `[0, 1]`.
- The function then iteratively computes the next numbers in the sequence by summing the last two numbers in the list and appending the result.
- The final list of `n` Fibonacci numbers is returned.

**Usage:**
- Run the script.
- Input the number of Fibonacci numbers you want to generate.
- The script will output the sequence of Fibonacci numbers.

**Example:**
Enter the number of Fibonacci numbers to generate: 10
[0, 1, 1, 2, 3, 5, 8, 13, 21, 34]

**Features:**
- **Dynamic Length:** Generate as many Fibonacci numbers as needed by specifying the desired length.
- **Efficient Calculation:** The script efficiently computes the sequence using iteration and list indexing.

---

## 🎯 Guess the Number Game
This Python script is a simple number-guessing game where the player has to guess a randomly generated number between 1 and 20. The game provides feedback after each guess, guiding the player towards the correct number, and tracks the player's score based on the number of attempts.

**How It Works:**
- The script generates a random number between 1 and 20 using the `random.randint()` function.
- The player has up to 6 attempts to guess the correct number.
- After each guess, the script provides feedback:
  - If the guess is correct, the player wins ("BINGO!!") and the game displays the player's score.
  - If the guess is too high, the script suggests trying a lower number.
  - If the guess is too low, the script suggests trying a higher number.
- The player's score starts at 60 and decreases by 10 points with each incorrect guess.
- The player can choose to continue or exit the game after each guess.

**Usage:**
- Run the script.
- Input your guess when prompted.
- The script will provide feedback and, if necessary, prompt you to guess again.
- If you guess the correct number, the game will display your score. You can continue playing or exit the game based on your choice.

**Example:**
Guess the number b/w 1-20: 15
Guessing high...Try with a lower number..

Guess the number b/w 1-20: 10
Guessing low...try with a higher number..

Guess the number b/w 1-20: 12
BINGO!! Score: 40

**Features:**
- **Random Number Generation:** Ensures each game is unique by generating a new random number each time.
- **Score Tracking:** The game rewards players for guessing the correct number in fewer attempts.
- **User-Friendly Interface:** Provides clear feedback and allows players to continue or exit the game based on their preference.

---

## ➗ Python Calculator Programs
This repository contains various Python scripts that implement basic and scientific calculators. These calculators perform a range of arithmetic operations, from simple addition and subtraction to more complex calculations like exponentiation and modulus.

### Simple Calculator:
- Performs basic arithmetic operations: addition, subtraction, multiplication, and division.
- User inputs two numbers and selects the operation they wish to perform.

**Example:**
Enter first number: 10
Enter second number: 5
Enter choice (1/2/3/4): 1
Output: 15

### Program Calculator:
- Similar to the Simple Calculator but accepts floating-point numbers and includes an additional option for exponentiation.

**Example:**
Enter first number: 2.5
Enter second number: 4.0
Enter choice (1/2/3/4/5): 5
Output: 39.0625

### Scientific Calculator:
- A more advanced calculator that allows for the addition, subtraction, multiplication, division, modulus, and exponentiation of three numbers.
- Includes error handling for division by zero.

**Example:**
Enter the first number: 10
Enter the second number: 2
Enter the third number: 5
Addition: 17.0
Subtraction: 3.0
Multiplication: 100.0
Division: 1.0
Modulus: 0.0

**Features:**
- **User Input:** All calculators prompt users to input numbers and select the desired operation.
- **Error Handling:** The calculators include basic error handling for invalid operations, such as division by zero.
- **Modular Design:** The scripts are modular, allowing for easy addition of new operations or modification of existing ones.


## 🔑 Random Password Generator
This Python script generates a secure, random password based on user-defined length. It uses a combination of letters, digits, and special characters to create a strong and unpredictable password.

**How It Works:**
- The `generate_password` function takes an integer `length` as input, which determines the number of characters in the password.
- The function combines letters (both uppercase and lowercase), digits, and punctuation symbols to form a pool of possible characters.
- A password is generated by randomly selecting characters from this pool until the desired length is reached.
- The generated password is then returned and displayed to the user.

**Usage:**
- Run the script.
- Input the desired length for the password when prompted.
- The script will generate and display a random password of the specified length.

**Example:**
Enter password length: 12
Generated Password: &aT4k9*ZmVq#

**Features:**
- **Customizable Length:** Users can specify how long they want the password to be.
- **High Security:** The generated password includes a mix of uppercase and lowercase letters, numbers, and special characters, ensuring strong security.
- **Simple and Fast:** The script quickly generates a secure password with minimal input required.

This project is ideal for anyone looking to enhance their understanding of Python's `random` and `string` modules, while also creating a practical tool for generating secure passwords.

---

## 🎲 Pig Game
This Python project implements a text-based version of the classic "Pig" dice game. The game is designed to be versatile, offering different modes of play, including single-player, multiplayer, challenge mode, and a tournament format.

### Game Modes:
- **Single-Player Mode:** A single player rolls a die to reach a target score. The player can choose to keep rolling or hold, but if they roll a 1, their turn ends and they lose any points accumulated in that turn.
- **Multiplayer Mode:** Multiple players take turns rolling the die. Players can decide to keep rolling or hold, and the first player to reach the target score wins. The number of players is determined by the user.
- **Challenge Mode:** A single player plays against a custom target score. This mode adds an extra level of difficulty by allowing the player to set a challenging score to beat.
- **Tournament Mode:** Multiple players compete in a series of matches to determine the overall winner. Each player plays individually, and the scores are compared at the end to rank the players.

**How It Works:**
- The game simulates rolling a six-sided die using Python's `random.randint()` function.
- Each player accumulates points based on the die rolls. If a player rolls a 1, their turn ends, and they lose all points for that round. The player can choose to hold (end their turn voluntarily) to bank their points.
- The first player to reach or exceed the target score wins the game.

**Usage:**
- Run the script.
- Select the desired game mode (Single, Multi, Challenge, or Tournament).
- Follow the on-screen prompts to roll the die and accumulate points. The game continues until a player reaches the target score.

**Example:**
Select game mode: (1) Single, (2) Multi, (3) Challenge, (4) Tournament: 1
Player 1 rolled a 5
Player 1's current score: 5
Player 1, roll again? (y/n): y
Player 1 rolled a 3
Player 1's current score: 8
Player 1, roll again? (y/n): n

**Features:**
- **Multiple Game Modes:** Choose from single-player, multiplayer, challenge, or tournament modes.
- **Customizable Target Score:** In challenge mode, set a target score to increase the difficulty.
- **Tournament Play:** Compete in a series of matches to determine the ultimate winner.

This project is a fun way to explore Python programming, especially in working with loops, conditional statements, user input, and random number generation.

---

## 🏞️ Text-Based Adventure Game
This Python script creates a simple text-based adventure game where players make choices to navigate through a cave and experience different outcomes. The game provides a basic interactive storyline where decisions impact the progress and ending of the adventure.

**How It Works:**
- The game begins at the entrance of a cave, and the player is presented with choices on how to proceed. Depending on the player's decisions, different scenarios and outcomes are revealed:
  - **Enter the Cave:**
    - **Light a Fire:** Allows the player to see better in the cave and choose between following a path or returning to the entrance.
    - **Explore the Cave:** Leads to discovering a treasure and winning the game.
  - **Run Away:** Ends the game with the player running away from the cave.

**Gameplay:**
- The game starts by asking the player to choose between entering the cave or running away.
- If the player chooses to enter the cave, they are given further options:
  - Light a fire to reveal more options.
  - Explore the cave to find treasure.
- The game continues based on the player's choices until an end condition is reached.

**Example:**
Welcome to the adventure game! You are at the cave entrance. What do you want to do?

Enter the cave
Run away
You are inside the cave. What do you want to do?

Light a fire
Explore the cave
You explored the cave and found a treasure! Congratulations, you won!

**Features:**
- **Interactive Storyline:** Engage with a simple narrative where choices lead to different outcomes.
- **Multiple Scenarios:** Experience various endings based on player decisions.
- **User Input:** The game prompts players for input and responds dynamically to their choices.

This project is a great introduction to Python programming, focusing on loops, conditional statements, and user interaction. It demonstrates how to build a basic interactive experience and can be expanded with more complex scenarios and choices.

---

## 📝 To-Do List Application
This Python script implements a basic To-Do List application, allowing users to manage tasks through a simple command-line interface. The application supports adding, displaying, and deleting tasks, making it a practical tool for organizing daily activities.

**Features:**
- **Show Tasks:** Displays the current list of tasks.
- **Add Task:** Allows the user to add a new task to the list.
- **Delete Task:** Enables the user to remove a task by specifying its number.
- **Quit:** Exits the application.

**How It Works:**
- **Initialization:** The `ToDoList` class initializes with an empty list of tasks.
- **Main Menu:** The `run` method provides a menu with options for the user to interact with the application:
  - **Show Tasks:** Prints the list of tasks.
  - **Add Task:** Appends a new task to the list.
  - **Delete Task:** Removes a task based on the user's input (task number).
  - **Quit:** Ends the application.

**Example Usage:**
- Run the script.
- Choose from the available options by entering the corresponding number:
  - Show tasks
  - Add task
  - Delete task
  - Quit

**Example:**
Show tasks
Add task
Delete task
Quit
Choose: 2
Task: Buy groceries

Show tasks
Add task
Delete task
Quit
Choose: 1
['Buy groceries']

Show tasks
Add task
Delete task
Quit
Choose: 3
Task #: 1

**Features:**
- **Simple Interface:** Easy-to-use command-line interface for task management.
- **Task Management:** Basic functionality for adding, viewing, and deleting tasks.

This project is a practical exercise in Python programming, demonstrating class creation, list manipulation, and user input handling. It's a good starting point for building more complex task management applications.

---

## 🔄 Unit Converter
This Python script provides a simple unit conversion tool, allowing users to convert between various units of measurement. The tool supports conversions between kilometers and miles, as well as between Celsius and Fahrenheit.

**Features:**
- **km to miles:** Converts kilometers to miles.
- **miles to km:** Converts miles to kilometers.
- **Celsius to Fahrenheit:** Converts Celsius temperatures to Fahrenheit.
- **Fahrenheit to Celsius:** Converts Fahrenheit temperatures to Celsius.

**How It Works:**
- The `convert_units` function presents a menu with conversion options.
- The user selects a conversion type by entering the corresponding number.
- Depending on the selection, the function prompts the user for input values and performs the appropriate conversion.

**Conversion Details:**
- **Kilometers to Miles (km-mi):** Conversion factor: 1 km = 0.621371 miles
- **Miles to Kilometers (mi-km):** Conversion factor: 1 mile = 1.60934 km
- **Celsius to Fahrenheit (C-F):** Conversion formula: `F = (9/5) * C + 32`
- **Fahrenheit to Celsius (F-C):** Conversion formula: `C = (5/9) * (F - 32)`

**Example Usage:**
- Run the script.
- Select the desired conversion type by entering the corresponding number.
- Input the value you wish to convert when prompted. The script will display the converted value.

**Example:**
Unit Converter
1 km-mi, 2 mi-km, 3 C-F, 4 F-C: 1
km: 5
5.0 km = 3.106855 miles

**Features:**
- **Simple Interface:** User-friendly command-line interface for unit conversion.
- **Multiple Conversions:** Supports conversions for distance and temperature units.

This project is a practical example of Python's ability to handle basic calculations and user input, making it an excellent exercise for beginners looking to create useful utilities.

