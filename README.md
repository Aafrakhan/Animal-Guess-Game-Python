# 🐾 Animal Guess Game

A simple command-line trivia game built in Python where players answer fun animal-themed questions and try to score as many points as possible. This was one of my early mini-projects while learning Python fundamentals.

## 📋 About the Project

Animal Guess Game is a text-based quiz that tests your knowledge of animal facts from the fastest land animal to the smallest creature on Earth. It was built to practice core Python concepts like functions, loops, conditionals, and global variables.

## ✨ Features

- 6 animal trivia questions covering fun facts (fastest, largest, smallest, longest, and heaviest animals)
- Up to 3 attempts per question before revealing the correct answer
- Case-insensitive answer checking
- Live score tracking throughout the game
- Final score summary at the end

## 🎮 How It Works

The game is powered by a `check_guess()` function that:
1. Takes the player's guess and compares it to the correct answer
2. Gives the player up to 3 attempts to get it right
3. Increases the score by 1 for each correct answer
4. Reveals the correct answer if all attempts are used

## 🚀 Getting Started

### Prerequisites
- Python 3.x installed on your machine

### Running the Game
1. Clone this repository
   ```bash
   git clone https://github.com/Aafrakhan/Animal-Guess-Game.git
   ```
2. Navigate to the project folder
   ```bash
   cd Animal-Guess-Game
   ```
3. Run the script
   ```bash
   python Animal_Guess_Game.py
   ```
4. Answer each question when prompted and see your final score at the end!

## 🖥️ Sample Gameplay

```
Guess the Animal
Which bear lives at the North Pole? tiger
Sorry Wrong Answer, try again bear
Sorry Wrong Answer, try again polar bear
Correct Answer
...
Your Score is 5
```

## 🛠️ Built With

- **Python** — core game logic, functions, loops, and conditionals

## 📚 What I Learned

This project helped me practice:
- Writing and calling custom functions
- Using global variables to track state across function calls
- Working with `while` loops and nested conditionals
- Taking and validating user input

## 👩‍💻 Author

**Aafra Khan**
GitHub: [@Aafrakhan](https://github.com/Aafrakhan)

⭐ If you liked this project, feel free to star the repo!
