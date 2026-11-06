# Paper Dungeon

A solo dungeon crawl you play with **pen, graph paper and a set of dice**. You draw the dungeon as you explore it, one octagon room at a time. Find the **superschat** to win.

A quick game for a few minutes before bedtime. Little material needed.

## What you need

- Pen or pencil and graph paper
- Dice: **d4, d6, d8, d10, d12, d20**

## The goal

Find the **superschat** (a 10-12 on the treasure d12) to win the game. Along the way you can collect gold for a score, if you want one (see [Score](#score)).

The game is over when your hit points (hp) reach 0.

## Setup

1. Roll a **d12 + 3** for your starting hp. Your maximum hp is **15**.
2. Draw an octagon in the middle of the paper. This is your starting room.

## A turn

1. **Roll a d8 for the direction.** 1 is north, then go clockwise around the octagon (2 = north-east, 3 = east, and so on).
2. **Look at that wall on your octagon.**
   - If the wall is already known (a door, a wall, or the way you came in), use it. No roll needed.
   - If the wall is still undefined, **roll a d6**:

| d6 | Wall |
|---|---|
| 1-3 | Wall |
| 4 | Door |
| 5 | Locked door (you need a key to open it) |
| 6 | Dark room (see [Dark rooms](#dark-rooms)) |

3. **If it is a wall**, you stay where you are and your turn ends.
4. **If it is a door**, you walk through and draw a new octagon next to the old one. The wall you came through is always a door in the new room.
5. **Roll a d20 for the room event** (see below). You only do this the first time you enter a room.

When you walk back into a room you already explored, there is no new roll, and walls that already have a meaning are not rolled again.

## Room events (d20)

| d20 | Event | What happens |
|---|---|---|
| 1 | Cave-in | Lose 1 hp |
| 2-3 | Trap | Roll a d8: 4-8 you evade it, otherwise lose 1 hp |
| 4-8 | Monster | Roll a d10 on the [monster list](#monsters-d10), then fight |
| 9-11 | Nothing | Nothing happens |
| 12-15 | Item | Roll a d12 on the [item list](#items-d12) |
| 16-18 | Treasure | Roll a d12 on the [treasure list](#treasure-d12) |
| 19 | Magic item | Roll a d10 on the [magic item list](#magic-items-d10) |
| 20 | Potion | Roll a d4: restore that many hp (never above 15) |

## Dark rooms

A dark room is only a problem without light.

- **With a torch**, the room is a normal room.
- **Without a torch**:
  - A monster gets the advantage in a fight (see [Fighting](#fighting)).
  - You find **no items, magic items or treasure** in the room.

A torch burns out when you roll a 1 on a d6, which you check each time you enter a new room while it is lit.

## Fighting

Fights are played in rounds.

1. **You roll a d10, the monster rolls a d8.** Add all bonuses.
2. **The highest total wins the round.** On a tie, roll again.
3. **If you win**, the monster loses 1 hp.
4. **If the monster wins**, you lose hp equal to the monster's damage.
5. Repeat until the monster or you are at 0 hp.

**Dark room without a torch:** the monster rolls its d8 twice and takes the higher result.

**Bonuses and tools**

| Thing | Effect in a fight |
|---|---|
| Shield | Blocks one hit of damage, then breaks |
| Dagger | Thrown: adds 1d4 to your roll for one round, then it is gone |
| Magic weapon (+1) | You keep it. +1 to your roll and +1 damage on every won round |
| Magic missile wand | A missile is an automatic win of the round. The monster loses 1 hp. No roll |
| Smoke bomb | Escape the fight with no damage |
| Invisibility cloak | Skip the monster fight completely |

## Monsters (d10)

| d10 | Monster | HP | Damage | Special |
|---|---|---|---|---|
| 1 | Rat | 1 | 1 | |
| 2 | Bat | 1 | 1 | Erratic: ties go to the bat |
| 3 | Skeleton | 2 | 1 | |
| 4 | Goblin | 3 | 2 | |
| 5 | Two goblins | 3 + 3 | 2 each | Both attack each round. You roll once, and if you win you hit one goblin |
| 6 | Thief imp | 2 | 0 | If it wins a round it steals a random item and runs away |
| 7 | Giant spider | 3 | 1 | Poison: lose 1 extra hp after the fight |
| 8 | Troll | 4 | 2 | |
| 9 | Ghost | 3 | 2 | Ignores your shield |
| 10 | Dragon | 6 | 3 | |

## Items (d12)

All items are used up when you use them, unless it says otherwise.

| d12 | Item | Use |
|---|---|---|
| 1-2 | Torch | Lights a dark room. Burns out on a 1 on a d6, checked in each new room |
| 3-4 | Key | Opens one locked door |
| 5 | Bread | Restores 1 hp |
| 6 | Rope | Cancels one trap automatically |
| 7 | Shield | Blocks one monster hit, then breaks |
| 8 | Dagger | Throw it in a fight: add 1d4 to your roll for that round |
| 9 | Map scrap | Shows the whole octagon next to you: its walls and doors, but not what is inside |
| 10 | Pickaxe | Turns one wall into a door |
| 11 | Smoke bomb | Escape any fight with no damage |
| 12 | Lucky coin | Reroll any one die, once |

## Magic items (d10)

| d10 | Magic item | Effect |
|---|---|---|
| 1-2 | Healing potion | Roll a d4: restore that many hp |
| 3 | Teleport | Go to any space you already know, no action needed |
| 4 | Compass | Choose the direction you go instead of rolling the d8 |
| 5 | Map | Shows a fully known octagon: walls, doors and what is inside |
| 6 | Magic weapon (+1) | A weapon you keep: +1 to your roll and +1 damage on every won round |
| 7 | Magic missile wand | Roll a d4 for its charges. Each missile is an automatic hit. It is gone when empty |
| 8 | Amulet of life | At 0 hp you come back with a d4 hp, once |
| 9 | Crystal ball | Roll the d20 for one room next to you before you enter it, so you know what is inside |
| 10 | Invisibility cloak | Skip one monster fight completely |

## Treasure (d12)

| d12 | Treasure | Gold |
|---|---|---|
| 1-2 | Copper coins | 10 |
| 3-4 | Silver coins | 25 |
| 5-6 | Gem | 50 |
| 7 | Golden chalice | 75 |
| 8 | Jeweled crown | 100 |
| 9 | Ancient scroll | 150 |
| 10-12 | **Superschat** | **You win!** |

**Mimic check:** when you find treasure (but not the superschat), roll a d6 first. On a 1 it is a **mimic** with 4 hp and 2 damage. If you win the fight, the treasure's gold is doubled.

## Score

Scoring is optional and just for fun, to compare games:

**Score = gold from treasure + (explored octagons x 5)**

You can add a bonus for finding the superschat, for example 200 gold.

## Odds

| Per room | Chance |
|---|---|
| Monster | 25% |
| Item | 20% |
| Treasure | 15% |
| Superschat | about 3.75% (roughly one in 27 rooms) |

A fight round without bonuses: you win 55%, a tie happens 10%, the monster wins 35%.

## Ideas to change

All the numbers in the tables are meant to be adjusted. If the game feels too easy or too hard, change the superschat range (it is the d12 treasure table) or the monster hp.
