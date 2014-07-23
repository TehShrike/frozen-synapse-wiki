title: Move

<div class="thumb tright"><div class="thumbinner" style="width:202px;"><img src="images/thumb/8/8a/Waypoints.png/200px-Waypoints.png" />  <div class="thumbcaption">A series of waypoints leading from left to right. Each waypoint is one move order. The unit will stop when it reaches the rightmost waypoint.</div></div></div>

## <span class="mw-headline" id="Basic_Principle">Basic Principle</span>

Commands a [[unit-types.md|unit]] to move to a specified position. Each move order shows as a waypoint with a line linking it to the previous and next waypoint in the sequence. Other [[orders.md|orders]] will show up on the waypoints themselves but the presence of a waypoint implicitly tells your unit to go there.

## <span class="mw-headline" id="Using_the_Move_Command">Using the Move Command</span>

Select a unit and double click on an empty space or right click and select Move. Once placed an order can be moved by dragging and dropping with the mouse. It is possible to add a waypoint inbetween two existing waypoints by dragging the line inbetween them to form a new waypoint.

Holding the shift key while adding a move order will prevent any automatic pathfinding between the previous waypoint and the new waypoint. This can be used to destroy a wall during a turn and walk through it in the same turn. If the order will result in the unit getting stuck the game won't let you submit the turn until you stop the unit getting stuck. It isn't possible to submit plans that might rely on an opponent blowing up a wall mid turn as the game can't guarantee that the move order will be valid during planning.

## <span class="mw-headline" id="Movement_Speed">Movement Speed</span>

Different units will move at different speeds. A ranking of the standard (multiplayer) units, starting with the fastest:

1.  [[unit-types.md|Shotgun]]

2.  [[unit-types.md|Machine gun]]

3.  [[unit-types.md|Rocket]] / [[unit-types.md|Grenade launcher]]

4.  [[unit-types.md|Sniper]]

There are additional units in the campaign who will move at different speeds.

<!-- 
NewPP limit report
Preprocessor node count: 11/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:140-0!*!0!!*!2!* and timestamp 20140722233542 -->