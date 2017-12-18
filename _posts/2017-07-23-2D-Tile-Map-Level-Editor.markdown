---
layout: default
modal-id: 4
title: 2D Tile Map Level Editor
date: 2014-07-15
img: 2DTileMapLevelEditor-Index-Image.png
alt: 2D-Tile-Map-Level-Editor
---

[Unity Asset Store][asset-store] and [Website][website]

While starting out as an in-house tool for developing _Kick-It_ levels, the 2D Tile Map Level Editor was reworked and released in the Unity Asset Store for free to give other developers the option of adding a level editor to their game and allow for easy level creation.

An impression of the initial version was posted [here][reddit-demo] on Reddit, to determine whether further development would be beneficial. This version was limited in functionality and did not scale according to screen size since it used the deprecated OnGUI method to draw the user interface. The user interface was rebuild using the new Unity Canvas GUI system, to improve user experience.

<img src="{{ site.baseurl}}/assets/images/2D_tile_map_level_editor/Platformer-Preview.png" class="img-responsive img-centered" alt="Platformer Preview<">
<img src="{{site.baseurl}}/assets/images/2D_tile_map_level_editor/Sokoban-Preview.png" class="img-responsive img-centered" alt="Sokoban Preview"/>

After adding several features, the 2D Tile Map Level Editor was released in the [Unity Asset Store][asset-store] and is open source if users want to change it. For more information (features, setup, etc.) see the [website][website]. The editor is under active development to resolve bugs and open for pull and feature requests.

[asset-store]: https://www.assetstore.unity3d.com/en/#!/content/90420
[website]: https://gracesgames.github.io/2DTileMapLevelEditor/
[reddit-demo]: https://www.reddit.com/r/Unity2D/comments/641toe/made_an_2d_ingame_level_editor_anyone_interested/