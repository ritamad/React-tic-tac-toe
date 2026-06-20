#  React Tic-Tac-Toe (Work in Progress)

A dynamic, production-grade Tic-Tac-Toe game built with **React** and **Vite**. This project serves as a practical deep dive into advanced state management patterns, component scalability, and optimization techniques.

## Status: In Development
This repository tracks my active learning journey. I am building this app piece by piece, focusing on clean architecture and strict React best practices.

## Core Concepts & Patterns Explored
So far, this project features:
* **Two-Way Data Binding:** Applied to handle real-time user inputs dynamically for player name customization.
* **Lifting State Up:** Centralized the game turns history into the closest common ancestor (`App` component) to synchronize multi-directional data flow between separate sibling components.
* **State Immutability:** Enforced safe state updates by deep-cloning multidimensional arrays/objects using modern JavaScript (`.map()` and the spread operator `...`).
* **Derived State (Computed Values):** Optimized app performance and eliminated redundant state bugs by deriving the `gameBoard` layout and the `activePlayer` identity directly from a single source of truth (`gameTurns`).

## 🛠️ Tech Stack
* React 19 (Hooks, Functional Components)
* Vite (Build tool)
* Modern CSS
