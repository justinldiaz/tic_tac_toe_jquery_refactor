##Tic Tac Toe jQuery Refactor

####Goal
Refactor the tic tac toe app to use jQuery instead of plain JavaScript.  Either use your existing Tic Tac Toe project, or if you aren't satisfied with your code, you can also work off of the solution provided in this sample solution file set.  Find these files in the sample_solution branch.
* `ttt-solution.js`
* `ttt-solution.html`
* `ttt-solution.css`

####Steps
* Note: you do NOT need to fork this repository. We will be updating the same `tic-tac-toe` repo you created for your weekend lab.
* In your local `tic-tac-toe` repo, create a new file called `ttt-jq-refactor.js`.
* Copy your existing tic tac toe `app.js` (or `ttt-solution.js`) into the `ttt-jq-refactor.js` file. 
* Replace `app.js` with `ttt-jq-refactor.js` in your `<script>` tag in  `index.html`, so that your site will use the refactored code instead of the old `app.js`.
* Include jQuery in your app by adding another HTML `<script>` tag. Try linking to a CDN.
* In your `ttt-jq-refactor.js`, comment out each section of old JavaScript code and write the corresponding jQuery below it. 

####Submission
* Add and commit your work in your local repository.
* Push your changes to your gitHub repo.
* Submit the link to your tic-tac-toe github repo (the same link you submitted over the weekend).

####Hints
* Use the [docs](https://api.jquery.com/). They outline the full jQuery API on the front page. Try using <ctrl> + F to search particular keywords. Otherwise, Google should get you what you're looking for.
* Test your changes as you go!

####Bonus Challenges
* Allow your user to "undo" or "replay" moves (start by keeping track of the game's state).
* Create a mode where the computer plays against the user. Consider looking up how to put in a small time delay so that the computer's moves aren't instant.
* SUPER BONUS: Allow the user choose which mode to use at the beginning of the game.
