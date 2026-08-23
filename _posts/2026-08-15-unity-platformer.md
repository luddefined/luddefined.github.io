---
title: "Unity Platformer"
excerpt: "another platformer for testing audio."
categories:
- Projects
tags:
- Unity
- C#
- University Project
gallery:
- url: assets/images/unity-platformer-main.jpg
  image_path: assets/images/unity-platformer-main.jpg
- url: assets/images/unity-platformer-settings.jpg
  image_path: assets/images/unity-platformer-settings.jpg
- url: assets/images/unity-platformer-jumping.jpg
  image_path: assets/images/unity-platformer-jumping.jpg
header:
  image: assets/images/header/unity-platformer.jpg
---

{% include video id="1iSEzP0nsNNnAdUX4nBHwMkbzV3JhwG1Z" provider="google-drive" %}

> [See project repository and download here.](https://github.com/Faisa-l/AT-Sensory-Friendly-Experiences-Project)
{: .notice--primary}

**Original project date:** 07/03/26 - 24/04/26
{: .notice--info}

This is yet another platformer, made during the second semester of my third year at university. While the aim of the project a focus somewhere along the lines of "sensory-friendly experiences, including games", my personal focus was on discovering the capability of Unity's sound system. *How are you supposed to implement an audio framework for a game? What even are the components used to play sounds? How should they be implemented?* These were the lines I was mainly focusing on, whilst keeping within the framework of sensory-friendly audio. 

For the purposes of this website this is called "Unity Platformer", however it has the much more serious and formal title of *Jumpy Sphere Ball*. The sphere ball which has jumpy properties comes from a [tutorial](https://catlikecoding.com/unity/tutorials/movement/) I implemented now two years ago as I write this post. Most of the sounds come from various [freesound.org](https://freesound.org/) searches or were some random audio file hiding somewhere in [Safety Optional]({% post_url 2026-08-09-safety-optional %}). For those who have read another article, you may notice the music is the entire [tea time original soundtrack](https://retraace.bandcamp.com/album/tea-time-ep) (shoutout retraace, yet again). This marks the first time I have seriously looked into solving sound and audio design questions within game development, with there still being much to learn about.

A large majority of this project's code was made for the purpose of being reused in other projects, and to test out different types of architectures and designs for said projects too. 
- The sound system is used in another project which is, at the time of writing, too underdeveloped to have a post on this website.
- The scriptable object system was an interesting investigation though I am probably unlikely to reuse it because of how many objects and individual classes it requires.
- The settings system *might* be reused in said underdeveloped project? It would be with a different UI framework for binding data, however.

# Gallery

{% include gallery %}