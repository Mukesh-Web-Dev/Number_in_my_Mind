# Number_in_my_Mind 🎮

A JavaScript-based number guessing game created for fun and to learn ES6 concepts.

**Live Demo:** [https://mukesh-web-dev.github.io/Number_in_my_Mind/](https://mukesh-web-dev.github.io/Number_in_my_Mind/)

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Project Structure](#project-structure)
- [Learning Outcomes](#learning-outcomes)
- [Contributing](#contributing)
- [License](#license)

## 🎯 About

Number_in_my_Mind is an interactive web-based number guessing game built with vanilla JavaScript, HTML, and CSS. The project was developed to practice and master ES6 JavaScript concepts while creating an engaging user experience.

## ✨ Features

- **Interactive Gameplay** - Guess the random number within a limited number of attempts
- **Real-time Feedback** - Get hints whether your guess is too high, too low, or correct
- **Score Tracking** - Keep track of your attempts and final score
- **Responsive Design** - Works seamlessly on desktop and mobile devices
- **Smooth Animations** - Enhanced user interface with CSS animations
- **Reset Functionality** - Play multiple rounds without refreshing

## 🛠️ Tech Stack

- **HTML5** - Semantic markup and structure
- **CSS3** - Styling with animations and responsive design (48.5% of codebase)
- **JavaScript (ES6+)** - Game logic and DOM manipulation (39.9% of codebase)

## 📥 Installation

1. Clone the repository:
```bash
git clone https://github.com/Mukesh-Web-Dev/Number_in_my_Mind.git
cd Number_in_my_Mind
```

2. Open `index.html` in your web browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

3. Visit `http://localhost:8000` (or your configured port) in your browser

## 🎮 How to Play

1. The game thinks of a random number between 1 and 100
2. You have a limited number of attempts to guess the number
3. After each guess, you'll receive feedback:
   - "Too High!" if your guess is greater than the number
   - "Too Low!" if your guess is less than the number
   - "🎉 Correct! You Won!" when you guess the right number
4. Try to guess the number in the fewest attempts possible
5. Click "Reset Game" to play again

## 📁 Project Structure

```
Number_in_my_Mind/
├── index.html          # Main HTML file
├── style.css           # Styling and animations
├── script.js           # Game logic (ES6)
├── README.md           # This file
└── assets/             # (Optional) Images and icons
```

## 🎓 Learning Outcomes

This project demonstrates knowledge of:

- **ES6 Features:**
  - Arrow functions
  - `const` and `let` variable declarations
  - Template literals
  - Event listeners and handlers
  - DOM manipulation

- **Game Development Basics:**
  - Random number generation
  - User input validation
  - Game state management
  - Score calculation

- **Web Design:**
  - Responsive CSS Grid/Flexbox layouts
  - CSS animations and transitions
  - User-friendly interface design

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the MIT License. Feel free to use it for learning and personal projects.

---

**Author:** [Mukesh-Web-Dev](https://github.com/Mukesh-Web-Dev)

**Created:** 2024 | **Last Updated:** 2026-03-24

Happy Coding! 🚀