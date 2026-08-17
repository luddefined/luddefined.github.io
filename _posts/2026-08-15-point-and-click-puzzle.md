---
title: "Point and Click Puzzle"
categories:
- Projects
tags:
- C++
- University Project
gallery:
- url: assets/images/pnc-main.jpg
  image_path: assets/images/pnc-main.jpg
- url: assets/images/pnc-end.jpg
  image_path: assets/images/pnc-end.jpg
- url: assets/images/pnc-room.jpg
  image_path: assets/images/pnc-room.jpg
header:
  image: assets/images/header/pnc.jpg
---

{% include video id="1k8V9RQLFCSdN5JIxu-LYVpzrFq5-Uth0" provider="google-drive" %}

> [See project repository here.](https://github.com/luddefined/point-and-click-puzzle-game)
{: .notice--primary}

**Original project date:** 23/10/24 - 12/12/24
{: .notice--info}

This is possibly the smallest game that I will ever come to make. It was the first C++ assignment in my second year of university, the goal being a simple 2+ room point and click puzzle game. 

Aside from smaller design goals, the big thing this assignment included was permission to use the standard template library. It was described as being too confusing to understand, too unwieldy and monstrous, and that knowing of its existence earlier in our learning journey would have contributed more harm than good. 

In my experience at least, none of this was ever the case, and it made working with C++ no more confusing than it already was. If anything, the containers and smart pointers made it way easier to manage the more simpler tasks, though I can see what they mean if you happen to encounter an error when implementing anything from this library.

Did this unlock the potential to make truly inspirational stuff? What you see here is the most compact project that I've completed, and it may stay that way far into the future. With the anaemic gameplay loop consisting of merging items together to open doors, I wouldn't blame you if you said the execution best fits the "demonstraton" or "concept" categories. 

Despite the simplicity of the game's content, the codebase which powers it is all fairly complex and well developed to allow for semi-dynamic merging of any item, provided there exists a sprite for that combination (that's where the 'semi' part comes from), and if it weren't for dealing with other assignments I could have very easily added more rooms to confuse onlookers that more depth exists behind each unopened door.

# Gallery

{% include gallery %}