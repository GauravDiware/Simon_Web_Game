🎮 Simon Says Game

💡Welcome to the Simon Says Game — a fun and interactive memory challenge built using HTML, CSS, and JavaScript!

🧠 How to Play
1.	Press any key to start the game.
2.	The game will flash a color pattern (starting with one color).
3.	Click the buttons in the same order as the pattern.
4.	If you get it right, the next level adds another color.
5.	The game ends when you press a wrong button.
6.	Your score is the last level you reached.

🎯 Game Features
•	✅ Easy-to-understand UI
•	✅ Level tracking
•	✅ Pattern grows as you progress
•	✅ Visual feedback for both game and user inputs
•	✅ Game Over screen with score display

🛠️ Tech Stack
Technology	Description
HTML5	Markup structure
CSS3	Styling and animations
JavaScript	Game logic & DOM interaction

🧾 Project Structure
bash
CopyEdit
simon-game/
│
├── index.html      # Main game page with embedded styles & JS
├── simon.js        # (Optional) JS file if you extract script separately
├── simon.css       # (Optional) CSS file if you extract style separately
└── README.md       # Project documentation

📄 Code Explanation (Highlights)
•	gameSeq[]: Stores the randomly generated pattern.
•	userSeq[]: Stores the player's inputs.
•	checkAns(): Compares user input to game sequence.
•	levelUp(): Moves to next level and flashes new color.

📦 How to Run Locally
1.	Clone this repository
bash
CopyEdit
git clone https://github.com/GauravDiware/Simon_Web_Game.git
cd simon-game
2.	Open index.html in your browser
Double-click or right-click and choose “Open with Live Server”.

👨‍💻 Author
Gaurav Diware
Student at LSPGCOER
Feel free to connect or contribute!

