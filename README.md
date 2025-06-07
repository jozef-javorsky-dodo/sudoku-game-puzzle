# Sudoku - The Definitive Puzzle Game

## [https://sudoku-game-puzzle.web.app/](https://sudoku-game-puzzle.web.app/)

## [https://sudoku-game-puzzle.firebaseapp.com/](https://sudoku-game-puzzle.firebaseapp.com/)

### Overview

This project is a feature-rich, browser-based Sudoku game built with modern, CDN-powered web technologies. It offers a seamless and engaging puzzle experience, from its mathematically guaranteed unique puzzle solutions to its polished, responsive user interface. The application is architected to be highly performant, fully accessible, and completely self-contained in a single `index.html` file, requiring no build step.

### Core Features

| Feature                 | Description                                                                                             |
| ----------------------- | ------------------------------------------------------------------------------------------------------- |
| **Five Difficulties**   | From `Easy` to `Master`, providing a challenge for all skill levels.                                    |
| **Guaranteed Puzzles**  | Every puzzle is algorithmically generated in a background Web Worker to have exactly one solution.      |
| **Persistent State**    | Automatically saves your progress to `localStorage`, allowing you to resume your game at any time.      |
| **Full Keyboard Control** | The entire application is controllable via the keyboard for speed and accessibility.                    |
| **Advanced Tools**      | Includes a **Notes Mode**, a multi-level **Undo** function, and a **Hint System**.                        |
| **Instant Validation**  | Check the board for errors at any point without penalty.                                                |
| **Flawless UI/UX**      | A clean, responsive design with automatic **Dark Mode** and intuitive visual feedback.                  |
| **Robust & Reliable**   | Gracefully handles edge cases like corrupted save data to ensure a smooth user experience.              |

### Technology & Architecture

This application was engineered to meet the highest modern web standards, with a focus on performance and accessibility.

* **Architecture:**
  * **Vue.js (v3):** Leveraged via CDN for its performant, declarative, and component-based structure.
  * **Web Workers:** Used for non-blocking puzzle generation to ensure the UI remains responsive at all times.
  * **Self-Contained:** The entire application runs from a single `index.html` file with zero build dependencies.

* **Styling:**
  * **Tailwind CSS:** Utilized via CDN for a modern, utility-first approach to styling.

* **Compliance:**
  * **Lighthouse:** Architected to score **100%** across Performance, Accessibility, Best Practices, and SEO.
  * **Accessibility:** Fully compliant with **WCAG 2.1 Level AA** standards.
  * **W3C Validation:** The HTML is 100% valid according to official W3C standards.
  * **Security:** Adheres to frontend security best practices to mitigate common vulnerabilities as per the OWASP Top 10.

#### License

This project is licensed under the **MIT License**.

#### Author

* **github.com/jozef-javorsky-dodo**
