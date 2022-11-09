**Wasteland Rally**
===================

Wasteland Rally is a post apocalyptic vehicle combat game module for the Open Fire tabletop wargame system. It uses heavily modified diecast cars, brimming with armour and weapons, to represent the ramshackle and deadly vehicles of the most popular sport in the Wasteland.

You will need [the core rules for Open Fire](https://github.com/open-source-tabletop/openfire/) to play this game.

# Introduction

## The End of the World

The world ended in nuclear war that destroyed nearly everything, but you've heard that story before. The end of the world before is just history, a myth of a time that no one really remembers. 
These days people get by in small enclaves, heavily fortified camps, scraping by on the meager resources they scavenge from the endless wasteland.

The wasteland is too vast and too dangerous to scavenge on foot, instead the enclaves assemble vehicles from the plentiful wreckage along the old roads and cities. Teams are sent out to pull together whatever they can find. But there are other ways to acquire a little extra...

## The Racing Arena

It's human nature to see a niche and exploit it. That's how we got here in the first place. Against a backdrop of near endless struggle came the racing arenas, and the Wasteland Rally.

Those same teams that scour the wasteland have the opportunity to turn their pitiful hauls into a bounty that will sustain their enclave for months (at just a little personal risk). Competing against other teams in violent races and arena battles, the eventual winner takes all, minus a small fee to the organizer of course.

# Module Rules

## Gates

### Objective Gates

Wasteland Rally uses a custom type of objective marker called a **gate**, which is a line roughly 8-10 inches wide (though you can model more interesting terrain for your gates). Each gate also has a direction, which should be marked on the gate itself and is the direction vehicles must travel across it to count as **crossing the gate**. A vehicle has crossed a gate when it moves so that the entire vehicle has moved across the line in the correct direction.

Some gates will be designated as a **Start or Finish Gate** (and sometimes both) and are used to determine the starting and finishing position of a vehicle in a race.

### Final Finishing Positions

At the end of each round in which vehicles cross the finish gate any vehicle that has crossed the finish line will be removed from the game and ranked according to its finishing position among all vehicles that may have already finished. If more than one vehicle has crossed the finish line at the end of a round the vehicles that have crossed the line are ranked by their distance from the finish line, with the higher distances finishing in front.

### Elimination Gates

Some missions require all vehicles to maintain a position in the race, with vehicles falling behind being eliminated. These missions will require you to mark your gates in a sequence with the first gate being number 1. Some gates can have multiple numbers in the sequence if the players must complete multiple laps. When the game starts the second gate is designated the **elimination gate**.

The first time a round ends where all, or all but one, vehicles have crossed the current elimination gate, one vehicle will be eliminated and removed from the game. If one vehicle has not crossed the elimination gate it is removed from the game, otherwise it is the vehicle that is closest to the elimination gate at the end of that round that is removed. Once a vehicle has been removed the next gate in the sequence becomes the elimination gate.

In addition, if any vehicle crosses a gate that is 2 gates ahead of the current elimination gate (i.e. a vehicle crosses gate 4 when gate 2 is still the elimination gate) then any vehicle that has not crossed the elimination gate is also removed. This happens immediately, and not at the end of the round. Afterwards, the next gate in the sequence becomes the new elimination gate.

## Vehicle Rules

### Losing Control

In Wasteland Rally the **command** attribute of a vehicle represents the drivers skill and control of their vehicle. Any time a vehicle is required to take a **command test** they are at risk of **losing control**. 

If a vehicle must take a command test and fails they will immediately stop moving and the player with the nearest vehicle to their own gets to change the position of the vehicle - note that this sometimes includes the player that owns the vehicle. In addition the vehicle must take a **defence test** when they lose control and take 1 point of damage if they fail.

When changing the position of the car it may be rotated up to 45 degrees in any direction and moved up to 1 inch in any direction. This move cannot cause the vehicle to move over the base of another vehicle, to move out of the battlefield, or over any terrain. In addition, this move cannot trigger additional command tests.

### Moving Over Other Vehicles

A vehicle is permitted to move across the base of any other vehicle so long as it has sufficient movement to completely pass to the other side. To move a vehicle over another, first move it so that it is in contact with the vehicle it wishes to pass, both vehicles will then take a **command test** to see if they lose control.

If the currently activated car passes this test then it may complete its move, passing over the base of the other vehicle. If the test is failed the currently active car loses control as outlined above. If the car that is being passed over also fails its test it loses control but this happens after the currently active car has completed its move.

### Critical Hits

When a vehicle is attacked there is a chance that it will lose control. When a vehicle is attacked and the attacking player hits with a critical success the vehicle must take a command test to avoid losing control.

### Vehicle Weapons

Unless otherwise specified all weapons may only target enemy units in their **front arc**. A weapon will have a special rule for each arc it can attack in if it does not attack in the front arc, i.e. **side arc** and **rear arc**.

## Terrain

### Colliding With Terrain

It can be tricky to manoeuvre a vehicle so that it does not collide with terrain, especially in tight spaces. Any time a vehicle moves so that it is touching any **impassable** terrain it must take a **command test** to avoid losing control. If the vehicle has moved in such a way that it cannot continue moving without reversing then it must wait until its next activation to do so.

### Wreckage

**Wreckage** is a new terrain keyword for Wasteland Rally that represents terrain that vehicles may be able to drive through. When colliding with wreckage the player takes a command test as normal but on a success the wreckage is destroyed and removed from the game and the player can continue their movement. Otherwise the vehicles movement ends immediately.

### Exploding Terrain

Exploding is a new terrain keyword for Wasteland Rally that represents volatile objects set up to be destroyed, potentially causing harm to nearby vehicles. If a player moves into contact with exploding terrain they take a command test as normal but may not move through the terrain. In addition the currently active player should roll a D12 and on a roll of 9 or more the terrain explodes.

Exploding terrain may also be triggered by players shooting at it. On a critical success on a **battle skill test** the terrain explodes.

When exploding terrain explodes every vehicle within 4 inches must take a defence test, if they fail they take 3 hit points of damage. If they are touching the exploding terrain when it explodes they must take 2 defence tests, losing 3 hit points for each failure.

## Additional Special Rules

### Dropper

Dropper is a special rule for weapons. When this weapon is used every vehicle in the rear arc and within range, both friendly and enemy, has an attack made against them with the weapon. Each attack uses the full number of attacks in the weapons profile.

### Obstructing

Obstructing is a special rule for weapons. When a vehicle is hit by a weapon with obstructing it immediately takes a **command test** to avoid **losing control**.

# Building Your Team

When you build a team you create a number of vehicles, spending points on weapons and upgrades.

## Vehicle Types

For each vehicle in your team start by choosing a vehicle type:

| Vehicle    | MOV | SKL | DEF | CMD | HP  | Special  | Points |
| :--------- | :-: | :-: | :-: | :-: | :-: | :------- | :----: |
| Car        | 10  |  9  |  5  |  6  | 10  |          | 10     |
| Hotrod     | 11  |  9  |  5  |  6  | 10  | Fast     | 11     |
| Sports Car | 12  |  9  |  5  |  6  |  9  | Fast     | 11     |
| Buggy      | 9   |  8  |  6  |  6  |  8  | Rugged   | 9      |
| Truck      | 9   |  9  |  4  |  6  | 12  | Rugged   | 13     |

## Weapon Upgrades

Each vehicle may be equipped with one ranged weapon and one other weapon from any category:

| Ranged Weapons          | RNG | ATT | DMG | PRC | Special            | Points |
| :---------------------- | :-: | :-: | :-: | :-: | :----------------- | :----- |
| Light Machine Gun       | 12  | 2   | 1   | 0   |                    | 1      |
| Twin Light Machine Guns | 12  | 3   | 1   | 0   | Rapid Fire         | 2      |
| Heavy Machine Gun       | 16  | 2   | 2   | 1   |                    | 2      |
| Twin Heavy Machine Guns | 16  | 3   | 2   | 1   | Rapid Fire         | 3      |
| Minigun                 | 18  | 4   | 2   | 1   | Torrent            | 4      |
| Rocket Launcher         | 18  | 3   | 3   | 2   | Suppression, Blast | 6      |
| Flamethrower            | 8   | 8   | 1   | 0   | Torrent            | 3      |

| Melee Weapons | RNG | ATT | DMG | PRC | Special                      | Points |
| :------------ | :-: | :-: | :-: | :-: | :--------------------------- | :----- |
| Driver Pistol |  6  |  2  |  1  |  0  | Melee                        | 1      |
| Spiked Ram    |  1  |  2  |  2  |  2  | Melee                        | 2      |
| Spiked Wheels |  1  |  2  |  1  |  1  | Melee, Side Arc              | 2      |
| Wrecker Arm   |  1  |  2  |  3  |  2  | Melee, Unwieldy, Obstructing | 3      |

| Dropped Weapons | RNG | ATT | DMG | PRC | Special              | Points |
| :-------------- | :-: | :-: | :-: | :-: | :------------------- | :----- |
| Smoke Dropper   |  5  |  1  |  -  |  -  | Dropper, Obstructing | 1      |
| Oil Dropper     |  3  |  2  |  -  |  -  | Dropper, Obstructing | 1      |
| Spike Dropper   |  3  |  2  |  1  |  0  | Dropper, Obstructing | 2      |

## Weapon Modifications

Each vehicle may choose to modify its ranged weapons, weapons which cost 4 or more points pay an additional point to be modified:

| Modification    | Effect | Points |
| :-------------- | :----- | :----- |
| Improved Sights | This weapon gains the **Accurate** and **Rending (1)** special rule | 2 |
| Inferno Ammo    | This weapon increases its **damage** attribute by 1. Cannot be taken for a flamethrower | 2 |
| Armour Piercing | This weapon increases its **piercing** attribute by 1. Cannot be taken for a flamethrower | 2 |
| Stabilised      | This weapon increases its range by 6 inches | 1 |
| Turret Mount    | This weapon may target enemy models in arcs other than the front, though if it does so it has a -1 to its **battle skill test** | 1 |

## Vehicle Upgrades

Each vehicle is permitted upgrades totalling no more than 4 points.

| Upgrade           | Effect | Points |
| :---------------- | :----- | :----: |
| Tank Tracks       | This vehicle may make a 2nd free manoeuvre when it moves and reduces its movement rate by 2 | 3 |
| Reinforced Armour | This vehicle increases its defence by 1 | 2 |
| Boost             | One use only at the start of a vehicles movement action. This unit immediately moves directly forward 9 inches | 2 |
| Sturdy            | Add 2 to this vehicles **hit points** | 2 |

## Driver Upgrades

Each of your vehicles is permitted one of the following upgrades:

| Upgrade        | Effect | Points |
| :------------- | :----- | :----: |
| Marksman       | This vehicle improves its **skill** attribute to 7 | 2 |
| Skilled Driver | This vehicle improves its **command** attribute to 4 | 1 |
| Reckless       | Vehicles which must take a **command** test due to this vehicle moving over them have a -3 to their test | 1 |

# Campaigns and Missions

## One-Off Game

If players wish to play a single game they should agree on which size of game they want to play and any constraints on the number of vehicles being used. They can then build their team following the rules in the previous section on building a team. 

Some common game sizes:

- Small Game: 3-5 vehicles, 50 points
- Medium Game: 6-8 vehicles, 100 points
- Large Game: 8-10 vehicles, 150 points

## Campaigns

If players prefer they can play Wasteland Rally as a campaign, this is a series of linked games for 2 or more players. To play a campaign players will start by creating a roster: a large team of 8-10 vehicles from which they can draw to play each game. During a campaign vehicles may be destroyed or damaged, teams may upgrade their weapons on their vehicles, and drivers gain experience. Each victory will score a team a point with the player with the most points at the end of the campaign being the winner.

### Creating a Roster

The first step in playing a campaign is for each player to create a roster of between 8 and 10 vehicles up to a maximum of 100 points. Each vehicle may only be given one weapon upgrade and no other upgrades. Note these down somewhere you can track changes to your vehicles over the course of your campaign.

If you do not spend all 100 points you may retain up to 10 points and add it to your **points pool**, a resource you will use throughout the campaign to maintain and upgrade your vehicles that should be tracked between games.

### Campaign Structure

A campaign is played through a number of rounds during which each player will be able to play 1 game. In a 2 and 3 player campaign each round has one game featuring every player. In a campaign with more players you should randomly determine which players will play against each other so that each game features 2 or 3 players, whichever works best for your group size.

Your campaign can run for as many rounds as you wish, typically at least 3, with the missions as follows:

- **First Round**: Two Lap Race
- **Additional Rounds**: Randomly determine mission
- **Final Round**: Outrun

When randomly determining missions for each round simply roll a D12, if you roll the same mission as the previous round then select the next mission in the list:

- 1-3: Two Lap Race
- 4-6: Arena Race
- 7-9: Elimination Race
- 10-12: Battle Royale

### Upgrade Stage

During a campaign a new stage is added to the game, taking place after the battle stage, where players will determine the outcome of destroyed or damaged vehicles, earn points to upgrade or replace vehicles, earn experience for their drivers, and earn campaign points towards winning the overally campaign.

The upgrade stage follows these steps:

- Determine total points earned for the round
- Determine outcome for each vehicle
- Upgrade vehicles
- Upgrade drivers
- Tally up campaign points

#### Determine Total Points Earned

After a battle each player will earn points according to the objectives of the mission that was played. These should be tallied up and added to the players **points pool**.

#### Determine Outcome of Vehicles

Vehicles that have been damaged or destroyed are dragged back to the team's workshop after each campaign round.

Roll a D12 for each vehicle that was destroyed during a game:

| Number | Result                                                                              |
| ------ | ----------------------------------------------------------------------------------- |
| 1-9    | The vehicle is destroyed but you gain points from the scrap equal to the dice roll. |
| 10-12  | The vehicle is recovered and can compete in the next mission as normal.             |

Roll a D12 for each vehicle that was damaged during a game:

| Number | Result                                                                                                    |
| ------ | --------------------------------------------------------------------------------------------------------- |
| 1-9    | The vehicle can be repaired at a cost equal to the dice roll, you cannot use this vehicle until repaired. |
| 10-12  | The vehicle can be saved at the cost of 5 points, otherwise it is destroyed but you gain 5 points.        |

## Missions

### Two Lap Race

Teams line up to race around a circuit for two laps with points awarded for finishing positions at the end of the race.

#### Terrain

Set up your terrain so that there is a closed loop race track roughly 60-80 inches long. Place a gate to indicate the start/finish gate and a second gate at the furthest point on the track from the first gate.

#### Deployment Areas

Starting with the player that won the roll for deployment, each player alternates placing a vehicle as close as possible to the starting gate without placing any part of the vehicle over the gate itself. Vehicles must also be placed at least 2 inches away from other vehicles.

### Arena Race

Teams race from gate to gate scoring points for the first vehicle to cross each line in a maze-like arena.

#### Terrain

Set up your terrain so that there are 2 gates facing each other on opposite sides of the board, at least 36 inches away. One gate will be the start/finish gate. The rest of the terrain should be set up to allow multiple ways to cross the board between the gates.

#### Deployment Areas

Starting with the player that won the roll for deployment, each player alternates placing a vehicle as close as possible to the starting gate without placing any part of the vehicle over the gate itself. Vehicles must also be placed at least 2 inches away from other vehicles.

### Elimination Race

Teams race around a closed circuit with the last driver to cross each gate in turn eliminated from the race.

##-## Terrain

Set up your terrain so that there is a closed loop race track at least 60 inches long. Place a gate to indicate the start/finish line and a second gate at the furthest point on the track from the first gate.

#### Deployment Areas

Starting with the player that won the roll for deployment, each player alternates placing a vehicle as close as possible to the starting gate without placing any part of the vehicle over the gate itself. Vehicles must also be placed at least 2 inches away from other vehicles.

### Battle Royale

Teams are positioned around a large arena with points awarded for each time an opponent is damaged.

#### Terrain

Set up your terrain so that is evenly distributed and vehicles may pass easily between each piece. Set up a number of gates equal to the number of players facing the center of the table, evenly distributed and 16 inches away from the center.

#### Deployment 

The player that won the roll for deployment chooses one of the gates as their start line, the other player uses the other gate.

Starting with the player that won the roll for deployment, each player alternates placing a vehicle as close as possible to their starting gate without placing any part of the vehicle over the gate itself. Vehicles must also be placed at least 2 inches away from other vehicles.

### Scavengers

Teams that are falling behind often use the downtime between races to scrounge up some extra scrap to boost their standings, unfortunately the other teams see this as an opportunity to do some extra damage.

#### Terrain

Set up terrain so that it is evenly distributed and vehicles may pass easily between each piece. Set up one gate in the middle of any table edge facing off the battlefield.

#### Deployment Areas

The team with the lowest number of points will be set up anywhere within 12 inches of the battlefield edge with the gate on it. The other players may set up anywhere within 6 inches of the same battlefield edge and at least 6 inches from the

### Outrun

Winning the Wasteland Rally means nothing if you cant get the goods back to safety, and once your out in the Wasteland theres nothing stopping the other teams simply trying to take what they want.

#### Terrain

Set up terrain so that it creates a single track that is at least 60 inches long, with plenty of obstacles along the way. Place one gate at the end of this track so that it is along an edge of the battlefield.