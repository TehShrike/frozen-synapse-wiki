title: Level Editor

Frozen Synapse features a complete level editor. It is accessed by typing `loadeditor();` into the console (Accessed with ~ key). It's similar in some ways to the [[advanced-setup.md|Advanced Setup]], but has a somewhat different feature-set. Players are able to either create a new level from scratch or edit a saved map. It is also possible to import maps from png image files. Players are able to modify the landscape and place triggers around the map to create unique scenarios. It is possible to use a custom level in a multiplayer match, but it is not recommended as it may cause bugs that may result in a broken game.



## <span class="mw-headline" id="Starting_a_New_Map"> Starting a New Map</span>

As it currently stands it appears the only way to start a new map is to load a blank .png file. The size of the .png is the size of the game field.  Typical games appear to be about 1024x768, although other sizes will work. It should be fully white, and the border needs to be white for it to work correctly. To add walls to your .png, use red pixels. If you'd like to add cover, use blue pixels. You do not have to do this from the .png, as it can be done in-game. Once your .png is finished you need to save it into Frozen Synapses' folders. The easiest way I've found is to save it into the "psychoff" folder (as this is the folder it browses in-game).

It is also possible to simply load a map that has already been created in-game. Loading the editor while in a multiplayer game, or attempting to load a multiplayer game that's in progress causes the map to break. Instead, load a map from a .png file that is already in Frozen Synapses' folders. For a completely blank file choose "blank.enc" . This is the easiest way to start a new map.

If starting with a blank map, you create zones using the "t" key (click and drag to create the shape then release to finish). Name the zone you want the game to be played in "gameZone."

## <span class="mw-headline" id="Creating_the_Game"> Creating the Game </span>

Once you have your blank map, it is time to add walls. Raise them wherever you'd like. This is done by holding the "n" key and dragging. At this point it will not show you the shape you're about to make until you've released the key. After it is released you can still edit the size by dragging the corners, or move it around by clicking and dragging. To select a shape you've made, right click. Note that if you can't select/add walls, you need to mouse over the "Editor Window" and select "Toggle Editing Te" (The last word is cut off). Also noteworthy, the outside walls of the level are invisible, but they are there. Walls can be placed outside it, but units cannot. Walls dragged outside the game area appear to be uneditable after they are dropped there.

After you've put walls up, you can now add cover. As far as I can tell, the only way to do this in game is to create walls, and then *middle mouse button* click them to turn them into cover. On the mac platform depending on your mouse/keypad this may be impossible at this time. The only workaround appears to be uploading a .png with cover already on it. (Note that you can simply put a dozen or so pieces of cover on your .png and edit it later in game to be the shapes and sizes you want it.)

Make sure units can path through all doorways you make with pathing tests before attempting to use a game.

## <span class="mw-headline" id="Placing_Units"> Placing Units</span>

Once your level looks the way you'd like, it's time to add units to it. This requires you to go back to the "Editor Window" and click on "Toggle Editing Te" once more. This will allow you to edit and create units and modify them, instead of the walls and cover. To add a unit simply right click and choose "Add Unit." From there you name the unit (appear s to have no effect on it's behavior), choose the Unit Team (1=green, 2=red. No support for other teams at this time), and finally pick the Unit Type. This allows you to choose from any unit in the game, including campaign units (and apparently units the developers are using for testing: "MachinegunNerf.")

**Standard Game Units** These are the units that appear in normal multiplayer games

*   Snipster

*   machineGun

*   rocketLauncher

*   grenadeLobster

*   ShotGun

If you want to change a unit that's already placed go to the Editor Window and choose Edit Unit. To delete a unit, right click on it and choose Delete Unit. In the right click options are all the standard commands for units, which allows you to set their state for the first turn.

## <span class="mw-headline" id="Advanced_Unit_Options"> Advanced Unit Options </span>

There are many advanced options for unit triggers and actions. Some of these may be broken, including the Animation, possibly the spawner feature, and several others. It is highly recommended not to attempt to use most of these options for multiplayers games, especially against people you're not familiar with. Using the majority of these features may create broken maps. When functioning correctly triggers can make units react to certain situations with certain reactions which can make for many and varied scenarios.

Unfortunately because of the font clipping it is impossible to make use of many of the options just because you can't read the options.

## <span class="mw-headline" id="Saving"> Saving </span>

Once you're satisfied, used the Save As feature to save your game. Note that it should be saved as a .enc file, which you will have to write onto the filename yourself. Once the file is saved, you'll need to get to it on your computer (in your Frozen Synapse files, under Psychoff -&gt; Data -&gt; Encounters and drag it into a new file in the Data folder which you should name userLevels. Once it's in here, it is finished and ready to play.

Play it by going from Main Menu -&gt; Multiplayer -&gt; Create Game -&gt; Advanced Setup -&gt; Load Level -&gt; Yourlevelname. Once it's input you can do any last minute edits you'd like, then hit Submit. Choose the game made and setup all the options. Note that the "open" opponent option does not work, so you MUST specify an opponent.

## <span class="mw-headline" id="Links"> Links </span>

*   [SP campaign editing and some advanced commands](http://forums.mode7games.com/viewtopic.php?f=27&amp;t=2587)

*   [Basic info](http://forums.mode7games.com/viewtopic.php?f=27&amp;t=2697)

*   [Also basics, may be dated info](http://forums.mode7games.com/viewtopic.php?f=20&amp;t=2306)

## <span class="mw-headline" id="Known_Bugs"> Known Bugs </span>

*   The "main menu" option sometimes disappears while editing a level. You can attempt to load a new game to get it to reappear.

*   Almost all of the editor-specific menu's appear to have clipping in their animation that causes some of the text to be invisible.

*   Walls placed outside the game area cannot be edited or erased.

*   Macintosh users may not be able to convert walls to cover without a third-party mouse.

*   Animation feature appears to be broken.

*   Opening the Advanced Options from the multiplayer menu will cause the level editor to be inaccessible via the console command until a relaunch.

<!-- 
NewPP limit report
Preprocessor node count: 27/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:206-0!*!0!!en!*!* and timestamp 20140723013832 -->
