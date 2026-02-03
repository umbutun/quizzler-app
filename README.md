# ❓ Quizzler App

A trivia quiz application that fetches questions from an API and tracks your score — built with Python, Tkinter, and OOP principles.

---

## Features

- **Live Questions:** Fetches trivia questions from Open Trivia Database API
- **True/False Format:** Simple, fast-paced gameplay
- **Score Tracking:** Real-time score updates
- **Visual Feedback:** Green/red flash for correct/incorrect answers
- **OOP Architecture:** Clean separation of concerns (Quiz, Question, UI classes)

---

## Screenshot

```
┌─────────────────────────────────────┐
│  Score: 7                           │
├─────────────────────────────────────┤
│                                     │
│   "The Great Wall of China is      │
│    visible from space."             │
│                                     │
├─────────────────────────────────────┤
│      [  ✓  ]      [  ✗  ]          │
└─────────────────────────────────────┘
```

---

## How It Works

1. App fetches 10 True/False questions from Open Trivia DB
2. Questions displayed one at a time
3. Click ✓ (True) or ✗ (False) to answer
4. Screen flashes green (correct) or red (incorrect)
5. Final score displayed at the end

---

## Project Structure

```
quizzler-app/
├── main.py           # Entry point
├── question_model.py # Question class
├── data.py           # API call to fetch questions
├── quiz_brain.py     # Quiz logic and scoring
└── ui.py             # Tkinter GUI
```

---

## Tech Stack

- **Python 3**
- **Tkinter** — GUI framework
- **Requests** — API calls
- **Open Trivia Database** — Question source

---

## Run Locally

```bash
git clone https://github.com/umbutun/quizzler-app.git
cd quizzler-app
pip install requests
python main.py
```

---

## What I Learned

- Consuming REST APIs with the `requests` library
- Object-Oriented Programming with multiple classes
- Separating data, logic, and UI layers
- Tkinter canvas and dynamic UI updates

---

## Part Of

🐍 [100 Days of Code — Python Projects](https://github.com/umbutun/python-100-days-of-code)

---

## License

[MIT License](LICENSE)
