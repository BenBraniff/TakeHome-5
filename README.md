Programming Assignment 5

Ben Braniff

CSI 3150
Professor Sen
# Questions & Answers
1.	Problem statement of the App: A concise summary of less than 150 words outlining what the app is all about.

    ```
    A 5 question quiz about the meaning of some computer science acronyms where you get 15 seconds to answer each question. 
    ```

2.	Functional features of the App: written as a bullet list, outline the functional features of the app.

    ```
    Start Quiz:
    Allows the user to begin the quiz.

    Quiz Instructions:
    Displays rules and instructions before starting the quiz.

    Timer:
    Tracks 15 seconds for each question.

    Question Display:
    Dynamically displays questions with options.

    Answer Validation:
    Evaluates whether the selected answer is correct or incorrect.

    Score Calculation:
    Calculates and displays the user's score at the end of the quiz.

    Progress Bar:
    Shows a visual representation of the remaining time.

    Next Question:
    Navigates to the next question after the user selects an answer.

    Result Display:
    Shows the user's score at the end of the quiz.

    Replay and Exit:
    Options to replay the quiz or exit it at any point.
    ```

3.	Explanation of the directory structure/setup of the App as present in the code base and how different files are linked and working together.

    ```
    - index.html links to style.css for styling and quizApp.js for quiz logic.

    - quizApp.js dynamically loads questions from questions.js.

    - questions.js contains the question data array.
    ```

4.	Explanation of the codebase in each of relevant files, which in this case are the index.html, style.css, questions.js, and quizApp.js files.

    ### index.html
    ```
    Contains the quiz UI elements: start button, info box, quiz box, result box.

    Links external CSS and JavaScript files.

    Uses <script> with defer to ensure scripts load after HTML.
    ```
    ### style.css
    ```
    Defines styles for quiz elements, including buttons, containers, and animations.

    Provides responsive design adjustments.
    ```
    ### questions.js
    ```
    Stores an array of objects, each representing a question with options and the correct answer.

    Used by quizApp.js to populate quiz content dynamically.
    ```
    ### quizApp.js
    ```
    Manages quiz logic, including:

    Event listeners for buttons (Start, Next, Restart, Quit).

    Functions to display questions, validate answers, and update the score.

    Timer and progress bar management.

    Handling of correct and incorrect answers with visual feedback.

    Displaying quiz results at the end.

    Integrating audio feedback for answers.
    ```

# Refereces

[martysen > DemoQuizApp](https://github.com/martysen/DemoQuizApp/)

[adam-p > markdown-here](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet#links)

[lifeparticle > Markdown-Cheatsheet](https://github.com/lifeparticle/Markdown-Cheatsheet)