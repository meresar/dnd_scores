# Modeling "Weird Dice"

## Idea

In TTRPGs (in particular, Pathfinder and Dungeons & Dragons), you use a 20 sided die to determine success and failure, with a 1 being an absolute failure and a 20 being an excellent success. One of the things my group likes to talk about is alternate schemes for rolling these; Mike calls them "weird dice."

Similarly, there are many ways to get the 6 ability scores your character is based on. I'm curious what the distributions look like for these (both for each score and for overall characters).

### Alternate versions of success/failure
- 1d20 (obviously equal probabilities of everything)
  * advantage/disadvantage
  * 2d20 average and truncate
- 2d10 (no way to get a 1)

### Different ways to roll ability scores

With ability scores there are options where you roll all the ability scores individually and then just assign them and versions where you look at the 6 ability scores as a whole. I'll focus mainly on the ones considered individually, at least to start.

#### Considered individually

In these methods you roll 6 scores and then assign them:

* Roll 4d6, sum the three largest (standard)
* Roll 4d6, reroll 1s, sum the three largest (what we did in college)
* Roll 3d6 and sum (classic)
* Roll 3d6, reroll 1s, sum (classic+)

#### Character as a whole

In these methods, you have a pool of some kind and distribute the points among the different scores:

* 24d6, choose number of dice per stat and roll (dice pool)
  - same as above but 28d6 (heroic dice pool)
* Point buy: all ability scores start at 10, and you're given a certain number of points that can be distributed with increases "costing more" and decreases "refunding less" as you get to the extremes


##### Point buy tables:
via https://www.d20pfsrd.com/basics-ability-scores/ability-scores/

| Campaign type   | Points  |
| -------------   |--------:|
| Low fantasy     | 10      |
| Standard fantasy| 15      |
| High fantasy    | 20      |
| Epic fantasy    | 25      |


Cost/Refund
|Score   |  Points|
|:------:|:------:|
|7       |  -4|
|8       |  -2|
|9       |  -1|
|10      |   0|
|11      |   1|
|12      |   2|
|13      |   3|
|14      |   5|
|15      |   7|
|16      |  10|
|17      |  13|
|18      |  17|