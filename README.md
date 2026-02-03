🎮 Interactive Tic-Tac-Toe
A sleek, responsive, and logic-driven Tic-Tac-Toe game built with vanilla web technologies. This project demonstrates my ability to manage application state, implement game logic, and create a seamless UI/UX without external frameworks.
🌟 Key FeaturesReal-time Logic: Instant win/draw detection using coordinate-based arrays.Dynamic 
UI: Responsive grid layout that provides visual feedback on hover.
Game State Management: Ability to restart the session without refreshing the page.
Clean Code: Written with a focus on modular functions and readable JavaScript.
🛠️ Tech StackStructure: HTML5Styling: CSS3 (Grid System & Transitions)Logic: Vanilla JavaScript (ES6+)
🕹️ How to PlayOpen the tic-tac-toe.aap.html file in any modern web browser.Player X starts the game by clicking any empty cell.Players take turns until one matches 3 symbols horizontally, vertically, or diagonally.If the board fills up without a winner, the game declares a Draw.Click "Restart Game" to reset the board and play again!
🧠 Logic HighlightsThe game evaluates winning patterns using a 2D-mapped array logic:JavaScriptconst winConditions = [
  [0,1,2], [3,4,5], [6,7,8], // Rows
  [0,3,6], [1,4,7], [2,5,8], // Columns
  [0,4,8], [2,4,6]           // Diagonals
];
This ensures the game remains lightweight while maintaining $O(1)$ efficiency for win-checking.📈 Future Enhancements[ ] Add an "Unbeatable" AI mode using the Minimax algorithm.[ ] Implement dark mode support.[ ] Sound effects for winning/clicking.👨‍💻 About MeI am a recent MCA graduate passionate about Full-Stack development. I love turning complex logic into simple, beautiful user experiences.
