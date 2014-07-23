title: Check

<div class="thumb tright"><div class="thumbinner" style="width:202px;"><img src="images/thumb/2/2a/Check.png/200px-Check.png" />  <div class="thumbcaption">A check order. In this case the unit can't see the circle that indicates where the check order was given so it will not look that way until it can draw line of sight, which will be roughly when it reaches the doorway.</div></div></div>

The **check** command instructs a unit to slow momentarily and look in a specified direction. Its behaviour differs from the [[aim.md|aim]] order in a number of small, but important, ways:

*   Check does not force [[continue-on-sight.md|Engage on Sight]]; I.E., your units will not engage enemy units if they are currently [[continue-on-sight.md|continuing on sight]].

*   After performing the check, your unit will either continue moving in the same way it was before the check or continue to look in the checked direction if the unit has reached the end of its movement.

*   Check incurs a small penalty to kill-time.

Due to the penalty the Check order occurs, it should only ever be used for scouting while on Continue on Sight.

Unlike the aim order the exact position that you click to create the check order matters. If that position is out of line of sight of your unit when they try to execute the command they won't look in that direction until they move to another position where they can see the position. As soon as they can draw line of sight to the position in the future they will look there. This is different to aiming, where only the direction of the aim order matters.

Check is most valuable in dark game modes.

<!-- 
NewPP limit report
Preprocessor node count: 1/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:22-0!*!0!*!*!2!* and timestamp 20140722093206 -->