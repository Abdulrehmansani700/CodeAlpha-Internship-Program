# CodeAlpha Internship - Python Programming Tasks
Welcome to my repository for the **CodeAlpha Internship Program**. This repository contains the source code and implementations for the assigned Python programming tasks, focusing on interactive console applications, data structures, and file handling.

---

## 🚀 Repository Overview
This repository includes two primary tasks implemented using interactive Python notebooks (`.ipynb`):
1. **Task 01: Interactive Hangman Game** - A classic word-guessing game with visual representation.
2. **Task 02: Stock Portfolio Tracker** - A lightweight financial utility to simulate and track stock investments.

---

## 🎮 Task 01: Hangman Game
A fully interactive, console-based **Hangman Game** where the player tries to guess a hidden word chosen randomly from a predefined library by guessing letters one by one.

### Key Features
* **Visual Hangman Stages:** Features custom ASCII art that dynamically updates with every wrong guess.
* **Robust Input Validation:** Prevents the user from entering multiple characters, non-alphabetic symbols, or repeating already guessed letters.
* **Dynamic State Tracking:** Displays remaining wrong guesses left and alphabetically shows all letters guessed so far.
* **Replayability:** Includes a continuous game loop allowing the user to play multiple rounds without restarting the script.

### Word Database
The game randomly selects from a diverse list of technical and general words:
`"python"`, `"hangman"`, `"programming"`, `"computer"`, `"laptop"`

---

## 📈 Task 02: Stock Portfolio Tracker
A dynamic **Stock Portfolio Management System** that allows users to simulate the purchase of various stocks, view their real-time portfolio breakdown, and export their investment summary.

### Predefined Market Data
The application handles real-time calculation based on the following asset prices:
* **AAPL:** $180
* **TSLA:** $250
* **GOOGL:** $140
* **AMZN:** $175
* **MSFT:** $380

### Key Features
* **Interactive Input Loop:** Allows users to continuously add available stock tickers and custom quantities until typing `done`.
* **Instant Valuation:** Dynamically calculates individual holding totals as well as the absolute total investment amount.
* **Persistent File Storage:** Offers an option to automatically export the final portfolio summary and financial breakdown into a clean text file (`portfolio_result.txt`).
* **User-friendly Validation:** Alerts the user if a requested stock ticker is invalid or currently unavailable.

---

## 🛠️ Requirements & Installation
To run these notebooks locally, you need Python installed along with Jupyter Notebook or JupyterLab.
