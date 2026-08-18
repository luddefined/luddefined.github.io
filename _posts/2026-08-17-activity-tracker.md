---
title: "Activity Tracker"
categories:
- Projects
tags:
- Godot
- Android
- Java
- University Project
gallery:
- url: assets/images/activity-tracker-blank.jpg
  image_path: assets/images/activity-tracker-blank.jpg
- url: assets/images/activity-tracker-walking.jpg
  image_path: assets/images/activity-tracker-walking.jpg
- url: assets/images/activity-tracker-schedule.jpg
  image_path: assets/images/activity-tracker-schedule.jpg
header:
  image: assets/images/header/activity-tracker.jpg

# Unsure if I want to record a video of this because it's a bit annoying to do
# May need to crop veritcal images to 720x405 
# Also this header is really funny
---

> [See project repository and download here.](https://github.com/Faisa-l/AT-Interactivity-for-Activity-Project)
{: .notice--primary}

**Original project date:** 24/10/25 - 18/10/25
{: .notice--info}

This is an mobile phone app. An Android app to be specific. It comes from an assignment in my third year of university, centred around designing a solution to target student physical inactivity. My answer to the assignment was to develop a prototype of a single-screen app that incentivises performing light physical activites (walking, cycling, etc.), emulated through many timers and a simple step counter.

I chose to implement this in Godot, rather than a dedicated software for developing mobile apps. Some say this is because I do not know what this software is and can only create games, though I say it's because I find Godot to be very well suited for prototyping. It also helps that I know a lot of Godot.

The app features scheduling activities, with some examples for walking and cycling. Completing these activites would improve the stats of a "pet" which is the acting representation of the user's level of activity. Not only would you be able to share this with your friends, but your friends could also join in on your activities.

Including a step counter required a journey into Android's API, written in Java, and integrated into the Godot project through a plugin. This project is secretly two different projects as a result. Thie main Godot project is the app itself, whereas the *'telemetry utility'* project is the bit that would actually track the activity. The goal would have been to create a single plugin that can activate all necessary activity tracking services, with a singleton class to hold the data retrieved from the plugin. Given time constraints (and the very long amount of time taken to figure out how to get activity tracking services working), the step counter is the current output.

# Gallery

{% include gallery %}