---
layout: post
title: Boss 5
parent: Scarlet Enclave
nav_order: 8
subtitle: Boss 5
---
{: .warning .fs-3}
This guide is still a work in progress.

# Boss 5: Alexei the Beastlord
*Last updated: 4/18/25*

There are two bosses, [Alexei the Beastlord](https://www.wowhead.com/classic/npc=240794) and [Sir Dornel](https://www.wowhead.com/classic/npc=241906). The bosses have a shared health pool.

This boss is very straightforward - it's like a smaller version of SoM/SoD BWL's Twin Drakes, which itself is already a smaller version of Vanilla Naxx's Four Horsemen.

Every 16 seconds, Alexei will afflict up to 5 nearby players with [Enkindle](https://www.wowhead.com/classic/spell=1230242/enkindle), a stacking DoT that deals more damage per stack. Sir Dornel will simultaneously cast a twin debuff, [Enervate](https://www.wowhead.com/classic/spell=1230200).

{: .tip .fs-3}
Each debuff lasts 30 seconds, and casts occur every 16 seconds. This means that if you have a single stack, and then the boss casts another round and you aren't afflicted with the second round, your stack *will* be guaranteed to fall off before the next debuff goes out.

Unlike on Twin Drakes, these debuffs are not applied to all players within a 50 yard radius - instead, they're only applied to the closest 5 players within a 30 yard radius.

Each boss also has two additional mechanics:

### Alexei the Beastlord

* **[Rending Slash](https://www.wowhead.com/classic/spell=1230099)**: Frontal cleave. Melee should stand behind the boss. Be sure to focus heals on the tank whenever one goes out.
* **[Entangling Shot](https://www.wowhead.com/classic/spell=1230255)**: Will occasionally trap players in a nearby area with Entangling Roots for a few seconds. Annoying, but not a big deal.

### Sir Dornel

* **[Wild Aperture](https://www.wowhead.com/classic/spell=1230105)**: Occasionally, the boss will create a pattern of small green dots on the ground. After a second, these will explode and deal damage to anyone caught near them. Simply reposition so you're not standing on one before they burst.
* **[Stomp](https://www.wowhead.com/classic/spell=1228295)**: Players in melee range will be damaged and temporarily stunned. Annoying, but not a big deal.

There are a number of ways to approach fighting this boss.

{% tabs beastlord %}
  {% tab beastlord#The Exchange %}

    <p><b>Run three tanks.</b> Have one tank hold each boss around 20 yards from each other, and have the third tank wait on standby. When one of the boss tanks reaches 2-3 stacks, have the third tank come in and pick up that boss. The old tank should rotate to the other boss and relieve the other tank, who should flip over to the first boss again.</p>
    <p class="tip fs-3">This is the safest strategy in a PUG situation.</p>

  {% endtab %}
  {% tab beastlord#The Swivel %}

    <p><b>Run two tanks.</b> Have each tank hold each boss around 10 yards from each other. Have the tanks stand at the maximum range from the boss, while at least 5 melee sit on each boss. The melee on each boss should stand as close as possible to the boss, closer than the tank is, to ensure the tank never receives a stack. Whenever a wave of Enkindle/Enervate goes out, all melee should swap sides, to ensure there are always 5+ players closer to each boss than the tanks.</p>
    <p class="tip fs-3">This is the cleanest strategy, as long as you have 10+ melee DPS that can reliably position themselves.</p>

  {% endtab %}
  {% tab beastlord#Tank Kiss %}

    <p><b>Run two tanks.</b> Have each tank hold a boss 15 yards apart. Every 2 stacks received by the tanks, have them drag the bosses to meet each other, taunt-swap to exchange bosses, then drag them apart again, until another 2 stacks have built up. This is risky as there's little wiggle room if a taunt gets resisted.</p>

  {% endtab %}
  {% tab beastlord#Zug Zug %}

    <p><b>Run two tanks.</b> Run two tanks. Stack the two bosses together, with one tank holding threat on each boss. Whenever a player receives a debuff stack, have them pivot to the other boss, standing further away so they don't get two stacks. This is basically a riskier version of The Swivel that allows you to cleave, and relies on sheer numbers to avoid debuff overlap.</p>
    <p class="tip fs-3">You'll need stronger raid heals to ensure this goes smoothly, but if you have a lot of players this could lead to very quick kills, since you can cleave.</p>

  {% endtab %}
{% endtabs %}

In all situations, melee should watch their stacks and rotate between bosses at 1-2 stacks based on raid healing capacity. Casters and healers are practically guaranteed to never receive stacks, so they should just dodge mechanics as necessary.

{: .tip .fs-3}
In a pinch, you can have casters/healers stand in melee to soak stacks. This is crucial to the success of the Zug Zug method, but can also be employed elsewhere in case of fewer melee, especially for beefy specs like Holy Paladin.

{: .highlight .fs-3}
Once Alexei has been pulled at least once, he (and Sir Dornel) begin patrolling up and down the road. They will briefly return back to the original stables at the end of each patrol.