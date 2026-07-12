---
layout: post
title: Chromaggus
parent: Blackwing Lair
nav_order: 6
---
# Chromaggus
*Last updated: 7/12/26*

*This fight is more similar to Era than SoM. Unfortunate, because I sort of wanted to show folks how cool this fight was in SoM! Oh well.*

Before pulling the boss, distribute [Hourglass Sand](https://www.wowhead.com/classic/item=19183/hourglass-sand) amongst all raiders. It drops from the trash between Firemaw and Chromaggus.

Chromaggus is pulled by activating the lever in his room, at which point the gate opens and he runs into the center of the room. His encounter begins immediately when he reaches the center.

Every 18 seconds, Chromaggus will [**Frenzy**](https://www.wowhead.com/classic/spell=23128/frenzy), increasing his attack speed by 150% for 8 seconds. This will need to be tranq'd by a Hunter.

Chromaggus has an Elemental Shield that makes him resistant to all but one school of magic ([Arcane](https://www.wowhead.com/classic/spell=22281/elemental-shield), [Fire](https://www.wowhead.com/classic/spell=22277/elemental-shield), [Frost](https://www.wowhead.com/classic/spell=22278/elemental-shield), [Nature](https://www.wowhead.com/classic/spell=22280/elemental-shield), [Shadow](https://www.wowhead.com/classic/spell=22279/elemental-shield)). Throughout the fight, this shield's vulnerability will change, making him weak to a different one. He only takes 25% damage from schools of magic he's resistant to, but takes 1200% damage from schools he's vulnerable to. Mages must keep Detect Magic up on the boss at all times to reveal which vulnerability is active, just like with the trash prior.

At 20% health, Chromaggus will [**Enrage**](https://www.wowhead.com/classic/spell=23537/enrage), buffing his damage and increasing his attack speed by 50%. This will persist until he's killed.

## Brood Afflictions

Chromaggus will periodically put debuffs on random raid members which must be dispelled. These are themed after the five dragon flights, and are as follows:

- [**Brood Affliction: Black**](https://www.wowhead.com/classic/spell=23154/brood-affliction-black): **Curse**, increases Fire damage taken by 100%.
- [**Brood Affliction: Bronze**](https://www.wowhead.com/classic/spell=23170/brood-affliction-bronze): Periodically stuns for 4 seconds. Can only be removed by using **Hourglass Sand**.
- [**Brood Affliction: Blue**](https://www.wowhead.com/classic/spell=23153/brood-affliction-blue): **Magic**, burns ~50 Mana every second, increases cast time by 50% and reduces movement speed by 30%.
- [**Brood Affliction: Green**](https://www.wowhead.com/classic/spell=23169/brood-affliction-green): **Poison**, deals 250 damage every 5 seconds and reduces Healing taken by 50%.
- [**Brood Affliction: Red**](https://www.wowhead.com/classic/spell=23155/brood-affliction-red): **Disease**, deals 50 damage every 3 seconds. If the player dies while afflicted with this, they also heal Chromaggus for +150k HP.

**Always keep the main tank fully dispelled.** If someone reaches 3 debuffs, dispellers should prioritize them over everybody else (except the tank).

If a single raid member gets all 5 debuffs at the same time, they will be transformed into a hostile [Chromatic Drakonid](https://www.wowhead.com/classic/npc=14302/chromatic-drakonid) and must be offtanked for the rest of the fight. Killing a Chromatic Drakonid will heal Chromaggus for +150k HP. Letting someone reach 5 stacks is not a guaranteed wipe, but it's very likely to cause one, and two Drakonids is almost assuredly a wipe.

## Breaths

Chromaggus will periodically cast breaths on the raid. Unlike dragon fights, these breaths hit all players in a 360 degree around Chromaggus, but they can be line of sighted behind cover.

- [**Ignite Flesh**](https://www.wowhead.com/classic/spell=23316/ignite-flesh): Deals ~800 Fire damage every 3 seconds. Lasts 1 minute. Can stack if not LoS'd.
- [**Time Lapse**](https://www.wowhead.com/classic/spell=23310/time-lapse): Frozen in time (stuns). Health reduced by 50%. Lasts 8 sec.
- [**Frost Burn**](https://www.wowhead.com/classic/spell=23187/frost-burn): Deals frost damage, drains mana, and reduces attack speed by 400% for 15 sec.
- [**Corrosive Acid**](https://www.wowhead.com/classic/spell=23313/corrosive-acid): Deals ~950 damage every 3 sec. Armor reduced by 4500. Lasts 15 sec.
- [**Incinerate**](https://www.wowhead.com/classic/spell=23309/incinerate): Deals 4200 Fire damage.

At the beginning of the fight, Chromaggus will pick *two* of the above breaths. He will cast one breath roughly every 30 seconds, but will alternate back and forth between his two chosen breaths for each cast.

Here's an example [from one log](https://sod.warcraftlogs.com/reports/YdnCamVcxLJBtpyg#fight=33&type=casts&hostility=1&source=83):

![Chromaggus Breath Pattern]({{site.url}}/bwl/i/chromag_breath.png)

{: .tip .fs-3}
*He will continue using these two breaths for your raid instance until the next weekly instance reset. His pick is unique to your raid ID, meaning other raid teams in separate instances during the same week will get a different pair.*

## Positioning
Chromaggus is typically tanked in the doorway between his room and the Twin Drakes'. Have the tank grab him and pull him until he's right in the doorway, with the tank staying in the Twin Drakes' room. Melee should then enter Chromaggus' room and stack tightly behind him. Casters should stay off to the side, with most healers grouped with them. There should also be a healer floating around the melee stack to cover their healing as needed. These positions allow all players (besides the main tank) to run behind cover for the various breaths to LoS them. Healers should be positioned to heal the MT whilst still being behind cover, similar to Firemaw.

![Chromaggus Positioning]({{site.url}}/bwl/i/chromag.png)

---

{: .blacktrial }
> On top of the normal alternating breaths described above, roughly once per minute, Chromaggus will do a volley where he fires off all five breaths in quick succession. The timing of this volley is inconsistent - usually the first happens around the 40 second mark, and successive ones happen on average every 60 seconds after that.
> 
> {: .tip .fs-3}
> *The order he casts these in will be unique to your raid ID, which means he will continue casting them all in the same order for each subsequent pull.*
> 
> He will cast all 5 breaths as part of this volley, regardless of whichever two he's chosen as his normal breaths. If a normal breath is timed to occur during one of these volleys, it may be skipped, or it may be queued up and come out a few seconds later, but it will not delay his future alternating breath. See below for an example, [pulled from this log](https://sod.warcraftlogs.com/reports/TN6gMbCDHVdrt3k4#fight=45&type=casts&hostility=1&source=57).
> 
> ![Chromaggus Breath Volley Pattern]({{site.url}}/bwl/i/sod_bwl_chromag_breaths.png)
> 
> With the Black Trial enabled, in addition to the Breath changes, Nefarius will participate in the fight. He will occasionally give Chromaggus commands:
> * [***Fetch!***](https://www.wowhead.com/classic/spell=467883): This first occurs 20 seconds into the fight, and again every 40 seconds after that. When commanded, Chromaggus will grab a random player and hold onto them for a few seconds before releasing them.
> * [***Roll Over!***](https://www.wowhead.com/classic/spell=468598): Leading up to the 50% health mark, Nefarius will command Chromaggus to roll over, and around 50% he finally does. This causes the arena to shake and [meteors to fall down](https://www.wowhead.com/classic/spell=468199/roll-over), which must be dodged (like Golemagg).
