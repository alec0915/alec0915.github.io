---
layout: post
title:  "Dungeon Toxicrawlogy"
date:   2026-07-06 
categories: personal projects
---

<a href="https://alec0915.itch.io/dungeon-toxicrawlogy" target="_blank"><img src="/pictures/dt.png"></a>


This is the first game I've ever published. I worked on it for a game jam with a friend. I coded the game, and she sourced the visual and audio assets. It's free to play. 

We used GameMaker Studio to build it. GML was pretty easy for me to grasp because it still follows the same logic that other programming languages have. 

The game is a 2D dungeon crawler where the player's goal is to find the cure for the poison that is killing the player. Delve through three levels to finally cure yourself. The game is a bit difficult with the amount of steps the player can take; since it's so short, it's intended to be played several times to memorize layouts and pick the best path.  

<img src="/pictures/dt4.png">


The bottom bar is the player's Toxic Meter; it fills up with each step, up to 100.


<img src="/pictures/dt5.png">

As the bar fills, the screen will slowly begin to turn purple. A game object modifies the Colourize effect layer with a liner interpolation based on the player's steps and how close that is to 100.

<img src="/pictures/dt6.png">

Eventually purple is the only color the player can see.



It was a great opportunity to personally design a few mazes. 

<img src="/pictures/dt1.png">

I wanted this first level to be a simple and more open maze to navigate. While the pathways may be one block wide, they openings in the rooms are vast and much bigger than any room in the other two levels. I also added a few extra healing items to this stage to try and help make it through.

<img src="/pictures/dt2.png"> 

This second level was based on the idea of picking a path and sticking to it. It has very long hallways, so if the player turns back, they probably won't make it. The final corridor before the exit stairs is somewhere around 95 steps. There is a full heal just before it, but, if the player hesitates at all, their odds of surviving to floor 3 drop.

<img src="/pictures/dt3.png">

This final maze has long false paths, and one particularly long dead end near where the cure is. This floor has the least amount of healing items, so, with enough mistakes, the player might not make it to the end. 