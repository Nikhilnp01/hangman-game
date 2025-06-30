# hangman-game
# Hangman Game

A classic Hangman word-guessing game built with Python.

## 🎯 Objective

Guess the hidden word one letter at a time. You have 6 chances before the hangman is fully drawn!

---

## 📦 Requirements

- Python 3.x
- A `words.json` file in the same directory with the following structure:

```json
{
  "word_list": ["python", "hangman", "developer", "function", "variable"]
}

🚀 How to Run
Clone or download the repository.

Make sure words.json is in the same folder as hangman.py.

Run the game using:

bash
Copy
Edit
python hangman.py
🎮 How to Play
Guess a letter or the entire word.

You have 6 wrong tries before the game ends.

You win if you guess the full word before the hangman is completed.

🔁 Replay
After finishing a game, you can choose to play again by entering Y.

📌 Example Output
arduino
Copy
Edit
Let's play Hangman!
_ _ _ _ _ _ _
Length of the word: 7

Please guess a letter or the word: e
Good job, E is in the word!
🛠️ Future Improvements
Add difficulty levels (Easy, Medium, Hard)

Add support for phrases

GUI version using Tkinter or PyQt
