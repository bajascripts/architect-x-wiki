---
title: Latest Update
description: 
published: true
date: 2025-06-07T14:44:01.048Z
tags: 
editor: markdown
dateCreated: 2025-05-04T06:27:06.560Z
---
# v0.5.12 | 2025-06-11

- Fixed an issue where tycoonID/owner attributes did not clean up causing black-box glitch.

# v0.5.11 | 2025-06-11

- Fixed tycoon unloading wrong ids
- Fixed tutorial staying put when leaving tycoons
- Fixed many errors/warns in console

# v0.5.10 | 2025-06-10

- Improved user interface error handler page with reconnect button
- XP bar now shows real number
- Increased XP earnings from SCP tests

# v0.5.9 | 2025-06-10

- Fixed an issue where tycoon saves did not close out correctly.

# v0.5.8 | 2025-06-10

- Analytics improvements

# v0.5.7 | 2025-06-10

- Improved linking control to show the objects that can be used to satisfy the requirements.

# v0.5.6 | 2025-06-09

- Data Loading Fixes

# v0.5.5 | 2025-06-07

- Fixed view filters with decorations

# v0.5.4 | 2025-06-07

- Barrier decorations added!

# v0.5.3 | 2025-06-07

- Tycoons are now saved immediately after process receipt


# v0.5.2 | 2025-06-07

- Amended fixes

# v0.5.1 | 2025-06-07

- Fixed accumulated profits
- Fixed chat ui disappearing
- Fixes tycoons not unloading correctly
- Tycoon Names may contain hyphens in the middle

# v0.5.0 | 2025-06-07

- Profile Service switched to Document Service for data saving. This may cause issues, please report any issues.

Due to this change this update is a minor version change.

# v0.4.31 | 2025-06-05

- Adjusted scaling of all menus for mobile and desktop resolutions
- Made every menu use space more efficiently (filling the entire screen)
- Switch research UI to use ScrollingFrames instead of custom approach

# v0.4.30 | 2025-06-05

- UI now adjusts to roblox's horrid core gui (that has less features and is bigger btw)

# v0.4.29 | 2025-06-05

- Bottom bar converts to topbar on small screens
- Adjusted scaling in menus to be more responsive

# v0.4.28 | 2025-06-05

- Mobile Compatibility for Build/Delete/Linking!

# v0.4.25 | 2025-06-03

- Added angry skippy when scientists die.

# v0.4.24 | 2025-06-03

- Added the ability to teleport to other bases
- Added sprint ability


# v0.4.22 | 2025-06-03

- HUD and build menu has been reworked
- Added new selection mode to build mode
- New Tutorial!
- Fixed an error in findHomeStations

# v0.4.21 | 2025-06-01

- Added a setting to show/hide timers
- Fixed office roof wedge
- Fixed memory leak with collision notifier

# v0.4.20 | 2025-06-01

- In editor mode, you can now see the floors below you when on higher floors
- XP scaling added for SCPs

# v0.4.19 | 2025-06-01

- SCP Finances redone to "profits"
- Added name change in SCPF Management
- Added perm-deletion of saves


# v0.4.18 | 2025-06-01

- Fixed collision issue

# v0.4.17 | 2025-06-01

- HUD Fixes
  - Fixed xp colliding with music/version
  - You can now see finances of other people's bases
  - HUD cleans up on other bases
- Payperiod is now 3 minutes
- Readjusted profits of all SCPs using formulas for balances
- Leveling balances and SCPs give higher XP for longer tests
- Added additional lighting effects to SCP4854

# v0.4.16 | 2025-06-01

- Floors are now required for NPCs to walk
  - This has added benefit of lowering the amount of nodes required to be queried for paths.
- Beds can be placed against walls and still work
  - The pathfinder will attempt to pathfind to the center of the bed rather than bottom edge.
- Fixed being able to place objects over other

# v0.4.15 | 2025-06-01

- New Grid units option for building!

# v0.4.14 | 2025-05-31

- Adjusted timers
- SCP Effects for all SCPs except SCP 005 (more later)

# v0.4.13 | 2025-05-31

- Removed zone view filter
- SCPs will only follow NPCs
- Timers added to show NPC progress and cooldowns
- XP from test is now scaled based on SCP profits
- SCPs now have cooldowns (shown)
- Rebalance of many scp profits and costs
- Level Rebalances
- Tests now start immediately, no need to go to the ClassD cell.

# v0.4.12 | 2025-05-31

- LIMIT of 50 of each furnishing object has been implemented.
- Scientist NPC is now limited to a maximum of 20.
- Security NPC is now limited to a maximum of 10.
- Pathfinding revised for better performance.

# v0.4.11 | 2025-05-29

- Fixed pathfinding performance issues

# v0.4.10 | 2025-05-29

- Fixed NPC client models to be transposed on spawn
- Fixed ClassD spawn issue
- Fixed diagonal doors

# v0.4.9 | 2025-05-29

- SCP 999 has made an appearance!
- SCP 999 will follow people!

# v0.4.8 | 2025-05-29

- Fixed packs not updating object browser
- Improved accuracy of deletionControlV2
- Fixed multi-threading after unloading a base

# v0.4.7 | 2025-05-29

- Changed npc simulation cycle to 10 times a second instead of 20 to improve performance.

# v0.4.6 | 2025-05-29

- Improved NPC finding home station query performance

# v0.4.4 | 2025-05-29

- Switched tycoons to multi-threaded with 16 threads for pathfinding and other expensive calculations.

# v0.4.3 | 2025-05-29

- Changed pathfinding queue process rate

# v0.4.2 | 2025-05-29

- Removed zoning button that shouldn't be there

# v0.4.1 | 2025-05-29

- Fixed unpublished flag for variants

# v0.4.0 | 2025-05-28

- Internal/UI: new object browser component
- ECS reworked for better stability
- Auto zoning removed in favor of a new manual linking system
- Fixed pathfinding grid errors by using re-construction
- Fixed bug with research points
- Class D limiter fixed
- Fixed testing between sectors (and anything really)
- Fixed researching

# v0.3.3 | 2025-05-26

- Improvements to accuracy of auto zoning system

# v0.3.2 | 2025-05-26

- Adjacent room system for SCP containment chambers
- Restructured requirement description
- Increased size maximum for zones

# v0.3.1 | 2025-05-26

- Fixed testing profits being 0

# v0.3.0 | 2025-05-26

- Small Pathfinding Node graph fix when deleting objects
- Fixed office roof wedge being upside down
- New intro scene thanks to racemaniak2000
- Auto Zoning System, manual zoning has been removed.
- Fixed issue where Class Ds wouldn't cleanup when you destroy a bed.

# v0.1.36 | 2025-05-24

- NPCs now respect NPC Render Distance setting
- Animations now respect NPC animation setting
- Fixed NPCs disappearing when entering menu
- Jabby (internal debugging) patches

# v0.1.35 | 2025-05-24

- Fixed Replication System when loading new bases

# v0.1.34 | 2025-05-24

- New Replication System (Experimental)
 - NPCs are now rendered on the client, freeing up lots of server resources.
 - Your tycoon objects will soon be client rendered only.

# v0.1.33 | 2025-05-22

Floor/Roof Wedges

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
