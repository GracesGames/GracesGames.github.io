---
layout: default
modal-id: 6
title: Interactive Tile Map
date: 2014-07-22
img: InteractiveTileMap-Index-Image.png
alt: Interactive-Tile-Map
tool: Unreal Engine
language: Blueprints
---

{:.p-center}
[Unreal Marketplace][unreal-marketplace]{:target="_blank"}{:rel="noreferrer"} and [Website][website]{:target="_blank"}{:rel="noreferrer"}

Interactive Tile Map allows you to add interactive elements to your tile map without manually placing them. 
This will allow you to use the tile map editor as a level editor, thereby speeding up your level design process.

You define which tile is replaced by which actor or flipbook animation using the provided [Data Asset](https://dev.epicgames.com/documentation/en-us/unreal-engine/data-assets-in-unreal-engine){:target="_blank"}{:rel="noreferrer"} or the [Data Tables](https://dev.epicgames.com/documentation/en-us/unreal-engine/data-driven-gameplay-elements){:target="_blank"}{:rel="noreferrer"}.
The tiles can be defined using TileIdentifier (TileSet + Index) or the Tile User Data Name.

This product is implemented as an ActorComponent and can be added to any actor (e.g. Paper Tile Map Actor). 
The replace function can be called at any time and only requires a PaperTileMapComponent to perform the logic on. 
It will replace all instances of the defined tiles with the corresponding actors and flipbooks.

Created using Blueprints, fully documented and easy to customize.

The project will be maintained, so feel free to get in touch to suggest changes, features or anything else.

The main features are:
- Replace tiles with actors and/or flipbooks
- Option to spawn flipbook actors or components as children of the tile map actor
- Respects both tile map actor transform and tile transform (e.g. rotation and flip values)
- Set up your desired replacements using Data Assets or Data Tables
- Specify specific layers to keep the performance high
- And much more

For a complete overview, see the [features page][feature-page]{:target="_blank"}{:rel="noreferrer"}

##### Gameplay

<DIV class="figure-block">
    <iframe width="80%" height="350" src="https://www.youtube.com/embed/5xa-H1VNZNk" frameborder="0" allowfullscreen></iframe>
</DIV>

##### Visuals

<img src="{{site.baseurl}}/assets/images/interactive_tile_map/TileMapImage.PNG" class="img-responsive img-centered" alt="TileMapImage"/>
<img src="{{site.baseurl}}/assets/images/interactive_tile_map/Settings.PNG" class="img-responsive img-centered" alt="Settings"/>

[unreal-marketplace]: https://www.unrealengine.com/marketplace/interactive-tile-map
[website]: https://gracesgames.com/InteractiveTileMap/
[feature-page]: https://gracesgames.com/InteractiveTileMap/features/
