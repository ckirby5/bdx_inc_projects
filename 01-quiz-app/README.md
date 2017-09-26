>The technology stack that you are allowed to use for this project is: HTML, CSS, and JavaScript.

# BUILD A QUIZ APPLICATION
Your challenge, should you choose to accept it, is to build a quiz application which meets the following specifications:

## SPECIFICATIONS
>While I strongly suggest you use vanilla JavaScript to solidify your learning of the language, if you need to, you can use a JavaScript library or framework (such as jQuery) to assist you.

>If you use a library like jQuery to complete the project, you should go back afterward and attempt to complete the project once again using vanilla JavaScript.

  * Create a simple quiz application. The user should be able to select an answer corresponding to each question by using **radio buttons**. The quiz can be made up of any number of questions with any number of answer choices (I suggest no less than three questions).

  * The application should only display one question at a time as well as a **next** button. When the next button is clicked, you will need to dynamically remove the current question and add the next question to the page so the user can navigate forward through the quiz.

  * On the final question, replace the next button with a **submit** button. When the submit button is clicked, tally the users score and display the final quiz score.

  * On the last page you will only show the final quiz score; so you will need to remove the last question and the submit button so only the quiz score is shown.

## IMPROVING YOUR APPLICATION
Once you've completed all of the specifications, improve your quiz application as follows:

  * Add client-side data validation to make sure the user answers each question before proceeding to the next question. If the user attempts to move to the next question before answering the current question, the question text should turn red and an error message should indicate that they must answer the question before proceeding.

  * Add a **back** button to allow the user to return to the previous question and change their answer. The user can go all the way back to the first question and when they cannot go back any further, the back button should be removed. For the questions that the user has answered already, be sure to show the appropriate radio button as selected, so that the user is not forced to answer the questions again. Lastly, the back button should not be available if the quiz has been submitted and scored.

  * Add transitions/animations so that when the next, back, and submit buttons are clicked you fade out the previous question and fade in the next question or final score.

  * Store the quiz questions in an external JSON file.

## EXTRA CREDIT
  * Add user authentication to allow users to log in using their login credentials. You can save their login credentials to local storage using HTML5 browser storage.

  * Use cookies to remember the user and show a "Welcome, [First Name]" message when the user returns to the quiz.