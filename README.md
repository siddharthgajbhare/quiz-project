# 🧠 QuizMaster Pro

**QuizMaster Pro** is a modern, interactive quiz web application built with **HTML, CSS, and JavaScript**.

It provides an engaging quiz experience with multiple categories, difficulty levels, timed questions, daily challenges, practice mode, statistics, achievements, leaderboard, and custom questions.

---

## 🚀 Features

### 🎯 Quiz Modes

- **Normal Quiz** – Play a standard quiz with customizable settings.
- **Daily Challenge** – Complete a daily fixed question set.
- **Practice My Mistakes** – Practice questions answered incorrectly in previous games.

### 📚 Quiz Customization

- Multiple categories
- Easy, Medium, and Hard difficulty
- Choose **5, 10, 15, or 20 questions**
- Optional timer
- 15, 20, or 30 seconds per question
- Randomized questions
- Randomized answer options

### ⏱️ Timed Quiz

Each question can have a countdown timer.

When the timer reaches zero, the question is automatically submitted.

The timer changes appearance when only a few seconds remain.

### 🛟 Lifelines

- ✂️ **50/50** – Removes incorrect options.
- ⏭️ **Skip** – Skip a difficult question.

Each lifeline can be used once per quiz.

### 📊 Results & Performance

After completing a quiz, users can see:

- Total score
- Correct answers
- Wrong answers
- Best streak
- Average response time
- Accuracy percentage
- Detailed question review
- Correct answers
- Skipped questions
- Newly unlocked badges

### 🏆 Leaderboard

The application maintains a local leaderboard containing:

- Player name
- Score
- Percentage
- Date

The top 10 scores are displayed.

### 📈 Statistics Dashboard

Track overall performance including:

- Total games played
- Total correct answers
- Overall accuracy
- Category-wise accuracy
- Earned badges

### 🏅 Achievement Badges

QuizMaster Pro includes achievement badges such as:

| Badge | Requirement |
|---|---|
| 🎯 Perfect | 100% on 5+ questions |
| ⚡ Speedster | Average time under 6 seconds |
| 🔥 On Fire | 5 correct answers in a row |
| 🎮 Veteran | Play 10 games |
| 🎓 Scholar | 50 correct answers |
| 📅 Daily Player | Complete a daily challenge |

### 🌙 Dark Mode

Switch between:

- ☀️ Light Mode
- 🌙 Dark Mode

The selected theme is saved locally.

### 🔊 Sound Effects

Optional sound effects provide feedback for correct and incorrect answers.

Users can enable or disable sound at any time.

### ⌨️ Keyboard Controls

During a quiz:

```text
1 - Select option 1
2 - Select option 2
3 - Select option 3
4 - Select option 4
Enter - Move to next question
```

### ✏️ Custom Questions

Users can create their own questions with:

- Question
- Four options
- Correct answer
- Category
- Difficulty
- Explanation

Custom questions are stored locally and can be exported as JSON.

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling and responsive UI |
| JavaScript | Quiz logic and functionality |
| LocalStorage | Saving user data |
| Web Audio API | Sound effects |
| JSON | Custom question export |

---

# 📂 Project Structure

```text
quiz-project/
│
├── index.html
├── README.md
└── assets/
    └── images/
```

> The current application is implemented as a client-side web application, with the HTML, CSS, and JavaScript contained in the main application file.

---

# 🎮 How to Run

## Option 1: Open Directly

Clone the repository:

```bash
git clone https://github.com/siddharthgajbhare/quiz-project.git
```

Enter the project directory:

```bash
cd quiz-project
```

Open the HTML file in your browser.

---

## Option 2: Run Using VS Code

Install the **Live Server** extension in VS Code.

Then:

1. Open the project.
2. Open the main HTML file.
3. Right-click the file.
4. Select **Open with Live Server**.

The application will open in your browser.

---

# 🧩 Available Categories

The current quiz contains categories such as:

- 🔬 Science
- 💻 Technology
- 🌍 Geography
- 📜 History
- ⚽ Sports
- 🧠 General Knowledge

The application also supports adding custom categories.

---

# 💾 Data Storage

QuizMaster Pro uses **Browser LocalStorage** for client-side persistence.

The application can store:

```text
Player Name
Quiz Scores
Leaderboard
Statistics
Wrong Questions
Custom Questions
Theme Preference
Sound Preference
Achievements
```

No external database is required.

---

# 🔐 Privacy

QuizMaster Pro is primarily a client-side application.

User quiz data is stored locally in the browser using LocalStorage and is not automatically uploaded to a server.

Clearing browser storage may remove saved quiz data.

---

# 📱 Responsive Design

The interface is designed to work across different screen sizes.

The UI includes:

- Responsive cards
- Mobile-friendly controls
- Flexible layouts
- Touch-friendly buttons
- Dark/light themes

---

# 🧠 Quiz Scoring

The scoring system rewards both correctness and speed.

A correct answer can receive:

```text
Base points
+
Speed bonus
+
Streak bonus
```

Incorrect answers reset the current streak.

This encourages users to answer both **correctly and quickly**.

---

# 🔄 Application Flow

```text
                 QuizMaster Pro
                       │
                       ▼
                    Home Page
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
        Normal       Daily       Practice
         Quiz       Challenge     Mistakes
          │            │            │
          └────────────┼────────────┘
                       ▼
                 Select Questions
                       │
                       ▼
                 Start Quiz
                       │
                 ┌─────┴─────┐
                 ▼           ▼
              Answer       Timer
                 │           │
                 └─────┬─────┘
                       ▼
                  Next Question
                       │
                       ▼
                    Results
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
       Review       Statistics   Leaderboard
```

---

# 📊 Performance Tracking

The statistics dashboard provides category-wise performance.

Example:

```text
Technology    85%
Science       75%
History       90%
Geography     70%
Sports        80%
```

This helps users identify topics that need more practice.

---

# 📥 Export Custom Questions

Custom questions can be exported as a JSON file.

Example:

```json
[
  {
    "category": "Technology",
    "difficulty": "Easy",
    "question": "What does CPU stand for?",
    "options": [
      "Central Processing Unit",
      "Computer Personal Unit",
      "Central Program Utility",
      "Core Processing Utility"
    ]
  }
]
```

---

# 🔮 Future Improvements

The project can be further upgraded with:

- 🔐 User authentication
- ☁️ Cloud database
- 👤 User profiles
- 📊 Advanced analytics
- 📱 Progressive Web App (PWA)
- 🌐 Online multiplayer quizzes
- 🏆 Global leaderboard
- 👨‍🏫 Admin dashboard
- 📚 Larger question bank
- 🤖 AI-generated questions
- 📝 Quiz creation and sharing
- 📈 Performance charts
- 📥 PDF result reports
- 🔗 Shareable quiz links
- 🗄️ MySQL / MongoDB backend

---

# 🎯 Project Goals

The main goals of QuizMaster Pro are:

- Make online quizzes more interactive.
- Provide instant feedback.
- Help users identify weak topics.
- Encourage regular practice.
- Track long-term performance.
- Provide a simple and modern quiz interface.

---

# 👨‍💻 Author

**Siddharth Gajbhare**

GitHub:  
`https://github.com/siddharthgajbhare`

Repository:  
`https://github.com/siddharthgajbhare/quiz-project`

---

# ⭐ Support

If you like this project, consider giving the repository a ⭐ on GitHub.

---

## 📄 License

This project is created for **educational and learning purposes**.
