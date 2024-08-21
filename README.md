
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

