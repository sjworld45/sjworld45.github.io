<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="index.css" />
    <title>Ping Pong</title>
  </head>
  <body>
    <div class="modal-container">
      <div class="modal">
        <div class="prev-score"><h1>0</h1></div>
        <div class="buttons">
          <button class="start">Start</button>
        </div>
      </div>
    </div>
    <div class="left_btn"></div>
    <main>
      <h1>PONG</h1>
      <div class="container">
        <div class="bat" style="position: relative; left: 150; top: 0"></div>
        <div class="ball" style="position: relative; left: 0; top: 0"></div>
      </div>
      <div class="scoresheet">
        <div class="score-container">
          <h2 class="score-label">Score:</h2>
          <span class="score">0</span>
        </div>
        <div class="high-score-container">
          <h2 class="high">High Score:</h2>
          <span class="high-score">0</span>
        </div>
      </div>
    </main>
    <div class="right_btn"></div>
  </body>
  <script src="index.js" defer></script>
</html>
