<h1>Minesweeper AI with Propositional Logic</h1>
This is an AI program that plays the classic Minesweeper game using propositional logic. The program uses logical inference and knowledge representation techniques to reason about the game board and make intelligent moves.

The program is written in Python 3 and uses the PySAT library to handle the logical reasoning. The Pygame library is used for the graphical interface.

<b>Installation</b>
<br />
<ol>
  <li>Clone this repository to your local machine.</li>
  <li>Install the required dependencies by running pip install -r requirements.txt in your terminal.</li>
</ol>

<b>Usage</b>
<br />
To run the Minesweeper AI program, simply run the minesweeper.py file in your terminal using Python 3.

Once the game is launched, you can use your mouse to click on a cell to reveal it, or right-click to flag it as a mine. The AI will make its moves automatically based on the logical inferences it has made about the game board.

<b>How it Works</b>
<br />
The program works by first representing the game board as a set of logical propositions. Each cell on the board is represented as a propositional variable that can take on the values of either being a mine or not being a mine.

The program then applies logical inference techniques to deduce information about the game board based on the cells that have already been revealed. It uses this information to make intelligent moves that minimize the risk of hitting a mine.
