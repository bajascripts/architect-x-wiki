---
title: Latest Update
description: 
published: true
date: 2025-05-19T00:10:59.471Z
tags: 
editor: markdown
dateCreated: 2025-05-04T06:27:06.560Z
---
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
