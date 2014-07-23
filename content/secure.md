title: Secure

<div class="thumb tright"><div class="thumbinner" style="width:302px;"><img src="images/thumb/a/a6/Map_secure.jpg/300px-Map_secure.jpg" />  <div class="thumbcaption">An example map. The white rectangles are the bidding areas, and the red rectangle is the attacker's spawn area.</div></div></div>

Secure is the [[game-modes.md|game mode]] where you are protecting or attacking a specific area on the map.
By default the attacker has 12 turns to get a unit into the marked zone.

Secure starts with a [[bidding.md|bidding]] phase to see who will be attacking and who will be defending, then plays as normal.



## <span class="mw-headline" id="Bidding_Phase"> Bidding Phase </span>

Each player 'bids' on a section of the map they think they can defend against attack.
Click on the area(s) you think you can defend with the units you are given.

You can have the AI bid for you, but that might not be the best option since by looking at the units you have you can probably pick a better and bigger area to defend than the AI will, as the AI seems to simply choose the smallest corner-of-the-map area it can find.

Once each player has primed, the player that bid the largest area has to defend it and the other player will be attacking.  The area enclosing the losing bid is shown in purple.

When bidding you both have to consider whether you want to be attacker or not (bid a smaller area if you want to attack), how easy it'd be for you to defend that area, how hard it would be to attack any given area, and how much score you want to risk. If both players choose the same area or areas of exactly equal size, the defense/offense is randomized.

## <span class="mw-headline" id="First_Turn"> First Turn </span>

If you are defending you can only deploy your [[unit-types.md|units]] in the zone you bid. Remember that you can drag them around in that area AND [[making-a-plan.md|plan]] orders for them.

If you are attacking you can deploy in the areas that were marked in red during the bidding phase. You can both choose their starting position and their starting orders.

## <span class="mw-headline" id="Ending_conditions"> Ending conditions </span>

If the below conditions are not met, the default turn limits for secure are 12 turns if it is a game of Dark Secure, or 6 turns if it is a game of Light Secure.

The attacker wins if they: Eliminate all enemy units, or get a unit into the marked area and have him survive inside for 3 seconds **after the first 2 turns**.

The defender wins if they: Eliminate all enemy units, or the turns run out before the attacker can get a unit into the marked zone.

The 3 second rule means the attacker must have entered the zone before 2 seconds have elapsed in the final turn. (This assumes 5s turns).

## <span class="mw-headline" id="Scoring"> Scoring </span>

The [[scoring.md|scoring]] is based on the size of the area bid by the bid winner. The exact formula is below, and the max score is 200.

50 + mCeil(propise(%bidArea, 0, 120000) * 150) + mCeil(proportionise(%bidArea, 120000, 500000) * 50)

This basically means that up to a certain point the score rises quickly, and after that point only at 1/3 the speed.

## <span class="mw-headline" id="Common_Strategies"> Common Strategies </span>

This section is intended to prepare players for strategies they're likely to face while playing Secure.

### <span class="mw-headline" id="Corner_Humping"> Corner Humping </span>

If one player possesses substantially more long-ranged units than his or her enemy and there's a corner without cover facing it, expect to see one player stack all his units in the corner, aiming directly away from it, such that it's impossible to approach without losing to the stillness/movement [[principles-of-combat.md|Principle of Combat]]. This player then bids everything safely within their line of fire and wins a large quantity of points. Game ORIGINAL:16092 [[1]](http://www.youtube.com/watch?v=Yv1JU5vf2KA) demonstrates this problem despite a glitch causing his [[unit-types.md|Assault Rifle]] unit to stare off into the distance despite the aim order it was issued.

If there isn't any suitable cover at all or unit randomization causes a severe imbalance (as seen above), then this is basically unbeatable; in such a case, it must be prevented before stacking can happen, by winning the defense bid. This can, itself, be very difficult, and if this is inevitable it may be in your best interest to simply not submit your bid and allow the game to be canceled by the server.

Additionally, different unit types can lend themselves to different types of Corner Humping in different parts of the map, as demonstrated in UK7:31124 and UK7:28305. 

### <span class="mw-headline" id="Counters_to_Corner_Humping"> Counters to Corner Humping </span>

If there isn't a total lack of cover and/or the units are relatively even, it's possible to beat the strategy with judicious use of the [[ignore-focus.md|Ignore/Focus]] orders. For instance, let's say you each have three Machine Guns. Your enemy is in the corner. Your units duck behind cover, aim at them, and each receive a focus order for a different enemy Machine Gun and a stand command, followed by an order to clear focus/ignore after moving a tiny distance (which they will only do if their focus target is out of sight or dead). They should, in an ideal situation, pop up and (despite the brief [[principles-of-combat.md|inability to acquire targets due to standing]]) they will then kill 2-3 of the enemy with 0-1 casualties. At that point, the Clear Focus/Ignore will go through and the remaining 2-3 of your units will finish off the enemy's last unit if it's still alive. If there's no suitable cover, doing this from emerging around a corner is also possible. You'll be deprived of the cover bonus, making it almost certainly 2-for-1, but it'll be 2-for-1 in your favor, earning you the win.

If the enemy is also using Focus/Ignore on his corner humpers, it becomes a matter of luck. Your best bet is that, as his units are almost certainly at the precise same coordinates, to issue yours by sending all your units to the same coordinate by double-clicking without moving your mouse. You should send your units around a corner all at the same time, already aiming, and basically hope as hard as you can that you get a unit he isn't focusing, as Focus commands as of the current version act as an Ignore on every other unit. This will, ideally, net a free kill to gain you the advantage for a victory.

An additional option is to take advantage to the precise rule of victory - 3 seconds in the red at the end of the turn wins for the attacker.  Using long range, movement, and distraction, the time to kill for a corner humping unit may be greater than 3 seconds.  See an example in game 192180 where range and movement end the final turn with a unit surviving under fire from corner humping defenders.

## <span class="mw-headline" id="Secure_Mode_Links"> Secure Mode Links </span>

[Mode7 Secure Tutorial](http://youtu.be/pnXFVnsNIMA)

<!-- 
NewPP limit report
Preprocessor node count: 31/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:60-0!*!0!!en!2!* and timestamp 20140722165619 -->