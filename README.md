# Rock Paper Scissors, DOM Edition

Following on from last week's hackathon, we want to refactor our rock, paper, scissors console application and turn it into an interactive HTML page.

This repo has a console rock, paper, scissors starter in [main.js](main.js) which you will be using for the workshop.

> ⚠️ Please remember to do all your work in this repo and **not** the previous hackathon repo.

## DOM

Refactor the application so that all interactions are through elements in the HTML/on the DOM rather than via confirm, alert, and prompt. There are elements already in the [HTML file](index.html) as a starting point.

Using the DOM allows our game to be event-driven, so you may want to remove the while loop and instead compute the winner when an event is fired.

This will be deemed as complete when confirm, alert and prompt are no longer used, user interaction is handled with elements, and all the information is displayed on the page.

Once you've completed this and have a working game in your browser, start tackling the challenges below!

## Validation

Create a username input field and use the username the player inputs in the game so that a player can see their name on the page when looking at where the scores are displayed.

To make it more uniform, restrict the number of characters a username can be to 10 or fewer.

This will be deemed as complete when the users cannot enter a username longer than 10 characters.

- 🌟 BONUS: Make it so that valid usernames should only start with letters, not numbers or symbols.
- 🌟 EXTRA BONUS: Make it so that the first letter of the username should be capitalised.

## Style

Use CSS to add some style, flair, and animation to the playing experience on the page. Be creative! ✨

Some resources:

- [Animations](https://www.w3schools.com/css/css3_animations.asp)
- [Colour schemes](https://coolors.co/)
- [Gradients](https://www.w3schools.com/css/css3_gradients.asp)
- [Box shadows](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow)

## Fetch

Add an element to your page which you populate using data received from a fetch request.

This can be decorating your game with a pithy quote from the [Kanye API](https://kanye.rest/), or you can experiment with [another free API](https://github.com/public-apis/public-apis).

## Refactor

Look at the existing code of the game logic, and break it down into the smallest pieces of logic you can. With your partner, pick a chunk of logic and see if you can refactor it. How many ways can you write the logic to have your game still work?

In programming, there's rarely one correct answer. There are usually multiple ways to solve a problem, and each way has tradeoffs, positive and negative (reusability, readability, etc.). What are the tradeoffs of each way of writing the code?

Commit after you've coded and tested each refactor with a commit message summarizing what you've done so you can record your refactoring in your commit history.

Once you've finished all the ways you can think of, move on to the next piece of logic and keep refactoring and committing.
