# 🎮 JavaScript Quiz Game

An interactive and fun *Quiz Game* built using *HTML, CSS, and JavaScript* — completely frontend and offline.  
This project displays multiple-choice questions, checks the user's answers, tracks the score, and shows the final results with a “Play Again” option.

---

## 🚀 Features

✅ 5 multiple-choice questions about Java basics  
✅ Instant feedback for correct or wrong answers  
✅ Dynamic “Next” and “Play Again” buttons  
✅ Final score display at the end of the quiz  
✅ Responsive and modern UI design  
✅ 100% frontend — no backend or database required  
✅ Works fully offline

---

## 🧩 Technologies Used

| Technology | Description |
|-------------|-------------|
| *HTML5* | Structure and layout of the quiz interface |
| *CSS3* | Styling, colors, and visual design |
| *JavaScript (ES6)* | Quiz logic, question handling, and interactivity |

---

🧠 Quiz Game Logic

Here’s how the game works step-by-step:

1. Questions and answers are stored in a JavaScript array in script.js.


2. Each question object includes:

The question text

Four possible answers

A flag (true/false) for the correct one.



3. When the user selects an answer:

Correct answers turn green ✅

Wrong answers turn red ❌



4. The Next button loads the next question.


5. At the end, the final score is displayed.


6. The Play Again button restarts the quiz from the beginning.




---

📸 Example Screenshot

<img width="1920" height="1080" alt="Screenshot 2025-11-04 111128" src="https://github.com/user-attachments/assets/d725d1c9-11ae-4d54-a7ef-f363c3dc7b04" />

<img width="1920" height="1080" alt="Screenshot 2025-11-04 111204" src="https://github.com/user-attachments/assets/25354660-2f71-4728-a723-f289f3281a83" />

---

🎨 Design Details

Background: Gradient dark theme (#20232a → #3c4048)

Text color: White for readability

Highlight color: Light blue (#61dafb)

Buttons: Rounded with hover effects

Layout: Centered, clean, and responsive

Font: “Poppins”, sans-serif



---

🔍 Code Explanation

📄 index.html

Contains the quiz container, question box, buttons, and links the CSS + JS files.


🎨 style.css

Adds background, font styles, button colors, and animations.

Uses flexbox for centering and spacing.


⚙ script.js

Handles all logic:

Displays questions

Checks answers

Tracks score

Updates the UI dynamically




---

🧰 Example Code Snippets

JavaScript Question Object

{
  question: "Who developed Java?",
  answers: [
    { text: "James Gosling", correct: true },
    { text: "Dennis Ritchie", correct: false },
    { text: "Bjarne Stroustrup", correct: false },
    { text: "Guido van Rossum", correct: false }
  ]
}

Adding a New Question

To add more questions, just add another object to the questions array in script.js.


---

🧪 Future Improvements

✨ Randomize question order
✨ Add countdown timer per question
✨ Add categories (Java, HTML, CSS, etc.)
✨ Save high scores using localStorage
✨ Add progress bar and sounds


---

🏗 Project Setup Summary

File	Purpose

index.html	Displays quiz interface
style.css	Handles layout and design
script.js	Controls quiz logic and flow



---

🧑‍💻 Author

Your Name
📧 raaviprabhas5@gmail.com
💻 GitHub: Raavi-Sai-Prabhas
🌍 Project made with ❤ using pure web technologies.


---


💬 Final Note

This mini project is perfect for:

Web development beginners

School/college practical submissions

Portfolio projects showcasing frontend skills


🎯 Learn. Code. Play. Improve.

---
