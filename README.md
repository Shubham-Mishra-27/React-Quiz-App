# React Quiz Application
# React + Vite

# Introduction
This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

This is a React Quiz Application where students can take a quiz consisting of 10 questions. The application is built using React and manages state using hooks. The quiz provides an interactive experience, allowing students to select answers, track progress, and view results at the end.

# Features

  - 10 multiple-choice questions.
  - Interactive UI with real-time feedback.
  - Progress tracking.
  - Result display at the end.
  - Error handling for data fetching.

# Folder Structure

## Folder Structure
```
reactQuiz/
│── data/
│   └── questions.json          # JSON file containing quiz questions
│── dist/                       # Build files (generated)
│── node_modules/               # Dependencies
│── public/
│   ├── logo512.png             # Logo image
│   ├── vite.svg                # Vite logo
│── src/
│   ├── assets/                 # Additional assets
│   ├── Components/             # React components
│   │   ├── Error.jsx           # Error message component
│   │   ├── FinishScreen.jsx    # Final score display
│   │   ├── Footer.jsx          # Footer component
│   │   ├── Header.jsx          # Header component
│   │   ├── Main.jsx            # Main quiz logic
│   │   ├── NextButton.jsx      # Button to proceed to next question
│   │   ├── Options.jsx         # Answer options component
│   │   ├── Progress.jsx        # Progress tracking bar
│   │   ├── Questions.jsx       # Questions display component
│   │   ├── StartScreen.jsx     # Start quiz screen
│   │   ├── Timer.jsx           # Quiz timer
│   ├── App.css                 # Global styles
│   ├── App.jsx                 # Main app component
│   ├── index.css               # Index styles
│   ├── main.jsx                # Main entry point
│── .gitignore                   # Git ignore file
│── index.html                    # Main HTML file
│── package.json                 # Project dependencies
│── README.md                    # Project documentation
│── eslint.config.js             # ESLint configuration
│── package-lock.json            # Lock file for dependencies
│── package.json            
│── vite.config.js 
```

# Installation

1. Clone the repository:
```
git clone https://github.com/Shubham-Mishra-27/React-Quiz-App.git
```

2. Navigate to the project folder:
```
cd react-quiz-app
```

3. Install dependencies:
```
npm install
```

4. Start the development server:
```
npm run dev
```

# Usage

  - Click the "Start Quiz" button.
  - Answer each question by selecting an option.
  - Click the "Next" button to move to the next question.
  - View your progress using the progress bar.
  - See the final score at the end of the quiz.

# Technologies Used

  - React
  - JavaScript (ES6+)
  - Vite (for fast development build)
  - Tailwind CSS (for styling)
