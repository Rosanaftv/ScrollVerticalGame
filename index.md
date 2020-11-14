<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="./styles/game.css">
  <link rel="stylesheet" href="./styles/countersStyles.css">
  <title>Vertical scroll game Reboot proyect</title>
</head>

<body>
  <div id="menu">
    <button id="startButton">¡Start game!</button>

  </div>
  <section id="background">
    <header>
      <div id="headerTitles">
        <h1>Lives</h1>
        <h1>Points</h1>
      </div>
      <div id="headerCounters">
        <label id="livesCounter" class="headerInfoBoxes">
          <div id="livesContainer">
            <img id="live1" src="./assets/images/spaceships/player1.png">
            <img id="live2" src="./assets/images/spaceships/player1.png">
            <img id="live3" src="./assets/images/spaceships/player1.png">
          </div>
        </label>
        <label id="pointsCounter" class="headerInfoBoxes">
          00000
        </label>
      </div>
    </header>
    <div id="game">

    </div>
  </section>
  <script src="./scripts/main.js" type="module"></script>
</body>

</html>