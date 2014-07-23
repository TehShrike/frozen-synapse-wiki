title: IRCbot Shapeform

Shapeform is an IRC bot that gives answers based on keywords and can do some simple commands.

To suggest new features for the bot, check out the talk page!



## <span class="mw-headline" id="Maintainers"> Maintainers </span>

Shapeform was made by Void and is maintained by the people listed below:

<table cellpadding="5" cellspacing="0" border="1">
<tr>
<td>Draz
</td>
<td>Can add, remove, and edit keywords
</td></tr>
<tr>
<td>[[user-hdfisise.md|Hd]]
</td>
<td>Can add, remove, and edit keywords - HAS FORGOTTEN HOW TO!
</td></tr>
<tr>
<td>[[user-meneth.md|Meneth]]
</td>
<td>Can add, remove, and edit keywords. Controls the Info rotation.
</td></tr>
<tr>
<td>[[user-mr.k.md|Mr_K]]
</td>
<td>Can add, remove, and edit keywords
</td></tr>
<tr>
<td>[[user-tehshrike.md|TehShrike]]
</td>
<td>Can add, remove, and edit keywords
</td></tr>
<tr>
<td>[[user-void.md|Void]]
</td>
<td>Can add, remove, and edit keywords, as well as add entirely new commands and modify existing ones
</td></tr></table>

## <span class="mw-headline" id="Playerstats"> Playerstats </span>

Retrieve statistics of a player.

<pre>!? Nickname</pre>

Do remember that FS nicks are case sensitive.

Thanks to Sid, who provides the [[api.md|API]].

## <span class="mw-headline" id="Wiki_.26_Google_Search"> Wiki &amp; Google Search </span>

You can search the wiki and google with IRCbot Shapeform.

<pre>!wiki searchkey1 (searchkey2)
!google searchkey1 (searchkey2)
</pre>

For example:

<pre>!wiki combat
!wiki line of sight
!google frozen synapse
</pre>

Another way to search the wiki, also inside of sentences (with some minor flaws, see discussion):

<pre>Have a look at [[Line of Sight]], my friend!</pre>

## <span class="mw-headline" id="Last_Seen_.26_Spoke"> Last Seen &amp; Spoke </span>

You can ask Shapeform when a user was last seen in the channel or when he last spoke.

<pre>!seen NICK
!lastspoke NICK
</pre>

For example:

<pre>!seen Omroth
!lastspoke Mr_K
</pre>

## <span class="mw-headline" id="Murphy.27s_Laws"> Murphy's Laws </span>

Whenever someone mentions the keywords below, a random quote from Murphy's Laws will be sent to the channel.

<pre>murphys law
murphy's law
</pre>

## <span class="mw-headline" id="Voting"> Voting </span>

The syntax is: "!vote &lt;time&gt;|&lt;topic&gt;|&lt;answers&gt;" (separated by "|"). 

The different possible answers are separeted by ":".

The time is given in the following way:
xxm: xx minutes; xxh: xx hours. No mixing of minutes and hours. 

"12m" for 12 minutes, "24h" for 24 hours. "24h 30m" is not allowed.

<pre>!vote 10m|What's your favourite color?|have none:green:red:yellow:blue</pre>

Show information about current / last vote

<pre>!vote</pre>

Help

<pre>/msg &lt;botnick&gt; vhelp</pre>

Give your vote

<pre>/msg &lt;botnick&gt; vote &lt;answer&gt;</pre>

The vote-starter can end the vote before time's out

<pre>!endvote</pre>

## <span class="mw-headline" id="Keywords"> Keywords </span>

Below is a list of keywords you can ask IRCbot Shapeform in #mode7games.

The format for keywords is this:

<pre>?? KEYWORD
?? KEYWORD &gt; Nick (sends definition via query)
?? KEYWORD @ Nick (sends definition to channel and highlights nick)
</pre>

For example:

<pre>?? faq
?? combat &gt; Void
?? rocket @ Meneth
</pre>

### <span class="mw-headline" id="List_of_Keywords"> List of Keywords </span>

<table cellpadding="5" cellspacing="0" border="1">
<tr>
<td>2v2
</td>
<td>"Omroth: yes 2v2 and FFA are planned but not particularly soon."
</td></tr>
<tr>
<td>2weeks
</td>
<td>It'll take 2 weeks for a game to finish if one party abandons it. Whoever hasn't primed loses, unless it's still turn 1. If it's turn 1, it's a draw.
</td></tr>
<tr>
<td>42
</td>
<td>The Answer to the Ultimate Question of Life, the Universe, and Everything.
</td></tr>
<tr>
<td>7zip
</td>
<td>7-zip is one of the best compression tools on the market, and is free. [http://www.7-zip.org/](http://www.7-zip.org/)
</td></tr>
<tr>
<td>??
</td>
<td>Usage: "?? KEYWORD (@ (highlight in channel) or &gt; (query) NICK)"
</td></tr>
<tr>
<td>adam_0
</td>
<td>Wiki-contributor.
</td></tr>
<tr>
<td>aim
</td>
<td>FS Wiki/Aim: [http://fs.error420.com/wiki/Aim](http://fs.error420.com/wiki/Aim)
</td></tr>
<tr>
<td>ballmer
</td>
<td>Rigorous testing by thynnmas shows no indication of Ballmer Peak in FS skills.
</td></tr>
<tr>
<td>ballmer_peak
</td>
<td>Rigorous testing by thynnmas shows no indication of Ballmer Peak in FS skills.
</td></tr>
<tr>
<td>ballmerpeak
</td>
<td>Rigorous testing by thynnmas shows no indication of Ballmer Peak in FS skills.
</td></tr>
<tr>
<td>bid
</td>
<td>FS Wiki/Bidding: [http://fs.error420.com/wiki/Bidding](http://fs.error420.com/wiki/Bidding)
</td></tr>
<tr>
<td>bidding
</td>
<td>FS Wiki/Bidding: [http://fs.error420.com/wiki/Bidding](http://fs.error420.com/wiki/Bidding)
</td></tr>
<tr>
<td>blog
</td>
<td>FS blog: [http://www.mode7games.com/blog/](http://www.mode7games.com/blog/)
</td></tr>
<tr>
<td>blue
</td>
<td>What else would FS be? Pink?
</td></tr>
<tr>
<td>bot
</td>
<td>I'm a bot, but thanks for thanking me anyway.
</td></tr>
<tr>
<td>bug
</td>
<td>Post your bugs here: [http://forums.mode7games.com/viewforum.php?f=25](http://forums.mode7games.com/viewforum.php?f=25)
</td></tr>
<tr>
<td>bugs
</td>
<td>Post your bugs here: [http://forums.mode7games.com/viewforum.php?f=25](http://forums.mode7games.com/viewforum.php?f=25)
</td></tr>
<tr>
<td>buyit
</td>
<td>Just buy the game, it's worth your money.
</td></tr>
<tr>
<td>cake
</td>
<td>The cake is a lie.
</td></tr>
<tr>
<td>campaign
</td>
<td>FS Wiki/Campaign: [http://fs.error420.com/wiki/Campaign](http://fs.error420.com/wiki/Campaign)
</td></tr>
<tr>
<td>charge
</td>
<td>FS Wiki/Charge: [http://fs.error420.com/wiki/Charge](http://fs.error420.com/wiki/Charge)
</td></tr>
<tr>
<td>chatmove
</td>
<td>To move the chat window, open [[console.md|console]] (` or ^) and write: "Chanwindow.canMove = 1;" | for a permanent solution and resizing the window: [http://j.mp/iYa6Jy](http://j.mp/iYa6Jy)
</td></tr>
<tr>
<td>check
</td>
<td>The check command instructs a unit to momentarily slow down and look in a direction. More info: [http://fs.error420.com/wiki/Check](http://fs.error420.com/wiki/Check)
</td></tr>
<tr>
<td>chess
</td>
<td>Frozen Synapse is basically chess with guns.
</td></tr>
<tr>
<td>combat
</td>
<td>You want to be behind cover, and you want to see them first. Also, being drunk beats anything else. More wisdom at [http://fs.error420.com/wiki/Principles_of_Combat](http://fs.error420.com/wiki/Principles_of_Combat)
</td></tr>
<tr>
<td>combatjuan
</td>
<td>He's too smart for his own good.  Having an affair with TehShrike.  Wiki contributor.
</td></tr>
<tr>
<td>command
</td>
<td>FS Wiki/Orders: [http://fs.error420.com/wiki/Orders](http://fs.error420.com/wiki/Orders)
</td></tr>
<tr>
<td>commands
</td>
<td>FS Wiki/Orders: [http://fs.error420.com/wiki/Orders](http://fs.error420.com/wiki/Orders)
</td></tr>
<tr>
<td>community
</td>
<td> Twitter: [http://twitter.com/mode7games](http://twitter.com/mode7games)  [http://twitter.com/ianhardingham](http://twitter.com/ianhardingham) | Forums: [http://forums.mode7games.com/index.php](http://forums.mode7games.com/index.php) | Facebook: [http://www.facebook.com/pages/Visiting-the-Village/75735991802?ref=ts](http://www.facebook.com/pages/Visiting-the-Village/75735991802?ref=ts)
</td></tr>
<tr>
<td>connect
</td>
<td>If you can't connect to the server, try restarting the game.
</td></tr>
<tr>
<td>connection
</td>
<td>If you can't connect to the server, try restarting the game.
</td></tr>
<tr>
<td>consolidation
</td>
<td>The reason you cannot create games anymore is because this has now been limited to UK1 only. This is part of the move back to only one server. Offical post on this: [http://www.mode7games.com/blog/2011/07/22/new-games-disabled-on-older-servers/](http://www.mode7games.com/blog/2011/07/22/new-games-disabled-on-older-servers/)
</td></tr>
<tr>
<td>continue
</td>
<td>FS Wiki/Continue on Sight: [http://fs.error420.com/wiki/Continue_on_Sight](http://fs.error420.com/wiki/Continue_on_Sight)
</td></tr>
<tr>
<td>cookie
</td>
<td>Gives Void a cookie.
</td></tr>
<tr>
<td>cos
</td>
<td>FS Wiki/Continue on Sight: [http://fs.error420.com/wiki/Continue_on_Sight](http://fs.error420.com/wiki/Continue_on_Sight)
</td></tr>
<tr>
<td>cover
</td>
<td>FS Wiki/Cover: [http://fs.error420.com/wiki/Cover](http://fs.error420.com/wiki/Cover)
</td></tr>
<tr>
<td>crouch
</td>
<td>FS Wiki/Crouch: [http://fs.error420.com/wiki/Duck](http://fs.error420.com/wiki/Duck)
</td></tr>
<tr>
<td>custom
</td>
<td>To make a custom match, open up the tool to challenge another player, then click Advanced Setup. This will let you do things like change the layout of a level, add units and NPCs, and change the turn limit. More info: [http://fs.error420.com/wiki/Advanced_Setup](http://fs.error420.com/wiki/Advanced_Setup)
</td></tr>
<tr>
<td>cyron
</td>
<td>Don't ask him hard questions. Wiki-contributor.
</td></tr>
<tr>
<td>dark
</td>
<td>FS Wiki/Dark Mode: [http://fs.error420.com/wiki/Dark_Mode](http://fs.error420.com/wiki/Dark_Mode)
</td></tr>
<tr>
<td>devgaming
</td>
<td>DevGaming League: [http://devgaming.net/tournaments.php?c=12](http://devgaming.net/tournaments.php?c=12)
</td></tr>
<tr>
<td>dgl
</td>
<td>DevGaming League: [http://devgaming.net/tournaments.php?c=12](http://devgaming.net/tournaments.php?c=12)
</td></tr>
<tr>
<td>dgl1
</td>
<td>DevGaming League #1: [http://devgaming.net/tournaments.php?do=view&amp;id=2](http://devgaming.net/tournaments.php?do=view&amp;id=2)
</td></tr>
<tr>
<td>dgl2
</td>
<td>DevGaming League #2: [http://devgaming.net/tournaments.php?do=view&amp;id=8](http://devgaming.net/tournaments.php?do=view&amp;id=8)
</td></tr>
<tr>
<td>dgl3
</td>
<td>DevGaming League #3: [http://devgaming.net/tournaments.php?do=view&amp;id=9](http://devgaming.net/tournaments.php?do=view&amp;id=9)
</td></tr>
<tr>
<td>dgl4
</td>
<td>DevGaming League #4: [http://devgaming.net/tournaments.php?do=view&amp;id=10](http://devgaming.net/tournaments.php?do=view&amp;id=10)
</td></tr>
<tr>
<td>dgl5
</td>
<td>DevGaming League #5: [http://devgaming.net/tournaments.php?do=view&amp;id=12](http://devgaming.net/tournaments.php?do=view&amp;id=12)
</td></tr>
<tr>
<td>dgl6
</td>
<td>DevGaming League #6: [http://devgaming.net/tournaments.php?do=view&amp;id=13](http://devgaming.net/tournaments.php?do=view&amp;id=13)
</td></tr>
<tr>
<td>dgl7
</td>
<td>DevGaming League #7: [http://devgaming.net/tournaments.php?do=view&amp;id=14](http://devgaming.net/tournaments.php?do=view&amp;id=14)
</td></tr>
<tr>
<td>dgl8
</td>
<td>DevGaming League #8: [http://devgaming.net/tournaments.php?do=view&amp;id=15](http://devgaming.net/tournaments.php?do=view&amp;id=15)
</td></tr>
<tr>
<td>dgl9
</td>
<td>DevGaming League #8: [http://devgaming.net/tournaments.php?do=view&amp;id=16](http://devgaming.net/tournaments.php?do=view&amp;id=16)
</td></tr>
<tr>
<td>disputed
</td>
<td>FS/Wiki Disputed [http://fs.error420.com/wiki/Disputed](http://fs.error420.com/wiki/Disputed)
</td></tr>
<tr>
<td>distraction
</td>
<td>FS Wiki/Distraction: [http://fs.error420.com/wiki/Distraction](http://fs.error420.com/wiki/Distraction)
</td></tr>
<tr>
<td>draz
</td>
<td>Just some guy. Can add definitions to Shapeform.
</td></tr>
<tr>
<td>duck
</td>
<td>FS Wiki/Duck: [http://fs.error420.com/wiki/Duck](http://fs.error420.com/wiki/Duck)
</td></tr>
<tr>
<td>dupe
</td>
<td>FS Wiki/Duplicate: [http://fs.error420.com/wiki/Duplicate](http://fs.error420.com/wiki/Duplicate)
</td></tr>
<tr>
<td>duplicate
</td>
<td>FS Wiki/Duplicate: [http://fs.error420.com/wiki/Duplicate](http://fs.error420.com/wiki/Duplicate)
</td></tr>
<tr>
<td>editor
</td>
<td>open [[console.md|console]] (` or ^) and put: loadeditor(); More info: [http://fs.error420.com/wiki/Level_Editor](http://fs.error420.com/wiki/Level_Editor)
</td></tr>
<tr>
<td>ext
</td>
<td>FS Wiki/Extermination: [http://fs.error420.com/wiki/Extermination](http://fs.error420.com/wiki/Extermination)
</td></tr>
<tr>
<td>extermination
</td>
<td>FS Wiki/Extermination: [http://fs.error420.com/wiki/Extermination](http://fs.error420.com/wiki/Extermination)
</td></tr>
<tr>
<td>facebook
</td>
<td>FS' Facebook page: [http://www.facebook.com/pages/Visiting-the-Village/75735991802?ref=ts](http://www.facebook.com/pages/Visiting-the-Village/75735991802?ref=ts)
</td></tr>
<tr>
<td>fans
</td>
<td>I laugh at your silly fan-wars.
</td></tr>
<tr>
<td>faq
</td>
<td>FS FAQ: [http://www.frozensynapse.com/features.html#FAQ](http://www.frozensynapse.com/features.html#FAQ)
</td></tr>
<tr>
<td>feed
</td>
<td>I feed on your hate.
</td></tr>
<tr>
<td>ffa
</td>
<td>"Omroth: yes 2v2 and FFA are planned but not particularly soon"
</td></tr>
<tr>
<td>fight
</td>
<td>You want to be behind cover, and you want to see them first. More wisdom at [http://fs.error420.com/wiki/Principles_of_Combat](http://fs.error420.com/wiki/Principles_of_Combat)
</td></tr>
<tr>
<td>focus
</td>
<td>FS Wiki Ignore/Focus: [http://fs.error420.com/wiki/Ignore/Focus](http://fs.error420.com/wiki/Ignore/Focus)
</td></tr>
<tr>
<td>forum
</td>
<td>FS forum: [http://forums.mode7games.com/index.php](http://forums.mode7games.com/index.php)
</td></tr>
<tr>
<td>forums
</td>
<td>FS forum: [http://forums.mode7games.com/index.php](http://forums.mode7games.com/index.php)
</td></tr>
<tr>
<td>fov
</td>
<td>FS Wiki/Line of Sight [http://fs.error420.com/wiki/Line_of_Sight](http://fs.error420.com/wiki/Line_of_Sight)
</td></tr>
<tr>
<td>fps
</td>
<td>Type "metrics(fps);" into the [[console.md|console]] to see your framerate. Fuck knows how to turn it off though apart from restarting your game.
</td></tr>
<tr>
<td>freecopy
</td>
<td>FS Freekey: [http://www.frozensynapse.com/features.html#freekey](http://www.frozensynapse.com/features.html#freekey)
</td></tr>
<tr>
<td>freekey
</td>
<td>FS Freekey: [http://www.frozensynapse.com/features.html#freekey](http://www.frozensynapse.com/features.html#freekey)
</td></tr>
<tr>
<td>friend
</td>
<td>FS Freekey: [http://www.frozensynapse.com/features.html#freekey](http://www.frozensynapse.com/features.html#freekey)
</td></tr>
<tr>
<td>friendcopy
</td>
<td>FS Freekey: [http://www.frozensynapse.com/features.html#freekey](http://www.frozensynapse.com/features.html#freekey)
</td></tr>
<tr>
<td>fs
</td>
<td>Better than French hookers!
</td></tr>
<tr>
<td>fsl
</td>
<td>FS Wiki/Frozen Synapse Live: [http://fs.error420.com/wiki/Frozen_Synapse_Live](http://fs.error420.com/wiki/Frozen_Synapse_Live)
</td></tr>
<tr>
<td>fslive
</td>
<td>FS Wiki/Frozen Synapse Live: [http://fs.error420.com/wiki/Frozen_Synapse_Live](http://fs.error420.com/wiki/Frozen_Synapse_Live)
</td></tr>
<tr>
<td>game_modes
</td>
<td>FS Wiki/Game Modes: [http://fs.error420.com/wiki/Game_modes](http://fs.error420.com/wiki/Game_modes) Videos: [http://www.frozensynapse.com/tutorials.html](http://www.frozensynapse.com/tutorials.html)
</td></tr>
<tr>
<td>gameid
</td>
<td>FS Wiki/Game ID: [http://fs.error420.com/wiki/Game_ID](http://fs.error420.com/wiki/Game_ID)
</td></tr>
<tr>
<td>gift
</td>
<td>FS Freekey: [http://www.frozensynapse.com/features.html#freekey](http://www.frozensynapse.com/features.html#freekey)
</td></tr>
<tr>
<td>girl
</td>
<td>Just go look at some porn.
</td></tr>
<tr>
<td>goateh
</td>
<td>Wiki-contributor.
</td></tr>
<tr>
<td>grats
</td>
<td>You're really awesome.
</td></tr>
<tr>
<td>gratz
</td>
<td>Congratulations with your achievement!
</td></tr>
<tr>
<td>grenade
</td>
<td>FS Wiki/Grenade Launcher: [http://fs.error420.com/wiki/Grenade_Launcher](http://fs.error420.com/wiki/Grenade_Launcher)
</td></tr>
<tr>
<td>grenades
</td>
<td>FS Wiki/Grenade Launcher: [http://fs.error420.com/wiki/Grenade_Launcher](http://fs.error420.com/wiki/Grenade_Launcher)
</td></tr>
<tr>
<td>hate
</td>
<td>I feed on your hate.
</td></tr>
<tr>
<td>hd
</td>
<td>IRC guy of the century.
</td></tr>
<tr>
<td>hdfisise
</td>
<td>Also kind of sounds like "HD fart gnome" in Norwegian.
</td></tr>
<tr>
<td>hdfisise
</td>
<td>IRC guy of the century.
</td></tr>
<tr>
<td>hello
</td>
<td>Good &lt;insert time of day&gt;!
</td></tr>
<tr>
<td>help
</td>
<td> FAQ: [http://j.mp/kzJ49i](http://j.mp/kzJ49i) | Forums: [http://j.mp/igef0P](http://j.mp/igef0P) | If you have a question, just ask it here.
</td></tr>
<tr>
<td>helpus
</td>
<td>Come quickly, Omroth, your presence is requested!
</td></tr>
<tr>
<td>hey
</td>
<td>Good &lt;insert time of day&gt;!
</td></tr>
<tr>
<td>hi
</td>
<td>Good &lt;insert time of day&gt;!
</td></tr>
<tr>
<td>hostage
</td>
<td>FS Wiki/Hostage: [http://fs.error420.com/wiki/Hostage](http://fs.error420.com/wiki/Hostage)
</td></tr>
<tr>
<td>hotkeys
</td>
<td>FS Wiki/Shortcuts: [http://fs.error420.com/wiki/Shortcuts](http://fs.error420.com/wiki/Shortcuts)
</td></tr>
<tr>
<td>id
</td>
<td>FS Wiki/Game ID: [http://fs.error420.com/wiki/Game_ID](http://fs.error420.com/wiki/Game_ID)
</td></tr>
<tr>
<td>ignore
</td>
<td>FS Wiki Ignore/Focus: [http://fs.error420.com/wiki/Ignore/Focus](http://fs.error420.com/wiki/Ignore/Focus)
</td></tr>
<tr>
<td>illuminati
</td>
<td>[http://fs.error420.com/wiki/IRCbot_Shapeform#Maintainers](http://fs.error420.com/wiki/IRCbot_Shapeform#Maintainers)
</td></tr>
<tr>
<td>irc
</td>
<td> Channel: #mode7games | FS Wiki/IRC: [http://fs.error420.com/wiki/IRC](http://fs.error420.com/wiki/IRC)
</td></tr>
<tr>
<td>ircstats
</td>
<td>[http://shapeform.dyndns.org/](http://shapeform.dyndns.org/)
</td></tr>
<tr>
<td>kevyg
</td>
<td>Has to think. Wiki-contributor.
</td></tr>
<tr>
<td>key
</td>
<td>FS Freekey: [http://www.frozensynapse.com/features.html#freekey](http://www.frozensynapse.com/features.html#freekey)
</td></tr>
<tr>
<td>keys
</td>
<td>FS Freekey: [http://www.frozensynapse.com/features.html#freekey](http://www.frozensynapse.com/features.html#freekey)
</td></tr>
<tr>
<td>kuroyuri
</td>
<td>Lover of all things pink and pretty! Wiki-contributor.
</td></tr>
<tr>
<td>layer
</td>
<td>FS Wiki/Layers: [http://fs.error420.com/wiki/Layer](http://fs.error420.com/wiki/Layer)
</td></tr>
<tr>
<td>layers
</td>
<td>FS Wiki/Layers: [http://fs.error420.com/wiki/Layer](http://fs.error420.com/wiki/Layer)
</td></tr>
<tr>
<td>league
</td>
<td>Unofficial FSLeague: [http://frozensynapseleague.com/](http://frozensynapseleague.com/)
</td></tr>
<tr>
<td>level
</td>
<td>It's a number that goes up as you play more games (winning games will make it go up faster)
</td></tr>
<tr>
<td>light
</td>
<td>FS Wiki/Light Mode: [http://fs.error420.com/wiki/Light_Mode](http://fs.error420.com/wiki/Light_Mode)
</td></tr>
<tr>
<td>live
</td>
<td>FS Wiki/Frozen Synapse Live: [http://fs.error420.com/wiki/Frozen_Synapse_Live](http://fs.error420.com/wiki/Frozen_Synapse_Live)
</td></tr>
<tr>
<td>livestreram
</td>
<td>FS Wiki/Frozen Synapse Live: [http://fs.error420.com/wiki/Frozen_Synapse_Live](http://fs.error420.com/wiki/Frozen_Synapse_Live)
</td></tr>
<tr>
<td>los
</td>
<td>FS Wiki/Line of Sight: [http://fs.error420.com/wiki/LoS](http://fs.error420.com/wiki/LoS)
</td></tr>
<tr>
<td>love
</td>
<td>I love this game.
</td></tr>
<tr>
<td>luck
</td>
<td>There is no such thing as luck, only bad predictions.
</td></tr>
<tr>
<td>mac
</td>
<td>User files on OS X: user dir/Library/Application Support/Frozen Synapse
</td></tr>
<tr>
<td>machinegun
</td>
<td>FS Wiki/Machine Gun: [http://fs.error420.com/wiki/Machine_gun](http://fs.error420.com/wiki/Machine_gun)
</td></tr>
<tr>
<td>manual
</td>
<td>In-game manual: [http://www.mode7games.com/inGameHelp.txt](http://www.mode7games.com/inGameHelp.txt) Wiki: [http://fs.error420.com/wiki/Main_Page](http://fs.error420.com/wiki/Main_Page) Technical issues FAQ: [http://www.frozensynapse.com/features.html#FAQ](http://www.frozensynapse.com/features.html#FAQ)
</td></tr>
<tr>
<td>matchmaking
</td>
<td>FS Wiki/Matchmaking: [http://fs.error420.com/wiki/Matchmaking](http://fs.error420.com/wiki/Matchmaking)
</td></tr>
<tr>
<td>meh
</td>
<td>Deal with it. It's being worked on.
</td></tr>
<tr>
<td>meneth
</td>
<td>Random helpful nerd. Can add definitions to Shapeform. Admin of the FS side of DevGaming. Wiki-administrator. Occasional FSLive helper.
</td></tr>
<tr>
<td>merge
</td>
<td>The reason you cannot create games anymore is because this has now been limited to UK1 only. This is part of the move back to only one server. Offical post on this: [http://www.mode7games.com/blog/2011/07/22/new-games-disabled-on-older-servers/](http://www.mode7games.com/blog/2011/07/22/new-games-disabled-on-older-servers/)
</td></tr>
<tr>
<td>metacritic
</td>
<td>FS Metacritic page: [http://www.metacritic.com/game/pc/frozen-synapse](http://www.metacritic.com/game/pc/frozen-synapse)
</td></tr>
<tr>
<td>metascore
</td>
<td>FS Metacritic page: [http://www.metacritic.com/game/pc/frozen-synapse](http://www.metacritic.com/game/pc/frozen-synapse)
</td></tr>
<tr>
<td>mg
</td>
<td>S Wiki/Machine Gun: [http://fs.error420.com/wiki/Machine_Gun](http://fs.error420.com/wiki/Machine_Gun)
</td></tr>
<tr>
<td>mode7
</td>
<td>Mode 7 Games are the creators of Frozen Synapse. Give them your money.
</td></tr>
<tr>
<td>mode7games
</td>
<td>Mode 7 Games are the creators of Frozen Synapse. Give them your money.
</td></tr>
<tr>
<td>modes
</td>
<td>FS Wiki/Game Modes: [http://fs.error420.com/wiki/Game_modes](http://fs.error420.com/wiki/Game_modes) Videos: [http://www.frozensynapse.com/tutorials.html](http://www.frozensynapse.com/tutorials.html)
</td></tr>
<tr>
<td>modesuggestions
</td>
<td>Suggested game modes: [http://fs.error420.com/wiki/Suggested_Modes](http://fs.error420.com/wiki/Suggested_Modes)
</td></tr>
<tr>
<td>monitor
</td>
<td>You can never have too many monitors.
</td></tr>
<tr>
<td>monitors
</td>
<td>You can never have too many monitors.
</td></tr>
<tr>
<td>more
</td>
<td>We need more matches!
</td></tr>
<tr>
<td>move
</td>
<td>FS Wiki/Move: [http://fs.error420.com/wiki/Move](http://fs.error420.com/wiki/Move)
</td></tr>
<tr>
<td>movechat
</td>
<td>To move the chat window, open [[console.md|console]] (` or ^) and write: "Chanwindow.canMove = 1;" | for a permanent solution and resizing the window: [http://j.mp/iYa6Jy](http://j.mp/iYa6Jy)
</td></tr>
<tr>
<td>movement
</td>
<td>FS Wiki/Move: [http://fs.error420.com/wiki/Move](http://fs.error420.com/wiki/Move)
</td></tr>
<tr>
<td>moving
</td>
<td>FS Wiki/Move: [http://fs.error420.com/wiki/Move](http://fs.error420.com/wiki/Move)
</td></tr>
<tr>
<td>mr_k
</td>
<td>If he sings on the stream I would make a better description
</td></tr>
<tr>
<td>msg
</td>
<td>To talk directly to a person here, just write /msg &lt;name&gt; &lt;message&gt;
</td></tr>
<tr>
<td>music
</td>
<td>Here, listen to this: [http://www.youtube.com/watch?v=Uz1ftZ5e3hQ](http://www.youtube.com/watch?v=Uz1ftZ5e3hQ)
</td></tr>
<tr>
<td>needed
</td>
<td>Work needed on the wiki: [http://fs.error420.com/wiki/Work_Needed](http://fs.error420.com/wiki/Work_Needed) Doing one of these tasks will also get you a custom definition for your nick in Shapeform.
</td></tr>
<tr>
<td>night
</td>
<td>Good night. Sleep well.
</td></tr>
<tr>
<td>no
</td>
<td>No.
</td></tr>
<tr>
<td>offline
</td>
<td>To play offline, and thus not get any challenges, press the button that says "Play Offline" on the log-in screen.
</td></tr>
<tr>
<td>ohmygod
</td>
<td>[http://www.youtube.com/watch?v=HyophYBP_w4](http://www.youtube.com/watch?v=HyophYBP_w4)
</td></tr>
<tr>
<td>omroth
</td>
<td>He's the guy who made FS, and he deserves your love.
</td></tr>
<tr>
<td>order
</td>
<td>FS Wiki/Orders: [http://fs.error420.com/wiki/Orders](http://fs.error420.com/wiki/Orders)
</td></tr>
<tr>
<td>orders
</td>
<td>FS Wiki/Orders: [http://fs.error420.com/wiki/Orders](http://fs.error420.com/wiki/Orders)
</td></tr>
<tr>
<td>pan
</td>
<td>To pan the camera hold down the right mouse-button and drag or use the arrow keys.
</td></tr>
<tr>
<td>panning
</td>
<td>To pan the camera hold down the right mouse-button and drag or use the arrow keys.
</td></tr>
<tr>
<td>password
</td>
<td>Go to this page if you wish to change your FS password: [http://www.mode7games.com/support/changePassword.php](http://www.mode7games.com/support/changePassword.php)
</td></tr>
<tr>
<td>pilen
</td>
<td>Pilen is mean.
</td></tr>
<tr>
<td>piracy
</td>
<td>Just buy the game, it's worth the money.
</td></tr>
<tr>
<td>plan
</td>
<td>FS Wiki/Making a plan: [http://fs.error420.com/wiki/Making_a_plan](http://fs.error420.com/wiki/Making_a_plan)
</td></tr>
<tr>
<td>planned
</td>
<td>Planned Features: [http://fs.error420.com/wiki/Planned_Features](http://fs.error420.com/wiki/Planned_Features)
</td></tr>
<tr>
<td>please
</td>
<td>Skip the pleasantries and just state your question.
</td></tr>
<tr>
<td>pohaenix
</td>
<td>Sex is not the answer. Sex is the question. 'Yes' is the answer. Wiki-contributor.
</td></tr>
<tr>
<td>possibly
</td>
<td>Nothing could possibly go wrong... That's the first thing that has ever gone wrong
</td></tr>
<tr>
<td>puff
</td>
<td>puff, pass
</td></tr>
<tr>
<td>pw
</td>
<td>Go to this page if you wish to change your FS password: [http://www.mode7games.com/support/changePassword.php](http://www.mode7games.com/support/changePassword.php)
</td></tr>
<tr>
<td>questica
</td>
<td>He wanted me to put "awesomeness" here.
</td></tr>
<tr>
<td>rank
</td>
<td>FS Wiki/Rank: [http://fs.error420.com/wiki/Rank](http://fs.error420.com/wiki/Rank)
</td></tr>
<tr>
<td>ranking
</td>
<td>FS Wiki/Rank: [http://fs.error420.com/wiki/Rank](http://fs.error420.com/wiki/Rank)
</td></tr>
<tr>
<td>rathshock
</td>
<td>Some guy. Wiki-contributor.
</td></tr>
<tr>
<td>replay
</td>
<td>To view a match without any pauses, open [[console.md|console]] (` or ^) and write "testSnapcam();"
</td></tr>
<tr>
<td>req
</td>
<td>FS System Requirements: [http://www.frozensynapse.com/features.html#sysReqs](http://www.frozensynapse.com/features.html#sysReqs)
</td></tr>
<tr>
<td>reqs
</td>
<td>FS System Requirements: [http://www.frozensynapse.com/features.html#sysReqs](http://www.frozensynapse.com/features.html#sysReqs)
</td></tr>
<tr>
<td>requirements
</td>
<td>FS System Requirements: [http://www.frozensynapse.com/features.html#sysReqs](http://www.frozensynapse.com/features.html#sysReqs)
</td></tr>
<tr>
<td>resign
</td>
<td>You are encouraged to minimize your losses, there is no surrender
</td></tr>
<tr>
<td>restart
</td>
<td>Have you tried turning it off and on again?
</td></tr>
<tr>
<td>review
</td>
<td>To view a match without any pauses, open [[console.md|console]] (` or ^) and write "testSnapcam();"
</td></tr>
<tr>
<td>rigel
</td>
<td>One of the first to beat the campaign.
</td></tr>
<tr>
<td>rocket
</td>
<td>Rockets cannot directly hit units. If the rocket launcher is standing, the rocket will fly over half-height objects, but if he's crouching the rocket can impact half-height objects.
</td></tr>
<tr>
<td>rockets
</td>
<td>Rockets cannot directly hit units. If the rocket launcher is standing, the rocket will fly over half-height objects, but if he's crouching the rocket can impact half-height objects.
</td></tr>
<tr>
<td>score
</td>
<td>Scoring is done in respect to who the server believes is Player 1. So if it says - 50 points when you win it means player 1 got -50 and you recieved +50points. More info: [http://fs.error420.com/wiki/Scoring](http://fs.error420.com/wiki/Scoring)
</td></tr>
<tr>
<td>scoregraphic
</td>
<td>Is still trying to defend that bloody lift on second floor. Wiki-contributor.
</td></tr>
<tr>
<td>scoring
</td>
<td>Scoring is done in respect to who the server believes is Player 1. So if it says - 50 points when you win it means player 1 got -50 and you recieved +50points. More info: [http://fs.error420.com/wiki/Scoring](http://fs.error420.com/wiki/Scoring)
</td></tr>
<tr>
<td>secure
</td>
<td>FS Wiki/Secure: [http://fs.error420.com/wiki/Secure](http://fs.error420.com/wiki/Secure)
</td></tr>
<tr>
<td>server
</td>
<td>The reason you cannot create games anymore is because this has now been limited to UK1 only. This is part of the move back to only one server. Offical post on this: [http://www.mode7games.com/blog/2011/07/22/new-games-disabled-on-older-servers/](http://www.mode7games.com/blog/2011/07/22/new-games-disabled-on-older-servers/)
</td></tr>
<tr>
<td>sg
</td>
<td>FS Wiki/Shotgun: [http://fs.error420.com/wiki/Shotgun](http://fs.error420.com/wiki/Shotgun)
</td></tr>
<tr>
<td>shades
</td>
<td>Some guy who spams me too much.
</td></tr>
<tr>
<td>shapeform
</td>
<td>FS Wiki/IRCbot Shapeform: [http://fs.error420.com/wiki/IRCbot_Shapeform](http://fs.error420.com/wiki/IRCbot_Shapeform)
</td></tr>
<tr>
<td>shapeform
</td>
<td>Shapeform is female: [http://namtz.org/fs/shapeform.jpg](http://namtz.org/fs/shapeform.jpg)
</td></tr>
<tr>
<td>sharding
</td>
<td>The server sharding is only a temporary stop-gap measure.
</td></tr>
<tr>
<td>shortcuts
</td>
<td>FS Wiki/Shortcuts: [http://fs.error420.com/wiki/Shortcuts](http://fs.error420.com/wiki/Shortcuts)
</td></tr>
<tr>
<td>shotgun
</td>
<td>FS Wiki/Shotgun: [http://fs.error420.com/wiki/Shotgun](http://fs.error420.com/wiki/Shotgun)
</td></tr>
<tr>
<td>sid
</td>
<td>The creator of the API and the match history extraction script.
</td></tr>
<tr>
<td>sight
</td>
<td>FS Wiki/Line of Sight: [http://fs.error420.com/wiki/Line_of_Sight](http://fs.error420.com/wiki/Line_of_Sight)
</td></tr>
<tr>
<td>silly
</td>
<td>Stop that. It's silly!
</td></tr>
<tr>
<td>sinwrath
</td>
<td>His philosophy is "fuck you".
</td></tr>
<tr>
<td>sleep
</td>
<td>Can't sleep now, I have to do well on the FS rankings.
</td></tr>
<tr>
<td>sniper
</td>
<td>FS Wiki/Sniper: [http://fs.error420.com/wiki/Sniper](http://fs.error420.com/wiki/Sniper)
</td></tr>
<tr>
<td>someonetoloveme
</td>
<td>No one loves you.
</td></tr>
<tr>
<td>soundtrack
</td>
<td>If you didn't buy the soundtrack edition and now want the soundtrack, you'll have to wait for the soundtrack to be released separately which the devs have stated will happen soon. Also: [http://www.frozensynapse.com/features.html#soundtrack](http://www.frozensynapse.com/features.html#soundtrack)
</td></tr>
<tr>
<td>space
</td>
<td>[http://www.spaaaaaaaaaaaaaaaaaaaaaaaccee.com/](http://www.spaaaaaaaaaaaaaaaaaaaaaaaccee.com/)
</td></tr>
<tr>
<td>split
</td>
<td>The server sharding is only a temporary stop-gap measure. Stats will be synced soon.
</td></tr>
<tr>
<td>spluuga
</td>
<td>His only achievement of note is thinking he got eliminated.
</td></tr>
<tr>
<td>stand
</td>
<td>FS Wiki/Stand: [http://fs.error420.com/wiki/Stand](http://fs.error420.com/wiki/Stand)
</td></tr>
<tr>
<td>started
</td>
<td>FS Wiki/Getting started: [http://fs.error420.com/wiki/Getting_Started](http://fs.error420.com/wiki/Getting_Started)
</td></tr>
<tr>
<td>stop
</td>
<td>Stop that. It's silly!
</td></tr>
<tr>
<td>suggest
</td>
<td>Post your suggestions here: [http://forums.mode7games.com/viewtopic.php?f=20&amp;t=1813](http://forums.mode7games.com/viewtopic.php?f=20&amp;t=1813)
</td></tr>
<tr>
<td>suggestion
</td>
<td>Post your suggestions here: [http://forums.mode7games.com/viewtopic.php?f=20&amp;t=1813](http://forums.mode7games.com/viewtopic.php?f=20&amp;t=1813)
</td></tr>
<tr>
<td>suggestions
</td>
<td>Post your suggestions here: [http://forums.mode7games.com/viewtopic.php?f=20&amp;t=1813](http://forums.mode7games.com/viewtopic.php?f=20&amp;t=1813)
</td></tr>
<tr>
<td>support
</td>
<td> E-mail: support@mode7games.com
</td></tr>
<tr>
<td>switch
</td>
<td>To switch servers, you currently have to restart the game.
</td></tr>
<tr>
<td>swuboo
</td>
<td>Likes being insulted, apparently.
</td></tr>
<tr>
<td>tehshrike
</td>
<td>He's probably right. Can add definitions to Shapeform.
</td></tr>
<tr>
<td>work
</td>
<td>Not actually working.
</td></tr>
<tr>
<td>thanks
</td>
<td>Why, thank you!
</td></tr>
<tr>
<td>theraven42
</td>
<td>Nevermore. Wiki-contributor.
</td></tr>
<tr>
<td>thynnmas
</td>
<td>Wiki-contributor. Up for a challenge.
</td></tr>
<tr>
<td>toolbox
</td>
<td>FS Wiki/Toolbox: [http://fs.error420.com/wiki/Toolbox](http://fs.error420.com/wiki/Toolbox)
</td></tr>
<tr>
<td>tournament
</td>
<td>DevGaming League: [http://devgaming.net/tournaments.php?c=12](http://devgaming.net/tournaments.php?c=12)
</td></tr>
<tr>
<td>tray
</td>
<td>Tray notification tool: [http://forums.mode7games.com/viewtopic.php?f=20&amp;t=1996](http://forums.mode7games.com/viewtopic.php?f=20&amp;t=1996)
</td></tr>
<tr>
<td>traynotification
</td>
<td>Tray notification tool: [http://forums.mode7games.com/viewtopic.php?f=20&amp;t=1996](http://forums.mode7games.com/viewtopic.php?f=20&amp;t=1996)
</td></tr>
<tr>
<td>troll2
</td>
<td>[http://www.youtube.com/watch?v=HyophYBP_w4](http://www.youtube.com/watch?v=HyophYBP_w4)
</td></tr>
<tr>
<td>turns
</td>
<td>The max number of turns in a match is indicated in the upper right corner underneath the player names.
</td></tr>
<tr>
<td>twitter
</td>
<td>Omroth's Twitter: [http://twitter.com/mode7games](http://twitter.com/mode7games) [http://twitter.com/ianhardingham](http://twitter.com/ianhardingham)
</td></tr>
<tr>
<td>tyyger
</td>
<td>Neither creative, nor witty. Wiki-contributor.
</td></tr>
<tr>
<td>ui
</td>
<td>FS Wiki/UI: [http://fs.error420.com/wiki/UI](http://fs.error420.com/wiki/UI)
</td></tr>
<tr>
<td>uneven
</td>
<td>Omroth: "Tellingly, often both players on a map will think they have the worse side." [http://www.mode7games.com/blog/2011/05/11/in-defense-of-uneven-sides/](http://www.mode7games.com/blog/2011/05/11/in-defense-of-uneven-sides/)
</td></tr>
<tr>
<td>unit
</td>
<td>FS Wiki/Units: [http://fs.error420.com/wiki/Unit_Types](http://fs.error420.com/wiki/Unit_Types)
</td></tr>
<tr>
<td>unitnumber
</td>
<td>The number next to an unit indicates which key to push to select it.
</td></tr>
<tr>
<td>units
</td>
<td>FS Wiki/Units: [http://fs.error420.com/wiki/Unit_Types](http://fs.error420.com/wiki/Unit_Types)
</td></tr>
<tr>
<td>upcoming
</td>
<td>Planned Features: [http://fs.error420.com/wiki/Planned_Features](http://fs.error420.com/wiki/Planned_Features)
</td></tr>
<tr>
<td>upload
</td>
<td>Upload page for the wiki: [http://fs.error420.com/wiki/Special:Upload](http://fs.error420.com/wiki/Special:Upload)
</td></tr>
<tr>
<td>view
</td>
<td>FS Wiki/Line of Sight [http://fs.error420.com/wiki/Line_of_Sight](http://fs.error420.com/wiki/Line_of_Sight)
</td></tr>
<tr>
<td>void
</td>
<td>The creator of me, Shapeform.
</td></tr>
<tr>
<td>wait
</td>
<td>FS Wiki/Wait: [http://fs.error420.com/wiki/Wait](http://fs.error420.com/wiki/Wait)
</td></tr>
<tr>
<td>waiting
</td>
<td>FS Wiki/Wait: [http://fs.error420.com/wiki/Wait](http://fs.error420.com/wiki/Wait)
</td></tr>
<tr>
<td>whowins
</td>
<td>If an extermination match reaches it's turnlimits, whoever killed the most enemies wins. He gets 10 points times the difference in remaining units.
</td></tr>
<tr>
<td>wiki
</td>
<td>FS Wiki: [http://fs.error420.com/wiki/Main_Page](http://fs.error420.com/wiki/Main_Page)
</td></tr>
<tr>
<td>window
</td>
<td>In windowed mode you cannot use max resolution, only one step below. This is due to limitations with the Torque engine. However, you can set the resolution to something higher, but lower than your native resolution, in frozen synapse/common/preferences/prefs.cs
</td></tr>
<tr>
<td>windowed
</td>
<td>In windowed mode you cannot use max resolution, only one step below. This is due to limitations with the Torque engine. However, you can set the resolution to something higher, but lower than your native resolution, in frozen synapse/common/preferences/prefs.cs
</td></tr>
<tr>
<td>wishes
</td>
<td>Post your suggestions here: [http://forums.mode7games.com/viewtopic.php?f=20&amp;t=1813](http://forums.mode7games.com/viewtopic.php?f=20&amp;t=1813)
</td></tr>
<tr>
<td>wreckage
</td>
<td> Takes everything seriously | Forever alone.
</td></tr>
<tr>
<td>wtf
</td>
<td>Watch this: [http://www.youtube.com/watch?v=9jJrUY27O0Y](http://www.youtube.com/watch?v=9jJrUY27O0Y)
</td></tr>
<tr>
<td>yes
</td>
<td>Yes.
</td></tr>
<tr>
<td>yeyaswizaw
</td>
<td>Taking the 'the' out of 'psychotherapist'. Wiki-contributor.
</td></tr>
<tr>
<td>ymir
</td>
<td>A fucking frost giant. One of his legs mated with the other. Apparently in love with ChrisIhao.
</td></tr>
<tr>
<td>zone
</td>
<td>To make a zone, hover your mouse over where you want the first corner to be then hold down T, move your mouse to where you want the other corner to be, then release T. Zones currently cannot be removed. More info: [http://fs.error420.com/wiki/Zones](http://fs.error420.com/wiki/Zones)
</td></tr>
<tr>
<td>zones
</td>
<td>To make a zone, hover your mouse over where you want the first corner to be then hold down T, move your mouse to where you want the other corner to be, then release T. Zones currently cannot be removed. More info: [http://fs.error420.com/wiki/Zones](http://fs.error420.com/wiki/Zones)
</td></tr></table>

<!-- 
NewPP limit report
Preprocessor node count: 94/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:24-0!*!0!!en!*!* and timestamp 20140723025856 -->