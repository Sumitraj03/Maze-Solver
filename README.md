# Maze Solver Project

This project is a web-based maze solver that visually demonstrates three popular pathfinding algorithms: **Breadth-First Search (BFS)**, **Depth-First Search (DFS)**, and **A\* Search**.

### Features
* **Dynamic Maze Generation**: The project creates a new, solvable maze every time the page is loaded.
* **Algorithm Visualization**: It highlights the path found by the selected algorithm, allowing users to compare how each one works. The paths are colored differently for easy identification:
    * **BFS**: Green
    * **DFS**: Sky Blue
    * **A\***: Dark Pink
* **User Controls**: You can select an algorithm from a dropdown menu, solve the maze, and restart to generate a new one.
* **Sound Effects**: The project includes sound effects for button clicks and to indicate when the maze is being solved or if no path is found.
* **Scoreboard**: A simple counter tracks the number of paths found.

### How to Run
1.  **Clone or download** the project files.
2.  **Open `index.html`** in your web browser.

### Files
* `index.html`: The main HTML file that provides the structure of the webpage.
* `style.css`: The CSS file that handles the styling and layout of the maze and controls.
* `script.js`: The JavaScript file that contains all the logic for maze generation, algorithm implementation, and user interactions.
* `click.mp3`, `Super Fast Run after Star.mp3`, `sad.mp3`, `over.mp3`: Sound files used for various user events and aural feedback.
