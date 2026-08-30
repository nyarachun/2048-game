# 2048 Game

A classic single-player sliding tile puzzle game built from scratch. The objective is to slide numbered tiles on a grid to combine them and create a tile with the number 2048. 

## Live Preview
Experience the live website: [2048 game Demo](https://nyarachun.github.io/2048-game/)

## Technologies Used
* **HTML5** – Structure and semantic layout
* **SCSS** – Styling, variables, and keyframe animations
* **JavaScript** – Game logic, DOM manipulation, and event handling
* **Parcel** – Web application bundler

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/your-username/project-name.git
cd project-name
```

3. Install dependencies:
```bash
npm install
# or
yarn install
```


3. Run the project locally:
```bash
npm start
# or
yarn start
```

## Features
* **Keyboard Controls:** Fully playable using standard keyboard arrow keys (`↑`, `↓`, `←`, `→`).
* **Classic Game Logic:** Fully functional 4x4 grid with accurate tile generation, movement, and merging mechanics.
* **Score Tracking:** Real-time score updates as tiles merge.
* **Dynamic Game States:** Built-in tracking for 'idle', 'playing', 'win' and 'lose' states, complete with dynamic UI messages.
* **Modular Codebase:** Clean separation of concerns with a dedicated `Game` class for logic and a separate script for DOM interaction.
