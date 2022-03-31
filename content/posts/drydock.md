---
title: "Dry Dock"
draft: false
date: 2015-11-25T00:00:00+00:00
image: images/drydock/list.png
categories: 'Game Jam'
summary: Procedurally generated capital ship interiors
subhead: Generator Galactica
---
![Different classes of ships can be designed, and then different ships can be generated from that class.](../../images/drydock/editor.png)
## Commander on Deck
Dry Dock was my project for the 2015 ProcJam. I had seen some truly excellent generators for space ship designs before, but they had always focused on the exterior design of the ships, and never the interiors. So I set out to build a generator for the interior design of the ships.
![Along with the ship's outline, the interior .](../../images/drydock/rooms.png)
## Generator Technique
The players define the type of rooms that can exist, and what sort of items would be in those rooms. Then, classes of ships can be built by specifying size parameters, and defining which rooms take up which percentage of the hull space. Then, a central "spine" hallway is drawn across the entire hull, and "rib" hallways branch out from it at regular intervals. This process continues in a recursive way until the edge of the hull or another hallway has been reached. At this point the hull has been separated into chunks, which become rooms of different sizes. The rooms are assigned functions based on the priority and size of the room, trying to keep the percentages balanced as per the design of the ship's class.
![A few simple obstacles meant that levels could be built relatively quickly.](../../images/drydock/2.png)
## Moving Forward
The plan for this project originally, was to become a sci-fi roguelike, where the player explored wrecks of these massive ships. However, the scope of the generator was even reduced from it's original goal: to have multi-layered 3D ship interiors as well. For a week's worth of work, though, it was an interesting project.
![Since the levels were static, and relatively short, the time to get through them was very short.](../../images/drydock/3.png)
## Link
Dry Dock can be downloaded [here](https://realtalk.itch.io/dry-dock)