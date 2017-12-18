---
layout: default
modal-id: 2
date: 2014-07-17
img: Simple-File-Browser-Index-Image.png
alt: Simple-File-Browser   
---

{:.p-center}
[Unity Asset Store][asset-store] and [Website][website]

After releasing the _2D Tile Map Level Editor_ in the Unity Asset Store, a GitHub issue was created that the project did not build. Having used only the source code version, I confirmed that building was not possible since the Unity Editor namespace was required in the project. The namespace was used for the EditorUtility.OpenFilePanel and EditorUtility.SaveFilePanel methods used to save files.

A solution to this problem, would be to create my own file browser. After some research, I also noticed a great lack of free and open source file browser in the Unity Asset Store. So I created the Simple File Browser, which allows the user to browser their file system and to save and load file. 

The Simple File Browser currently supports Windows, Mac and Linux computers and Android mobile devices, while iOS might be supported but is untested. A portrait interface was developed to better support the mobile users. 

<img src="{{site.baseurl}}/assets/images/simple_file_browser/Load.png" class="img-responsive img-centered" alt="Load Dialog"/>
<img src="{{site.baseurl}}/assets/images/simple_file_browser/Save.png" class="img-responsive img-centered" alt="Save Dialog"/>

The Simple File Browser was released in the [Unity Asset Store][asset-store] and is open source. For more information (features, setup, etc.) see the [website][website]. The editor is under active development to resolve bugs and open for pull and feature requests.

[asset-store]: https://www.assetstore.unity3d.com/en/#!/content/98451
[website]: https://gracesgames.github.io/SimpleFileBrowser/