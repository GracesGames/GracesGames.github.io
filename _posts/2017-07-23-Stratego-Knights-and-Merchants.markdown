---
layout: default
modal-id: 9
title:  Stratego - Knights and Merchants
date: 2014-07-13
img: KAM-Index-Image.png
alt: Knights-And-Merchants
tool: XNA
language: C#
---

##### Motivation

Inspired by the childhood nostalgia of the game [Knights and Merchants: The Shattered Kingdom][wikipedia-kam]{:target="_blank"}{:rel="noreferrer"}, my first developed game was the board game [Stratego][wikipedia-stratego]{:target="_blank"}{:rel="noreferrer"}. 

A board game was chosen since the turn-based system results in less complexity and also removes the need to simulate (real-time) physics.   
Stratego fitted the different types of Knights and Merchants soldiers quite well and the rules complied to the used grid system and tile engine.

##### Gameplay

Each game of Stratego starts with the setup phase, where both players place their army on the field. When completed, the game starts turn-based until one of the players captures the other player's flag.   
Each turn, the player moves a piece on the board and when the new location contains an enemy piece, a soldier battle starts.   
The general rule is that soldiers with higher numbers beat lower numbers, but there are some special pieces like the bomb which can only be swept by the miner.  
For more information please read the [Stratego Wikipedia page][wikipedia-stratego]{:target="_blank"}{:rel="noreferrer"}.

##### Technology

This game was developed in C# using the [XNA framework][wikipedia-xna]{:target="_blank"}{:rel="noreferrer"}. First a 2D tile engine was developed using a tutorial from [this book][book-xna]{:target="_blank"}{:rel="noreferrer"}, which is used to determine the click events and movement of the different soldiers.  
The sprites and songs were ripped from the Knights and Merchants CD using third-party tools.

##### Status

The game is not in development anymore even though it has been successfully converted to the [MonoGame framework][monogame]{:target="_blank"}{:rel="noreferrer"} after the XNA framework discontinued.  
It is not available online since copyright laws would be violated, but should be seen as a tribute to the classic Knights and Merchants game.

##### Visuals

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

[wikipedia-kam]: https://en.wikipedia.org/wiki/Knights_and_Merchants:_The_Shattered_Kingdom
[wikipedia-stratego]: https://en.wikipedia.org/wiki/Stratego
[wikipedia-xna]: https://en.wikipedia.org/wiki/Microsoft_XNA
[book-xna]: https://www.packtpub.com/game-development/xna-40-game-development-example-beginners-guide
[monogame]: http://www.monogame.net