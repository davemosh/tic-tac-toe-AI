# 🎮 Tic-Tac-Toe AI Game in Python

This is a 2-player Tic-Tac-Toe game built with **Python** and **Pygame**, where you play against an unbeatable **AI opponent** powered by the **Minimax algorithm**.

---

## 🧠 Features

- 🎯 Human vs AI gameplay
- 🧠 AI uses the **Minimax algorithm** (perfect play)
- ✅ Detects wins and draws
- 🔄 Press **R** to restart the game
- 🎨 Clean grid UI with colored win lines
- 🟢 Green: Player win, 🔴 Red: AI win, ⚪ Gray: Draw

---


## 🚀 How to Run

### Prerequisites:
- Python 3.x installed
- `pygame` library

### Install `pygame`:
```bash
pip install pygame
````

### Run the game:

```bash
python main.py
```

## 🎮 Controls

* **Mouse Click** to make your move
* **R Key** to restart the game

---

## 🏗️ Project Structure

```
tic_tac_toe/
│
├── main.py          # Game logic and main loop
├── README.md        # Project documentation
└── requirements.txt # Optional: add pygame here
```

---

## 🧠 AI Logic

The AI uses the **Minimax algorithm** to evaluate all possible future moves and always picks the best outcome. It cannot be defeated if it plays first or second.

---

## ✅ To Do / Ideas

* Add score tracking
* Add sound effects
* Add difficulty levels (Easy, Medium, Hard)
* Turn it into a web app using Flask or React + Flask backend

---

## 🧑‍💻 Author

Made with ❤️ by **David George**

---

pygame>=2.0.0
numpy>=1.20.0
