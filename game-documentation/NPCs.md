---
title: NPCs
description: 
published: true
date: 2025-07-07T02:59:56.088Z
tags: 
editor: markdown
dateCreated: 2024-12-11T03:15:43.217Z
---

# NPCs

**NPCs (non-player character)s** in SCP Architect X serve many functions for your foundation.

**NPCs are meant to be predictable, and have limited random properties or decisions unless explicitly stated**.

## NPC Needs

# NPC Prices

Prices currently depend on the number of NPC's of a certain type that you own and the base price of whichever one your purchasing.

## Math

The prices for NPC's are determined by this

$$
f(c, n) = \mathrm{round}(c \cdot 1.4^n)
$$

where

$c$ - base cost (1000 for Scientist and 1500 for security)

$n$ - number of NPCs (of whichever type you're buying) that you already have

In this provided function, it's raising 1.4 (the scaling factor / growth rate) to the $n$ and then multiplying it by $c$ followed by rounding it to a whole number


Think of $c$ as the base cost,  
and $1.4^n$ as the inflation multiplier that increases the price each time you buy another one.

The total cost of buying $n$ NPCs:

$$
\text{total}(c, n) = \mathrm{round}\left(c \cdot \frac{1.4^n - 1}{1.4 - 1}\right)
$$

## Graphs

These following graphs are for the prices of NPC's for each type of NPC.

### Security price graph
<iframe src="https://www.desmos.com/calculator/3ayynnuwf8?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

### Scientist price graph
<iframe src="https://www.desmos.com/calculator/choujqm7sf?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

# NPC Behavior

Outlined below is the static behavior of every NPC. An NPC's lifecycle is a loop of actions and decisions an NPC will make during it's life time (from hiring to firing).

// for braden to do when behavior trees are implemented