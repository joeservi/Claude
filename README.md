# Android HTML Games - ACode Edition

Create and run JavaScript HTML games on your Android device using ACode.

## How to use

1. **Describe a game** - Tell Claude what game you want to build
2. **Claude generates it** - I'll create the HTML/JavaScript files
3. **Copy to ACode** - Transfer the files to your Android device
4. **Run in ACode** - Open and run directly in ACode

## Project Structure

```
games/
  └── [game-name]/
      ├── index.html      (Main game file)
      ├── game.js         (Game logic - optional)
      └── styles.css      (Styling - optional)
```

## Quick Start

To play a game:
1. Open the game's folder in ACode
2. Open `index.html` 
3. Use ACode's preview/run feature or open in browser

## Available Games

- **clicker-game** — Incremental/idle clicker with upgrades
- **snake-game** — Classic snake with touch controls
- **tower-defender** — Full 3D (three.js) perspective turret defense. Sweep your turret to fire down a battlefield as enemies advance from the distance; earn coins, spend them in an offense/defense upgrade shop, and build up to 4 auto-turrets. Adaptive difficulty ramps faster the harder you dominate. Uses WebGL with bloom post-processing; three.js is vendored locally in `tower-defender/vendor/` so it runs offline.

Check the `games/` folder for pre-built games ready to play!
