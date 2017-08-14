---
layout: post
title:  2D Tile Map Level Editor (Unity Tool)
date:   2017-07-23 04:00:00 +0200
categories: Unity Tool
image: ../assets/images/2D_tile_map_level_editor/2DTileMapLevelEditor-Index-Image.png
---

{:.p-center}
In the [Unity Asset Store][asset-store] and on [GitHub][github]

While starting out as an in-house tool for developing [Kick-It][gg-kick-it] levels, the 2D Tile Map Level Editor was reworked and released in the Unity Asset Store for free to give other developers the option of adding a level editor to their game and allow for easy level creation.

An impression of the initial version was posted [here][reddit-demo] on Reddit, to determine whether further development would be beneficial. This version was limited in functionality and did not scale according to screen size since it used the deprecated OnGUI method to draw the user interface. The user interface was rebuild using the new Unity Canvas GUI system, to improve user experience.

<DIV class="figure-block">
    <figure class="center-image">
        <img src="{{site.baseurl}}/assets/images/2D_tile_map_level_editor/Platformer-Preview.png" alt="Platformer Preview"/>
        <figcaption>Platformer Preview</figcaption>
    </figure>
    <figure class="center-image">
        <img src="{{site.baseurl}}/assets/images/2D_tile_map_level_editor/Sokoban-Preview.png" alt="Sokoban Preview"/>
        <figcaption>Sokoban Preview</figcaption>
    </figure>
</DIV>

After adding several features, the 2D Tile Map Level Editor was released in the [Unity Asset Store][asset-store] and it source is available on [GitHub][github]. The editor is under active development to resolve bugs and open for pull and feature requests.

[asset-store]: https://www.assetstore.unity3d.com/en/#!/content/90420
[github]: https://github.com/GracesGames/2DTileMapLevelEditor
[gg-kick-it]: {% post_url 2017-07-23-Kick-It %}
[reddit-demo]: https://www.reddit.com/r/Unity2D/comments/641toe/made_an_2d_ingame_level_editor_anyone_interested/