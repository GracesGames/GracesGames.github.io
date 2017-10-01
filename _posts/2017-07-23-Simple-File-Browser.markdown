---
layout: post
title:  Simple File Browser (Unity Tool)
date:   2017-07-23 05:00:00 +0200
categories: Unity Tool
image: ../assets/images/simple_file_browser/File-browser-icon.png
---

{:.p-center}
In the [Unity Asset Store][asset-store] and on [GitHub][github]

After releasing the [2D Tile Map Level Editor][gg-2DTMLE] in the Unity Asset Store, a GitHub issue was created that the project did now build. Having used only the source code version, I confirmed that building was not possible since the Unity Editor namespace was used in the project. The namespace was used for the EditorUtility.OpenFilePanel and EditorUtility.SaveFilePanel methods used to save files.

A solution to this problem, would be to create my own file browser. After some research, I also noticed a great lack of free and open source file browser in the Unity Asset Store. So I created the Simple File Browser, which simply allows the user to browser their file system and to save and load file. The Simple File Browser currently supports Windows Mac and Linux devices. Mobile support will be added soon.

<DIV class="figure-block">
    <figure class="center-image">
        <img src="{{site.baseurl}}/assets/images/simple_file_browser/Save.png" alt="Save Dialog"/>
        <figcaption>Save Dialog</figcaption>
    </figure>
    <figure class="center-image">
        <img src="{{site.baseurl}}/assets/images/simple_file_browser/Load.png" alt="Load Dialog"/>
        <figcaption>Load Dialog</figcaption>
    </figure>
</DIV>

The first version of the Simple File Browser was released in the [Unity Asset Store][asset-store] and it source is available on [GitHub][github]. The editor is under active development to resolve bugs and open for pull and feature requests.

[asset-store]: https://www.assetstore.unity3d.com/en/#!/content/98451
[github]: https://github.com/GracesGames/SimpleFileBrowser
[gg-2DTMLE]: {% post_url 2017-07-23-2D-Tile-Map-Level-Editor %}