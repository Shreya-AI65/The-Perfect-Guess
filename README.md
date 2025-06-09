🎯 The Perfect Guess Game
Welcome to The Perfect Guess Game — a simple and fun number guessing game made with Python!
Test your intuition and see how many attempts it takes you to guess the right number. 💡

📜 How It Works
The computer randomly selects a number between 1 and 100.

You try to guess the number.

After each guess, the game gives you a hint:

🔽 "Lower number, please" if your guess is too high.

🔼 "Higher number, please" if your guess is too low.

Once you guess the correct number, it congratulates you and shows how many attempts you took.

📌 Code

import random
n = random.randint(1, 100)
a = -1
guesses = 1

while a != n:
    a = int(input("Guess a number: "))
    if a > n:
        print("Lower number, please")
        guesses += 1
    elif a < n:
        print("Higher number, Please")
        guesses += 1

print(f"You have guessed the number {n} correctly in {guesses} attempts.")

🚀 How to Run
Make sure Python is installed.

Copy the code into a file named perfect_guess.py.

Run it using:
python perfect_guess.py

🙌 What's Cool?
Basic use of Python's random module.

Interactive console input/output.

Simple control flow using while loops and if-else statements.

Great for Python beginners to understand loops, conditions, and user interaction.
