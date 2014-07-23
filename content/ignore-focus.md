title: Ignore/Focus

<div class="thumb tright"><div class="thumbinner" style="width:202px;"><img src="images/thumb/c/c7/Ignore_Unit.png/200px-Ignore_Unit.png" />  <div class="thumbcaption">The green unit is ignoring the red unit. It will not attack the red unit if seen.</div></div></div>
<div class="thumb tright"><div class="thumbinner" style="width:202px;"><img src="images/thumb/d/d0/Focus_Unit.png/200px-Focus_Unit.png" />  <div class="thumbcaption">The green unit is focusing on the lower red unit. It will not attack the other red unit.</div></div></div>
<div class="thumb tright"><div class="thumbinner" style="width:202px;"><img src="images/thumb/1/1e/Ignore_Zone.png/200px-Ignore_Zone.png" />  <div class="thumbcaption">The unit is ignoring the zone. It will not attack any enemies that are in the zone.</div></div></div>
<div class="thumb tright"><div class="thumbinner" style="width:202px;"><img src="images/thumb/f/f0/Focus_Zone.png/200px-Focus_Zone.png" />  <div class="thumbcaption">The unit is focusing on the zone. It will not attack any enemies that are outside the zone.</div></div></div>

This command has two different functions:

*   Ignore/Focus Enemy

*   Ignore/Focus Area


## <span class="mw-headline" id="Ignore_Enemy"> Ignore Enemy </span>

When a unit is told to Ignore it will do as the name suggests; if that enemy comes into [[line-of-sight.md|Line of Sight]] it will be completely ignored, much like [[continue-on-sight.md|Continue on Sight]] but for a specific enemy.

### <span class="mw-headline" id="Breaking_Ignore_Enemy"> Breaking Ignore Enemy </span>

There are three ways to cancel Ignore:

*   Clear Focus/Ignore

*   Focus on the ignored Enemy/Zone

*   The ignored unit dying

### <span class="mw-headline" id="Ignore_Zone"> Ignore Zone </span>

This is done by using the [[shortcuts.md|hotkey]] "T" and dragging with the mouse over an area, which will create a highlighted [[zones.md|zone]] on the map. This highlighted area can then be used the same way as Ignore Enemy, except it affects a specific area so if any enemy units go inside that area your unit will ignore them.

Your enemy however, will see this zone in the following turns. It won't show if it was used for ignore or focus, or at all, only that it's there. This is due to a bug in the game, and is likely to be fixed soon.

### <span class="mw-headline" id="Basic_Uses"> Basic Uses </span>

The Ignore commands have many uses, but here are a few important ones:

*   Like Continue On Sight, Ignore (but not Focus!) can be used at the start of the turn to break out of a firefight.

*   They can be used to ignore [[unit-types.md|Rocket Launchers]] and [[unit-types.md|Grenade Launchers]] for a short period of time so as to get out of the potential blast radius, and only then breaking ignore and killing them.

*   Getting past enemies you know you cannot kill.

*   Focusing on more important enemies.

## <span class="mw-headline" id="Focus"> Focus </span>

Focus, like ignore, has two different functions:

*   Focus on Enemy

*   Focus on Area

Focus makes a unit concentrate on a unit/units, or an area. It causes the unit to ignore everything but the area/unit that is focused upon.

### <span class="mw-headline" id="Focus_on_Enemy"> Focus on Enemy </span>

This command makes an unit ignore all enemies bar the one(s) you have focused on. Due to this, the unit will attempt to kill focused upon enemies and never engage any other enemies.

### <span class="mw-headline" id="Focus_on_Zone"> Focus on Zone </span>

First one creates a zone, as described in Ignore area. This highlighted area can then be used the same way as Focus Enemy, and causes the unit to ignore any enemy outside the focus zone. Seeing as it uses the same zone system as Ignore Zone, it also has the same problems.

### <span class="mw-headline" id="Breaking_Focus"> Breaking Focus </span>

The only ways to break focus is by using a Clear Focus/Ignore command.

### <span class="mw-headline" id="Basic_Uses_2"> Basic Uses </span>

*   Prioritizing high-risk enemies.

*   Ignoring enemy distraction techniques.

## <span class="mw-headline" id="Combining_focus.2Fignore_with_other_orders"> Combining focus/ignore with other orders </span>

*   A Focus order automatically cancels any Continue-On-Sight order that is in effect.

*   A unit can ignore and focus multiple enemies and zones at once.

    *   Focusing on some enemies is the same as ignoring the others (except that Focus does not break firefights).

        *   Focusing on some zones is the same as ignoring the rest of the map, and vice versa (except that Focus does not break firefights).

        *   A unit will only engage an enemy if it is one of the enemies focused upon _and_ it is inside one of the focused zones.

        *   Ignore orders take priority, so for example if a focused enemy is in an ignored zone, it will be ignored.

<!-- 
NewPP limit report
Preprocessor node count: 39/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:98-0!*!0!!en!2!* and timestamp 20140723034330 -->