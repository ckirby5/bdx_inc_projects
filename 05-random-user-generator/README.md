# RANDOM USER GENERATOR
You will use Asynchronous Javascript and XML (AJAX) to access an API endpoint and parse the response. Since there are multiple methods, you will gain experience with AJAX via the XMLHttpRequest (XHR) object, the HTML 5 Fetch API, Axios, and jQuery.

Sure, in a real-world application you would not use every possible AJAX method for requesting data asynchronously, but I think it's important to learn each method to find each of their strengths and downfalls.

## RESOURCES
  * You'll need Axios and jQuery for this project.

      * Axios [https://cdnjs.cloudflare.com/ajax/libs/axios/0.16.2/axios.min.js](https://cdnjs.cloudflare.com/ajax/libs/axios/0.16.2/axios.min.js)

      * jQuery [https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js](https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js)

## SPECIFICATIONS
  * Your HTML page should include four buttons:

      * XHR
      * Fetch
      * Axios
      * jQuery

  * When a button is clicked, you will use the specified method for requesting a random user from the following API endpoint:

      * [https://randomuser.me/api](https://randomuser.me/api)

  * Upon receiving a response from the API, you will need to parse the JSON data and display the following user information (the style is up to you - be creative!):

      * Profile Picture
      * Full Name (first and last)
      * Username
      * Location (City and State)
      * Age (calculated from the date of birth)
      * Gender
      * Email
      * Nationality

## EXTRA CREDIT
  * Instead of just the text for the user's nationality, display their native flag. [These flag icons](http://flag-icon-css.lip.is/) may come in handy for this. 😉

  * Add transitions between newly generated random users.

  * Calculate the amount of time that elapses while a new user is being generated and display the information as "User generated in *N* seconds."

## EXAMPLE
[Here is an example](https://codepen.io/tophergates/full/eGMebm/) of how this might look. **DO NOT LOOK AT THE SOURCE CODE! THAT'S CHEATING!!**
