# Hangman Game - E2E Project🎮

## Overview
This is a Hangman game where users must log in or register to play.  
The game uses cookies for session management, and when the cookie expires, the user must log in again.  
Upon login, the user can choose to view their game history, play a new game, or exit.

## Features
- User registration and login
- Cookie-based session management with expiration
- Play Hangman with 7 attempts per game
- Game words are fetched from the server
- User statistics tracked:
  - Number of games played
  - Number of wins
  - List of guessed words

## Technologies Used
- Python
- Flask
- Requests
- JSON

## How to Run
1. Start the server:  
   ```bash
   python server.py
   ```
2. Run the client:  
   ```bash
   python client.py
   ```

## API Endpoints
- `POST /register` - Register a new user
- `POST /login` - Log in an existing user
- `GET /getWords` - Retrieve words for the game
- `GET /check_cookie` - Check if the user session is active
- `POST /updateWin` - Update the user's win count
- `POST /addPlay` - Increment the user's games played count
- `POST /updateUsedWord` - Save the word used in a game
- `GET /getHistory` - Retrieve user's game history

---

Enjoy playing and improving your vocabulary!
