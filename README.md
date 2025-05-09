# Color Vision Game

A simple color perception game built with JavaScript.  
Players must identify the button with a slightly different color from the rest to progress through levels.

## 🕹️ Gameplay

- A grid of buttons is displayed.
- One button has a different color from the others.
- Click the correct button to go to the next level.
- Every 4 levels, the grid expands (e.g., from 2×2 to 3×3, and so on).
- The game gradually becomes more challenging with more buttons.

## 🛠️ Current Features

- Dynamic button grid generation (`createBtns`)
- Randomly selected target button (`selectBtn`)
- Click event handling (`addListener`)
- Level progression and grid scaling (`nextLevel`)

## 🚧 Known Issues

- Button colors do not update correctly between levels.
- No visual feedback on incorrect clicks.

## 📁 Tech Stack

- HTML / CSS / JavaScript (Vanilla JS)

## 📌 Future Improvements

- Add color transition between levels
- Gradually reduce color difference between buttons to increase difficulty
- Visual or sound feedback on correct/incorrect actions
- Timer and scoring system