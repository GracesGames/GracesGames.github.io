---
layout: post
title:  Sokoban - Goof Troop
date:   2017-07-23 01:00:00 +0200
categories: XNA/MonoGame Windows
image: ../assets/images/sokoban_goof_troop/Sokoban-Index-Image.png
---

My second game, or actually a trimmed down clone, of the SNES game [Goof Troop][wikipedia-goof-troop]. This game featured physics and real-time movement given the player a fun puzzle game that is inspired by the [Sokoban][wikipedia-sokoban] puzzles.

This game was developed in C# using the [XNA framework][wikipedia-xna] just like [Stratego - Knights and Merchants][gg-stratego]. The developed 2D tile engine was extended to simulate the physics and determine the win condition (every cube is correctly place on the empty spots). Sprites and songs were ripped from the Goof Troop ROM and other online sources.

The GIF below shows the main game mechanic, the player kicking the cubes into one direction.

{:.p-center}
![Main game mechanic]({{ site.url }}/assets/images/sokoban_goof_troop/Kicking-Mechanic.gif)

All twelve puzzles from Goof Troop were implemented in some form or another to fit the game. Below two puzzles are shown.

<DIV class="figure-block">
    <figure class="center-image">
        <img src="{{site.url}}/assets/images/sokoban_goof_troop/Level1.png" alt="Goof Troop Level 1"/>
        <figcaption>Goof Troop Level 1</figcaption>
    </figure>
    <figure class="center-image">
        <img src="{{site.url}}/assets/images/sokoban_goof_troop/Level2.png" alt="Goof Troop Level 2"/>
        <figcaption>Goof Troop Level 2</figcaption>
    </figure>
</DIV>

The game is currently not in development anymore even though it has been successfully converted to the [MonoGame framework][monogame] since the XNA framework is discontinued. It is not available online because copyright laws would be violated, but should be seen as a tribute to the classic Goof Troop game. It's puzzle concept is however reused in the game [Kick-It][gg-kick-it].

[wikipedia-goof-troop]: https://en.wikipedia.org/wiki/Goof_Troop_(video_game)
[wikipedia-sokoban]: https://en.wikipedia.org/wiki/Sokoban
[wikipedia-xna]: https://en.wikipedia.org/wiki/Microsoft_XNA
[gg-stratego]: {% post_url 2017-07-23-Stratego-Knights-and-Merchants %}
[monogame]: http://www.monogame.net
[gg-kick-it]: {% post_url 2017-07-23-Kick-It %}
