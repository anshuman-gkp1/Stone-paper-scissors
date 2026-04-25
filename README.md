# ✂️ Rock Paper Scissors

A classic **Rock Paper Scissors** browser game built with pure **HTML and JavaScript**. Play against the computer with real-time score tracking!

## 🎮 How to Play

1. Open the game in your browser
2. Click on **Rock 🪨**, **Paper 📄**, or **Scissors ✂️** image to make your move
3. The computer randomly picks its move
4. An alert shows the result and running score
5. Click **RESET** to clear the scoreboard and start fresh

## ✨ Features

- 🤖 **vs Computer** — Computer picks a random move every round
- 📊 **Score Tracking** — Live Wins / Losses / Ties counter
- 🔄 **Reset Button** — Clears the score to start over
- 🖼️ **Image-based Controls** — Click images to select your move (no buttons needed)
- ⚡ **Zero Dependencies** — Pure HTML + JS, works in any browser

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Page structure |
| Vanilla JavaScript | Game logic & score tracking |
| CSS (inline) | Basic layout |

## 🚀 How to Run

No setup required — it's a single HTML file!

```bash
git clone https://github.com/anshuman-gkp1/Stone-paper-scissors.git
cd Stone-paper-scissors
```

Then simply open `rock-paper-scissor.html` in any web browser.

## 🧠 Game Logic

```
Rock     beats Scissors
Paper    beats Rock
Scissors beats Paper
```

The computer uses `Math.random()` to generate a move with equal probability (~33% each).

## 📁 Project Structure

```
Stone-paper-scissors/
└── rock-paper-scissor.html   # Complete game (HTML + JS in one file)
```

## 🔮 Future Improvements

- Replace `alert()` with in-page result display
- Add animations for move selection
- Add best-of-5 mode
- Mobile-friendly responsive layout
