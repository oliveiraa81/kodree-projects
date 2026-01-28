# 🎮 MazeQuest Mini

A top-down puzzle adventure where you navigate a maze, solve puzzles, and collect treasures.

## Overview

MazeQuest Mini is an engaging browser-based puzzle game built with React and TypeScript. Players must navigate through a challenging maze, collect coins, find keys to unlock doors, avoid traps, and ultimately reach the exit. The game features a clean, modern UI with responsive controls for both desktop and mobile play.

## Features

### 🎯 Core Gameplay
- **Maze Navigation** - Navigate through a 15x12 grid maze with walls, doors, and traps
- **Coin Collection** - Collect all 4 coins scattered throughout the maze to unlock the exit
- **Score System** - Earn points by collecting coins (100 pts) and gems (500 pts)
- **Timer** - Track your completion time from start to finish

### 🔑 Keys & Doors
- **Color-coded Keys** - Find red and blue keys hidden in the maze
- **Locked Doors** - Use the matching colored key to unlock doors and access new areas

### ⚡ Interactive Elements
- **Switches** - Toggle switches to deactivate trap zones
- **Traps** - Active traps block your path until deactivated
- **Bonus Gems** - Find hidden gems for extra points

### 🎨 User Experience
- **Keyboard Controls** - Use Arrow Keys or WASD to move
- **Mobile Controls** - Touch-friendly directional buttons for mobile play
- **Visual Feedback** - Toast messages for game events (key collected, door unlocked, etc.)
- **Victory Screen** - Displays final score and completion time

## Tech Stack

- **React** - UI framework
- **TypeScript** - Type-safe JavaScript
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Styling
- **Lucide React** - Icons

## Getting Started

### Prerequisites
- Node.js installed on your system

### Installation

1. Extract the `mazequest-mini.zip` file
2. Navigate to the extracted directory
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set your Gemini API key in `.env.local` (if required)
5. Run the development server:
   ```bash
   npm run dev
   ```

## How to Play

1. Click **Start Adventure** to begin
2. Use **Arrow Keys** or **WASD** to move your character
3. Collect all **4 coins** to unlock the exit
4. Find **colored keys** to open matching doors
5. Locate and toggle **switches** to deactivate traps
6. Reach the **exit** to complete the level

**Tip:** Explore carefully and remember where you found each key!

## License

This project was created with AI Studio.
