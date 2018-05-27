---
layout: default
modal-id: 2
date: 2014-07-20
img: WeStudy-Index-Image.png
alt: WeStudy-Pronunciation
---

{:.p-center}
To be released in the [Google Play Store][google-play-store] and [Apple App Store][apple-app-store]

##### Motivation

While working in a co-working space in Hanoi, Vietnam I was approached by the founder of [WeStudy][westudy] with the request to make a game for them.  
WeStudy is an online learning service that aims to provide quality online courses. The goal of the game was to let users practice their English pronunciation while having fun.  
The project allowed me to get in touch with new technologies (Speech-to-Text), and get my first experience working on a (remote) freelance project.

##### Gameplay

In WeStudy Pronunciation, the player is represented by a tank, while the words to pronounce are visualized as crates heading towards the player.  
If the word on the crate is pronounced correctly the tank fires a missile, destroying the crate and increasing the score. If the player however fails to pronounce the word correctly or at all, the crate will collide with the player resulting in a decrease in score and player health.  
The game is over when the predefined amount of words is completed or the health bar of the player is depleted. The user can then start a new game with options to select the amount of words, and speed of the crates.

##### Technology

WeStudy Pronunciation is developed in C# using the [Unity Engine][unity-3d], since it allows a single code base while releasing for both Android and iOS.   
The game uses an external Speech-to-Text module, available in the [Unity Asset Store][speech-to-text], which support Speech-to-Text for both Android and iOS.  
Public domain assets from [Kenney][kenney] were used.

##### Status

WeStudy Pronunciation is currently under development and will be released in the [Google Play Store][google-play-store] and [Apple App Store][apple-app-store]. 

##### Visuals

<img src="{{ site.baseurl }}/assets/images//westudy_pronunciation/Ingame.png" class="img-responsive img-centered" alt="WeStudy Pronunciation Gameplay">
<img src="{{ site.baseurl }}/assets/images/westudy_pronunciation/MainMenu.png" class="img-responsive img-centered" alt="WeStudy Pronunciation Main Menu">

[google-play-store]: https://play.google.com/store
[apple-app-store]: https://www.apple.com/lae/ios/app-store/
[westudy]: https://westudy.vn/
[unity-3d]: https://unity3d.com/unity
[speech-to-text]: https://assetstore.unity.com/packages/tools/audio/mobile-speech-recognizer-73036
[kenney]: https://kenney.nl/