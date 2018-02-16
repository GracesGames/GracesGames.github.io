---
layout: default
modal-id: 8
title:  Sokoban - Goof Troop
date: 2014-07-11
img: Sokoban-Index-Image.png
alt: Gooftroop-Sokoban
---

##### Motivation

The second game I developed is actually a trimmed down clone of the SNES game [Goof Troop][wikipedia-goof-troop].
It focuses on the [Sokoban][wikipedia-sokoban] inspired puzzles of the game.  
To challenge myself, this game featured physics and real-time movement which meant upgrading the developed engine. 

##### Gameplay

Each puzzle contains several movable cubes, and a set of goal positions. The GIF below shows the main game mechanic, the player kicking the cubes into one direction. The catch is that once a cube is moving, it can only by stopped by colliding with another level piece.

<img src="{{ site.baseurl }}/assets/images/sokoban_goof_troop/Kicking-Mechanic.gif" class="img-responsive img-centered" alt="Main game mechanic">

##### Technology

This game was developed in C# using the [XNA framework][wikipedia-xna] just like _Stratego - Knights and Merchants_.  
The developed 2D tile engine was extended to simulate physics and determine the new win condition (every cube is correctly placed on the empty spots).  
Sprites and songs were ripped from the Goof Troop ROM using third-party tools.

##### Status

The game is not in development anymore even though it has been successfully converted to the [MonoGame framework][monogame] after the XNA framework discontinued.  
It is not available online because copyright laws would be violated, but should be seen as a tribute to the classic Goof Troop game. It's puzzle concept is however reused in _Kick-It_.

##### Visuals

All twelve puzzles from Goof Troop were implemented in some form or another to fit the game. Two puzzles are shown below.

<img src="{{ site.baseurl }}/assets/images/sokoban_goof_troop/Level1.png" class="img-responsive img-centered" alt="Goof Troop Level 1">
<img src="{{ site.baseurl }}/assets/images/sokoban_goof_troop/Level2.png" class="img-responsive img-centered" alt="Goof Troop Level 2">

[wikipedia-goof-troop]: https://en.wikipedia.org/wiki/Goof_Troop_(video_game)
[wikipedia-sokoban]: https://en.wikipedia.org/wiki/Sokoban
[wikipedia-xna]: https://en.wikipedia.org/wiki/Microsoft_XNA
[monogame]: http://www.monogame.net
