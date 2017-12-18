---
layout: default
modal-id: 9
title:  Stratego - Knights and Merchants
date: 2014-07-10
img: KAM-Index-Image.png
alt: Knights-And-Merchants
project-date: April 2014
---

Inspired by the childhood nostalgia of the game [Knights and Merchants: The Shattered Kingdom][wikipedia-kam], my first developed game was the board game [Stratego][wikipedia-stratego]. A board game was chosen since they are simpler to developed using the turn system and the absence of simulating (real-time) physics. The board game Stratego fitted the different types of soldiers of the Knights and Merchants quite well and was not as complicated rule-wise.

This game was developed in C# using the [XNA framework][wikipedia-xna]. First a 2D tile engine was developed using a tutorial from [this book][book-xna], which is used to determine the click on and movement of the different game board spaces. The game manager determines the turn and the game logic. Sprites and songs were ripped from the Knights and Merchants CD using tools found online.

These images give an impressive of the game. First the player can setup his army and save/load his favorite setup strategies. The chosen setup is then used for the game while the AI chooses a setup. Each turn the player can move a soldier according to the Stratego rules as shown in the mid-battle image. When the game is over, the statistics are shown.

<DIV class="figure-block">
    <figure class="center-image">
        <img src="{{site.baseurl}}/assets/images/stratego_kam/ArmyPlacement.png" class="img-responsive img-centered" alt="Army Placement"/>
        <figcaption>Allow the player to setup the army</figcaption>
    </figure>
    <figure class="center-image">
        <img src="{{site.baseurl}}/assets/images/stratego_kam/Ingame.png" class="img-responsive img-centered" alt="Ingame"/>
        <figcaption>Beginning of the battle</figcaption>
    </figure>
    <figure class="center-image">
        <img src="{{site.baseurl}}/assets/images/stratego_kam/Midgame.png" class="img-responsive img-centered" alt="Midgame"/>
        <figcaption>On the winning side</figcaption>
    </figure>
    <figure class="center-image">
        <img src="{{site.baseurl}}/assets/images/stratego_kam/Victory.png" class="img-responsive img-centered" alt="Victory"/>
        <figcaption>Victory</figcaption>
    </figure>
</DIV>

The game is currently not in development anymore even though it has been successfully converted to the [MonoGame framework][monogame] since the XNA framework is discontinued. It is not available online because copyright laws would be violated, but should be seen as a tribute to the classic Knights and Merchants game.

[wikipedia-kam]: https://en.wikipedia.org/wiki/Knights_and_Merchants:_The_Shattered_Kingdom
[wikipedia-stratego]: https://en.wikipedia.org/wiki/Stratego
[wikipedia-xna]: https://en.wikipedia.org/wiki/Microsoft_XNA
[book-xna]: https://www.packtpub.com/game-development/xna-40-game-development-example-beginners-guide
[monogame]: http://www.monogame.net