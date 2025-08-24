version 0.01

# ael-structures

This is a simple ttrpg system (yet another, yay!) that is focused on sci-fi and space exploration.
The system was designed to be learned in 30 minutes, and so that the first mission to be played in 2-3 hours.

Another important difference from other systems is that players will generate most of the story and events themselves.

# World description

Humanity spread over thousands of galaxies long time ago. Then their transportation system collapsed, and now only military spaceships are able to travel fast enough to cross star systems.
You are located on the outer side of the HumanUnion - state that united humanity after The Great Depression. Not every nation or system in the union is happy to be part of it. They are ok to have business with outlaws like you.
You live on a space station. Everyone on it is an outlaw. Not that important to send force to kill or capture you, but if you are captured, you will be sent to the mines where you will die in 3-5 years.
Your station is on the constant move to avoid military or other enemies. You learned to survive by performing various unlawful missions.
Some corporations have their secret labs and factories on the outer side.


# Game setup and layout


# Turns

Each turn is 1 minute

# Base generation (cellgrid)

Throw dice to calculate building heights above surface level. Size of the dice is closest to the number of cells on one side of the paper. Draw tiny line to outline surface.

GM generates 3 rooms, above surface if possible, close to top, each with own outer hatch/gate. Great if one is hangar that could fit ship.

## Room generation

cell = 2m*2m*2m meter 

Room sizes (in cells): 
- corridor: 1xN
- small: 2x2 - 3x4
- med: 3x3 - 5x5
- big: 
- huge: 8x6
  - hangars 
    - 3x3 for tiny ships
    - 4x4 for small ships
  - storage

For reference, player mission ship is roughly 6x4x4 meters. (could fit into 4x4 cell hangar, or 8x8 metres)


room size: d6 + d4
new doors: min of above/2 (round up)

If one of the dice values is 1 - then it is just a corridor.


To find out the room type, throw d4. Next time for room type, throw d6, and keep increasing dice size until d20.


storage
living quarters / residential
kitchen and canteen
engine/machinery
station operator 
operative room
hydroponics / garden
med bay
armory
research
jail
repairs
security
dataframe
robot repair hangar?
factory
water purification 
air purification
gravity generator (disabled)
radar room?
defensive ECM
unused room (repairs, redecoration)
throne room
mining/drilling room
junkyard
morgue
cave


## mission in game

After 5th room throw d20. if d20 result less than number of discovered rooms + modifier - that is the mission room.

Mission room have -10 to planned actions complexity.



# Combat

attack dices per team

consumables could add modifiers:
 - e.g. stun grenade may add modifier to enemy attack by x0.5

Each turn team have 2 actions points to perform 2 different actions in any order:
 - attack (either CC or RC)
 - move to another room
 - use skills (every member could use one of his skills)

Note: if more than half of team members are down - move requires two action points. 

## Hitpoints

Team share hitpoints. Calculate hitpoints before each round: participating players * 10 + survival skill rolls.

When team hitpoints reduced by 50% - one person becomes inactive. Everyone rolls survival, player with lowest result. All his skills are /3 round down. Recalculate current dmg dices. 
When team hitpoints reduced by 75% - one more person become inactive.
When team hitpoints reduced by 87% - one more person become inactive.
When team hitpoints reduced by 94% - one more person become inactive.
When team hitpoints reduced by 97% - one more person become inactive.

When hitpoints become less than number of alive players, everyone alive rolls survival, character with lowest result becomes completely dead.

Example 
4 players. One is pilot who stays in ship. One character have 5 survival, another have 2 survival: 3 * 10 + d4 + 5 + 2

# Skills

Each player may have all possible skills at level 0. 

Skill check consist of:
1. d20 + modifiers for attempt complexity.
2. Character skill + rolls + assists for success.
Success if character roll/skill sum is bigger than complexity sum.

Complexity depends on the following things:
1. Player character participating in the game.
2. Common sense on actual task complexity.

## Skill roll
skill - roll
0 - 0 (no dice)
1 - 1 (no dice)
2 - 2 (no dice)
3 - 3 (no dice)
4 - 1d4 + 4
5 - 1d4 + 5
6 - 1d6 + 6
7 - 1d6 + 7
8 - 1d8 + 8
9 - 1d8 + 9
10 - 1d10 + 10
11 - 1d10 + 12
...
15 - 1d10 + 1d4 + 15
16 - 1d10 + 1d6 + 16
...
19 - 1d10 + 1d8 + 19
20 - 2d10 + 20
21 - 2d10 + 21
...

Each 5 levels (starting from 5th) player add specialization to the skill. 

Rolls sum = roll + 5 for each matching skill +3 for every assist matching skill.



## Skill levels examples

| Skill | Level                 | Combat                         | Medical             | 
|-------|-----------------------|--------------------------------|---------------------|
| 1     | novice                | knows how to not shoot himself | .                   |
| 3     | hobbyist              | .                              | first aid skills    |
| 7     | amateur               | guard                          | nurse               |
| 10    | professional          | soldier                        | surgery operations  |
| 15    | elite                 | swat                           | brain surgery       |
| 20    | best in area          | specops                        | brain implants      |
| 30    | best in empire        | .                              | create new diseases |
| 50    | best in world         | superhero                      | .                   |
| 80    | best in universe      | .                              | cure civilization   |
| 130   | best in all universes | god of war                     | .                   |


## Skills.
Survival - find interesting things, +hp for game session, scavenging, taking cover, holding breath, helping others to stay alive, use of space suits.
Close Combat - same room, usually blades, shields, shotguns, smgs, rifles.
Ranged Combat - other rooms, rifles, sniper rifles, rocket launchers.
Medical - surgery operations, first aid during combat (consumables),  
Social - talk, trade, negotiate.
Hacking - computers, security, AI, identity forgery
Science - optics, electrics, energy, chemistry.
Mechanical Engineering - motors, pumps, engines, anything else that rotates or moves other things.
Piloting - any vehicles, drones, spaceships, mechanized armor, navigation.


## Additional items and consumables

By default each character have his primary weapon, clothes. 

Once per turn character could try to get some item from backpack to use.It could be consumables: grenade, medkit, etc. Or it could be Non-consumables.

To validate if character have it - roll d4. If > previous success - success. If success you get that item, mark 1 on the character sheet in backpack. Each new item reduces the chance to get next item. 

Chance modifiers: 
 - matching your skill +1
 - matching one of your specializations +1 (or matching multiple specializations +2)
 - small consumable +1
 - big item -1
 - for each 10 points in survival - +1


player roll d6 for any 

# Missions

## base types

warehouse
training
trading
research
military
jail

## missions
theft
eliminate person
retrieve data
rescue person
place explosive
clearing out enemies (inside friendly base)

## Mission generation

Roll d6 for base type and d6 for mission.

## GM preparation checklist

 - World story for new players.
 - Rules for new players.
 - Org name of employer.
 - Target org name.
 - Generated mission base room tables.
 - Generated mission NPC tables.
 - Pregen 3-6 characters.
 - Pregen GM character.
 - Empty character sheets.
 - Mission and ship printouts.
 - 3 set of dices (or more).
 - 


## Mission complexity

Intro session should have complexity -10 or even -15.


3 player each 40. Mission complexity -15.

Elite squad should have about 50 points each. Mission complexity +20. 

Superheros 130 each. Mission complexity +40. 

## Roles

Comms - GM, who usually stays in the ship. Rolls enemy dices. Draw rooms layout. If less than 4 players, preferably act as pilot.
Panic-monger - could cancel mission, and force everyone to escape. Always survive if cancel mission.
Squad leader - make decisions when no agreement. Roll team combat dices. Could not be same as Panic-monger
Pilot - control ship before landing. Ship can't fly away without him. 


# Rewards

If a mission is successful, then each player picks another player that he liked, and gives gim one skill point. Gm could also receive point, GM gives 3 points(could be to the same player).
How to do it.
1. Each player reflect on what he liked most during game. 
2. Then pick a dice, select player number (1 is left to GM, then CW) and place it in front of him covering by hand.
3. When everyone is ready, reveal choices simultaniousely. 
4. Starting from the player left to GM, share what he liked and why he is giving point to specific player. 


# Mercs and fast char generation

Here is a list of pregen characters for the first game. They could be used at any time, but they will not get any new skill points.
For 1 or 2 players it might be impossible to cover all of the skills. As an alternative, specialized bots could be used for first 10-15 minutes of mission.
Each bot may have 1 or 2 skills up to level 4. 

## 1 player

40-45 skill points, max skill 20
2 bots of choice, one with skill 6 + specialization, one with 2 skills of 2
(remember, GM also get points)

## 4-6 players fast gen
GM either have own character or participate in team generation. 
Each player pick 2 different skills from first 3 and give to his neibhours. Each of them will be 6 points.
Each player pick 2 different skills excluding first 3, and give to his neibhours. Each of them will be 6 points.
Each player add X points as they wish and add any specializations. Where X based on number of players:
4 players - 10 points (34 points total)
5 players - 6 points (30 points total)
6 players - 4 points (28 points total)



# Example of the game

GM do some preparation
Rules and skills explained
Roll characters


