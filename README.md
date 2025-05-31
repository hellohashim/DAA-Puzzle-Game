🎯 Heads Up: Coin Flip Puzzle Game (DAA Project)
Welcome to Heads Up, a puzzle game and algorithm simulation based on a classic Design & Analysis of Algorithms (DAA) challenge. Your goal? Flip coins to make them all heads up in the minimum number of moves!

📌 Problem Statement
You are given n coins in a line, randomly showing either heads (H) or tails (T).

🔁 On each move, you can flip any number of consecutive coins.

🎯 Objective: Turn all coins to heads using the minimum number of moves.

🧠 Algorithms Used
This puzzle is solved using two strategies:

✅ Algorithm 1: Greedy Flip
Flip each group of consecutive tails immediately.

Skips over heads.

🔁 Repeats until all are heads.

Time Complexity: Θ(n)

Best For: Mixed patterns with frequent tails.

🔄 Algorithm 2: Transform & Conquer
Push all non-heads (tails) to the end using swaps.

Then flip them all at once.

Time Complexity: Θ(n)

Best For: All tails at the start.


🕹️ Game Modes
🌐 Web Game (HTML/CSS/JavaScript)
An interactive drag-and-play browser game featuring:

🎨 Visually designed coins (via Figma)

🔁 Manual play with drag/drop or click-to-flip

⚙️ Auto-solve with Algorithm 1 or 2

🎯 Changeable goals (Heads or Tails)

📊 Move tracking + minimum moves indicator

🎉 Confetti animations on winning!

💡 Built using HTML, CSS, and JavaScript

Designed for learning and simulation

🚀 Getting Started
📦 Run the Web Version

1. Clone the repository:
bash
git clone https://github.com/your-username/heads-up-puzzle.git
cd heads-up-puzzle

2. Open index.html in your browser.

🎓 Educational Value
This project was developed as a part of the DAA course at Bahria University Islamabad, and demonstrates:

Real-world applications of greedy algorithms and transform-and-conquer

Creative problem-solving through interactive game development

Analytical comparison between algorithmic approaches

👨‍💻 Authors
M. Hashim Nazir
Humayun Tariq 

📄 License
MIT License — free to use, modify, and share.
