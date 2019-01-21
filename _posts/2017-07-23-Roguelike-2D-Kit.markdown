---
layout: default
modal-id: 2
date: 2014-07-20
img: Roguelike2DKit-Index-Image.png
alt: Roguelike-2D-Kit
tool: Unreal Engine 4
language: Blueprints
---

<iframe src="https://widgets.gamejolt.com/package/v1?key=i2dzMirW&theme=light" frameborder="0" width="100%" height="190"></iframe>  

{:.p-center} 
[Unreal Marketplace][unreal-marketplace]{:target="_blank"}{:rel="noreferrer"} and [Website][website]{:target="_blank"}{:rel="noreferrer"}

##### Motivation

Having released the Space Shooter 2D Kit on the Unreal Marketplace, I was inspired by the [roguelike][roguelike-wikipedia]{:target="_blank"}{:rel="noreferrer"} game [The Binding of Isaac][binding-of-isaac-wikipedia]{:target="_blank"}{:rel="noreferrer"} to create another kit.    
By creating the space shooter kit and working on Unreal Freedoom, my experience with the Unreal Engine improved. Everything I learned by making this kit could also be ported back to the other projects, resulting in overall higher quality products. 

This game would again be in 2D, on the one hand because The Binding of Isaac is 2D, but also because I think the [Paper 2D][paper-2d]{:target="_blank"}{:rel="noreferrer"} feature of Unreal Engine 4 is underappreciated.    
Another focus for this project would be the accessibility to designers. Everybody should be able to easily create levels using drag-and-drop, enemies using a [Entity–Component–System][entity–component–system]{:target="_blank"}{:rel="noreferrer"} and power-ups using data tables.  
The Roguelike 2D Kit provides the user with an example game that they can easily modify and extend. 

Although not originally envisioned, I encountered issue [UE-22623][issue]{:target="_blank"}{:rel="noreferrer"}, resulting in my first contribution to the Unreal Engine source code by creating this [Pull Request][pull-request]{:target="_blank"}{:rel="noreferrer"}.

##### Gameplay

The player has to beat an endless stream of rooms by killing/shooting enemies. The rooms can contain several power-ups (player stats improvements, weapon power-ups and more). The game includes multiple types of enemies, which can easily be extended.    
Example animations, sound effects and background music are provided. The kit also includes a playable level, main menu, pause menu and a game over screen.  
For a more detailed list of features please refer to the [feature page][feature-page]{:target="_blank"}{:rel="noreferrer"}.  

<DIV class="figure-block">
    <iframe width="80%" height="350" src="https://www.youtube.com/embed/ZcllQdTq2e4" frameborder="0" allowfullscreen></iframe>
</DIV>

##### Technology

The template is created using Blueprints, is fully documented and allows easy customization. The Roguelike 2D Kit currently supports desktop, web and mobile deployment. Users can test the kit by playing the game in the browser. 

##### Status

The Roguelike 2D Kit is available in the [Unreal Marketplace][unreal-marketplace]{:target="_blank"}{:rel="noreferrer"}. For more information (features, documentation and more) see the [website][website]{:target="_blank"}{:rel="noreferrer"}. The kit is under active development to resolve bugs, add features and open for suggestion and feedback.

##### Visuals

<img src="{{site.baseurl}}/assets/images/roguelike_2d_kit/Gameplay.png" class="img-responsive img-centered" alt="Gameplay"/>
<img src="{{site.baseurl}}/assets/images/roguelike_2d_kit/MobileGameplay.png" class="img-responsive img-centered" alt="MobileGameplay"/>

[unreal-marketplace]: https://www.unrealengine.com/marketplace/roguelike-2d-kit
[website]: https://gracesgames.com/Roguelike2DKit/
[roguelike-wikipedia]: https://en.wikipedia.org/wiki/Roguelike
[binding-of-isaac-wikipedia]: https://en.wikipedia.org/wiki/The_Binding_of_Isaac_(video_game)
[paper-2d]: https://docs.unrealengine.com/en-us/Engine/Paper2D
[entity–component–system]: https://en.wikipedia.org/wiki/Entity%E2%80%93component%E2%80%93system
[issue]: https://issues.unrealengine.com/issue/UE-22623
[pull-request]: https://github.com/EpicGames/UnrealEngine/pull/5354
[feature-page]:https://gracesgames.com/Roguelike2DKit/features/
