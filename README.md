# 2048 Game

## Introduction

Welcome to the **2048 Game** — a classic single-player sliding tile puzzle built from scratch with JavaScript. The goal of the game is to combine tiles with the same numbers and reach the **2048 tile**.

The game features a responsive interface, smooth tile animations, score tracking, and different game states for winning and losing.

### Key Features

- **Classic 2048 Gameplay**: Fully functional 4x4 game board with tile movement and merging mechanics.
- **Keyboard Controls**: Play the game using the arrow keys (`↑`, `↓`, `←`, `→`).
- **Score Tracking**: The current score is updated automatically whenever tiles are merged.
- **Game States**: The game supports `idle`, `playing`, `win`, and `lose` states with corresponding UI messages.
- **Restart Functionality**: Restart the game and begin a new round at any time.
- **Responsive Design**: The game interface adapts to different screen sizes.
- **Tile Animations**: Smooth animations are used for tile movement and merging.
- **Modular Codebase**: Game logic is separated from DOM manipulation, making the code easier to maintain.

## Challenges

Developing the 2048 game involved several challenges, especially when implementing the game mechanics and keeping the interface synchronized with the game state.

### Key Challenges

1. **Tile Movement and Merging**: Implementing the correct movement and merging logic while preventing tiles from being merged more than once during a single move.
2. **Game State Management**: Managing different game states and updating the interface depending on the current state of the game.
3. **Score Calculation**: Correctly calculating and updating the score after every successful tile merge.
4. **Responsive Design**: Adapting the game board and interface for different screen sizes.
5. **Animations**: Implementing tile movement and merge animations while keeping the game interaction smooth.

## Technical Requirements

To run this project locally, you will need:

- A modern web browser such as Chrome, Firefox, Safari, or Edge.
- **Node.js** 14.x or newer.
- **NPM** 6.x or newer.

## Installation and Setup

To install and run the project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/nyarachun/2048-game.git
```

2. Navigate to the project directory:

```bash
cd 2048-game
```

3. Install the dependencies:

```bash
npm install
```

3. Start the development server:
```bash
npm start
```

## Usage

After starting the project, open the local development server in your browser.

Use the arrow keys to move the tiles:

- `↑` — move tiles up
- `↓` — move tiles down
- `←` — move tiles left
- `→` — move tiles right

Combine tiles with the same value to increase your score and try to reach **2048**.

## Example

- [DEMO LINK](https://nyarachun.github.io/2048-game/)

## Technologies Used

This project was built using the following technologies:

- **HTML5** — for the structure and semantic layout.
- **SCSS** — for styling, variables, and animations.
- **JavaScript (ES6)** — for game logic, DOM manipulation, and event handling.
- **Parcel** — for bundling the web application.
- **Git** — for version control.
- **GitHub Pages** — for hosting the live demo.

## Design Specifications

- **Desktop**: 1280px
- **Tablet**: 640px
- **Mobile**: 320px+
