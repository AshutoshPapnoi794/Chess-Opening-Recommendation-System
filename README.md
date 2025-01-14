# Chess Opening Recommendation System

## Overview

This project implements a chess opening recommendation system using machine learning techniques and leverages the Stockfish chess engine for advanced analysis. The system analyzes chess game data to suggest optimal openings for a given player and provides insights into game performance, including blunder detection and accuracy calculation.

## Features

* **Popular Opening Analysis:** Identifies and visualizes the most frequently played chess openings in the dataset, along with their success rates.
* **KNN-Based Opening Recommendation:** Recommends openings based on the K-Nearest Neighbors algorithm, considering player ratings and game characteristics.
* **Personalized Opening Recommendation (Cosine Similarity):** Offers personalized opening recommendations by finding players with similar opening preferences using cosine similarity and suggesting openings that have performed well for them.
* **Anomaly Detection (Isolation Forest):** Detects potentially unusual or suspicious games based on player ratings and game performance using the Isolation Forest algorithm.
* **Blunder Detection with Stockfish:** Utilizes the Stockfish chess engine to identify blunders made during a game and suggest better moves.
* **Accuracy Calculation with Stockfish:** Calculates the move accuracy for both players in a given game using Stockfish's evaluation.
* **Move Probability Heatmaps:** Visualizes the probability of knight and bishop moves to specific squares on the chessboard.
* **Event Type Popularity:** Analyzes and displays the popularity of different chess event types.
* **Title Holder Analysis:**  Counts and visualizes the number of players holding different chess titles.

## Datasets

The project utilizes two datasets:

1. **`chess_data.csv`:**  A dataset containing information about online chess games, including player ratings, opening names, moves, and game outcomes.
2. **`chess_data2.csv`:** Another dataset containing detailed chess game information, including move evaluations and timestamps.

## Models Implemented

* **K-Nearest Neighbors (KNN):** Used for recommending openings based on similarities in game features.
* **Cosine Similarity:**  Used to find players with similar opening preferences for personalized recommendations.
* **Isolation Forest:**  Employed for detecting anomalous chess games.

## Libraries Used

* **pandas:** For data manipulation and analysis.
* **matplotlib:** For creating static, interactive, and animated visualizations in Python.
* **seaborn:** A Python data visualization library based on matplotlib.
* **scikit-learn (sklearn):** For machine learning tasks, including model building, preprocessing, and evaluation.
* **stockfish:** A Python library to interface with the Stockfish chess engine.
* **chess:** A Python library for working with chess games and positions.
* **numpy:** For numerical computations.
* **collections.Counter:** For counting hashable objects.
* **IPython.display:** For displaying chess boards within Jupyter Notebooks.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AshutoshPapnoi794/Machine-learning
   cd Machine-learning
