# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview

In the tabletop game Dungeons & Dragons, one of the most complicated mechanics of the game is combat. Each player has their own moves, statistics, special abilities, and items that affect how combat progresses and can result in a messy and unsatisfying fight if the Dungeon Master loses track of any one of those elements. My project is a simple, lightweight tool for Dungeon Masters to keep track of their players and whoever their players are battling (we'll call these enemies "Monsters" for brevity's sake). The idea for a more simplified tool comes from my own frustration with the available tools out there, which may be attached to a fairly unstable and desktop-only Tabletop simulator (Roll20.net) or a feature-bloated paid service (D&D Beyond). I wanted an easily customizable, tablet-friendly, and visually simple interface for adding player and monster information, setting up combat encounters, and tracking limited-use or timed abilities throughout the battle. This app is meant for at-the-table play, not as a replacement  or simulated tabletop (IE, there will be no dice rolling or battle-map features, since that happens at the table).

### Features
- User Accounts: Dungeon Masters can log in to keep their players and monsters saved to their account between sessions. If a battle has to extend over multiple sessions, the app will remember where you left off and what state each player/monster was in at the time.

- Create Characters/Monsters: In preparation for their game, dungeon masters can add players and monsters to their saved catalog, in as much or as little detail as they like (IE, if they just want a name and HitPoints that’s fine, or they can go into full detail by listing a character’s abilities, speed, statistics, or more). The character/monster builder is freeform, giving room for the dungeon master to customize their information as they like. 

- Track Battles: During the game, dungeon masters can pull characters and monsters into a battle scenario on the fly, order them by their Initiative Roll (the system used to determine who goes in what order), and start the battle. 

- Player View: During a battle scenario, players can access the Player View (via phone, tablet, or pc) and see the list of combatants, whose turn it currently is, and information about the character/monster who is currently taking their turn. The DM has the option to hide certain information from the Player View during monster creation (because it’s fun to have secrets sometimes). This would also be a handy way to display that information on a central screen (television, monitor) for the whole table to see together. 

### Technologies
- C#: to build web app
- Razr: for building characters/monsters with inputs
- Bootstrap?: for responsive layout on mobile
- Javascript: for player view updates
- SQL: for storing characters/monsters to user catalogs

### What I'll Have to Learn
- Cloud storage/persistence with SQL
### Project Tracker
https://trello.com/b/YyVyGLB4/dd-battle-tracker
