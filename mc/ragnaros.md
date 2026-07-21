---
layout: post
title: Ragnaros
parent: Molten Core (20)
nav_order: 10
subtitle: Ragnaros
---

# [Ragnaros](https://www.wowhead.com/classic/npc=228438)
*Last updated: 7/21/26*

Ragnaros is not a difficult fight, but it's a very complicated one. The majority of your time on this encounter will be spent positioning pre-pull. If you have trouble in this fight, most of those problems can be fixed with better pre-pull preparation.

**Tanks should be running a fire resist set on this fight to help resist Wrath, Intense Heat, and Sons of Flame.**

First, I'll cover his abilities, then I'll go over how these abilities affect positioning, then I'll explain how his normal phase operates, before finally detailing the Submerge phase.

Most of the changes in SoD only affect Submerge phase. If you're experienced with killing Ragnaros, [feel free to skip ahead]({{site.url}}{{page.url}}#submerge-phase-mechanics).

## Normal Phase Mechanics

### Ragnaros

* **[Wrath of Ragnaros](https://www.wowhead.com/classic/spell=20566)**: Hits all players in melee range when cast. Damages them, knocks them back very far, and drops their threat.
* **[Intense Heat](https://www.wowhead.com/classic/spell=21155)**: Randomly targeted at players with mana. Damages them and knocks them around.
* **[Lava Burst](https://www.wowhead.com/classic/spell=21158)**: The pools of lava in the terrain will occasionally burst, damaging anyone nearby for ~1.4k. This can hit you if you're on the shore of terrain but still close to lava.

There are two important mechanics during normal phases - Wrath of Ragnaros, and Intense Heat.

Periodically, Ragnaros will cast Wrath of Ragnaros, which hits every player in melee range, damages them, knocks them back very far, and drops their threat. You should be using DBM to track when he's able to cast it. All melee (except the current tank) should run 'out' whenever he's eligible to cast this ability, and run back 'in' after it's cast. For tanks, the offtank needs to run 'out' with the melee while the main tank needs to eat the Wrath. Once it occurs, the offtank should run in and pick up threat while the main tank makes their way back. It's essentially a forced tank swap.

While the melee are dealing with their own uptime nightmare, ranged have one of their own. Randomly throughout the fight, Ragnaros will cast Intense Heat, a blast targeted near players that will knock them back and deal damage to them, just like Wrath of Ragnaros. There is no way to avoid this mechanic, but you can minimize it by having anyone with a mana bar (all ranged) spread 20 yards apart from each other, like in the positioning diagram below.

{: .important .fs-3}
You may notice I said 'anyone with a mana bar' - yes, Ragnaros will target any melee players who have mana bars as well. This means that melee Hunters, Ret Paladins, and Enhance Shamans must stay out of the non-mana melee stack (Warriors, Rogues, Feral Druids) or else they risk blowing up those players with Intense Heat, on top of already having to deal with Wrath of Ragnaros as well. Melee mana users should position themselves around Ragnaros' other side, opposite the non-mana Melee. They still must run in and out for Wrath, but will *also* need to cope with Intense Heat. *It is not fun to be a melee mana user on this fight.*

### Positioning (Normal)

{: .mt-4 }
![Ragnaros Positioning (Regular Phase)]({{site.url}}/mc/i/ragnaros_positioning.svg)

The tanks should be on the south side of Ragnaros. If neither of your tanks is a mana user, they can stack during 'in' times, while the OT runs out during 'out' times; if one or both use mana they will need to stay apart to avoid Intense Heat.

## Submerge Phase Mechanics

Submerge phase begins after 3 minutes of the normal phase. In SoD, there is also a force Submerge triggered at 50% if one has not occurred yet.

Ragnaros sinks below the lava and will spawn Sons of Flame throughout the arena. They must be rounded up and killed. Ragnaros will re-emerge when all of the Sons die, or after 90 seconds, whichever comes first.

### Sons of Flame

*All of these abilities are new in SoD compared to Vanilla.*

* All Heat Levels: **[Lava Shield](https://www.wowhead.com/classic/spell=21858)**: Sons of Flame will burn 150 mana and 300 health per second from nearby (10yd) players.
* Heat 2+: **[Armageddon](https://www.wowhead.com/classic/spell=461863)**: Cast when Sons of Flame reach 10% health. They must die before the cast finishes (5sec) or they will kill all nearby players.
* Heat 2+: **[Pool of Fire](https://www.wowhead.com/classic/spell=461062/pool-of-fire)**: When Sons of Flame die, they scorch the earth below them, similar to Baron's Living Bombs on H2+. This will damage players who stand in it.
* Heat 3 Only: **[Scorching Fetters](https://www.wowhead.com/classic/spell=461874/scorching-fetters)**: When Sons of Flame die, they will grab nearby players (20yd) and pull them close.

### Positioning (Submerge)

{: .mt-4 }
![Ragnaros Positioning (Submerge Phase)]({{site.url}}/mc/i/ragnaros_submerge.svg)

Once Submerge begins, all players should run south of Ragnaros as shown above. The tanks need to round up the Sons and drag them into the "kill zone", where they need to be AoE'd down.

It is extremely helpful to have some way to slow down the Sons once they're in the kill zone, like a Hunter's [Frost Trap](https://www.wowhead.com/classic/spell=409520).

Since Sons of Flame burn the mana of nearby players, melee mana users should stay out of melee range during this phase or risk death. If you have ranged abilities, cast them to help out. Tanks typically run enough FR to protect themselves from this.

## Compared to Vanilla...

There's a few things to keep in mind about Vanilla mechanics that play out a little differently in Season of Discovery:

- Melee players with mana bars (Hunters, Shamans, Paladins) are viable targets for the ranged Wrath of Ragnaros cast, so they should spread apart from the non-Mana melee stack (Rogues, Warriors). This applies to tanks as well; tanks with mana bars should not stack with other tanks. This is rarely an issue in Vanilla due to the absence of these specs.
- With only 20 players instead of 40, it's far easier to position around the room. You do not need to double stack.
- With fewer healers and with more party-focused healing, it's more important to arrange groups based on proximity rather than buffs. Both are true if you're relying on Paladin auras or Shaman totems to hit FR craps. Critical buffs like Windfury are raid-wide, so those are less of an issue to orient around.

---

## Heat Level Changes
{: .text-center .mb-6 }

{: .heat1 .fs-3}
> *Compared to Vanilla:*
> - Rather than only submerging after 3 minutes, Ragnaros will also Submerge when he reaches 50% health, ensuring at least one Submerge phase per fight.
> - When Ragnaros' health drops below 25%, he will start spawning Sons of Flame for the rest of the fight. These should be banished or rounded up by the off-tank to ensure they don't run rampant killing your healers.

{: .heat2 .fs-3}
> *In addition to needing 96 Fire Resist:*
> - Sons of Flame will cast Armageddon when they're about to die, similar to Baron Geddon, becoming immoble for 5 seconds. If the cast finishes before they die, they will explode, instantly killing nearby players.
> - When Sons of Flame die, they leave behind a patch of scorched earth, similar in size to Baron Geddon's Living Bombs.

{: .heat3 .fs-3}
> *In addition to needing 226 Fire Resist:*
> - When Sons of Flame die, they will suck in nearby players.