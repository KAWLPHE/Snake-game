# Snake Game

Snake Game is a classic 2D arcade game where the player controls a snake, eats food, grows longer, and tries to get the highest score without hitting the wall or itself.

## Description

The goal of the game is to control the snake and collect as much food as possible. Each time the snake eats food, it becomes longer and the score increases. The game ends when the snake hits the wall or crashes into its own body.

## Features

- Classic snake gameplay
- Keyboard controls
- Score system
- Game over screen
- Restart option
- Simple and clean design
- Runs in the browser
- Beginner-friendly project

## Project Files

```text
snake-game/
│
├── index.html
├── package.json
├── tsconfig.json
├── metadata.json
└── README.md
```

## Controls

- Arrow Up / W — move up
- Arrow Down / S — move down
- Arrow Left / A — move left
- Arrow Right / D — move right
- P — pause the game
- R — restart the game

## Technologies Used

- HTML
- CSS
- JavaScript
- Node.js
- Vite
- TypeScript configuration

## How to Run

### Step 1: Open the project folder

Open the `snake-game` project folder in Visual Studio Code.

### Step 2: Open the terminal

Open the terminal inside the project folder.

You can do this in Visual Studio Code:

```text
Terminal → New Terminal
```

### Step 3: Install dependencies

Run this command:

```bash
npm install
```

### Step 4: Start the development server

Run this command:

```bash
npm run dev
```

### Step 5: Open the game

After running the command, the terminal will show a local link, for example:

```text
http://localhost:5173
```

Open this link in your browser.

## Important Note

Do not open the project by double-clicking `index.html`.

If you open it like this:

```text
file:///C:/Users/user/Downloads/snake-game/index.html
```

the page may show a blank white screen.

This project should be started with:

```bash
npm run dev
```

## Troubleshooting

If `npm run dev` does not work, check that Node.js is installed on your computer.

You can check it with:

```bash
node -v
```

You can also check npm with:

```bash
npm -v
```

If Node.js is not installed, install it first, then run:

```bash
npm install
npm run dev
```

## Author

Created as a simple web development project.
