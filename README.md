# 🧠 Quiz Time! — JS Quiz Engine

A fun, browser-based quiz game built with **Vanilla JavaScript**, **HTML5**, and **CSS3**. Test your programming & tech knowledge across 20 questions, with randomized order every round and a persistent high score.

---

## 🚀 Live Demo

> _Open `index.html` in any browser — no setup needed!_

---

## ✨ Features

- 🎲 **Randomized Questions** — 10 questions pulled randomly from a pool of 20 each round
- 🔀 **Shuffled Answers** — answer order is randomized so you can't memorize positions
- ✅ **Instant Feedback** — correct/incorrect answers highlighted immediately after selection
- 📊 **Progress Bar** — tracks how far through the quiz you are
- 🏆 **High Score Tracking** — saved locally via `localStorage` so it persists between sessions
- 📱 **Responsive Design** — works on mobile and desktop
- 🎨 **Clean UI** — warm colour palette with smooth hover and transition effects

---

## 🗂️ Project Structure

```
quiz-game/
├── index.html      # Main HTML structure (3 screens: Start, Quiz, Results)
├── style.css       # Styling, responsive layout, colour themes
└── script.js       # All game logic — shuffling, scoring, state management
```

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) | Page structure & screen layout |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) | Styling, animations, responsive design |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Game logic, DOM manipulation, localStorage |

---

## ⚙️ How It Works

1. **Start** — Click _Start Quiz_ to kick off a randomized 10-question round
2. **Answer** — Pick from 4 options; the correct answer highlights green, wrong ones highlight red
3. **Progress** — Watch the bar fill as you move through questions
4. **Results** — See your score, a performance message, and your all-time high score
5. **Restart** — Jump straight back in with a freshly shuffled set

---

## 📋 Question Topics

The question bank covers a range of beginner-to-intermediate tech topics:

- 🖥️ Programming fundamentals (variables, booleans, algorithms, debugging)
- 🌐 Web development (HTML, CSS, JavaScript, HTTP status codes)
- 🔧 Software concepts (APIs, servers, databases, version control, deployment)
- 📖 General tech knowledge (open-source, UI/UX, README files)

---

## 💾 High Score Persistence

High scores are saved using the browser's `localStorage` — so even after closing the tab, your best score sticks around.

```javascript
localStorage.setItem("high-score", highScore);  // Save
localStorage.getItem("high-score");              // Retrieve
```

---

## 🏃 Getting Started

No installs. No dependencies. Just clone and open.

```bash
git clone [https://github.com/chaitanyaCE/Quiz-Game.git](https://chaitanyace.github.io/JS-Quiz-Engine/)
cd quiz-game
```

Then open `index.html` in your browser — that's it!

---

## 🔮 Possible Future Improvements

- [ ] Timer per question ⏱️
- [ ] Category filtering 🗂️
- [ ] Difficulty levels 🎯
- [ ] Sound effects 🔊
- [ ] Leaderboard with player names 🏅

---

## 👤 Author

**Chaitanya**
- 🔗 [LinkedIn]([https://www.linkedin.com/in/your-profile](https://www.linkedin.com/in/chaitanya-patel-uwaterloo/))
- 🐙 [GitHub](https://github.com/chaitanyaCE)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
