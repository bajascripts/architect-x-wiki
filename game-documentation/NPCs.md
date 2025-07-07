---
title: NPCs
description: 
published: true
date: 2025-07-07T02:31:01.989Z
tags: 
editor: markdown
dateCreated: 2024-12-11T03:15:43.217Z
---

# NPCs

**NPCs (non-player character)s** in SCP Architect X serve many functions for your foundation.

**NPCs are meant to be predictable, and have limited random properties or decisions unless explicitly stated**.

## NPC Needs

# NPC Prices

TO BE DONE

# NPC Behavior

Outlined below is the static behavior of every NPC. An NPC's lifecycle is a loop of actions and decisions an NPC will make during it's life time (from hiring to firing).

## Global Steps

1.  IF Scientist, 75% to start Do a Test or Research.
2.  Miscellaneous Activity
    1.  25% Chance to **Eat**
    2.  25% Chance to **Use Toilet**
    3.  25% Chance to **Go to Sleep**
    4.  25% Chance to **Roam**

### Do a Test (Scientists only)

1.  Find available Class D (if a Class D is sleeping, they can't be chosen, any other tasks will be interrupted)
2.  Move to Class D's Bed (Class D moves to their Bed)
3.  Find available SCP (only 1 test per SCP allowed, the SCP will be in an occupied status for the duration of moving to the SCP and the test)
4.  Move to SCP
5.  Test on SCP (dispenses award on completion)
6.  Cleanup

### Research (Scientists *with pending researches* only)

Researches are accumulated after a test. Each test a scientist completes can be researched for 1.5x it's value once. 

1.  Find available Scientific Desk (in Lab Zone)
2.  Moving to Scientific Desk
3.  Conduct Research (dispenses award on completion)
4.  Cleanup

### Eat (All NPC's)

*_This task will negate the NPC's mood on failure and improve NPC's mood on success._*

1.  Find available Cafeteria Table (the table will be in occupied status for duration of moving to the table and eating)
2.  Moving to Cafeteria Table
3.  Eating
4.  Cleanup

### Use Toilet (All NPC's)

*_This task will negate the NPC's mood on failure and improve NPC's mood on success._*

1.  Find available Toilet (the toilet will be in occupied status for duration of moving to the toilet and using, Class D's will use their assigned cells while other personnel will use the restroom zones)
2.  Moving to Toilet
3.  Using Toilet
4.  Cleanup

### Go to Sleep (All NPC's)

*_This task will negate the NPC's mood on failure and improve NPC's mood on success._*

1.  Find available Bed (the bed will be in occupied status for duration of moving to the bed and sleeping, Class D's will use their assigned cells while other personnel will use the personnel quarters zones)
2.  Moving to Bed
3.  Sleeping
4.  Cleanup

### Roam (All NPC's)

1.  Find roam point (a random floor tile is selected)
2.  Moving to Roam Point
3.  Cleanup