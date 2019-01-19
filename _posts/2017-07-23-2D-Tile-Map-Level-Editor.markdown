---
layout: default
modal-id: 5
title: 2D Tile Map Level Editor
date: 2014-07-16
img: 2DTileMapLevelEditor-Index-Image.png
alt: 2D-Tile-Map-Level-Editor
tool: Unity3D
language: C#
---

{:.p-center}
[Unity Asset Store][asset-store]{:target="_blank"}{:rel="noreferrer"} and [Website][website]{:target="_blank"}{:rel="noreferrer"}

##### Motivation
The 2D Tile Map Level Editor starting out as an in-house tool for developing _Kick-It_ levels but was reworked and released in the Unity Asset Store for free to give other developers the option of adding a level editor to their game and allow easy level creation by players.

##### Gameplay

The 2D Tile Map Level Editor allows developers to create levels in a fast and intuitive manner. It also allows players to create and share their own levels. For a more detailed list of features please refer to the [feature page][feature-page]{:target="_blank"}{:rel="noreferrer"}.

##### Technology

A prototype of the level editor was developed using the [Unity Engine][unity-3d]{:target="_blank"}{:rel="noreferrer"} since it is used in the _Kick-It_ game. An impression of this prototype was posted on [Reddit][reddit-demo]{:target="_blank"}{:rel="noreferrer"}, to determine whether further development would be beneficial.  
This version was limited in functionality and did not scale according to screen size since it used the deprecated OnGUI method to draw the user interface. The user interface was rebuild using the new Unity Canvas GUI system, to improve user experience.

##### Status

After adding several features, the 2D Tile Map Level Editor was released in the [Unity Asset Store][asset-store]{:target="_blank"}{:rel="noreferrer"} and is open source available for users to customize. For more information (features, setup, and more) see the [website][website]{:target="_blank"}{:rel="noreferrer"}. The editor is under active development to resolve bugs and open for pull and feature requests.

##### Visuals

<img src="{{ site.baseurl}}/assets/images/2D_tile_map_level_editor/Platformer-Preview.png" class="img-responsive img-centered" alt="Platformer Preview<">
<img src="{{site.baseurl}}/assets/images/2D_tile_map_level_editor/Sokoban-Preview.png" class="img-responsive img-centered" alt="Sokoban Preview"/>

[asset-store]: https://assetstore.unity.com/packages/tools/sprite-management/2d-tile-map-level-editor-90420
[website]: https://gracesgames.com/2DTileMapLevelEditor/
[feature-page]: https://gracesgames.com/2DTileMapLevelEditor/features/
[unity-3d]: https://unity3d.com/unity
[reddit-demo]: https://www.reddit.com/r/Unity2D/comments/641toe/made_an_2d_ingame_level_editor_anyone_interested/