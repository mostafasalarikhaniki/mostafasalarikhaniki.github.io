---
layout: splash
title: Morabaraba
permalink: /projects/morabaraba/
author_profile: false
---

# Morabaraba

---
<html>

<style>
    html,
    body {
        width: 100%;
    }
    img.two {
        height: 720;
        width: 562;
    }
    * {
        box-sizing: border-box;
    }
    .column {
        float: left;
        width: 50%;
        padding: 5px;
    }
    .row::after {
        content: "";
        clear: both;
        display: table;
    }
</style>

<body>
    <center>
        <img class="two" src='/files/morabaraba/gameplay-1.png'>
        <br>
        <br>
    </center>
</body>
</html>

[Morabaraba](https://en.wikipedia.org/wiki/Morabaraba) is a strategic and traditional game with its origins in Africa. In this game, two players strive to remove their opponent's pieces. Each player has 12 pieces and moves them on a 9-square board, attempting to create rows of three pieces to remove their opponent's pieces.

The Minimax algorithm is an algorithm used in decision-making games with different and alternating states. It is employed to select the best move in two-player games with a decision-making environment. This algorithm is typically used in games such as chess.

In the Minimax algorithm, the main objective is to find the best move for a player that ideally leads to a win or minimizes the maximum possible damage. The Minimax algorithm achieves this by exploring all possible game states and finding the best move through this process.

My main goal in this project has been to implement the Morabaraba game with an intelligent AI opponent. Using the Minimax algorithm, the AI opponent can anticipate the best moves of the player and choose a move that creates the worst possible conditions for the player. This makes the game challenging and engaging for the player.

If you truly want to create a game that people will want to play, I recommend using commercial engines like Unity or Unreal. These engines will greatly enhance your game and make your work easier. However, since my goal wasn't that and I wanted a bit more challenge, I decided to build the game solely using the PyQt5 library and develop its components and algorithms myself.

<center>
<video controls autoplay="autoplay" loop="true" controls muted>
  <source src="/files/morabaraba/gamepaly-movie.mp4" type="video/mp4">
</video>
</center>


In conclusion, I'm very happy with how this project turned out and I had a lot of fun making it. 

[Link to source code on GitHub.](https://github.com/m-salari/Morabaraba/)

