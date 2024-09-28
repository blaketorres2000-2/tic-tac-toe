# Tic Tac Toe Game

## Overview

As a software developer, I strive to create engaging and interactive applications that enhance user experience. This project focuses on developing a simple yet addictive Tic Tac Toe game using Django, allowing players to challenge each other or play against themselves for practice. The goal is to provide an intuitive interface for players while implementing core game mechanics.

The game is built using HTML, CSS, and Django(Python), featuring a clean design and responsive layout. Players can take turns placing their markers (X or O) on a 3x3 grid, with the objective of getting three in a row—either horizontally, vertically, or diagonally.

This software aims to offer an enjoyable gameplay experience and help me further develop my web development skills while applying best practices in Django and web design.

**Software Demo Video:** [Tic Tac Toe Game Demo](https://youtu.be/YOUR_DEMO_LINK)

## Game Features

1. **Two-player Mode:**
   - Play against a friend, taking turns to place your markers on the board.

2. **Game Reset:**
   - Easily restart the game with a button click, allowing for continuous play without refreshing the page.

3. **Win Detection:**
   - The game checks for winning combinations after each move, declaring a winner or a draw as appropriate.

4. **User Input for Player Names:**
   - Players can enter their names at the beginning of the game, allowing for a personalized experience.
  
5. **Leaderboard:**
   - The leaderboard is displayed on the home page,
   - It displays the top 5 players with the most wins.

6. **Database:**
   - The database is used to store player names and wins.
   - The database used is SQLite, which is the default database provided by Django.
   - Django uses a built-in feature called ORM that allows database schema to be defined using Python classes, which correspond to database tables.

## Development Environment

- **Tools Used:** Visual Studio Code, GitHub
- **Programming Languages:** HTML, CSS, Python (Django)

## Useful Resources

* [Django Documentation](https://docs.djangoproject.com/en/stable/)
* [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [W3Schools - CSS](https://www.w3schools.com/css/)

## Future Work

* Implement AI for practicing by yourself without storing wins.
* Introduce mobile responsiveness and touch support for better gameplay on mobile devices.
* Add difficulty by making new boards with more cells that would make the player connect 4 in a row.
