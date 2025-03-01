---
title: "Senior Capstone: Cambrivival"
categories:
  - Game
tags:
  - Capstone
  - Godot
  - GDScript
---

This post is dedicated to all things related to my joint senior capstone project for the Computer Sciences and Geosciences.

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/cambrivival.png" alt="">

Cambrivival is a top-down 2D Video Game built in Godot and is centered around the Cambrian Period. The Cambrian Period was a time some 500 million years ago when life began to proliferate and expand at a massive rate. It is a time when the land was barren and life was contained within the oceans. The atmosphere, while present and contained oxygen, was not enough to protect the surface from harsh sun. 

Within Cambrivival, the player character is transported back to the Cambrian and must survive as they wait for their rescue. Besides surviving the harsh environment, players will come across different species that no longer exist and log them within your journal, the only thing that made it with you. This journal will display information about the species you can find, as well as tips that can help drive the player towards survival.

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/journal.png" alt="">

Cambrivival makes use of State Machines as the primary method for controlling behaviors within the game. This can range from the player idling, walking, running or dying to controlling an npc's behavior, whether it be passive or aggressive. The game also makes use of Godot's built-in resources and signals, both of which are heavily used for the Journal and State Machines respectively.
  
