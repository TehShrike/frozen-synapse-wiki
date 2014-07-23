title: Principles of Combat

<div class="thumb tright"><div class="thumbinner" style="width:182px;"><img src="images/thumb/c/c8/Example_of_how_line_of_sight_is_affected_with_unit_positioning_at_a_window.gif/180px-Example_of_how_line_of_sight_is_affected_with_unit_positioning_at_a_window.gif" />  <div class="thumbcaption">[[line-of-sight.md|Line of Sight]].</div></div></div>

Combat in Frozen Synapse is entirely deterministic, that is, for the same starting conditions and plans you will get the exact same result every time. This is a long way of saying that Frozen Synapse is not a game of chance.

Your primary units in a given match are likely to be direct fire units; units firing bullets. These units will attempt to engage any enemy unit that enters their vision and their [[line-of-sight.md|engagement range]]. Once a unit has engaged it will shoot at its target until either the target is no longer visible or one of the combatants is dead. The time it takes a direct fire unit to fire the kill shot (the shot that will actually kill the enemy unit, all other bullets fired being eye-candy) is determined by a number of bonuses and penalties described in detail below.

Indirect fire units function in a much simpler manner: they fire a rocket or a grenade, anything within the radius of the explosion (adjusted for cover) dies a horrible death.



## <span class="mw-headline" id="Common_mistakes">Common mistakes</span>

Ducking does not confer any bonus in a combat, it just allows you to cower behind cover like, well, a coward. Furthermore, changing state from standing to ducking will actually make your unit incapable of defending itself for a fraction of a second. This is often long enough for your unit to lose an engagement.

Partial line of sight does not provide a defensive bonus, I.E., peeking around a corner will not make you harder to hit.  Cover bonuses are only granted when standing behind half height (light blue) objects.

## <span class="mw-headline" id="Time_to_Kill">Time to Kill</span>

Which vatform will kill the other first?

NOTE: The following has been determined by observation of games and not of source code, the implementation of this system is almost certainly different to that described here. This section does, however, describes a good model for the behavior of the game's implementation.

When a direct fire unit, A, engages another unit, B, there is a computable time that it will take for A to fire a kill shot at B. If A dies or B moves out of A's vision or engagement range before this time is up, then no kill shot will be fired.

To have a better shot at winning a gun battle you want to engage an enemy unit at an appropriate range, where appropriate range is **S**hort for **S**hotguns, **M**edium for **M**achine guns and **F**ar for, er, sniper ri**F**les.  Some unit types (machine guns and sniper rifles) have a large difference in firing times based on range.

The factors that affect this time are listed in rough order below:

1.  **Unit type** - shotguns have the shortest time, snipers the longest.

2.  **Distance to target** - closer target: shorter time.

3.  **[[cover.md|Cover]]** - target in cover: longer time.

4.  **Stillness** - the more quickly a unit was moving before they started firing, the longer it takes for them to get a kill shot.

Furthermore, **there is a delay associated with changing stance** (from standing to ducking and vice versa).  A unit will not be able to fire (the kill timer will not count down) for .5 seconds after changing stance.

Finally, there is a tiny pseudo-random bonus or penalty determined by turn number and player id. This is not something worth worrying about as it will only matter in the case of a bilateral engagement between units whose other bonuses are exactly the same. In any case, you can't do much about it.

### <span class="mw-headline" id="How_losing_line_of_sight_affects_the_time-to-kill_counter"> How losing line of sight affects the time-to-kill counter </span>

If your unit is aiming at an enemy unit, losing line of sight to the enemy resets the time-to-kill counter for all unit types except the sniper.  The sniper was changed in a patch that was released at some point before the Red expansion.

If a sniper is aiming at a unit, loses sight of it, and then regains line of sight to the same unit, its time-to-kill timer **is not reset if**:

*   The target is within 60sq units of where it was last seen

*   The sniper is within 30sq units of where it was last aiming from

*   No more than 2.5 seconds have elapsed since the sniper was last aiming

## <span class="mw-headline" id="Bilateral_engagements">Bilateral engagements</span>

When engaging another unit, the engaged unit will often attempt to shoot back, even if the engaged unit was not previously looking at the engaging unit. Indeed, a unit will only not do so if it is set to [[continue-on-sight.md|Continue on Sight]] or it is an indirect fire unit. 

In this case, there is one additional factor to those discussed earlier: first sight. If unit A engages unit B and B is not aiming at A, then B will suffer a penalty for not having first sight; that is to say, unit B will be at a disadvantage because it joined the combat a bit late.

In a bilateral engagement, the distance to target for both units is the same and can thus be discarded leaving our new list of factors something like this:

1.  Unit type

2.  Cover

3.  First sight

4.  Stillness

It should be noted that it is not possible for both units in a Bilateral engagement to successfully fire kill shots at each other.

## <span class="mw-headline" id="Stillness"> Stillness </span>

How quickly a unit is moving is one of the things that determines the amount of time until a kill shot will occur. There are three levels of stillness:

1.  Standing still.
2.  Aiming while moving.

3.  Moving at full speed.

Ducking does not affect the stillness advantage.

Also note that ducking or aiming has no benefit while standing still.

The slower-moving unit has the advantage.  Being still gives you the best chance at winning an encounter, all other things being equal.

## <span class="mw-headline" id="Unit_types"> Unit types </span>

<div class="thumb tright"><div class="thumbinner" style="width:117px;"><img src="images/thumb/2/2b/Unit_MG.jpg/115px-Unit_MG.jpg" />  <div class="thumbcaption">A machine gunner.</div></div></div>

To discourage fraternization with the rank and file, you are encouraged to identify soldier units by the weapon they carry. Hence, a machine gun carrying vatform is not a machine gunner. It is a machine gun. Compliance is optional but non-compliance may be met with termination.

### <span class="mw-headline" id="Direct_fire"> Direct fire </span>

NOTE:  All bullet-based units fire automatically upon seeing a hostile (this is the default: you can alter this behaviour with a "Continue On Sight" order).  Their weapons cannot harm friendly units.

*   **[[unit-types.md|Machine Gun]]** - These are the bread-and-butter of your tactical assault team.  With a surprisingly long range, they can cover a significant area of the map and are vital to your assault force.

*   **[[unit-types.md|Shotgun]]** - These have a shorter range than machine gunners, but move much faster and will win most close-quarters encounters.

*   **[[unit-types.md|Sniper]]** - Snipers have the longest range, but take a while to fire, so position them where you think they can get a good look at the enemy.

### <span class="mw-headline" id="Indirect_fire"> Indirect fire </span>

<div class="thumb tright"><div class="thumbinner" style="width:117px;"><img src="images/thumb/1/1f/Unit_RL.jpg/115px-Unit_RL.jpg" />  <div class="thumbcaption">A rocket launcher.</div></div></div>

Indirect fire units will not fire until you instruct them to (using the [[aim.md|aim]] command).  Their weapons _do_ harm friendly units.

*   **[[unit-types.md|Rocket Launcher]]** - The correct use of a rocket launcher can cause you to dominate the map: their ability to destroy terrain can come in very useful. Rockets only explode on contact with walls (the edge of the level is not included in this) so you must time their use very carefully. Rocket launchers normally fire their rockets over half-height objects.  To hit them, the unit must be ducking before firing.

*   **[[unit-types.md|Grenade Launcher]]** - Grenades cause more splash damage than rockets, and can be bounced off walls. Grenades are the only weapons that can be fired over cover while ducked.

### <span class="mw-headline" id="Single_Player_Only">Single Player Only</span>

*   **[[unit-types.md|Commando]]** - The commando unit is, essentially, a very fast shotgunner.  Keep moving it around to make maximum use of its abilities.

*   **[[civilian.md|Civilians]]** - Green civilians can be moved around just like other units. They are unarmed.

*   **?** - There is one other secret unit in the single player.  Explaining it here would spoil your fun; it would make this Help a little bit like a rude clown or a biscuit that looks nice but is actually rubbish.  You know, one of those cheap biscuits?  Like that. If you _really_ want to know, go to the [[unit-types.md|Unit Types]] page.

## <span class="mw-headline" id="Examples_of_Engagement_Outcomes">Examples of Engagement Outcomes</span>

In general, for opposing units of the same type, given that all unmentioned factors are either equal or disregardable:

1.  a unit in cover will always beat a unit without cover despite any difference in sighting and stillness;

2.  a unit moving into cover will beat a standing unit without cover (unless both are close enough to the cover to count as being under cover);

3.  a unit changing stances (standing if it was ducked) in cover will:

    1.  lose if the opponent is close enough to kill it within 0.5 seconds (for good measure, consider it half the range of a Shotgun if the units are Machine Guns. If the units are Shotguns then the still one will win);

        2.  win if the opponent is at at sufficient range to not kill it in 0.5 seconds;

4.  a unit who first sighted another will always win despite any difference in stillness between them;

5.  a unit moving slower will always beat a unit moving faster;

6.  a unit changing stances will always lose to a unit not changing stances;

In general, for opposing units of different types, given that all unmentioned factors are either equal or disregardable:

1.  a Shotgun in cover will win against any other unit unless he is killed before he sights it;

2.  a Shotgun moving into cover will win against all units unless they are a Shotgun in cover with more stillness (see Stillness, above);

3.  a Shotgun, moving, will win against all units of different types if engaging at close range. Furthermore, a Shotgun at close range can likely fire twice or more before a Machine Gun can fire even once.

4.  a Shotgun without cover but in range of it will win against a Machine Gun in cover unless sighted first while moving at full speed.

5.  a Shotgun without cover but in range of it will win against a Sniper Rifle.

6.  a Machine Gun will win against a Sniper Rifle if engaging at short range, despite any bonuses the Sniper Rifle may have.

7.  a Machine Gun engaging a Sniper Rifle at medium range will:

    1.  lose if the Sniper Rifle is under cover while the Machine Gun is not;

        2.  lose if the Sniper Rifle sights the Machine Gun for 1-2 seconds before it is sighted back;

        3.  win in all other engagements.

8.  a Sniper Rifle will win against a Machine Gun if engaging at long range, despite any bonuses the Machine Gun may have.

## <span class="mw-headline" id="See_also"> See also </span>

*   [[getting-started.md|Getting Started]]

*   [[making-a-plan.md|Making a plan]]

<!-- 
NewPP limit report
Preprocessor node count: 43/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:15-0!*!0!!en!2!* and timestamp 20140722181111 -->