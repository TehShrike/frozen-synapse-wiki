title: Sync error

From [this forum post:](http://forums.mode7games.com/viewtopic.php?f=21&amp;t=4488)

If you get a 'Sync Error' when trying commit a turn please **try exiting to the main menu and reloading the game.** This should work for the majority of cases.

If that doesn't work, try 

1.  Make sure Frozen Synapse is running

2.  Open the affected game in Frozen Synapse

3.  Open up a file browser and navigate to psychoff/data/encounters in the Frozen Synapse game directory

4.  Find a file named ref[gameid of the affected game].enc (example: _ref123456.enc_), delete it and try to commit your turn. (Don't worry about any other .enc files in this directory.)

This should resolve the problem. Please [reply](http://forums.mode7games.com/viewtopic.php?f=21&amp;t=4488) if it doesn't, or if you need any help finding this file.

## <span class="mw-headline" id="Game_directory"> Game directory </span>

If you don't know where your game directory is, here are some likely locations:

*   Windows

    *   C:\FrozenSynapse\psychoff\data\encounters\

        *   C:\Program Files\Steam\steamapps\common\frozen synapse\psychoff\data\encounters\

        *   C:\Program Files (x86)\Steam\steamapps\common\frozen synapse\common\frozen synapse\psychoff\data\encounters\

*   OS X

    *   ~/Library/Application Support/FrozenSynapse/psychoff/data/encounters/

*   Linux

    *   ~/.local/share/FrozenSynapse/psychoff/data/encounters/

<!-- 
NewPP limit report
Preprocessor node count: 3/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:297-0!*!*!*!*!*!* and timestamp 20140723015121 -->