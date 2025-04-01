Programming Assignment 5

Ben Braniff

CSI 3150
Professor Sen

1.	Problem statement of the App: A concise summary of less than 150 words outlining what the app is all about.

    ```
    A 5 question quiz about the meaning of some computer science acronyms where you get 15 seconds to answer each question. 
    ```

2.	Functional features of the App: written as a bullet list, outline the functional features of the app.

    ```
    - Start Quiz button to begin the quiz.

    - Instruction box displaying quiz rules.

    - Multiple-choice questions dynamically loaded from questions.js.

    - Countdown timer (15 seconds per question).

    - Automatic answer validation (correct and incorrect indicators).

    - Score tracking and display upon quiz completion.

    - Restart and Quit options after completing the quiz.

    - Responsive UI with interactive elements.

    - Local storage support for tracking high scores.

    - Audio feedback for correct and incorrect answers.

    - Randomized question selection to enhance replayability.
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

    Includes styles for high-score displays.
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