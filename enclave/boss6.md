---
layout: post
title: Boss 6
parent: Scarlet Enclave
nav_order: 10
subtitle: Boss 6
---
{: .warning .fs-3}
This guide is still a work in progress.

# Boss 6: Reborn Council
*Last updated: 5/9/25*

![Boss 6, Reborn Council]({{site.url}}/enclave/i/boss6_intro.png)

This encounter has three separate bosses: <span class="class-mage">Doan</span>, <span class="class-warrior">Herod</span>, and <span class="class-rogue">Vishas</span>.

They pull together and have separate health pools.

Despite visually being Undead, they do not count as Undead enemies, so T3 6-piece bonuses do not work against them.

The bosses do not have to die simultaneously, but when each one dies, their death will change some fight mechanics.

This encounter has a 10 minute berserk timer - all bosses must die before this occurs.

{: .note .fs-3}
This timer is tight enough to warrant mentioning, but it's definitely possible to hit with 20 players, and much easier with more.

---
## Boss Mechanics

Unless otherwise noted, all of these mechanics will stop when that boss is killed.

{% tabs bosses %}
  {% tab bosses#Herod %}

    <p>The <span class="class-warrior">Warrior</span> of the trio. He must be tanked.</p>
    
    <h3><a href="https://www.wowhead.com/classic/spell=1231264">Blades of Light</a></h3>
    <p>This is a whirlwind ability that deals immense damage in an 8 yard radius around him. Only the Tank should stay in during this ability, to hold Herod still.</p>

    <h3><a href="https://www.wowhead.com/classic/spell=1231314">Radiant Divide</a></h3>
    <p>This is a frontal ability that will severely damage the tank and apply a Mortal Strike effect for 5 seconds, halving healing received. The boss must be tanked facing towards the wall to avoid this hitting other players.</p>

    <h3><a href="https://www.wowhead.com/classic/spell=1231383">Divine Avatar</a></h3>
    <p>This is a 15 second pseudo-Frenzy that will buff Herod's damage by 50% and cause a secondary effect to hit the raid, Divine Strike. While this behaves like a Frenzy, it cannot be tranq'd like one.</p> TODO: Confirm no tranq

    <h3><a href="https://www.wowhead.com/classic/spell=1231493">Divine Strike</a></h3>
    <p>Whenever Divine Avatar is active, holy rain will fall from the sky and land on the ground, similar to Solistrasza's Radiant Light. The damage radius from this is very well choreographed; as soon as you see holy circles, run out of them.</p>
    <p class="important fs-3">When Herod dies, Divine Strike will persist for the rest of the fight.</p>

    <h3><a href="https://www.wowhead.com/classic/spell=1231227">Reborn Inspiration</a></h3>
    <p>If Herod is within 10 yards of another boss, the other boss will take 50% less damage until they are moved apart.</p>


  {% endtab %}
  {% tab bosses#Vishas %}

    <p>The <span class="class-rogue">Rogue</span> of the trio. He must be tanked.</p>
    
    <h3><a href="https://www.wowhead.com/classic/spell=1231095">Peeled Secrets</a></h3>
    <p><b>This is the most important mechanic in this fight</b>. He will frequently try to cast Peeled Secrets. It has a 2 second cast time and MUST be interrupted. <ins>If a cast succeeds, this is almost a guaranteed raid wipe</ins>. You will need to devote at least 3 players to a kick rotation and they must stay on this boss for the entire duration of the fight. It's not a bad idea to have additional players on standby ready to kick as well, if needed. The majority of your raid chatter should be dedicated to communicating kicks. This DoT deals 1k damage every second raid-wide for 15 seconds, which far exceeds the healing capacity of most raid teams.</p>

    <h3><a href="https://www.wowhead.com/classic/spell=1231387">Garrote</a></h3>
    <p>Occasionally, Vishas will cast <a href="https://www.wowhead.com/classic/spell=1231389">Vanish</a>. After vanishing, he will dash between random members of the raid and Garrote them. These players must be healed above 90% to remove the DoT. He will do this for around 15 seconds before returning to normal. He does not return to his original position when this ends; he'll need to be picked up and dragged back.</p>

    <h3><a href="https://www.wowhead.com/classic/spell=1236339">Veil of Darkness</a></h3>
    <p>When Vishas is killed, the entire arena is plunged into darkness. This deals 100 damage per second to all players as long as they remain stationary.</p>

    <h3><a href="https://www.wowhead.com/classic/spell=1231230">Reborn Inspiration</a></h3>
    <p>If Vishas is within 10 yards of another boss, he increases their attack speed by 50%.</p>

  {% endtab %}
  {% tab bosses#Doan %}

    <p>The <span class="class-mage">Mage</span> of the trio. <b>He does not need to be tanked</b>, but he has the most mechanics of any other boss. He will periodically teleport around the arena; tanks will need to reposition the other two bosses to keep all three apart.</p>
    
    <h3><a href="https://www.wowhead.com/classic/spell=1231200">Fireball</a></h3>
    <p>This is his primary attack - it has a 2 second cast time and can be interrupted, but you should save your interrupt cooldowns for Vishas.</p>
    
    <h3><a href="https://www.wowhead.com/classic/spell=1231282">Molten Basin</a></h3>
    <p>Periodically, Doan will flood the lowest level of the arena with a lava pool. Climbing the first set of stairs is enough to avoid this.</p>
    <p class="note fs-3">This will begin around 1 minute 30 seconds and persist for around a minute, from start to finish. The cooldown begins when it ends, so this will first show up around 1:30, persist until around 2:30, and then reappear around 4:00.</p>
    <p class="important fs-3">When Doan is killed, Molten Basin becomes permanent for the rest of the fight.</p>
    
    <h3><a href="https://www.wowhead.com/classic/spell=1236157">Volcanic Unrest</a></h3>
    <p>Whenever Molten Basin is active, the arena will also be visited by a pair of fire tornados that sweep the upper circle path. These are positioned opposite each other and move fairly quickly in a clockwise pattern. While inside of one, you will take ~2k damage every 0.5 sec. Run through these in the opposite direction they're moving to only take 0-1 ticks of damage each time, rather than 2-3 ticks.</p>
    <p class="important fs-3">As these are tied to Molten Basin, when Doan is killed, these become permanent for the rest of the fight.</p>
    
    <h3><a href="https://www.wowhead.com/classic/spell=1231538">Blast Wave</a></h3>
    <p>Each time Doan teleports, he will cast Blast Wave, a short-range AoE knockback. The main risk here is the potential to get knocked into Molten Basin if it's currently active. All players must be proactive in watching for Doan's teleports to avoid this knockback.</p>
    
    <h3><a href="https://www.wowhead.com/classic/spell=1231000">Molten Remnant</a></h3>
    <p>These will frequently appear as small fire swirls on the ground. When standing on one, you will take ~500 damage per second, so most players should run out of these. Unless convenient, Tanks can easily soak these and should do so to keep their bosses stationary. Being inside of multiple does not cause you to take damage from multiple. These last for 15 seconds.</p>
    
    <h3><a href="https://www.wowhead.com/classic/spell=1236220">Slow</a></h3>
    <p>The first debuff he applies - you should focus dispelling this ASAP whenever it goes out, as the slowed movement speed makes it very hard to reposition to avoid other mechanics.</p>
    
    <h3><a href="https://www.wowhead.com/classic/spell=1230996">Imbued Assault</a></h3>
    <p>The second of two debuffs that Doan applies, this deals some damage when applied and acts as a medium-severity DoT. Magic dispel when able, but prioritize Slow.</p>
    
    <h3><a href="https://www.wowhead.com/classic/spell=1231231">Reborn Inspiration</a></h3>
    <p>If Doan is within 10 yards of another boss, he will heal them for 20k health every second.</p>

  {% endtab %}
{% endtabs %}

---

## Positioning
The entire fight should take place on the middle and upper levels of the arena, leaving the bottom floor empty to avoid having to reposition for Molten Basin.

Each boss has a unique Reborn Inspiration buff that applies to the other bosses if they are too close, so they must all be tanked at least 10 yards from each other.

{% tabs positions %}
  {% tab positions#Pull %}

    <br>

    <img src="{{site.url}}/enclave/i/boss6_pull.png">

    <p>Because the bosses will buff each other if they're too close, they must be tanked apart.</p>
    <p>Both <span class="class-warrior">Herod</span> and <span class="class-rogue">Vishas</span> should be dragged up to the middle floor. One should be dragged to one side, and the other to the other side, leaving the center open.</p>

    <p>Both bosses will need to be repositioned depending on where <span class="class-mage">Doan</span> decides to teleport to, making sure all 3 are kept separate. Click the next tab for examples of this.</p>


  {% endtab %}
  {% tab positions#Example 1 %}

    <br>

    <img src="{{site.url}}/enclave/i/boss6_example1.png">

    <p>This is what an early stage of the fight might look like right after a pull. Herod and Vishas have both been moved to their standard positions, and Doan has chosen to teleport to the top floor.</p>

    <p>Since they're far enough apart, you can just keep them in their default positions until Doan moves.</p>

  {% endtab %}
  {% tab positions#Example 2 %}

    <br>

    <img src="{{site.url}}/enclave/i/boss6_example2.png">

    <p>Compared to the last example, Doan has now chosen to teleport next to Vishas.</p>

    <p>The Vishas tank will need to drag him away to the open central position. There should be enough room in this example so that Herod can remain stationary.</p>

  {% endtab %}
  {% tab positions#Example 3 %}

    <br>

    <img src="{{site.url}}/enclave/i/boss6_example3.png">

    <p>Now things get complicated. Compared to Example 2, Doan has chosen to teleport beside Herod. This is unfortunate, but salvageable.</p>

    <p>To keep everyone apart, both Herod and Vishas will need to be dragged away. Vishas should be returned to his default position, and Herod should be moved to the central spot.</p>

  {% endtab %}
{% endtabs %}

---

## Strategy
Melee should be focused on killing Vishas and, when possible, Herod. Whenever Herod begins channeling Blades of Light, any melee on him should move back to Vishas.

Ranged should be focused primarily on killing Doan. While it's possible for melee to attack him, Blast Wave makes that very annoying, and it's also an outright pain to try and chase him around when he keeps teleporting. Casters with 30 yard spells should be able to reach most of the possible teleport locations as long as they're standing on the rim of the upper floor.

You should focus on killing Doan first, since his death will dramatically simplify the mechanics at play - killing him will remove both magic debuffs, Blast Wave, and Molten Remnants. While his death will cause a permanent Molten Basin and the accompanying tornados, these are relatively minor compared to the *massive* benefit of no longer having him teleport everywhere. Don't forget, with him dead, both of the other bosses can remain stationary for the rest of the fight.

Once Doan is dead, you should try and kill both Herod and Vishas around the same time as each other, with Herod dying just before Vishas. Melee will have been mostly focused on Vishas up until now, so he should have less health than Herod - have some melee swap to Herod along with all of the ranged.

{: .note .fs-3}
You can attempt to kill all 3 around the same time, but since the berserk timer was lifted to 10 minutes (on 4/29/25), the DPS race is nowhere near as difficult and this shouldn't really be necessary.