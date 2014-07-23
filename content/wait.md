title: Wait

<div class="thumb tright"><div class="thumbinner" style="width:202px;"><img src="images/thumb/9/93/Wait.png/200px-Wait.png" />  <div class="thumbcaption">A wait order. The unit will wait at that position until the time expires then move down.</div></div></div>
<div class="thumb tright"><div class="thumbinner" style="width:202px;"><img src="images/thumb/4/4c/Wait_Aim.png/200px-Wait_Aim.png" />  <div class="thumbcaption">A wait order with an aim order. The unit will wait half the time, turn and aim, wait the rest of the time and then move.</div></div></div>

## <span class="mw-headline" id="Basic_Principle">Basic Principle</span>

Commands a [[unit-types.md|unit]] to wait at a specific position for a fixed amount of time.

## <span class="mw-headline" id="Usage">Usage</span>

At any waypoint or position on a line between waypoints click and drag the clock icon to the right. The small number at the end of the line is the total number of seconds the wait order will last for. Other [[orders.md|orders]] can be placed on a wait order and will be executed when they are reached. For example, an order given halfway through a 4 second wait order will be executed after 2 seconds.

This is most commonly used to coordinate multiple units to enter a room at the same time, to make one unit check multiple angles from one position over the course of a turn and to tweak [[distraction.md|distractions]].

## <span class="mw-headline" id="Interaction_with_other_orders">Interaction with other orders</span>

Any order that is given in the middle of a wait order (placed on the wait line) will interrupt the wait time for the duration of the order. In most cases orders are instant so there is no impact but for rockets and grenade units firing takes a short amount of time and will cause the unit to wait for a total time longer than the wait order's time.

If a direct fire unit engages an enemy while waiting the wait time will be interrupted and only resume after the firefight has ended. For example, if a unit is told to wait 2 seconds but sees an enemy during that and shoots for 3 seconds, the total time elapsed between the start of the wait order and the end of the wait order will be 5 seconds.

<!-- 
NewPP limit report
Preprocessor node count: 11/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:141-0!*!0!!*!2!* and timestamp 20140722212804 -->