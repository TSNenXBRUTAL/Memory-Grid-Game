# 🧠 Memory Grid Game

## Overview
The Memory Grid Game is a sleek, web-based memory test that challenges players to rely on their short-term recall[cite: 2]. Built entirely with standard web technologies, the game generates a randomized puzzle every time it is played[cite: 2]. 

## Features
* **Dynamic Grid:** The game board consists of a 6x6 CSS grid containing 36 individual cells[cite: 2].
* **Randomized Targets:** Every game randomly selects exactly 10 unique boxes for the player to memorize[cite: 2].
* **Timer Mechanics:** Players are given a strict 5-second window to memorize the highlighted boxes before they disappear[cite: 2].
* **Real-time Statistics:** A live dashboard tracks your current Score, Remaining hidden boxes, and Wrong Taps[cite: 2].
* **Visual Feedback:** Correct taps instantly turn green, while incorrect taps turn red[cite: 2]. 
* **Win/Loss Conditions:** The game ends in a victory if the player successfully uncovers all 10 boxes, but ends in a "Game Over" if the player exceeds 3 wrong taps[cite: 2].
* **Auto-Restart:** Alerts notify the player of their final score and automatically reload the page to start a fresh game after 1 second[cite: 2].

## How to Play
1. Load the game in your browser[cite: 2].
2. Carefully watch the grid as 10 boxes light up in blue[cite: 2].
3. You have exactly 5 seconds to memorize their positions[cite: 2].
4. Once the blue highlights disappear, click on the grid cells where you remember the boxes being located[cite: 2].
5. Find all 10 boxes to win, but be careful—making more than 3 wrong taps will end the game[cite: 2]!

## Tech Stack
* **HTML5:** Structures the grid and status dashboard[cite: 2].
* **CSS3:** Uses CSS Grid for layout, a dark `#111` background theme, and interactive hover/transition effects[cite: 2].
* **Vanilla JavaScript:** Powers the core game logic, random number generation (`Math.random`), `setTimeout` timers, and event listener delegations[cite: 2].
