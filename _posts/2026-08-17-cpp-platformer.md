---
title: "C++ Platformer"
categories:
- Projects
tags:
- C++
- University Project
gallery:
- url: assets/images/cpp-platformer-main.jpg
  image_path: assets/images/cpp-platformer-main.jpg
- url: assets/images/cpp-platformer-dead.jpg
  image_path: assets/images/cpp-platformer-dead.jpg
- url: assets/images/cpp-platformer-level.jpg
  image_path: assets/images/cpp-platformer-level.jpg
header:
  image: assets/images/header/cpp-platformer.jpg
---

{% include video id="1WsVeqk5yheAee75ab2tjuocVbvKChm1U" provider="google-drive" %}

> [See project repository here.](https://github.com/luddefined/platformer-cpp)
{: .notice--primary}

**Original project date:** 10/04/24 - 25/04/24
{: .notice--info}

This platformer was the final C++ assignment of my first year of university, done without using the standard template library. Little did I know how many more I would be making in subsequent years...

For the 2 weeks it took to write everything, one of those weeks were dedicated to the player's movement physics. There is no way that the current solution is any bit fast, but I'm happy to have written something entirely by myself that works without issues (or at least, I'm too scared to find out when it may not work). 

Alongside bespoke player physics, level are also created using a custom tilemap system that uses CSV files and a hard-coded tileset. Though using Tiled might have been easier (a suggestion I took into the [top down game]({% post_url 2026-08-09-top-down-game %})), what I ended up implementing was fairly straightforward to expand, although I can't say Excel is at it's best as a tile map editor.

With a bit more playtesting, and some slightly better time management, I could have probably improved the player's movement to feel less 'slippery' across a couple more levels. Or, maybe I could have reused the same player movement into the enemy movement (they just move across a predetermined path). Despite all of this, I am happy that everything works fine.

# Gallery

{% include gallery %}