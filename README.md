# 2048 Game

![Screenshot](src/images/preview/reference.png)

A classic 2048 game implementation with a modern twist.

Welcome to my implementation of the popular puzzle game 2048! This project showcases my skills in JavaScript, HTML, CSS, and testing with Cypress, built with a focus on clean code and user experience. Perfect for adding to your portfolio or demonstrating to potential employers!

Table of Contents
Overview
Features
Technologies Used
Installation
How to Play
Contributing
License
Contact
Overview
This 2048 game is a single-player sliding tile puzzle where the goal is to combine tiles with the same number to reach the 2048 tile. The game features a responsive design, real-time score tracking, and a restart mechanism. It was developed as a personal project to hone my front-end development skills and problem-solving abilities.

# Features
Intuitive keyboard controls (arrow keys).
Real-time score updates.
Win/lose conditions with clear feedback.
Responsive and clean user interface.
Unit and integration tests with Cypress.

# Technologies Used
HTML5: Structured the game layout.
CSS3: Styled the game board and tiles with a modern aesthetic.
JavaScript (ES6+): Implemented game logic and interactivity.
Node.js: Managed dependencies and build process.
Parcel: Bundled the project for development and production.
Cypress: Ensured robust testing of game functionality.
Git & GitHub: Version control and project hosting.
Installation

# To run this project locally, follow these steps:

Clone the Repository

`git clone https://github.com/Radymyr/2048.git
cd js_2048_game`
Install Dependencies Ensure you have Node.js and npm installed. Then run:

`npm install`
Start the Development Server Launch the game in development mode with:

`npm start`
Open your browser and navigate to http://localhost:1234 (or the port specified in the output).
Build for Production To create a production build, run:

`npm run build`
The compiled files will be available in the dist folder.
Run Tests Verify the game works as expected with:

`npm test`

# How to Play
Start the Game
Click the "Start" button to begin. The board will initialize with two tiles (2 or 4).
Move Tiles
Use the arrow keys (↑, ↓, ←, →) to slide tiles in the desired direction.
Tiles with the same number merge into their sum when they collide.
Objective
Combine tiles to reach the 2048 tile. The game ends when you win (achieve 2048) or lose (no moves left).
Game Over
If you win, a "Win" message appears.
If you lose, a "Lose" message prompts you to restart.
Click "Restart" to reset the game.
Score
Your score increases with each merge. Check the score display at the top of the screen.
Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch: git checkout -b feature-name.
Make your changes and commit: git commit -m "Add feature".
Push to the branch: git push origin feature-name.
Open a pull request.
Please ensure your code follows the project's style guidelines and passes all tests.

License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as per the license terms.

* Contact
* GitHub: Radymyr
* Email: loboda.radimir@gmail.com
* LinkedIn: https://www.linkedin.com/in/radymyr-loboda-b4020417b/
