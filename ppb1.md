---
layout: page
title: "Heroes & Towns"
permalink: /heroestowns/
---

... is a town management and RPG hybrid that stemmed from [my game AI experiment]({% post_url 2018-02-05-rpg-fflike-part1 %}). It's being developed using Unity and is currently in **prototype** phase. Visually, it uses mostly free & very cheap assets, to keep the development costs as low as possible.

#### [Latest public build (Windows)](https://www.dropbox.com/s/temuqfgnqkaun13/ppb1.7z?dl=0) 

<ul>
    <li style="display:inline">
        <a href="/images/pq3d3.png" target="_blank"><img src="/images/pq3d3.png" width="417" height="169" /></a>
    </li>
</ul>

The goal is to develop your camp and the skills of your heroes, in order to fulfill the orders received from your king at the start of the scenario.

The party has dedicated heroes for particular tasks i.e. a warrior, a blacksmith, a hunter and a cook. All characters are AI-controlled but the player can influence their actions via buildings and giving orders.

<ul>
    <li style="display:inline">
        <a href="/images/pq3d1.png" target="_blank"><img src="/images/pq3d1.png" width="300" height="169" /></a>
        <a href="/images/pq3d2.png" target="_blank"><img src="/images/pq3d2.png" width="301" height="169" /></a>
    </li>
</ul>

### Short Tutorial

To manipulate the camera: middle mouse click & drag OR arrow keys for panning. Scrollwheel zooms in/out.

![pq3d](/images/pq3d4.jpg)

The panel in the bottom left corner of the screen shows you the list of heroes and some information about them. Click on the name of a hero to permanently follow them around. Press **"F"** or move the camera via panning to stop following them.

Their activity is written down next to their name. Next, there's their current major *thought*. Thoughts are very important as they give you clues as to what to do in order to progress in the game. You can hold the mouse cursor over a character's though to view a panel that shows *all* of their current thoughts, assuming there's more than one at that moment.

The flow of resources and activity is fairly simple: John the Hunter will periodically go to a hunting spot to hunt some boars. Depending on his luck, he will come back with less, more, or no raw meat at all. The raw meat is used by Escoffier the Chef to create cooked meat, which in turn is used by Bob the Righteous during his expeditions, more specifically to heal himself in combat. Albert the Smith uses the iron ore brought back by Bob to create equipment.

![pq3d](/images/pq3d5.jpg)

This is the camp's *stockpile*, a not-so-fancy chest. Resources are taken from and brought here. To see what's inside press the **T** key.

![pq3d](/images/pq3d6.png)

The top left menu shows you how much money you have left and allows you to open the building menu, the character info and expedition panels.

![pq3d](/images/pq3d7.png)

The character info panel lets you see the contents of each character's inventory, their equipment and their crafting skills & orders. 

You can click on the icon for each equipment slot, and, assuming that the stockpile contains equippable items for that slot, you will be presented with a menu which lets you change the equipped item in that particular slot.

You can tell a hero to craft a different item (currently only useful for Albert the Smith) by clicking on its icon in the skills subpanel, assuming the hero's level in that skill is high enough.

Note that when you give a hero an order e.g. change equipment, said order will go into a queue. Which means the hero must first complete his current activity before fulfilling the order.

**Important**
* It's best for your first building to be a Cooking Pot, to have ample food for expeditions — otherwise, Bob will die a lot. Bob automatically picks up any food he can find in the stockpile before going on an expedition.
* Don't build on top of heroes.