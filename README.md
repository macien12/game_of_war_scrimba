# Game of War

A simple card game built while following Scrimba's Fullstack Developer Path. Play against the computer by drawing two cards from a shuffled deck: the higher card wins the round, and a tie is called "War". The player with the most points when the deck runs out wins.

## What I learned

- Fetching data from an API with `fetch()` and handling responses with promises and `.then()`.
- Reading JSON data to get a deck ID, card images, card values, and the number of cards remaining.
- Using template literals to build API URLs and display dynamic content.
- Selecting and updating HTML elements with JavaScript, including text, card images, and button states.
- Responding to button clicks with event listeners.
- Keeping track of game state with variables and updating scores after each round.
- Comparing card ranks using an array and `indexOf()`, and using conditional logic to determine the winner.
- Styling a game interface with CSS, including Flexbox, background images, and disabled button styles.
- Running a frontend project locally with Vite.

## Run locally

```bash
npm install
npm start
```

Open the local URL printed in the terminal. The game needs an internet connection to fetch the deck and card images.

Click **New Deck** before clicking **Draw**. Each draw uses two cards, one for the computer and one for you.
