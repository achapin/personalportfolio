---
title: "Wasteland Workshop"
draft: false
date: 2018-12-02T00:00:00+00:00
image: images/wastelandworkshop/header.png
categories: 'Extra'
summary: A web-based squad builder for Fallout Wasteland Warfare
subhead: Order in the Wasteland
---
![](../../images/wastelandworkshop/survivor.png)
## Filling an unmet need
I am a fan of Modiphius' tabletop game Fallout Wasteland Warefare (based on Bethesda's Fallout series). However, part of the game involves building force lists - a task that required careful tracking of point costs cross-referenced with data sheets which update over time. So I decided to build a small web-based tool that allowed players more freedom to build these lists without having to keep track of everything manually.
![](../../images/wastelandworkshop/scavver.png)
## Old-School Approach
Since I didn't want to pay for web hosting for this project, I opted to use the handy Github Pages feature - where you can host static sites on github based on a given directory. This meant that I could not rely on any backend code whatsoever, it had to be completely frontend-only. Due to the seemingly simple requirements, I opted not to use any frameworks which could add bloat. So the entire page is hand-written javascript, html, and css. I kept the data completely separate from the code, which has meant that updates based on new releases has been a very simple process - which is crucial for a project that is only updated in my free time. It's not the prettiest tool in existence, but it definitely serves its purpose, and has been adopted fairly widely in the community.

The site is accessible [via my github account](https://achapin.github.io/wastelandworkshop).