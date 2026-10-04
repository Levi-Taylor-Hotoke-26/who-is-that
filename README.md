# Who's That Pokémon?

A browser game inspired by the classic "Who’s That Pokémon?" reveal.
You get a silhouetted sprite, type your guess, and build a streak of correct answers.

![Who's That Pokémon gameplay](https://github.com/user-attachments/assets/7796be76-13ff-4f66-ab0b-d826a2658d38)

## Features

- Random Pokémon silhouette challenge
- Enter-to-submit guessing flow
- Streak tracking
- Animated reveal after each guess
- Pokémon-themed styling and background

## Built With

- HTML
- CSS
- JavaScript (ES Modules)
- [PokéAPI](https://pokeapi.co/)

## Getting Started

### Prerequisites

- A modern web browser

### Run Locally

1. Clone the repository.
2. Open `/home/runner/work/who-is-that/who-is-that/index.html` in your browser.

> This project is fully client-side and does not require a backend server.

## How to Play

1. A hidden Pokémon sprite appears.
2. Type your guess in the input box.
3. Press **Enter**.
4. If your guess is correct, your streak increases.
5. The Pokémon is revealed and a new round starts automatically.

## Project Structure

- `/home/runner/work/who-is-that/who-is-that/index.html` – page structure
- `/home/runner/work/who-is-that/who-is-that/main.css` – styling and layout
- `/home/runner/work/who-is-that/who-is-that/main.js` – game logic and API integration

## Notes

- Pokémon names are validated case-insensitively.
- The current pool uses the first 665 Pokémon from the API list.
