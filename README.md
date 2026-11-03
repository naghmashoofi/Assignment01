# Assignment 01 — Game Engine Principles

## Partners
- Naghma Shoofi - 323968701
- Saeed Tarabeh - 322969288

## How to run
Open Assignment01.uproject in Unreal Engine, then open the
Lvl_ThirdPerson map, and press Play.

## Controls
- WASD: Move
- Mouse: Look around
- Space: Jump
- E: Open the door while nearby

## Features
- 100 randomly spawned collectibles: coins, gems, and potions.
- Each collectible awards a random score from 10 to 100.
- Collecting an item destroys it and updates the total score.
- Score changes are sent to the UI through an event dispatcher
  and printed on screen.
- A nearby door opens 90 degrees using a Timeline.
- Expanded spawn ranges: X [-1000, 1000], Y [-2000, 2000].
