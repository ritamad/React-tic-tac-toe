# React Tic-Tac-Toe

Live Demo: https://ritamad.github.io/React-tic-tac-toe/

A dynamic, production-grade Tic-Tac-Toe game built with React and Vite. This project represents a practical deep dive into advanced state management patterns, component scalability, optimization techniques, and clean code architecture.

The application is fully completed, architectural processes have been streamlined, and the interface features a custom minimalist design.

---

## Core Concepts & Patterns Explored

- **Lifting State Up:** Centralized the game turns history into the closest common ancestor (the `App` component) to synchronize multi-directional data flow between separate sibling components.
- **Derived State (Computed Values):** Optimized application performance and eliminated redundant state bugs by deriving the `gameBoard` layout, the active player identity, and the winner announcement directly from a single source of truth (`gameTurns`).
- **Two-Way Data Binding:** Applied to handle real-time user inputs dynamically for player name customization and state preservation.
- **State Immutability:** Enforced safe state updates by deep-cloning multidimensional arrays and objects using modern JavaScript (`.map()` and the spread operator `...`).
- **Architectural Refactoring:** Extracted complex computation logic into independent pure helper functions (`deriveWinner` and `deriveGameBoard`), keeping the main React components lean, readable, and maintainable.

---

## UI Redesign & Customization

The user interface has been completely overhauled from the standard course template to achieve a unique visual identity:

- **Muted Pastel Palette:** Replaced the original yellow and brown layout with a sophisticated combination of deep purple for the game containers and muted mint/sage green for active player highlights, symbols, and game over overlays.
- **Minimalist High-Contrast Layout:** Set against an absolute black background, the clean and geometric interface is designed to maximize readability and focus strictly on the gameplay experience.

---

## Tech Stack

- **React** (Hooks, Functional Components)
- **Vite** (Build tool)
- **Modern CSS** (Flexbox, Grid, Custom Keyframe Animations)
