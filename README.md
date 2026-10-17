# Aliens Campaign Prologue

**Aliens Campaign Prologue** this is the first version of my new alien campaign. It's not a full-fledged campaign yet, but a demo for testing and feedback.

## What implemented in this version

- **Two missions for the alien side.** The first version of the mod includes two missions that you can play for sectoid team against the different human forces.
- **New units** The current version 0.0.1 introduced several new units: farmers, soldiers, scientists, and several wild animals depending on the mission biome.
- **The third side - aggressive neutrals** These wild animals appearing in missions are aggressive neutral creatures (except for dogs, which are on the human side). Neutral animals attack both your Sectoids and enemy human forces, so this can add to the fun.
- **New abilities for sectoids** In my campaign, I plan to add more abilities that depend on the alien type. Some of them are already implemented in version 0.0.1. The full list will be below.
- **New building on the battlefield** I'm currently using the standard X-COM maps, but I've added a new building — the laboratory. It appears in some missions.

## New units

### Aliens fraction

1. The Drone Scout - is a reconnaissance drone, which can be spawned during combat.

### Humans fraction

1. Farmer - appears on the farm, uses a regular rifle or a pitchfork.
2. Old Farmer - the same that farmer, but another sprite
3. Dog - just a dog that appears with the farmers
4. Soldier - appears in the lab mission, uses a regular rifle
5. Scientist - appears in the lab mission, don't have a weapon

### Neutral fraction

Depending on the biome, some wild animals may appear. They will attack both sides: the sectoids and the humans.

1. Polar bear - arctic biome
2. Hyena - desert biome
3. Wolf - wood biome
4. Panther - jungle biome

## Allowed abilities list

### Sectoid commander

1. Psy control - standard ability, you can control living enemies (including animals)
2. Panic attack - standard ability, you can decrease enemies morale
3. Life detection - you can detect one random living enemy on the battlefield. Useful for locating hidden enemies.

### Sectoid medic

1. Heal - you can increase HP of your sectoids
2. Treat Wounds - you can remove one treat
3. Restore Morale - you can restore several morale points

### Sectoid navigator

1. Deploy Scout - you can summon one reconnaissance drone once per battle—this is a new flying support unit.


## Current version game restrictions

1. Wild animals are neutral objects, so you don't see them as enemy markers (but they will attack you). This is an OXCE limitation that I can't fix without using own fork.
2. The economic component is disabled, my mod doesn't support the economy right now, but I also can't disable it completely because it's an OXCE limitation, so it's still there, but with zeros.
3. A lot of what I planned hasn't yet been implemented in version 0.0.1. Currently, researches, production, buildings, the Ufopedia, and a number of other things haven't been introduced.

## How to play this mod

1. Unzip the archive into the mods folder. You can also download it from GitHub.
2. Launch OXCE and select this mod from the mod menu (it's a new separate mod).
3. Start new game
4. In the game, you'll have a set base, one medium scout, and several Sectoids. Missions will appear periodically. At the beginning of each month, you'll receive new Sectoids.
5. You can complete missions and use new mechanics


## Requirements

- OXCE 8.7.0
- Tested on Windows and Linux with OXCE 8.7.0

## What next

If this mod is accepted by the community and I have some free time, I have a plan for what to do next:

1. Complete missed mechanics: Researches, Manufacture, etc
2. New missions: I have a plan to finish the prologue, which will be a short campaign consisting of several missions.
3. New units, skills and items
4. New objects on the battlefield

Enjoy the game and have fun!

