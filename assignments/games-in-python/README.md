# 🎮 Hangman Game Challenge

Build the classic word-guessing game using Python strings, loops, and user input.

## 📋 Overview
Create a fully functional **Hangman** game where players guess letters to reveal a hidden word before running out of attempts. This project reinforces core programming concepts through an engaging game.

**Estimated time:** 2-4 hours  
**Difficulty:** Beginner-Intermediate

## 🎯 Learning Objectives
- Master string manipulation and formatting
- Work with loops and conditional logic
- Handle user input with validation
- Use randomness and lists effectively
- Implement game state tracking and win/lose conditions

## ✅ Must-Haves (Core Requirements)
Your game must:

- Randomly select a word from a predefined list (at least 10-15 words)
- Display the current progress using underscore format (e.g., `_ _ A _ _ _`)
- Accept single letter guesses (handle uppercase/lowercase)
- Track remaining incorrect guesses (start with 6-8 lives)
- Prevent guessing the same letter twice
- End the game when the word is fully guessed or attempts are exhausted
- Display clear win or lose messages with the correct word

## 📌 Additional Features (Recommended for Full Credit)
- ASCII art hangman stages that update with each wrong guess
- Option to play again after game ends
- Difficulty levels (different word lists or number of attempts)
- Score tracking across multiple rounds

## 🧪 Testing & Validation
- Test with both winning and losing scenarios
- Handle invalid input gracefully (non-letters, multiple characters)
- Ensure no crashes on edge cases

## 📁 Starter Code & Files
- Create `hangman.py` as the main file
- (Optional) Separate `words.py` for the word list

## 📬 Submission
- Submit your `hangman.py` (and any additional files) via GitHub repository or zip file.
- Include a short `README.md` in your submission describing how to run the game.

## 📊 Rubric
| Criteria                    | Points |
|----------------------------|--------|
| Random word selection      | 15     |
| Display & progress update  | 20     |
| Guess handling & validation| 20     |
| Win/Lose conditions        | 15     |
| User experience & polish   | 15     |
| Code organization & comments | 15   |
| **Total**                  | **100**|

## 🔗 Resources
- Python `random` module documentation
- String methods reference
- Example word lists online

---

**Ready to build!** Start by creating the word list and the main game loop.