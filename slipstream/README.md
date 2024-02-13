---
title: "Slipstream - Streamer.bot Toybox"
description: "Various helpful chat commands for providing information to viewers about Slipstream: Rogue Space."
permalink: /slipstream/
---

[<-- Return Home](../README.md)

# Slipstream v1.1.0

Various helpful chat commands for providing information to viewers about [Slipstream: Rogue Space](http://playslipstream.com/).

There are *a lot* of alternative forms for each command, so you don't have to remember all parts of each command. For example, `!ss help stations medical` is the same as `!ss medical`.

In addition to the commands, there are two other categories added:

- A timer message that can be used to remind viewers they can join the crew. Automatically stops posting when not playing Slipstream.

- A set of actions to automatically enable/disable the Slipstream commands when your category changes to/from "Slipstream: Rogue Space". (Disabled by default, enable the action "Toggle Slipstream Actions based on category" to use.)


## Installation

1. Copy the import string from [slipstream-toy.txt](./slipstream-toy.txt)
2. Go to your Streamer.bot instance
3. Click the "Import" button in the top left
4. Paste the import string into the top text box
5. Click "Import" to import the toy into your Streamer.bot instance
6. (Optional) Set the timer in the timer trigger for the "Timer Message" action
7. (Optional) Enable the action "Toggle Slipstream Actions based on category" and set the enable and disable action IDs

## Changelog

### v1.1.0

- Added commands for crew members and slugs.

### v1.0.1

- Corrected the Defense and Shield stat descriptions, which were both swapped and wrong.

## Commands

Here are all of the commands as well as the response for each one. The shortest alternate form is listed in parentheses next to the command.

If you're using a different chat bot, feel free to add any/all of these commands yourself!

### !slipstream (!ss)

```
Welcome to Slipstream: Rogue Space! Slipstream is an interactive streamer-led cooperative space adventure where chat (that's you!) are my crew, trying to nagivate through the dangers that await us in space! You can learn more at https://playslipstream.com!
```

### !slipstream help (!ss help)

```
Available help commands: !ss help join, !ss help stations, !ss help stats (with more subcommands for each one!)
```

### !slipstream help join (!ss join)

```
Chat (that's you!) can join the crew by downloading the game from https://playslipstream.com/ and signing in with Twitch. You can pick your first crewmember and join us from the Space Dock. Just look for my name!
```

### !slipstream help stations (!ss stations)

```
Stations are how crew members can help support the ship during the run. There are three main types of stations: Weapons (red, attacks enemy ship), Shields (blue, shields self and nearby stations), and Medical (green, heals/revives you) You can learn more about each individual station using the command !ss help <station name>
```

### !slipstream help stations medical (!ss medical)

```
The Medical station is how crew members can heal and revive themselves. When your health reaches zero, you cannot interact with other stations and move extremely slowly. You can heal at any time by using a Medical station.
```

### !slipstream help stations shields (!ss shields)

```
The Shields station is how crew members can apply shields to nearby stations (and themselves). It is the blue stations with the shield icon on the display. When shielded stations are damaged, the damage goes to the shield first, keeping the station online.. When you are shielded, any damage to you hits your shield first, it is recommended to have a shield whenever possible. (Note: Shields can only be applied during combat, and are removed afterwards)
```

### !slipstream help stations weapons (!ss weapons)

```
The Weapons station is how crew members can deal damage to an enemy ship. It is the red stations with the targeting icon on it. You can deal additional damage by working the station from within the active combat zone, indicated by the target on the mini-map. Remember that the fight immediately ends when the enemy ship is dead, so it's always useful to deal damage!
```

### !slipstream help stats (!ss stats)

```
Your crew member has many stats, including Health, Shields, Defence, Gunnery, Combat, Repairs, and Speed! You can learn more about each one by chatting "!ss stat" followed by the stat you want to know more about! (For example: !ss stat Health)
```

### !slipstream help stats health (!ss health)

```
The Heatlh stat determines how much damage your crew member can take before they are "downed" and cannot hold gems, cannot operate stations, and move extremely slowly.
```

### !slipstream help stats shields (!ss stats shields)

```
The Shield stat determines how much Shield you can hold, allowing you to take more damage before you need to regain your Shield at a Shield station.
```

### !slipstream help stats defense (!ss defense)

```
The Defense stat determines how effective your crew member is at operating the Shield station. Bigger numer => faster shields.
```

### !slipstream help stats gunnery (!ss gunnery)

```
The Gunnery stat affects how much damage your crew member deals while using the Weapons stations.
```

### !slipstream help stats combat (!ss combat)

```
The Combat stat affects how much damage your crew member deals to slugs attacking stations.
```

### !slipstream help stats repairs (!ss repairs)

```
The Repair stat affects how quickly your crew member repairs damaged stations.
```

### !slipstream help stats speed (!ss speed)

```
The Speed stat affects how quickly your crew member can run around the ship!
```

### !slipstream help gems (!ss gems)

```
As you do things around the ship, you'll generate gems! You can select the gems on the ground to pick them up, and then you can deposit them at the Gem Forge! (Purple station with a large number over it) Be aware you can only hold 2 at a time, so deposit often!
```

```
There are three tiers of gems: Purple (1), Red (2), and Gold (5)! It is almost always worth dropping a lower-tier gem to grab a higher one. (Or attempt to juggle!)
```

### !slipstream help crew (!ss crew)

```
There are many different crew members to unlock! The first one is automatically unlocked, the rest are unlocked using Data Keys earned from gameplay. The current roster are the Bear, Cat, Croc, Hamster, Octopus, and Turtle. You can learn more about each one using !ss crew <crew name>
```

### !slipstream help crew bear (!ss bear)

```
The Bear is the sturdy brawler, well suited for fighting slugs with its boosted base health and damage vs slugs with the downside of moving slowly.
```

### !slipstream help crew cat (!ss cat)

```
The Cat is the clever hacker, master of the Weapon station. They deal 2x damage to enemy ships. All should yield their weapon stations to the Cats.
```

### !slipstream help crew croc (!ss croc)

```
The Croc is the speedy brawler, well suited for being the first to fight the slugs with its big damage vs slugs and high speed with the downside of having a reduced base health.
```

### !slipstream help crew hamster (!ss hamster)

```
The Hamster is the speedy mechanic with a 1.5x repair speed and the fastest movement speed. Unfortunately, the Hamster has a reduced base health.
```

### !slipstream help crew octopus (!ss octopus)

```
The Octopus is the master mechanic, with a 3x repair speed. While not as fast as the Hamster, they are the undisputed master of repair speed.
```

### !slipstream help crew turtle (!ss turtle)

```
The Turtle is the shield expert, the rulers of the Shield stations. With their 2.5x Shield speed multiplier and a 50% Shield capacity boost as well as a 1.2x Repair speed boost, the only thing slowing them down is themselves. All should yield their Shield stations to the Turtles, on sight.
```

### !slipstream help slugs

```
The Slugs are our worst enemies, humanity fell to them but with their last act they uplifted the various animals of earth to the stars. There are five types of slugs: Grunt, Blitz, Tank, Bruiser, and Royal. You can learn more about each one by using the command !ss slugs <slug name>
```

### !slipstream help slugs grunt (!ss grunt)

```
The green Grunt is a footsolider without any feet. They deal minimal damage to crew members, medium damage to stations, and have a small amount of health.
```

### !slipstream help slugs blitz (!ss blitz)

```
The lime Blitz is the shock trooper of the slugs. They deal large amounts of damage to crew members, but minimal damage to stations and have a tiny amount of health.
```

### !slipstream help slugs tank (!ss tank)

```
The orange Tank has a thick hide, sluggish in every sense. They deal mininal damage to crew members, large damage to stations, and have a extreme amount of health.
```

### !slipstream help slugs bruiser (!ss bruiser)

```
The red Bruiser is clawed and dangerous, approach with caution. They deal large amounts of damage to crew members and stations, and have a medium-large amount of health.
```

### !slipstream help slugs royal (!ss royal)

```
The purple Royal are elite, vicious, and downright mean. Bring help. They deal extreme amounts of damage to crew members and stations, and have a extreme amount of health.
```

[<-- Return Home](../README.md)