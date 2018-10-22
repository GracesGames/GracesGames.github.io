---
layout: default
modal-id: 1
date: 2014-07-21
img: HouseOfDoom-Index-Image.png
alt: House-of-Doom
tool: Unreal Engine 4
language: C++
---

{:.p-center}
[Play Demo][gamejolt-house-of-doom]{:target="_blank"}{:rel="noreferrer"} 

{:.p-center}
[Source Code][github-house-of-doom]{:target="_blank"}{:rel="noreferrer"} and [Website][website]{:target="_blank"}{:rel="noreferrer"}

##### Motivation

After having developed several projects using Unity and C#, it was time to showcase a C++ project.
  
Several prototypes had already been created in [SFML][sfml]{:target="_blank"}{:rel="noreferrer"} and [Unreal Engine 4][unreal-engine-4]{:target="_blank"}{:rel="noreferrer"} using experience gained from books and online courses (e.g. [Beginning C++ Game Programming][packt-cpp-book]{:target="_blank"}{:rel="noreferrer"} and [Udemy Unreal Course][udemy-unreal-course]{:target="_blank"}{:rel="noreferrer"}). Since the Unreal Engine 4 is more often used in the industry, I opted to use this engine. 

To focus on showcasing C++ code and gameplay programming, I decided to develop a sprite-based shooter. By using sprites, the lighting, animation and level design workload was reduced. Another time-saver are the freely available resources of the [Freedoom Project][freedoom]{:target="_blank"}{:rel="noreferrer"}, giving the game it's old-school graphics.

##### Gameplay

Just like in [Doom (1993)][doom-1993]{:target="_blank"}{:rel="noreferrer"} the objective is simple, survive an onslaught of monsters while progressing through  the game.  
The game generates rooms on the fly to create an endless survival mode.
The player has a variety of weapons, can activate objects (e.g. sliding doors), and has to fight an assortment of enemies (melee, ranged, walking, flying and more).  
Features to be added continuously.

##### Technology

As this project is a showcase for my gameplay programming C++ experience, I opted to use an existing engine instead of developing my own. This allowed me to focus my energy and gain experience with Unreal Engine 4.  
The blueprint system of Unreal Engine 4 is used to quickly prototype new features, which are then re-implemented in C++. Asset binding and some User Interface elements are kept in Blueprint for dynamic change benefits.

##### Status

House of Doom is under active development, adding new features, enemies and more. The C++ code is freely available on [GitHub][github-house-of-doom]{:target="_blank"}{:rel="noreferrer"} using project name Unreal Freedoom. 

##### Visuals

<img src="{{ site.baseurl }}/assets/images/house_of_doom/Example1.png" class="img-responsive img-centered" alt="House of Doom Shotgun">
<img src="{{ site.baseurl }}/assets/images/house_of_doom/Example2.png" class="img-responsive img-centered" alt="House of Doom Freeze gun">

[gamejolt-house-of-doom]: https://gamejolt.com/games/house-of-doom/362512
[github-house-of-doom]: https://github.com/GracesGames/UnrealFreedoom
[website]: https://gracesgames.github.io/UnrealFreedoom/
[sfml]: https://www.sfml-dev.org/
[unreal-engine-4]: https://www.unrealengine.com/en-US/what-is-unreal-engine-4
[packt-cpp-book]: https://www.packtpub.com/game-development/beginning-c-game-programming
[udemy-unreal-course]: https://www.udemy.com/unrealcourse/
[freedoom]: https://freedoom.github.io/
[doom-1993]: https://en.wikipedia.org/wiki/Doom_(1993_video_game)