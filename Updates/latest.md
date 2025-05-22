---
title: Latest Update
description: 
published: true
date: 2025-05-22T04:46:25.522Z
tags: 
editor: markdown
dateCreated: 2025-05-04T06:27:06.560Z
---
# v0.1.32 | 2025-05-22

Fixed multi-placing objects going over limit and the cost not reflecting.
Rebalanced SCP pricing to match new profits


# v0.1.30 | 2025-05-22

Added private server to main menu (more features coming soon).

# v0.1.29 | 2025-05-22

Added Free-Cam for everyone (Shift+P)
Added mouse overlay with estimate cost/refund and loadicon
Improved accuracy of the DeletionV2 select box
Rebalanced income from SCP tests.

# v0.1.28 | 2025-05-22

Started working on an auto-zone system.
Fixed being able to place multiple of a max object by using multi place.
Added a notification when you hit ClassD limit
Fixed a DeletionV2 bug with objects not removing
Fixed a UI issue where pressing the notifications keybind also opens feedback.

# v0.1.27 | 2025-05-21

## PathfindingV2
- Changed PathfindingV2 Grid unit from 2 to 4, reducing node count from 70,688 (All 4 Sectors) to 18,432 (All 4 Sectors). This will hopefully prevent the huge performance drop on servers at the expense of need a space between diagonal hallways. (Every 4 studs is a valid NPC path instead of 2). Diagonal Walls will work like normal but the minimum path width will be 8 studs instead of 4. This will not be changed back to the 2 studs, it's not worth the performance drops.
- When debug is enabled, the pathfinding node graph will be visible on all 4 sectors. A red cube denotes a blocked node.

- Fixed an issue when translating real world coordinates to pathfindingV2 grid. math.floor switched to math.round

## NPCs
- Fixed some issues with Class D spawning.
- Fixed some issues with Scientists finding Class Ds
- Class Ds will now only use the Toilet, or go to Sleep

**Class Ds are still a bit buggy, I am working out what's going on with them in the coming days.**

## Placement
- Fixed PlacementV2 not placing consistently

# v0.1.24 | 2025-05-21

Adjusted Pathfinding Heuristic for better accuracy
Added shift click multi select for deletionV2
Added backwards rotating with new keybind
Improved PlacementV2 collisions

# v0.1.22 | 2025-05-21

- Fixed Bed Pathfinding
- New Roaming System
- Deletion Control V2!
- Scientific Desk rebranded to Computer Desk and model re-adjusted for better performance
- Labzone accepts Computer or Standard desk

# v0.1.21 | 2025-05-20

Added Number Notifier Icon to Research to show Research Points
Song UI
Fixed NPCs not going to their positions at the end of walking paths.
Improved HUD left/right side texts for more dynamic options

Re-picked many Background Musics

# v0.1.20 | 2025-05-20

Batching system for pathfinding
Vector:ID() Memorized for better performance
Added Staging to Version Text in HUD

# v0.1.19 | 2025-05-20

Staging Place system

# v0.1.17 | 2025-05-20

Fixed large server-sided memory leaks regarding pathfinderV2
Actor objects are properly cleaned up and tycoon world instances are destroyed

# v0.1.16 | 2025-05-20

PathfinderV2 removed extra data passing through actors
Throttled pathfinding to less than 5ms frame time max
Implemented Caching of paths

# v0.1.15 | 2025-05-20

PathfinderV2 switched to parallel lua

# v0.1.12 | 2025-05-20

PathfindingV2 between sectors is now implemented
Placement preview no longer shows node graph attachments
HUD ui padding fixes

# v0.1.11 | 2025-05-20

Fixed Pathfinding Diagonals

# v0.1.10 | 2025-05-20

PathfinderV2 Implemented

# v0.1.9 | 2025-05-19

Fixed Metal Detector Pathfinding
Added throttling to pathfinding fails to prevent lag from no paths
Improved Elevator Pathfinding

# v0.1.8 | 2025-05-19
Widened angled door pathfinding 2

# v0.1.4 | 2025-05-19
Added a Default Base for New Tycoons
Fixed an issue where ClassDs would fill up datastores.
Fixed NPC Idling
Additional camera fixes.
Performance improvements.
# v0.1.2 | 2025-05-18

New Versioning System

# 05/18/2025
Fixed script crash from dispersing level points
Fixed sector selection menu getting you stuck if you are in first person
All menus now respect the back button keybind (default X on computer)
Fixed zoning positioning being inconsistent
Fixed camera getting stuck when closing out a menu
Improved efficiency of pathfinding cache by only invalidating caches that are blocked by an object
Improved NPC Simulation Lerping (ditched tween service)
Improved the loading process of a tycoon
Fixed short walls pathfinding
Fixed lag when loading a tycoon due to class ds
Fixed research readability
Fixed zones colliding across sectors
Added feedback button
Fixed roofs staying hidden outside of build mode
Drastically improved server performance by simplifying and optimizing NPC queries for animations and station bindings.

# 05/17/2025
Initial Alpha Release

## Free Weekend Begins
