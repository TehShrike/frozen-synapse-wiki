title: Layers

<div class="thumb tright"><div class="thumbinner" style="width:202px;"><img src="images/thumb/4/46/Toolbox.png/200px-Toolbox.png" />  <div class="thumbcaption">The Toolbox, which includes layers.</div></div></div>

A layer is part of a unit's plan that been separated into a separate planning layer from the rest of the unit's orders using the UI [[toolbox.md|toolbox]]. They are used to allow more reasonable editing of overlapping waypoints.

Layers are created using the toolbox available at the bottom right. Select a [[waypoint.md|waypoint]], click on New and the current waypoint will become the splitting point between two layers, one of everything before the waypoint (up to the previous layer if using multiple) and one of everything after the waypoint (up to the next layer if using multiple).

[[orders.md|Orders]] that are not in the current layer are dimmed and can't be changed. Orders in the current layer will show as normal. To change between layers use the next and previous buttons in the toolbox.

Layers are only useful for plans that will double back and overlap themselves where you want to add specific orders in both directions. For example, if a [[unit-types.md|unit]] is going to walk around a corner and then back the same way you might create a layer at the furthest point around the corner. The orders taking the unit around the corner will show as one layer and the orders taking the unit back will show as another layer. In most cases they shouldn't be needed.

<!-- 
NewPP limit report
Preprocessor node count: 1/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:146-0!*!0!*!*!2!* and timestamp 20140722120416 -->