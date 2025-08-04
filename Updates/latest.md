---
title: Latest Update
description: 
published: true
date: 2025-07-27T16:57:36.998Z
tags: 
editor: markdown
dateCreated: 2025-05-04T06:27:06.560Z
---
# v1.9.16 | 2025-08-04

- Competition Game Mode

# v1.9.15 | 2025-08-03

- Fixed potential store issue
- Game-mode backend
- Other improvements

# v1.9.14 | 2025-08-03

- Fixed duplicate purchases of skins with money
- Internal Adjustments
- Added loading status when loading a base
- Mobile sensitivity fixed
- Mobile UI scaling adjustments

# v1.9.13 | 2025-08-03

- Further pathfinding fixes with diagonal starts/ends

# v1.9.12 | 2025-08-03

- Fixed attempt to index nil in shop (and other areas too)

# v1.9.11 | 2025-08-03

- Fixed an error in the store
- Diagonal pathfinding fixes

# v1.9.10 | 2025-08-03

- Fixed an error in the store

# v1.9.9 | 2025-08-03

- Rate limited pathfinding grid updates for better performance

# v1.9.8 | 2025-08-03

- NPC Fixes
- Internal Changes

# v1.9.7 | 2025-08-03

- Fixed Weird ECZ Pack lighting
- Switched to new datastore wrapper (ProfileStore)
- Additional performance improvements for NPCs
- Added path blocked error icons to individual objects

# v1.9.6 | 2025-08-02

- Converted some scripts to native
- Removed debug parts

# v1.9.3 | 2025-08-02

- Fixed wall-walking NPCs
- Fixed barriers
- Fixed pathfinding at entrances

# v1.9.2 | 2025-08-02

- Added debug show pathfinding grid
   - Enable debug mode and its a button in the build editor
   - Not compatible on mobile
- Fixed "wall" text

# v1.9.1 | 2025-08-02

- Fixed Research
- Fixed Bombs
- Fixed Editing Tycoons

# v1.9.0 | 2025-08-02

## Updates
- New Light Zone Pack
- New Legacy Heavy Zone Pack
   - Purchasable with in-game money or Robux
- New NPC Pathfinding v4
   - Huge performance improvements
   - NPCs no longer roam
      - Class Ds will sleep if nothing to do
      - Scientists will research at a desk if nothing to do
      - Security will patrol place patrol points if nothing to do
      - Engineers will patrol generators if nothing to do
- Security carry guns to look extra mean

## Changes / Fixes
- Data saving fixes, rebuilt data saving system
- Increased limits on NPCs, Objects, and Decorations.
- Mobile improvements and fixes
- You can skip the intro by clicking/tapping.

# v1.8.1 | 2025-07-29

- Data Store Improvements

# v1.8.0 | 2025-07-27

- When calculating unpowered objects, objects closest to generators are prioritized to receive power
- When a scientist dies to an SCP, the SCP is sent in the notification.
- When a path to an SCP succeeds, it clears any old notifications about pathfinding automatically. This also applies to other stations such as tables or beds.


# v1.7.0 | 2025-07-27

- UI Spelling Fixes
- UI Performance Improvements
- Performance Improvements
- Server Performance Improvements
- Echo Pack fixes
- Elevated Pack Fixes
- Allow Collisions gamepass now applies to Decor/Furnishing/SCP

# v1.6.0 | 2025-07-26

## Updates
- New Engineering & Technical Staff
- New Generators and Power Requirements
- New ECHO Build Skin
## Fixes
- Data saving fixes
- Data session lock improvements
- Deletion Fixes
- Pathfinding Fixes

# v1.5.2 | 2025-07-20

- Adjusted npc server timings to improve performance


# v1.5.0 | 2025-07-19

## New Content
- SCP 010
- SCP 025
- SCP 099
- SCP 1025
- Premium Elevated Pack

## Changes
- NPC Limits adjusted, and added into a research tree (they will be expanded again).
- Level scaling lowered, speeding up progression of levels, this will be further increased as the research tree expands.
- Increased overall profit
- Lowered cooldown/testing time for SCPs


## Fixes
- Maintenance pack fixed (thanks Dav)
- Temp removed the auto creation of new base when you have non
- Fixed some errors in linking
- Fixed an issue where you could enter linking mode on someone else's base
- Fixed dialog showing up while on other people's base
- Opened up the pathfinding for Blast Door
- Misc Fixes

# v1.4.14 | 2025-07-19

- Floors no longer required for NPCs
- Fixed a loading issue with intro
- Game autoloads in a new tycoon when non are created

# v1.4.11 | 2025-07-14

- Added SCP Exposure in NPC Status page
- SCP 500 will cure all exposures restore health.

# v1.4.10 | 2025-07-14

- Lowered tick rate of task processor for better NPC performance
- Removed Gems from UI

# v1.4.8 | 2025-07-13

- UI Fixes & Improvements
- Bomb system added to store!
- 7 new songs added!

# v1.4.7 | 2025-07-13

- Added update status UI

# v1.4.6 | 2025-07-13

- Fixed descriptions in object browser
- Required safe humanoid before euclid in research tree
- Added chat tip system
- Added linking control in selection UI
- Added profit/xp per test, in selection UI
- Level up now gives 1 research star, every 5 levels you get 2 research stars.
- Drawn linking lines are only shown in linking mode

# v1.4.5 | 2025-07-13

- Tutorial fixed

# v1.4.4 | 2025-07-13

- New pack preview system
- New selection system (with move tool!)
- Menu keybind remapped as move keybind (no menu keybind anymore)
- Main menu save usage % fixed

# v1.4.3 | 2025-07-12

- Improved pathfinding error notifications to be more accurate and less false notifications
- Fixed a critical issue where a previous failed pathfinding attempt would cause a successful one to fail
- Fixed an issue where an NPC's true name would not show on the status page

# v1.4.2 | 2025-07-12

- Further collision tweaks
- NPC experience adjustments
- Security receive experience from tests

# v1.4.0 | 2025-07-12

## Updates
- SCP 004
- SCP 109
- SCP 034
- Sector 3
- Codes in Shop
## Fixes
- Many NPC fixes
- Improvements to linking
- Research tree improved and cleaned up for a much better look and functionality
- Quick settings button added
- Staff moved into SCPF management
- Improvements to the UI

# v1.3.28 | 2025-07-12

- Minor improvement to linking where when placing an object the object is auto-linked
- Lowered SCP collision boxes and improved them
- Fixed confusion when deleting SCPs that are moving

# v1.3.27 | 2025-07-12

- More NPC Fixes

# v1.3.26 | 2025-07-12

- Fixed NPCs

# v1.3.25 | 2025-07-11

- Improved the selection process of nearest tables ,toilets, and beds.

# v1.3.24 | 2025-07-11

- Placement Collisions Fixes
- Object  validity adjustments
- Pathfinding Improvements
- Main menu fixes

# v1.3.23 | 2025-07-11

- Added codes API in store

# v1.3.21 | 2025-07-11

- Fixed a critical pathfinding issue
- Fixed a critical NPC issue where they would freeze

# v1.3.20 | 2025-07-11

- Fixed an issue where NPCs would "error out" and freeze
- Improved collisions
- Fixed an issue where NPCs would roam into angled walls
- Roblox pathfinding now hybrid-used for cross-sector travel

# v1.3.19 | 2025-07-10

- You are now unable to place walls too close to SCPs

# v1.3.18 | 2025-07-10

- Pathfinding is offloaded to Roblox's pathfinding service when possible to save performance.
- When finding Toilets, Cafeteria Tables, and Beds, NPCs will now prefer the closest. (Except assigned beds for ClassD and SCPS)

# v1.3.16 | 2025-07-09

- Fixed being able to place objects outside your base.
- Blast Doors properly block NPCs
- Misc. UI Fixes and improvements

# v1.3.15 | 2025-07-09

- More Max Saves Game-pass
- Economy Balances

# v1.3.14 | 2025-07-08

- Fixed a critical bug with build objects being built outside of bases.

# v1.3.13 | 2025-07-08

- SCP 173 will not kill while Scientists walk to it for a test.

# v1.3.11 | 2025-07-07

## Update
- New Blast door (with research) to help you transition between sectors

## Fixes
- Improved replication performance
- Improved NPC performance when setting simulation distance
- Removed NPC Render distance in favor of simulation distance
- Main Menu Fixes

# v1.3.10 | 2025-07-06

- Pathfinding Grid is now  2 studs from 4 (4x more accurate). This means NPCs can now navigate diagonal cut-off floors.
- This may put extra stress on the server, however, initial testing has been promising.

# v1.3.8 | 2025-07-06

- UI Tweaks
- Fixed notification-drawer on mobile
- Major Economy Tweaks (more revenue, exponential progression)

# v1.3.7 | 2025-07-06

- Fixed elevator issues
- Cleaned up notifications to not show as many
- Wedges can now be collided 2 times to allow for both wedges to be placed in a single tile
- Fixes for NeoCore Pack
- Cleaned up and fixed main menu
- HUD improvements

# v1.3.2 | 2025-07-05

- Updated React (UI)
- NPCs can now roam through doors and a better fix to prevent NPCs from roaming into 173 has been implemented.
- Fixed elevator causing pathfinding bugs


# v1.3.1 | 2025-07-05

- NPCs no longer roam through doors
  - this addresses wandering into containment zones

# v1.3.0 | 2025-07-05
## Content
- SCP 173 (you'll want a containment cell!)
   - SCP 173 has a chance to randomly kill exposed NPCs (be careful!)
   - SCP 173 REQUIRES 1 Scientist, 3 Class D, AND 1 Security to Test
   - A more clear way of relaying this to the user is coming soon, for now its in the description of the SCP.
- NeoCore Build Skin
## Fixes
- Some replication optimizations
- Lighting optimizations
- Reduced lag in many scenarios for lower-end devices
- Added global shadows property for performance
- Mobile Camera improvements
- Fixed mobile placement placing twice

# v1.2.25 | 2025-07-03

- Removed pay period system for clarity- you now directly get your profits
- Added chat tags for alpha/beta testers
- Fixed pathfinding for barriers
- SCP 999 roaming finished

# v1.2.21 | 2025-07-03

- Fixed NPC needs related too passing out, this system has been removed and instead will prevent NPCs from being productive.

# v1.2.19 | 2025-07-03

- Fixed an issue where NPCs wouldn't address their needs if an SCP killed an NPC.

# v1.2.18 | 2025-07-02

- Re-Wrote ObjectService.ts to fix buying/selling objects.
- Improved mobile camera

# v1.2.17 | 2025-07-02

- Pathfinding Improvements
- Fixed Roaming causing NPCs to get stuck

# v1.2.16 | 2025-07-02

- Buying & Selling Fixes
- NPC Stability Improvements

# v1.2.15 | 2025-07-01

- Roaming Fixes

# v1.2.13 | 2025-07-01

- Roaming & Behavior Improvements for NPCs

# v1.2.11 | 2025-06-30

- Adjusted NPC Roaming to no longer use pathfinding

# v1.2.9 | 2025-06-29

- Fixed a critical bug with test profits

# v1.2.8 | 2025-06-29

- x2 Testing profits Pass

# v1.2.7 | 2025-06-29

- Improved performance by 10x by caching ECS queries. You should see better Client FPS and better Server FPS.
- Improved pathfinding speed by implementing caching
- Store Improvements
- Increased tolerance for collision checks


# v1.2.5 | 2025-06-28

- Corrected bell sound radius
- Added Gems to Store
- New Collisions Gamepass

# v1.2.2 | 2025-06-28

- Fixed a delete object bug
- Interface Colors Refreshed

# v1.2.1 | 2025-06-28

- Pathfinding performance improvements

# v1.2.0 | 2025-06-28

## Updates
- NEW SCP 426
- NEW SCP 513
- Powerful new SCP Effects system on NPCs (426,513 implemented more to come)
- New Background Music!
## Fixes
- Added "Max Placed" text to objects in the build menu
- Error catchers for haptics
- Fixed SCP behavior timings
- Improve mobile placement by delaying before mass placement activates
- Misc. Fixes
- Removed path failed markers, pending a different system
- Removed pathfinding blocks on all objects except walls
- Economy Adjustments

# v1.1.2 | 2025-06-22

Hot fixes to ECS cleanup

# v1.1.1 | 2025-06-22

- Maintenance pack fixes and adjustments
- Fixed collisions for build mode on desktop and mobile
- Added error catch to SCP profits tab
- Improved memory cleanup of ECS


# v1.1.0 | 2025-06-21

## Updates
- Maintenance Build Pack
- SCP 500 Added
- New Intro Screen
- New Menu Music
- Mobile mass-placement system
## Fixes
- Fixed a huge ECS memory leak
- Added money indicators to research & tests
- Store Updates
- Collision notifiers clean up
- Small tutorial edit for mobile
- Improved linking system
- Sped NPC queries by a lot
- Timers added to NPC status page
- Fixed object limiter on load
- Fixed tablet grid unit UI
- Improved accuracy of mass-placement system

# v1.0.3 | 2025-06-16

- Fixed elevator deletion issue
- Hunger/bathroom needs no longer slow NPCs down, instead of the need gets to bad they wont do other tasks (like tests)
- Test animations are now scaled based on simulation time
- If a Class D passes out during a test the test will fail
- Added in-game change log

# v1.0.2 | 2025-06-16

- Fixed Research points reward

# v1.0.0 | 2025-06-16

## Entering Beta
Game will switch to $R50 Paid Access after this free weekend

### NEW NPC Needs system
- You can see average needs in the staff menu
  - Food - NPCs need to eat, if they don't they will walk slower
  - Energy- NPCs need to sleep, if they don't they will walk slower and eventually pass out for 30 seconds
  - Bathroom - NPCs need to go! if they don't they will walk slower

### Economy Changes
- NPC costs are now scaled
- Starting cash for standard mode is now $25,000

### Other Fixes & Improvements
- Fixed shelf category
- increased max node search from 5000 to 7500 for pathfinding to improve reliability
- Decor limit is now 200
- Fixed mobile bug where the grid units and close buttons are hidden
- NPC Status Fixes
- Analytics corrections
- Fixed deletion bugs when changing floors
- Fixed elevator deletion
- Removed Sector 3,Omega to prevent confusion (not added yet, will make an appearance in time)
- Fixed Architect Doors Z-Fighting
- Added feedback messages for linking
- Improved feedback field and it's metrics
- Improved pathfinding by checking adjacent around start/finish nodes to if the closest start/finish node is blocked. This may result in a npc clipping through walls but, it's more forgiving and less confusing for players overall.
