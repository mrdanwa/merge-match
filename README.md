# CubePairs

**CubePairs** is a web-based puzzle game that challenges players to clear a grid by selecting and merging shapes strategically. The game offers four difficulty levels: **Easy**, **Medium**, **Hard**, and **Impossible**.

## 📜 Game Rules

- **Objective**: Clear the grid in as few moves as possible.
- **How to Play**:
  1. Select two cells.  
  2. If the shapes in the cells match, both cells are cleared.  
  3. If they don’t match, the second cell updates to a "mix" (XOR) of both patterns.  
  4. Follow the specific rules based on the selected difficulty level.

## 🎮 Difficulty Levels
1. **Easy**: Select any two cells.
2. **Medium**: Select two cells in the same row, column, or diagonal.
3. **Hard**: Select two cells in the same row or column.
4. **Impossible**: The second cell must be adjacent to the first.

## 🛠️ Features
- **Responsive Design**: Works well on both desktop and mobile devices.
- **Interactive Grid**: Dynamic grid with animated cell selection.
- **Customizable Levels**: Adjust your challenge with four levels of difficulty.
- **Randomized Gameplay**: New patterns generated for every restart.

## 🧩 Gameplay Mechanics
- **Grid**: 4x4 grid where each cell contains a shape made of 2x2 blocks.
- **Shape Logic**: Shapes "merge" based on the XOR operation when selected.

## 💻 Technologies Used
- HTML5
- CSS3
- Vanilla JavaScript

## 📜 License
This project is licensed under the **MIT License**.

