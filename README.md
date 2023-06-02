<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Quiz App Master</title>
</head>
<body>
  <h1>Quiz App Master</h1>

  <h2>Features</h2>
  <ul>
    <li>Create multiple quizzes with different sets of questions and answers.</li>
    <li>Edit existing quizzes by adding, removing, or modifying questions and answers.</li>
    <li>Allow users to take quizzes and provide immediate feedback on their answers.</li>
    <li>Display the final score and a detailed summary at the end of each quiz.</li>
    <li>Support for multiple-choice, true/false, and open-ended questions.</li>
    <li>User-friendly interface with intuitive navigation and responsive design.</li>
    <li>Robust error handling and input validation for a seamless user experience.</li>
  </ul>

  <h2>Technologies Used</h2>
  <ul>
    <li>HTML5</li>
    <li>CSS3</li>
    <li>JavaScript (ES6)</li>
    <li>Bootstrap (v4)</li>
    <li>jQuery (v3)</li>
    <li>Font Awesome (v5)</li>
    <li>JSON (for storing quiz data)</li>
  </ul>

  <h2>Getting Started</h2>
  <ol>
    <li>Clone the repository: <code>git clone https://github.com/your-username/quiz-app-master.git</code></li>
    <li>Navigate to the project directory: <code>cd quiz-app-master</code></li>
    <li>Open the <code>index.html</code> file in your web browser.</li>
  </ol>

  <h2>File Structure</h2>
  <pre>
    css/
    ├── style.css
    └── bootstrap.min.css

    fonts/
    └── font-awesome.min.css

    js/
    ├── app.js
    └── jquery.min.js

    quizzes/
    ├── quiz1.json
    ├── quiz2.json
    └── quiz3.json

    img/
    ├── header.jpg
    └── favicon.ico

    index.html
    README.md
  </pre>

  <h2>Adding/Editing Quizzes</h2>
  <p>To add or edit quizzes, you need to modify the JSON files in the <code>quizzes/</code> directory. Each JSON file represents a separate quiz and follows a specific structure. You can create new JSON files for additional quizzes or modify existing ones as per your requirements.</p>
  <p>Here's an example of the structure of a quiz JSON file:</p>
  <pre>
    {
      "title": "Sample Quiz",
      "questions": [
        {
          "question": "What is the capital of France?",
          "type": "multiple-choice",
          "choices": [
            "Paris",
            "London",
            "Madrid",
            "Berlin"
          ],
          "correctAnswer": "Paris"
        },
        {
          "question": "Is the Earth round?",
          "type": "true-false",
          "correctAnswer": true
        },
        {
          "question": "Name a famous physicist.",
          "type": "open-ended"
        }
      ]
    }
  </pre
