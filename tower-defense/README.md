# How to Play
Click on any space to move to it.
Green squares are trees, cut them down to get wood to trade.
The grey square is the spawn room, you can't see what's inside unless you're also inside.
Creatures that can spawn are:
- A dark blue Trader, who will give you one light blue Attractor for one wood
- A brown Mercenary, who will become a yellow Fighter for one wood
- A yellow Fighter, who will fight for you for free and defend the traders if they see an enemy in range
- A red Opposer, who will attack anything in range.

Every three minutes the game mode switches between resource mode and tower defence mode.
When tower defence mode starts, all Opposers will attempt to rush toward the white Victory Tower.
They can be distracted by placing an Attractor in their path, which will have a random chance of Attracting any Opposer within a certain radius. If this happens, that Opposer will move toward the Attractor instead of toward the Victory Tower until the Attractor fails to Attract it.

Placing an item is done by clicking on its label at the bottom of the screen to put it in the player character's hand and then clicking on a square to instruct the player character to move to that square and place it down.
Remove the item from your hand by clicking on the "wood" label at the bottom.

The game ends if you die or if the Victory Tower dies.

# Project Status
The prototype is as complete as I'm able to take it for now.
Other projects are taking up my time.

# Purpose
This is supposed to be a tower defence game.
Before the each defence round begins, a resource round plays out.
The idea is that there's a centre section that is hidden unless the player is inside it.
One of several creature types will spawn there each second:
  - Neutral traders
  - Mercenaries
  - Friendly fighters
  - Hostile mobs

If a hostile mob spawns then it will attack everyone else in the box.
The player can defeat a hostile mob easily enough,
but spending all their time inside the spawn box means they're not gathering resources from the map to trade with or buy mercenaries.
Luckily, if a friendly fighter has already spawned or a mercenary has been bought, they can take care of a hostile mob within a few rounds.

Once the resource round begins, the player chooses where to place the friendly fighters and purchased mercenaries before the wave spawns.
The wave will try to reach a target, following specific rules like being attracted to, repelled by, slowed down by, or damaged by various items.

If the player sets up the items and fighters well enough, all of the wave will be killed before it reaches its target.

# TO Do
- Create more items to buy
- Prevent multiple items from being in one square if they're different item types
- Indicate how many items of the same type are in one space
- Have traders spawn in with a random item for purchase (selected from the list of items without a trader), and indicate what item it is
