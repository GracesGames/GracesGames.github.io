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
[Source Code][github-house-of-doom]

##### Motivation

After having developed several projects using Unity and C#, it was time to showcase a C++ project.
  
Several prototypes had already been created in [SFML][sfml] and [Unreal Engine 4][unreal-engine-4] using experience gained from books and online courses (e.g. [Beginning C++ Game Programming][packt-cpp-book] and [Udemy Unreal Course][udemy-unreal-course]). Since the Unreal Engine 4 is more often used in the industry, I opted to use this engine. 

To focus on showcasing C++ code and gameplay programming, I decided to develop a sprite-based shooter. By using sprites, the lighting, animation and level design workload was reduced. Another time-saver are the freely available resources of the [Freedoom Project][freedoom], giving the game it's old-school graphics.

##### Gameplay

Just like in [Doom (1993)][doom-1993] the objective is simple, survive an onslaught of monsters while progressing through  the game.  
The player has a variety of weapons, can activate objects (e.g. sliding doors), and has to fight a assortment of enemies (melee, ranged, walking, flying and more).   
A future feature is to generate rooms to create an endless survival mode.

##### Technology

As this project is a showcase for my gameplay programming C++ experience, I opted to use an existing engine instead of developing my own. This allowed me to focus my energy and gain experience with Unreal Engine 4.  
The blueprint system of Unreal Engine 4 is used to quickly prototype new features, which are then re-implemented in C++. Asset binding and some User Interface elements are kept in Blueprint for dynamic change benefits.

##### Status

House of Doom is under active development, adding new features, enemies and more. The C++ code is freely available on [GitHub][github-house-of-doom] using project name Unreal Freedoom. 

##### Visuals

<img src="{{ site.baseurl }}/assets/images/house_of_doom/Ingame.png" class="img-responsive img-centered" alt="House of Doom Gameplay">

[github-house-of-doom]: https://github.com/GracesGames/UnrealFreedoom
[sfml]: https://www.sfml-dev.org/
[unreal-engine-4]: https://www.unrealengine.com/en-US/what-is-unreal-engine-4
[packt-cpp-book]: https://www.packtpub.com/game-development/beginning-c-game-programming
[udemy-unreal-course]: https://www.udemy.com/unrealcourse/
[freedoom]: https://freedoom.github.io/
[doom-1993]: https://en.wikipedia.org/wiki/Doom_(1993_video_game)