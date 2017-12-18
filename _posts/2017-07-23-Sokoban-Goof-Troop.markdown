---
layout: default
modal-id: 8
title:  Sokoban - Goof Troop
date: 2014-07-11
img: Sokoban-Index-Image.png
alt: Gooftroop-Sokoban
---

My second game, or actually a trimmed down clone, of the SNES game [Goof Troop][wikipedia-goof-troop]. This game featured physics and real-time movement given the player a fun puzzle game that is inspired by the [Sokoban][wikipedia-sokoban] puzzles.

This game was developed in C# using the [XNA framework][wikipedia-xna] just like _Stratego - Knights and Merchants_. The developed 2D tile engine was extended to simulate the physics and determine the win condition (every cube is correctly place on the empty spots). Sprites and songs were ripped from the Goof Troop ROM and other online sources.

The GIF below shows the main game mechanic, the player kicking the cubes into one direction.

<img src="{{ site.baseurl }}/assets/images/sokoban_goof_troop/Kicking-Mechanic.gif" class="img-responsive img-centered" alt="Main game mechanic">

All twelve puzzles from Goof Troop were implemented in some form or another to fit the game. Below two puzzles are shown.

<img src="{{ site.baseurl }}/assets/images/sokoban_goof_troop/Level1.png" class="img-responsive img-centered" alt="Goof Troop Level 1">
<img src="{{ site.baseurl }}/assets/images/sokoban_goof_troop/Level2.png" class="img-responsive img-centered" alt="Goof Troop Level 2">

The game is currently not in development anymore even though it has been successfully converted to the [MonoGame framework][monogame] since the XNA framework is discontinued. It is not available online because copyright laws would be violated, but should be seen as a tribute to the classic Goof Troop game. It's puzzle concept is however reused in the game _Kick-It_.

[wikipedia-goof-troop]: https://en.wikipedia.org/wiki/Goof_Troop_(video_game)
[wikipedia-sokoban]: https://en.wikipedia.org/wiki/Sokoban
[wikipedia-xna]: https://en.wikipedia.org/wiki/Microsoft_XNA
[monogame]: http://www.monogame.net
