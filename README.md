# 🚀 TypeRush - Typing Speed Test Application

A modern and responsive Typing Speed Test web application built using **HTML**, **Tailwind CSS**, and **Vanilla JavaScript**.

TypeRush helps users improve typing speed, accuracy, and keyboard efficiency with real-time feedback, difficulty levels, timer modes, and performance analysis.

---

# 🌟 Features

- 🎯 Multiple Difficulty Levels
  - Easy
  - Medium
  - Hard

- ⏱ Multiple Timer Modes
  - 30 Seconds
  - 60 Seconds
  - 120 Seconds

- 📊 Real-Time Statistics
  - Live WPM Calculation
  - Accuracy Tracking
  - Error Counting
  - Remaining Time

- ✨ Dynamic Character Highlighting
  - Correct characters
  - Wrong characters
  - Current typing position

- 🏆 Performance Analysis
  - Beginner
  - Average
  - Good
  - Excellent
  - Pro

- 💾 Best Score Storage
  - Uses `localStorage`
  - Saves highest WPM automatically

- 📱 Fully Responsive Design
  - Mobile Friendly
  - Tablet Support
  - Desktop Optimized

- 🎨 Modern UI
  - Dark Theme
  - Smooth Animations
  - Tailwind CSS Styling

---

# 🛠 Tech Stack

| Technology | Usage |
|------------|------|
| HTML5 | Structure |
| Tailwind CSS | Styling |
| JavaScript | Application Logic |
| LocalStorage | Best Score Saving |

---

# 📂 Project Structure

```bash
TypeRush/
│
├── index.html
├── README.md
│
└── assets/
```

---

# ⚙️ How It Works

1. User selects:
   - Difficulty level
   - Timer duration

2. A random paragraph is loaded.

3. Timer starts automatically when typing begins.

4. Application tracks:
   - Typed characters
   - Accuracy
   - Errors
   - WPM

5. After completion:
   - Final statistics are displayed
   - Best score is saved locally

---

# 🧠 WPM Calculation Formula

```javascript
const wordsTyped = correctCharacters / 5;
const wpm = wordsTyped / timeElapsed;
```

### Explanation

- 1 word = 5 characters
- WPM = Words Typed ÷ Time (minutes)

---

# 📸 Screens Included

- 🏠 Home Screen
- ⌨️ Typing Test Screen
- 📈 Result Screen

---

# 📱 Responsive Design

TypeRush is optimized for:

- Mobile Devices
- Tablets
- Laptops
- Large Screens

Responsive layouts are implemented using:
- Tailwind CSS
- Media Queries
- Flexible Grid System

---

# 🎯 Learning Concepts Used

This project demonstrates:

- DOM Manipulation
- Event Handling
- Timers (`setInterval`)
- Dynamic UI Updates
- LocalStorage
- Responsive Web Design
- Real-Time Input Tracking
- JavaScript Logic Building

---

# 🚀 Future Improvements

Possible future features:

- 🌍 Multiplayer Typing Race
- 🔥 Typing Heatmap
- 📊 Advanced Analytics
- 🎵 Sound Effects
- 🌐 API-Based Paragraphs
- 🧑 User Authentication
- 🏅 Leaderboard System
- 🌙 Theme Toggle
- 📈 Typing Progress Graphs

---

# ▶️ How To Run

## Method 1 — Direct Open

Simply open:

```bash
index.html
```

inside any browser.

---

## Method 2 — VS Code Live Server

1. Install VS Code
2. Install "Live Server" Extension
3. Right click `index.html`
4. Click:

```bash
Open with Live Server
```

---

# 🏆 Performance Levels

| WPM Range | Level |
|-----------|------|
| < 20 | Beginner |
| 20 - 34 | Average |
| 35 - 49 | Good |
| 50 - 69 | Excellent |
| 70+ | Pro |

---

# 📌 Highlights

✅ Beginner Friendly  
✅ Clean UI Design  
✅ Professional Project Structure  
✅ Real-Time Typing Analysis  
✅ Fully Responsive  
✅ Easy To Customize

---

# 👨‍💻 Author

Developed by **Adithya Vardhan**

- Frontend Developer
- JavaScript Enthusiast
- Software Engineering Fresher

---

# 📄 License

This project is open-source and available for learning and educational purposes.

---

# ⭐ Support

If you like this project:

- Star the repository
- Fork the project
- Share with others
- Improve and contribute

---

# 🔥 Final Note

TypeRush is a great beginner-to-intermediate frontend project that helps developers practice:

- JavaScript Fundamentals
- DOM Manipulation
- Real-Time UI Logic
- Responsive Design
- Project Structuring

while also building a strong portfolio project.

Happy Coding 🚀
