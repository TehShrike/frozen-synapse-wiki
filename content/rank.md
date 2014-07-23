title: Rank

<div class="thumb tright"><div class="thumbinner" style="width:456px;"><img src="images/thumb/2/20/Ranking.png/454px-Ranking.png" />  <div class="thumbcaption">The global ranking.</div></div></div>

Frozen Synapse has four main rankings, two based on today's play and two based on lifetime play.

Every game you play will have an impact on these rankings, whether it was created with automatic match making, a direct challenge, or an advanced (custom) map challenge.

As of September 2011, the [Elo rating system](http://en.wikipedia.org/wiki/Elo_rating_system) is used.



## <span class="mw-headline" id="Elo_ratings"> Elo ratings </span>

The Elo rating rewards players more based on the rating of the player they are matched against.  Losing against someone who is much lower rated than you will drop your rating much more than losing to someone who is higher rated than you.

Ian has made the rating implementation public!  You can see his first iterations [here](http://www.mode7games.com/blog/2011/09/09/elo-is-live-on-uk1/) and [here](http://www.mode7games.com/blog/2011/09/25/elo-and-generators/), with the latest version described in [this blog post](http://www.mode7games.com/blog/2011/09/11/elo-tweak/).

To see the rating changes that would occur for any particular game, see this [Elo calculator](http://error420.com/fs_elo_calculator/) implemented in Javascript by TehShrike.  It is based on the most recent code posted by Ian on the Mode7 blog.

## <span class="mw-headline" id="Global">Global</span>

The global rank is the one that is displayed before matches and is based upon your entire play history. It is based on the elo ratings of all players.

The record displayed is a total of a player's wins and losses.

New players start with a rating of 1200.  This can go up with wins or down with losses.

## <span class="mw-headline" id="Daily">Daily</span>

The daily chart is not based on Elo ratings, but is based on the number of points earned in the games played in the last ~24 hours.  The person at the top has received the most points of all players online today. If you haven't played today you won't appear on this list.

The record displayed is a total of a player's wins and losses today.

## <span class="mw-headline" id="Score_Streak">Score Streak</span>

A ranking of who has won the most consecutive games based on each player's entire match history. The score for each game doesn't matter as long as it's a win, so winning 10 games worth 10 points is worth more than winning 9 games worth 200 points.

The record displayed is a count of the longest victory streak that each player has ever achieved.

## <span class="mw-headline" id="Daily_Percentage">Daily Percentage</span>

This ranks individuals based on their performance across the [[duplicate.md|duplicate]] rankings for each game they've played today. It's possible to be high on this ranking without being high on the Daily ranking if you've managed to win setups that others haven't while not scoring highly overall.

The stats displayed on this screen have no bearing on the position in the rankings. There is no easy way to check how well someone has done compared to someone else in the list without retrieving all of their duplicate scoring data one game at a time.

<!-- 
NewPP limit report
Preprocessor node count: 19/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:135-0!*!0!!en!2!* and timestamp 20140722105425 -->