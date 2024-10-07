
# Chess Engine: Human vs AI

## Project Overview

This project is a Python-based chess engine, that I developed with a partner in a group of two in Artificial Intelligence course back in my undegraduate studies. This chess engine pits a human player against an AI opponent with Artificial Intelligence characteristics, leveraging deep learning techniques. The chess engine is built using `Pygame` and incorporates various algorithms such as MinMax for AI decision-making.

### Project Partners:
- Mahathir F Nabil 
- Md. Muntasir Mahmud 
---

## Features

- **Human vs AI Chess**: Engage in a classic chess game against an AI-powered opponent.
- **AI Algorithms**: The AI employs the MinMax algorithm to simulate intelligent decision-making.
- **Custom Board & Piece Movements**: Implement custom logic for valid moves, checkmate detection, and board highlighting.
- **Future Enhancements**: Includes plans for Alpha-beta pruning, user-friendliness improvements, and AI hints for human players.

---

## Installation

1. Clone the repository:


$ git clone https://github.com/your-repo-url/chess-engine-ai.git
$ cd chess-engine-ai


2. Install the required Python packages:


$ pip install pygame


---

## How to Run

Execute the following command to start the game:


$ python chess_game.py


This will launch the chess engine with a graphical interface where you can compete against the AI opponent.

---

## Module Overview

### Main Components:
- **GameState**: Manages the state of the game, including piece positions and game rules.
- **Pygame Functions**: Manages the rendering of the game, user input, and graphical updates.

### AI Components:
- **ChessAI**: Implements the MinMax algorithm for decision-making.
- **Move Class**: Handles the logic for valid moves, including special chess conditions like checkmate.

---

## Future Scope

- **Alpha-beta Pruning**: Enhance the AI's performance with a 7-step look-ahead mechanism.
- **AI Hints**: Add hints for the human player to improve gameplay.
- **User Interface**: Improve the game's usability and visual design for a better experience.

---

## Motivation

The motivation behind this project is to explore AI algorithms, deep learning, and their implementation in a real-world application such as chess. We aim to deepen our understanding of decision-making algorithms and their practical use cases in AI-powered games.

---

Feel free to adapt and expand upon this README as your project evolves.
