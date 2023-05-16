# Numerati: The Guessing Game

Numerati is an engaging and intuitive guessing game built with HTML, CSS, and JavaScript. The objective of the game is simple - guess the secret number that's between 1 and 20. But that's not all. With each incorrect guess, your score decreases. How high can you score?

## Features

- Single Page Application (SPA) for a seamless user experience.
- Dynamic score updating based on user's guess.
- Highscore tracking to keep the game competitive.
- Responsive design that looks good on both desktop and mobile devices.
- Colorful and clean UI that's easy on the eyes and simple to navigate.

## Project Structure

The project consists of three main files:

1. `index.html` - The main HTML file that contains the structure of the game.
2. `style.css` - The CSS file that provides styling to the game.
3. `script.js` - The JavaScript file that powers the game's functionality.

### index.html

This file is the core structure of our game. It features a minimalist design with a header section and a main section. The header section displays the game title, the secret number (once guessed correctly), and a button to restart the game. The main section contains the user input for the guessed number, the check button, and the score and highscore displays.

### style.css

The style file applies a modern and sleek styling to the game. It makes use of the Roboto font, a linear gradient for the header, a subtle background image for the body, and various other CSS properties to make the game visually appealing.

### script.js

The JavaScript file handles the core game logic. It randomly generates a secret number at the start of the game and whenever the game is restarted. It provides event listeners for the check and again buttons, implements score tracking and updating, highscore tracking, and also provides feedback messages to the user.

## How to Play

Start by inputting a guess between 1 and 20. Click "Check!" to see if your guess is correct. If your guess is too high or too low, your score will decrease by 1, and you'll be prompted to guess again. If your guess is correct, you'll see the secret number, and your score will become the new highscore if it's the highest so far. Click "Again!" to restart the game and try to beat your highscore!

