---
layout: default
modal-id: 4
date: 2014-07-17
img: Simple-File-Browser-Index-Image.png
alt: Simple-File-Browser
tool: Unity3D
language: C#
---

{:.p-center}
[Unity Asset Store][asset-store] and [Website][website]

##### Motivation

After releasing the _2D Tile Map Level Editor_ in the Unity Asset Store, a GitHub issue was created that the project did not build. Having used only the source code version until then, I confirmed that building was not possible since the Unity Editor namespace was required in the project. The namespace was used for the EditorUtility.OpenFilePanel and EditorUtility.SaveFilePanel methods used to save files.

A solution to this problem, would be to create my own file browser. After some research, I also noticed a great lack of free and open source file browsers in the Unity Asset Store. So, I created the Simple File Browser, which allows the user to browse their file system and to save and load files. 

##### Gameplay

The Simple File Browser allows users to browse their file system inside Unity and save and load files without any dependencies e.g. the UnityEditor namespace. For a more detailed list of features please refer to the [feature page][feature-page].

##### Technology

The Simple File Browser was developed using the [Unity Engine][unity-3d] since it is used in the _2D Tile Map Level Editor_ and the _Kick It_ game. The Simple File Browser currently supports Windows, Mac and Linux systems and Android devices, while iOS might be supported but this is untested. A portrait interface was developed to better support mobile users. 

##### Status

The Simple File Browser was released in the [Unity Asset Store][asset-store] and is open source for users to customize. For more information (features, setup and more) see the [website][website]. The editor is under active development to resolve bugs and open for pull and feature requests.

##### Visuals

<DIV class="figure-block">
    <figure class="center-image">
        <img src="{{site.baseurl}}/assets/images/simple_file_browser/Load.png" class="img-responsive img-centered" alt="Load Dialog"/>
        <figcaption>Desktop Load Dialog</figcaption>
    </figure>
    <figure class="center-image">
        <img src="{{site.baseurl}}/assets/images/simple_file_browser/Save.png" class="img-responsive img-centered" alt="Save Dialog"/>
        <figcaption>Mobile Save Dialog</figcaption>
    </figure>
</DIV>


[asset-store]: https://assetstore.unity.com/packages/tools/input-management/simple-file-browser-98451
[website]: https://gracesgames.github.io/SimpleFileBrowser/
[feature-page]: https://gracesgames.github.io/SimpleFileBrowser/features/
[unity-3d]: https://unity3d.com/unity
