---
title: "Escape From Zartron 10"
draft: false
date: 2021-04-27T00:00:00+00:00
image: images/zartron10/logo.png
categories: 'Game Jam'
summary: Big Mechs. Bigger Problems
subhead: 
---
![](../../images/zartron10/zartron10_1.png)
This was a silly game that I [submitted](https://itch.io/jam/mechjam/rate/1018572) for the [MechJam in 2021](https://itch.io/jam/mechjam). The idea was that these big stompy robots are actually probably quite unweildy to pilot, so I wanted to replicate that.
![](../../images/zartron10/zartron10_2.png)
To move, you have to press the left or right arrow key (or A or D). This lifts your opposite foot, and the whole giant mech slowly swings in the direction that you are trying to turn in. To move forward, you have to alternate left and right at a fairly slow cadence to get anywhere. If you want to back up, you press the Control key to reverse the direction of rotation.
![](../../images/zartron10/zartron10_3.png)
Getting the physics to work was tricky, the mechs are incredibly massive (which is to be expected). But in order to keep them on their feet, their Center of Gravity is artifically placed superlatively far under their feet. This causes them to wobble back and forth, but no matter how off-balance they get initially, they do become upright again eventually.
![](../../images/zartron10/zartron10_4.png)
The combat is relatively straightforward as well. Holding down the space bar fires the laser cannons, which are fixed in place. However, you can change the mech's torso elevation, which makes aiming about as tricky as moving - by design. Fortunately, the AI enemy mechs have the same restrictions, and are not much of a challenge in combat. The charge level of the lasers, as well as the player's health, are represented as deigetic interfaces on the mech itself, mainly because I didn't want to spend the time building a user interface.
![](../../images/zartron10/zartron10_5.png)
All in all, this was a fun little project, considering that it was built in around two weeks' worth of free time. It tested out the concept, and nailed the major mechanics, as well as being a complete experience - in terms of having a beginning as well as win and lose states.
For more details on the game, check the [itch.io page](https://realtalk.itch.io/assault-on-zartron-10)