title: Making a plan

To start making a plan, left-click on the [[unit-types.md|unit]] you wish to select. 

<div class="thumb tright"><div class="thumbinner" style="width:182px;"><img src="images/2/2e/Basic_plan.jpg" />  <div class="thumbcaption">A basic plan, with waypoints and an aim command.</div></div></div>

You will probably want to move your unit somewhere, so double-click on the map wherever you want him or her to go: this will create a [[waypoint.md|waypoint]].

Waypoints are generated with pathfinding: you don't need to make multiple waypoints to guide your unit around an obstacle.  If you want to override the pathfinding and position the next waypoint literally anywhere on the map, just hold down shift and double-click.

If you want to delete the most recent waypoint you have added, just press Backspace.

To delete the last 10 waypoints in your plan, press =.



## <span class="mw-headline" id="Testing">Testing</span>

How do we know where our unit will get to in the five seconds he has to move?  We can get an idea by testing our plan, so just click on the Play button on the time bar or press the spacebar.

The plan will run through, and then skip back to the start so you can continue to edit it.

It's important to note that your [[turns.md|turn]] may not play out exactly as it does when you test it: units can react dynamically to hostiles they encounter, so things may happen slightly differently.

However, it's a good idea to test!

## <span class="mw-headline" id="Aiming">Aiming</span>

[[principles-of-combat.md|Direct fire units]] ([[unit-types.md|machine gunners]], [[unit-types.md|shotgunners]] and [[unit-types.md|snipers]]) will automatically engage any enemy who enters their [[line-of-sight.md|field of view]] by default. However, they will gain an advantage if they are specifically [[aim.md|aiming]] in a particular direction when an enemy appears.

To tell your unit to aim:

1.  Left-click anywhere on your plan (not just on waypoints) to indicate when you would like your unit to start aiming.  If your unit does not yet have any movement orders, but you would like him to simply start aiming in a particular direction, you can skip this step.

2.  Click and drag the "aim handle" (the circular token that looks like a crosshair) in the direction you would like your unit to aim.

3.  Test your plan to ensure your order is working correctly
<div class="thumb tright"><div class="thumbinner" style="width:302px;"><img src="images/thumb/9/9e/Rocket_plan.jpg/300px-Rocket_plan.jpg" />  <div class="thumbcaption">A rocket launcher's fire command.</div></div></div>

Your unit will continue aiming in the direction you have indicated as he walks along.  To change the direction in which he is aiming, simply issue another aim order using the above method. If you would like to tell your unit to stop aiming completely, you will have to issue a "Cancel Aim" order.  Issuing other kinds of orders is dealt with in the next section. 

### <span class="mw-headline" id="Firing">Firing</span>

[[principles-of-combat.md|Indirect fire units]] ([[unit-types.md|rocket launcher]], [[unit-types.md|grenade launcher]]) will only fire when instructed to do so. To fire a rocket or grenade, drag out the aim handle as normal.  This will simply create a "Fire Now" order, which behaves in a similar manner to an Aim order.

## <span class="mw-headline" id="Giving_Orders">Giving Orders</span>

You can do more than simply moving your units around and aiming. To issue an order at the current point on your plan, just open the orders menu with right-click. If you want to issue an order at a different point, left-click on your plan to select when you would like it to be enacted.  Then right-click to open the orders menu.

You can move orders around your plan by dragging them, and you can delete specific orders by left-clicking on them and pressing Del. Remember that you can progressively delete your plan and orders using Backspace.  This is handy for quickly re-doing a part of your plan that is not working out as you intended.

## <span class="mw-headline" id="See_also">See also</span>

*   [[getting-started.md|Getting Started]]

*   [[principles-of-combat.md|Principles of Combat]]

*   [[turns.md|Turns]]

<!-- 
NewPP limit report
Preprocessor node count: 19/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:16-0!*!0!!en!2!* and timestamp 20140722161158 -->