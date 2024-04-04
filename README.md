## Harry Potter Quiz App

![hp-quiz](https://github.com/InRenck/HP-quiz/assets/133249054/562c0b97-3196-4f0a-9eb3-a59f69e9ea0c)

# Overview
This project is a Harry Potter-themed quiz app built using React. It allows users to answer a series of questions related to the Harry Potter series and provides immediate feedback on each question. The app displays the user's score at the end of the quiz.

# Table of Contents
 - Project Structure
 - Usage
 - CSS Styles
 - Quiz Data
 - License
# Link
https://hp-quiz-two.vercel.app/

# Project Structure
The project includes the following files:
 - HTML file (index.html):
   Contains the basic structure of the app, including the root element (<div id="root"></div>) where the React app will be mounted.
 - JavaScript files (main.jsx and Quiz.jsx):
   main.jsx: Initializes the React app and renders the App component. 
   Quiz.jsx: Defines the main quiz component (Quiz), including question rendering, answer handling, and score tracking.   
 - CSS file (quiz.css):
   Contains styles for the quiz app, defining the appearance of the container, question, options, and result sections.

# Usage
To use this project, follow these steps:
  1. Clone the repository: git clone <repository-url>
  2. Open the index.html file in your preferred web browser.
  3. Answer the Harry Potter-themed quiz questions by selecting options.
  4. After completing the quiz, view your final score and reset the quiz if desired.

# CSS Styles
The CSS styles are organized to create a visually appealing and themed design for the quiz app. The design features a container with a Harry Potter-inspired color scheme, options with distinct styles, and result sections.
  - Colors:
    Custom colors (#d8c7ff, #19006c, #553f9a, #dffff2, #ffebeb) are used for the background, gradients, buttons, and result sections.
  - Container:
    The container has a fixed width, centered margin, and a white background with a border-radius.
  - Options:
    Options are styled as list items with borders, rounded corners, and hover effects.
  - Result Section:
    The result section has a distinct background color based on the correctness of the answer.

# Quiz Data
The quiz data is stored in the data array within the Quiz.jsx file. Each object in the array represents a quiz question with the question, options, and the correct answer index.

# License
This project is licensed under the MIT License.
