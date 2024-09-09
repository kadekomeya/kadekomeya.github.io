---
layout: project
type: project
image: img/20230104234347_1.jpg
title: "Physics Trains"
date: 2023-Now
published: true
labels:
  - Unity
  - C#
  - Gaming
  - GitHub
summary: "A physics-based rail system for a vehicle sandbox game."
---
This was a long time coming - I like trains, so gathering all my past knowledge to make a mod about them sounded fun.
This was much more of a what-if scenerio during some free time.  What if there were trains in a game about prospecting?
It began with planning out the rail network.  To begin with rails typically tend to follow a linear path, while bending and conforming to the existing terrain to reach from point A to point B. With how far the two points could be, rendering all of the track at once could potetntially crash the game.  Splitting the track into segments and only calculating and rendering what was within range permitted tracks of nearly any length to exist safely.
I had orginally decided on using 3D bezier curves for the track generation algorithm to follow, but as-is it produced a track that floated in the air between the two points.  To resolve this, each loaded track segment would be procedually "shrink-wrapped" to the terrain.  This had considerable success, but not to the degree I was hoping for.  It took a layered algorithm to gradually taper the elevation and add bank on turns to make the tracks more natural.

I created some models and kitbashed them with others under permission to create a series of blocks to represent a basic train system.
All of it was put together, and some users who were curious about the mod playtested it. 

In hindsight the mod doesn't make much sense since most of the reasons for having a train is moot, and the mod remains unreleased to this day.

I may improve and use this knowledge if I ever decide on making a game though.

This pertains to a public game community on Steam and with any game it is populated with some complicated users.
For more details on the subject, please contact me in person in class.
