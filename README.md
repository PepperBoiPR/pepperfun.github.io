<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Game Portal</title>
  <style>
    body {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4, #fbc2eb, #8fd3f4, #84fab0);
      background-size: 400% 400%;
      animation: gradientAnimation 15s ease infinite;
    }

    @keyframes gradientAnimation {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    h1 {
      font-size: 3em;
      font-weight: bold;
      color: #ffffff;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
      margin-bottom: 30px;
    }

    .container {
      display: grid;
      grid-template-columns: repeat(5, 150px); /* 5 boxes per row */
      gap: 20px;
    }

    .rectangle {
      width: 150px;
      height: 150px;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column; /* Stack text vertically */
      color: white;
      font-size: 1.2em;
      font-weight: bold;
      text-align: center;
      border-radius: 10px;
      cursor: pointer;
      transition: transform 0.3s;
    }

    .rectangle:hover {
      transform: scale(1.1);
    }

    .tictactoe { background-color: #ff6f61; }
    .drawing { background-color: #6ab04c; }
    .hangman { background-color: #4b7bec; }
    .maze { background-color: #f39c12; }
    .memory { background-color: #9b59b6; }
    .sudoku { background-color: #e74c3c; }
    .geoquiz { background-color: #1abc9c; }
    .pingpong { background-color: #3498db; }
    .snakegame { background-color: #2ecc71; }
    .colormatch { background-color: #f1c40f; }
    .whackamole { background-color: #e67e22; }
    .passwordgame { background-color: #8e44ad; }
    .football { background-color: #16a085; }
    .mapsearch { background-color: #00cec9; }
    .cookieclicker { background-color: #d35400; }
    .dino { background-color: #FFA500; } /* Orange for Dino Game */
    .minesweeper { background-color: #95a5a6; } /* Minesweeper box styling */
    .spaceshooter { background-color: #2c3e50; } /* Deep Midnight Blue for Space Shooter */
    
    a {
      text-decoration: none;
      color: inherit;
    }
  </style>
</head>
<body>
  <h1>Game Portal</h1>
  <div class="container">
    <div class="rectangle tictactoe">
      <a href="tictactoe.html">Tic Tac Toe</a>
    </div>
    <div class="rectangle drawing">
      <a href="Drawing.html">Drawing Game</a>
    </div>
    <div class="rectangle hangman">
      <a href="hangman.html">Hangman</a>
    </div>
    <div class="rectangle maze">
      <a href="maze.html">Maze</a>
    </div>
    <div class="rectangle memory">
      <a href="memory.html">Memory Game</a>
    </div>
    <div class="rectangle sudoku">
      <a href="sudoku.html">Sudoku</a>
    </div>
    <div class="rectangle geoquiz">
      <a href="geoquiz.html">Geo Quiz</a>
    </div>
    <div class="rectangle pingpong">
      <a href="pingpong.html">Ping Pong</a>
    </div>
    <div class="rectangle snakegame">
      <a href="snakegame.html">Snake Game</a>
    </div>
    <div class="rectangle colormatch">
      <a href="colormatch.html">Color Match</a>
    </div>
    <div class="rectangle whackamole">
      <a href="whackamole.html">Whack-a-Mole</a>
    </div>
    <div class="rectangle passwordgame">
      <a href="passwordgame.html">Password <br> Game</a>
    </div>
    <div class="rectangle football">
      <a href="football.html">Football</a>
    </div>
    <div class="rectangle mapsearch">
      <a href="mapsearch.html">Map Search</a>
    </div>
    <div class="rectangle cookieclicker">
      <a href="cookieclicker.html">Cookie Clicker</a>
    </div>
    <div class="rectangle dino">
      <a href="endless_runner.html">Dino Game</a>
    </div>
    <div class="rectangle minesweeper">
      <a href="minesweeper.html">Minesweeper</a>
    </div>
    <!-- Space Shooter box -->
    <div class="rectangle spaceshooter">
      <a href="asteroid_crusher.html">Space Shooter</a>
    </div>
  </div>
</body>
</html>
