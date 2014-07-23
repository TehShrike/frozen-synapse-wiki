title: Scoring

<div class="thumb tright"><div class="thumbinner" style="width:402px;"><img src="images/thumb/c/c5/Scoring.png/400px-Scoring.png" />  <div class="thumbcaption">The Results page after a game of Secure.</div></div></div>

Frozen Synapse utilizes a numbered scoring system in order to provide a mathematical skill based ends to how a game is won or lost.

The score that a player gets in a game is used to calculate the change to their Elo [[rank.md|rating]].

This page is primarily meant just as a compilation of scoring mechanics.



## <span class="mw-headline" id="Some_Useful_Notes"> Some Useful Notes </span>

*   A draw results in a score of 0 (and vice-versa!)

*   The loser always gets the winner's score multiplied by -1.

*   A game result is always shown as relative to player one regardless of who wins. If player two wins the game will show a negative total score. The actual change to an individual's score is always positive for the winner and negative for the loser. Making it relative to player one means that comparing [[duplicate.md|Duplicate]] results of a game is very easy as it's obvious which way the game went.

## <span class="mw-headline" id="Extermination">Extermination</span>

*   10 * number of units killed

*   -10 * number of units lost

*   20 points for wiping out the enemy team

*   -1 * difference in initial unit numbers

Max score (with 4 units on each team): 60.

Do note that [[extermination.md|Extermination]] can have more units, but seldom does.

## <span class="mw-headline" id="Disputed">Disputed</span>

*   30 * boxes carried off the map (or held on to until the end of the game) by own units

*   -30 * boxes carried off the map (or held to until the end of the game) by enemy units

Max score: 150.

If one wipes out the enemy team before the boxes appear, one gets 140 points.

## <span class="mw-headline" id="Hostage">Hostage</span>

*   2 hostages escape - 50 point win to the attacker

*   1 hostages escape - 25 point win to the attacker

*   0 hostages escape - 40 point win to the defender

## <span class="mw-headline" id="Charge">Charge</span>

The score the winner gets in [[charge.md|Charge]] is 200 * (Winning) bid in&#160;% across the map. Max score is 189 (as one cannot bid quite all the way across the map), but won't happen unless co-operation is involved or one party is an idiot.

## <span class="mw-headline" id="Secure">Secure</span>

The size of the win is proportional to the size of the highest bid. A larger zone will result in a larger score. The exact formula is below, and the max score has been shown to be 200.

50 + mCeil(propise(%bidArea, 0, 120000) * 150) + mCeil(proportionise(%bidArea, 120000, 500000) * 50)

This basically means that up to a certain point the score rises quickly, and after that point only at 1/3 the speed.

<!-- 
NewPP limit report
Preprocessor node count: 23/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:125-0!*!0!!en!2!* and timestamp 20140723040212 -->