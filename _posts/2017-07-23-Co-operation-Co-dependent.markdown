---
layout: default
modal-id: 8
title:  Co-operation Co-dependent
date: 2014-07-12
img: CooperationCodependent-Index-Image.png
alt: Cooperation-Codependent
tool: Unity3D
language: C#
---

{:.p-center}
[Play Here][gamejolt-cooperation-codependent]{:target="_blank"}{:rel="noreferrer"}

##### Motivation

After developing several games that could not be released due to copyright laws (ripped assets), it was time to create a game from idea to release.  
My favorite games are co-operative games, since they allow players to achieve a common goal. By playing together, the fun is greater than the sum of its parts. This pushed me to create a game in which the players are co-dependent.

##### Gameplay

Co-operation Co-dependent consists of two sub-games, a space shooter on the top half of the screen and an endless runner on the bottom half. The unique element is that players of both games need each other to survive. By making the players survival dependent on the shared effort of both, the game is a test for true cooperation and teamwork. It is a fun collaborative experience which encourages bonding between people.  

In the space shooter, the player controls a spaceship with the goal to shoot and avoid the enemy spaceships while trying to collect hearts. These hearts increase the shared health pool, thereby keeping the players alive. If either player collides with an enemy, the team's health is reduced.

In the endless runner, the player controls a runner character with the goal to survive the endless spree of enemies and pitfalls, while collecting bullets along the way. These bullets are used by the spaceship player to shoot enemies. Both players can also pick up diamonds to further increase their shared score.

<DIV class="figure-block">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/ttoEdCzgCxA" frameborder="0" allowfullscreen ></iframe>
</DIV>

##### Technology

The first prototype was developed using [Unreal Engine 4][unreal-engine-4]{:target="_blank"}{:rel="noreferrer"}, yet after determining the lack of two-player keyboard support, I switched to [Unity Engine][unity-3d]{:target="_blank"}{:rel="noreferrer"} and C#.  
The (then newly released) 2D support of Unity sped up the development process significantly, resulting in a gameplay prototype (version 0.1).  
After that, the game was polished multiple times using the resources from [Kenney][kenney]{:target="_blank"}{:rel="noreferrer"} and version 0.5 was created.

##### Status

After several iterations, Co-operation Co-dependent was released with Early Access status on [GameJolt][gamejolt-cooperation-codependent]{:target="_blank"}{:rel="noreferrer"}. While active development has stalled for now to focus on other projects, there are still improvements and ideas to be implemented in the future.

##### Visuals

These screenshots show the progress between versions:

<DIV class="figure-block">
    <figure class="center-image">
        <img src="{{site.baseurl}}/assets/images/cooperation_codependent/Version0.1.png" class="img-responsive img-centered" alt="Version 0.1"/>
        <figcaption>Version 0.1</figcaption>
    </figure>
    <figure class="center-image">
        <img src="{{site.baseurl}}/assets/images/cooperation_codependent/Version0.5.png" class="img-responsive img-centered" alt="Version 0.5"/>
        <figcaption>Version 0.5</figcaption>
    </figure>
</DIV>

[gamejolt-cooperation-codependent]: https://gamejolt.com/games/co-operation-co-dependent/147907#close
[unreal-engine-4]: https://www.unrealengine.com/what-is-unreal-engine-4
[unity-3d]: https://unity3d.com/unity
[kenney]: https://kenney.nl/
