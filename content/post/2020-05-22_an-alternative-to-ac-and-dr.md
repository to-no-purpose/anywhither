---
title: "An Alternative to AC and DR"
date: "2020-05-22"
description: "An examination of the effectiveness of DR and a potential new armor mechanic."
categories:
- mechanics
tags:
- combat
- system-neutral
- setting-neutral

---

Lately I’ve been trying to decide if I should have attack rolls in my ruleset or not. I’ve played both ways and like auto-hit attacks for two reasons: they’re fast and missing is boring anyway. However, I recognize that the threat of a miss might encourage players to be more creative in combat and the ability to differentiate between a good fighter and a bad fighter just by looking at one number on a character sheet has some value.

But that’s a decision for another day. Were I to remove attack rolls I’d need a mechanic to represent armor in place of AC. Armor as damage reduction comes to mind and I did briefly trial it last year.

## Armor as DR

Here’s a look at the effects of DR:

| Armor | d4 average damage | d6 average damage | d8 average damage |
|:-----:|:-----------------:|:-----------------:|:-----------------:|
| None  |        2.5        |        3.5        |        4.5        |
| DR-1  |        1.5        |        2.5        |        3.5        |
| DR-2  |       0.75        |       1.66        |       2.625       |
| DR-3  |       0.25        |         1         |       1.875       |
| DR-4  |         0         |        0.5        |       1.25        |

DR is absurdly powerful at the damage scales commonly used in D&D and similar games. Any more than a couple points and you’re nigh unkillable.

Even at DR-2 you’re negating on average 70% of the damage from a d4 and 53% of a d6. Up just one step to DR-3 and you’re negating 90% of a d4 and 72% of a d6. On average, it takes 3 hits with a d6 weapon to down a character with 10 HP and no armor. That same character with DR-3 needs 10 hits to go down, or 20 with DR-4! With DR-3 against a d4 weapon, 40 hits would be required! Even 10 hits is far past my preferred combat pace – I like things quick and bloody.

This leaves only DR-1 and DR-2 usable. DR-3 might be suitable for rare late-game magical armor. That means players will only have two mechanically distinct armors to choose from for possibly the entirety of the campaign. For many games this is no problem but I want variety! I want interesting choices!

## Armor as AV

Enter Armor Value (AV). If a damage dice rolled against you comes up with a number matching your AV you ignore that dice. For example: AV\[2\] ignores any damage dice that come up as 2. You can find the reduction to average damage of a particular AV using the following formula: (Armor Value) ÷ (Die Size) = (Reduction to Average Damage). Some useful patterns emerge:

An AV will always reduce the average damage of a matching die size by exactly 1. Let’s look at AV\[6\] using the formula above: (Armor Value: 6) ÷ (Dice Size: 6) = 1 point reduction to average damage.

Each step of AV will reduce average damage by 1 ÷ Die Size. Each increment of AV versus a d4 will reduce average damage by ¼ of a point, each increment of AV versus a d6 will reduce average damage by ⅙ of a point, etc.

Here’s a look at the effects of AV\[1\] to AV\[6\]:

| Armor | d4 average damage | d6 average damage | d8 average damage |
|:-----:|:-----------------:|:-----------------:|:-----------------:|
| None  |        2.5        |        3.5        |        4.5        |
| AV[1] |       2.25        |       3.33        |       4.375       |
| AV[2] |         2         |       3.16        |       4.25        |
| AV[3] |       1.75        |         3         |       4.125       |
| AV[4] |        1.5        |       2.83        |         4         |
| AV[5] |        2.5        |       2.66        |       3.875       |
| AV[6] |        2.5        |        2.5        |       3.75        |

### Side Effects

An interesting consequence of AV is that smaller values lose effectiveness versus larger weapons. AV\[4\] reduces damage by an average of a whole point versus a d4 dagger but only by _half_ a point versus a d8 greatsword. Thematically, this makes sense: armor designed to stop a knife isn’t going to help nearly as much against a lance. And inversely, some larger values are totally ineffectual against smaller weapons. AV\[6\] will reduce average damage from a d6 by an entire point but will provide _no benefit_ against a d4. This makes sense as well: armor designed to deflect hits from big weapons might have small gaps that a dagger easily slides through.

### Better Armors

There’s a problem, though. None of these armors are particularly strong. It takes three d6 attacks to down a 10 HP character with no armor but only four attacks if that character has AV\[6\], the strongest armor available against a d6. That’s a respectable increase but I want more room to grow.

The obvious solution is to give out multiple AV to a single character either by having armor with multiple values (AV\[1-3\]) or by breaking armor down into a few pieces, each providing it’s own AV (chestplate AV\[6\], helmet AV\[2\], etc). In theory I love the idea of multiple pieces of armor – adventurers running around in a hodge-podge of mismatched armor is a great visual. In practice I’m not so sure – the benefits might not be worth the added overhead. In either case the effect is the same: players have multiple Armor Values protecting them.

We can still use the same formulas to evaluate the effectiveness of multiple AV, we just need to sum the values like so: (Sum of Armor Values) ÷ (Die Size) = (Reduction to Average Damage). Thus AV\[1-3\] reduces average damage of a d6 weapon by (1+2+3) ÷ (6) = 1 point reduction to average damage.

Here’s a look at the effects of multiple AV:

|    Armor    | d4 average damage | d6 average damage | d8 average damage |
|:-----------:|:-----------------:|:-----------------:|:-----------------:|
|    None     |       2.50        |       3.50        |       4.50        |
|   AV[1-2]   |       1.75        |       3.00        |       4.13        |
|   AV[2-3]   |       1.25        |       2.66        |       3.88        |
|   AV[3-4]   |       0.75        |       2.33        |       3.63        |
|   AV[4-5]   |       1.50        |       2.00        |       3.38        |
|   AV[5-6]   |       2.50        |       1.66        |       3.13        |
|   AV[1,6]   |       2.25        |       2.33        |       3.63        |
| AV[1-2,7-8] |       1.75        |       3.00        |       2.25        |

Obviously this is just a few of the possible combinations. The first five are fairly basic, offering incrementally increasing protection. AV\[1,6\], however, brings a d4 and a d6 down to roughly the same damage output while also offering a respectable decrease to the d8. AV\[1-2,7-8\] offers a little protection against d4 and d6 weapons but halves d8 damage output.

The biggest problem I see with this system is that it’s not intuitive. You can’t glance at a list of Armor Values and immediately discern the important differences. A possible remedy is to describe these differences in the flavor text – “This piece of armor offers a little protection against light and medium weapons but excels at protection from large weapons.”

Another addition to differentiate armors even further is Durability. Each piece of armor has a Durability score. Any time the armor is used, decrease this score. Once it reaches zero the armor is useless until it is repaired. Some armor may be highly protective and inexpensive but very fragile, while some may offer moderate protection but high reliability.

### Examples

Here’s a look at some traditional armors converted to AV:

|   Item   |   AV    | Dur. | Slots | Description                                                                                                             |
|:--------:|:-------:|:----:|:-----:| ----------------------------------------------------------------------------------------------------------------------- |
|   Hide   |  AV[1]  |  2   |   1   | Not particularly useful. Better than nothing, I guess.                                                                  |
| Leather  | AV[2-3] |  4   |   2   | The classic. An all-rounder.                                                                                            |
|  Chain   | AV[3-4] |  10  |   3   | Offers solid protection and good durability. A go-to.                                                                   |
| Lamellar | AV[4-5] |  4   |   2   | Useful in most situations. Somewhat vulnerable to daggers. Not particularly durable.                                    |
|  Plate   | AV[5-6] |  10  |   4   | Highly effective against medium/large weapons. Completely vulnerable to small weapons that can slip between the plates. |

And here’s some whackier implementations:

|         Item         |   AV    | Dur. | Slots | Description                                                                                                                                          |
|:--------------------:|:-------:|:----:|:-----:| ---------------------------------------------------------------------------------------------------------------------------------------------------- |
|    Lucky Buckler     | AV[all] |  1   |   1   | A small enchanted shield. Reliably blocks any weapon once. Cannot be repaired.                                                                       |
|    Stone Lamellar    | AV[5-8] |  2   |   5   | A suit of lamellar made from small stone squares. Extremely effective against large weapons, but very heavy and quite fragile.                       |
| Adamantite God-Armor | AV[odd] |  20  |   2   | Truly legendary. Extremely protective and durable. Might require a Godsmith to repair, unfortunately.                                                |
|      Mage Armor      | AV[7+]  | N/A  |  N/A  | A powerful spell that creates a field of dense air around the target. Large weapons are significantly slowed, but small weapons easily pass through. |

