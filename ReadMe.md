1. Create and Style the Home Page
we are going to create the home page along with a good chunk of the necessary CSS. The home page will consist of a few links for the Game and High Scores pages. We will also create helper CSS classes for Flexbox, buttons, and hiding elements.

I encourage you all to take a look at Emmet snippets for generating HTML and CSS.


2. Create and Style the Game Page
we will create the Game Page and display static question and answer information. Eventually, we will load questions from an API, but for now, we will hard code one question so to establish styling.


3. Display Hard Coded Question and Answers
In this video, we will load questions from a hard coded array and iterate through available questions as the user answers them. We will use custom data attributes, the ES6 spread operator, and JavaScript arrow functions.

4. Display Feedback for Correct/Incorrect Answers
we check the user's answer for correctness and display feedback to the user before loading the next question.

5. Create Head's Up Display (HUD)
 we will create a Heads Up Display (HUD) for our quiz app. This will display the user's score and current question number.

6. Create a Progress Bar
we will take our HUD one step further by creating a visual progress bar to track the user's progress through the questions.

7. Create and Style the End Page
we will create our End page where we will display the user's achieved score. This screen will provide a form for saving the score and links for playing again or going home.

8. Save High Scores in Local Storage
we will save and maintain a high scores array in Local Storage. To do this, we will need to JSON.stringify() and JSON.parse() to convert our high score array to a string and visa versa.

9. Load and Display High Scores from Local Storage
we will create our High Scores page. We will have to load the high scores from Local Storage, iterate through them, and display them on the screen.

10. Fetch API to Load Questions From Local JSON File
we will move our sample questions from a hard coded array to an external .json file. This will help clean up our Game.js file and set ourselves up to request questions from an API in the next step.

11. Fetch API to Load Questions from Open Trivia API
we will use Fetch to request a list of questions from the Open Trivia DB API.

12. Create a Spinning Loader
We will create a simple spinning loader in CSS that will be displayed until we are finished requesting/loading questions from the API.

13. Closing