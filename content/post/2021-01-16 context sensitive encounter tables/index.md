---
title: "Context Sensitive Encounter Tables"
date: "2021-01-16"
description: "A method for creating encounter tables that react to external variables."
image: "20140714-Thrihyrningur-path.jpg"
categories:
- mechanics
tags:
- system-neutral
- travel
- setting-neutral
- tables
---

The goal of these encounter tables is to provide dynamic, context-dependent encounters with as little additional work as possible pushed onto the referee. I recommend using the methods explained here alongside Retired Adventurer’s encounter grid (see [here](https://retiredadventurer.blogspot.com/2013/05/a-procedure-for-wandering-monsters.html) and [here](https://retiredadventurer.blogspot.com/2019/11/the-encounter-grid-six-years-out.html)), but for simplicity’s sake I won’t use the grid in the examples that follow.

Let’s start with a simple d6 encounter table.

| d6  | Overland Encounters |
| :-: | ------------------- |
| 1   | 1d4 crocodiles      |
| 2   | 1d6 lizardmen       |
| 3   | 2d4 bandits         |
| 4   | 1 merchant caravan  |
| 5   | 2d6 goblins         |
| 6   | 1d4 trolls          | 

Each entry has an equal chance of appearing, and there is no context-dependent element. Now let’s expand the table to 10 entries and include a potential modifier to the roll, +X.

| d6+X | Overland Encounters   |
|:----:| --------------------- |
|  1   | 1d4 crocodiles        |
|  2   | 1d6 lizardmen         |
|  3   | 2d4 bandits           |
|  4   | 1 merchant caravan    | 
|  5   | 2d6 goblins           |
|  6   | 1d4 trolls            |
|  7   | 1 herder + 3d10 sheep |
|  8   | 2d4 mountain goats    |
|  9   | 2d4 pilgrims          |
|  10  | 1 dragon              |

Rolling a d6 as normal on this table, it will function identical to the first. But if we add a modifier – say, +1 – the crocodiles are no longer a possible threat and the sheepherder is. For this table, the modifier refers to elevation – as you ascend, your random encounters change to reflect the terrain. The inclusion of just one additional operation in the random encounter procedure causes the results to change fluidly with the context.

Now, I play many of my games on topographic maps where it’s trivial to see the party’s current elevation and elevation matters – most people don’t, nor would they want to. But there are many other potential applications of this method. Let’s look at a context-sensitive dungeon encounter table:

| d6+X | Dungeon Encounters               |
|:----:| -------------------------------- |
|  1   | 1 ratman child                   |
|  2   | 1 ratman forager                 |
|  3   | 1 ratman chef and 1d4 assistants |
|  4   | 2d6 drunk ratmen                 |
|  5   | 1d4 ratman guards                |
|  6   | 1d4 ratman knights               |
|  7   | 1 ratmech                        |
|  8   | 1 ratwizard + 2d4 ratman guards  |
|  9   | 1 ratmech + 2d4 ratman knights   |
|  10  | 1 ratking + 3d6 ratman knights   |

Such a table can be utilized in a variety of ways. X might equal the number of rooms the party has explored – as they delve further into the dungeon, the pressure ramps up as the encounters get more and more dangerous. X might equal the number of exploration turns since the party was detected – if they can stay undetected they’re relatively safe, but as soon as they’re seen the pressure will steadily and inexorably ramp up as the dungeon denizens mount a response. X might equal the number of times they’ve done something noisy – if they can avoid bashing doors and getting in fights they might be safe. X might be more freeform, with the referee increasing or decreasing it as they feel appropriate.

Let’s look at another overland encounter table, and let X equal the number of major crimes the party is known to have committed.

| d6+X | Overland Encounters              |
|:----:| -------------------------------- |
|  1   | 3d4 mule deer                    |
|  2   | 2d10 mormon settlers             |
|  3   | 3d4 Ute tribesmen                |
|  4   | 1 bear                           |
|  5   | 2d4 homesteaders                 |
|  6   | 2 lawmen                         |
|  7   | 2 lawmen + 2d4 deputies          |
|  8   | 1 texas ranger                   |
|  9   | 1 Ute chief + 3d10 Ute tribesmen |
|  10  | 2 US marshals + 2d4 deputies     | 

As the party’s infamy spreads, they’ll begin to run into more trouble on their journeys.

There’s one more layer of complexity we can add – rather than a straight d6 roll, let’s use multiple dice. Say, 2d4. We’ll use another overland, elevation dependent table to illustrate.

| 2d4+X | Overland Encounters    | +0 odds | +2 odds | +8 odds |
|:-----:| ---------------------- | :-----: | :-----: | :-----: |
|   2   | 1d4 crocodiles         | **6%**  | 0%      | 0%      |
|   3   | 1 megaturtle           | **13%** | 0%      | 0%      |
|   4   | 2d4 crabfolk           | **19%** | **6%**  | 0%      |
|   5   | 1 trading caravan      | **25%** | **13%** | 0%      |
|   6   | 2d4 foraging villagers | **19%** | **19%** | 0%      |
|   7   | 3d4 sellswords         | **13%** | **25%** | 0%      |
|   8   | 1 megasnake            | **6%**  | **19%** | 0%      | 
|   9   | 3d4 howler monkeys     | 0%      | **13%** | 0%      |
|  10   | 2d4 raptors            | 0%      | **6%**  | **6%**  |
|  11   | 3d6 mountain apes      | 0%      | 0%      | **13%** |
|  12   | 3d6 pilgrims           | 0%      | 0%      | **19%** |
|  13   | 1 giant dragonfly      | 0%      | 0%      | **25%** |
|  14   | 1 rock-lion            | 0%      | 0%      | **19%** |
|  15   | 2d4 cliff goats        | 0%      | 0%      | **13%** |
|  16   | 1 dragon               | 0%      | 0%      | **6%**  |

When using multiple dice, the results in the middle of the possible range are more likely and the results at the ends of the range are less likely. The most common result at +0 will gradually fade away until it disappears as the modifier rises, creating a much smoother transition between possibilities. Villagefolk might be a common occurrence lower down, but as you ascend the mountain you’ll seem them less and less.

There are a lot of possibilities not covered by this post – and I’m curious if similar mechanics have appeared elsewhere. Let me know what you think!