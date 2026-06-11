# Task 02 — Number Guessing Game

A fun, interactive web-based number guessing game where the program generates a random number and challenges the user to guess it with helpful hints.

---

## 🎯 Features

- Randomly generates a number between 1 and 100
- 3 difficulty levels — Easy (15 tries), Medium (10 tries), Hard (5 tries)
- Tells you if your guess is too high or too low
- Visual range bar that narrows down after each guess
- Guess history log showing all previous attempts
- Tracks total wins and remaining attempts
- Press Enter or click Guess to submit

---

## 🌐 Live Demo
👉 [Click here to play the game](https://almasaji133-bytez.github.io/SCT_SD_2/number_guessing_game.html)

---

## 🚀 How to Run

1. Download or clone this repository
2. Open `number_guessing_game.html` in any web browser
3. No installation or internet connection required

---

## 📁 File Structure

```
Task-02-Number-Guessing-Game/
├── number_guessing_game.html    → Full app (HTML + CSS + JS)
└── README.md                    → Project documentation
```

---

## 🎮 How to Play

1. Select a difficulty level (Easy / Medium / Hard)
2. Type a number between 1 and 100 in the input box
3. Click **Guess** or press **Enter**
4. The program will tell you if your guess is too high or too low
5. Keep guessing until you find the number or run out of tries
6. Click **New Game** to play again

---

## 🔢 Program Logic

```
1. Generate a random number between 1 and 100
2. Prompt the user to enter a guess
3. Compare the guess to the generated number:
   - If guess == secret  → "Correct! You win!"
   - If guess < secret   → "Too low! Try higher."
   - If guess > secret   → "Too high! Try lower."
4. Repeat until correct guess or no tries remaining
5. Reveal the number if the user runs out of tries
```

---

## 🛠️ Technologies Used

- **HTML5** — Page structure
- **CSS3** — Styling and responsive layout
- **JavaScript (Vanilla)** — Game logic, random number generation, DOM manipulation

---

## 👨‍💻 Internship

**Organization:** SkillCraft Technology  
**Task:** 02 — Number Guessing Game  
**Intern:** [Your Name]
