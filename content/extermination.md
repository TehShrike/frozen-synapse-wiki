title: Extermination

<div class="thumb tright"><div class="thumbinner" style="width:302px;"><img src="images/thumb/1/12/Map_extermination.jpg/300px-Map_extermination.jpg" />  <div class="thumbcaption">An example map. Note that there is a chance that units will spawn in opposite corners, instead of all over the map.</div></div></div>

Extermination, the most commonly played [[game-modes.md|game mode]], is a straight forward death match in which each player tries to kill the opponent's [[unit-types.md|units]] while keeping their own alive.  By default, games last a maximum of 8 [[turns.md|turns]].



## <span class="mw-headline" id="Ending_conditions"> Ending conditions </span>

Most wins are achieved by killing all units of the opponent's team, however there is a [[scoring.md|scoring]] system at play (as in all game modes) and technically it's the player with the higher score at the end of turn 8 (or when one team is eliminated) that wins. A draw is possible if the score is equal at the end of the game. This most often occurs when teams are even and both players lose their last units during the same turn, or when an equal number of units on each team survives to and through the last turn.

<div class="thumb tright"><div class="thumbinner" style="width:302px;"><img src="images/thumb/8/8e/Map_red_squares.jpg/300px-Map_red_squares.jpg" />  <div class="thumbcaption">A map showing the red victory areas.</div></div></div>

Sometimes, red areas will appear in each players corner of the map. Another way of winning is to get one of your units into your opponents area. These areas can only appear if the spawns are in opposite corners, not all over the map. 

## <span class="mw-headline" id="Scoring"> Scoring </span>

Each unit killed gives the player 10 points. Each unit lost subtracts 10 points. A wipeout adds a bonus 20 points to the team still standing and subtracts 20 points from the wiped out team. Keeping in mind that it's possible to have uneven teams means that even with equal units left by both players at the end doesn't necessarily mean it's a draw. In the case of uneven teams, the player with fewer units gets one additional point per unit more than the other player. The player with more units conversely gets one point less per additional unit. All units have equal value.

Or put more simply: 10 x kills - 10 x losses + 20 bonus for wipeout + difference in teams.

Player 1 **always** gets the negative value of Player 2. If player 1 gets 10, player 2 gets -10. If player 1 gets -40, player 2 gets 40.

### <span class="mw-headline" id="Standard_Example"> Standard Example </span>

This is how scoring worked in game 4525:

<pre><span style="color:green;">Green</span> starts with 4 units.
<span style="color:red;">Red</span> starts with 4 units.
<span style="color:green;">Green</span> kills all 4 units.
<span style="color:red;">Red</span> kills only 2 units.
<span style="color:green;">Green</span> = 10*4-10*2+20 = 40
<span style="color:red;">Red</span> = 10*2-10*4-20 = -40
</pre>

<span style="color:green;">Green</span> player wins.

### <span class="mw-headline" id="Weird_example"> Weird example </span>

This is similar but not quite the same as game 12149 as both teams survived to the end of that customised game.
In this case the teams are highly unbalanced and even though Red kills all of Green's units Green still wins.

<pre><span style="color:green;">Green</span> starts with 1 unit.
<span style="color:red;">Red</span> starts with 5 units.
<span style="color:green;">Green</span> kills 4 units.
<span style="color:red;">Red</span> kills the unit of the <span style="color:green;">Green</span>'s team.
<span style="color:green;">Green</span> = 10*4-10*1-20+4 = 14
<span style="color:red;">Red</span> = 10*1-10*4+20-4 = -14
</pre>

<span style="color:green;">Green</span> player wins despite losing all (one) units.

<!-- 
NewPP limit report
Preprocessor node count: 73/1000000
Post‐expand include size: 580/2097152 bytes
Template argument size: 9/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:3-0!*!0!!en!2!* and timestamp 20140723004249 -->