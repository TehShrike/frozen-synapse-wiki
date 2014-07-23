title: Console

The console is a powerful tool, giving you access to many a function not included in the game's interface and spewing out lots of interesting behind the scenes data.

To open up the console press either ` or ^.

On some keyboard layouts it may not be easy to open the console. For instance a Swedish keyboard layout on Linux cannot open the console by default. In this case you should open the file called main.cs in any text editor which is in the game's root directory. At the end of the file, append:

<pre>GlobalActionMap.bind(keyboard, home, toggleConsole);
</pre>

Save the file, start the game and the home key will toggle the state of the console.

## <span class="mw-headline" id="Functions"> Functions </span>

Here's a list of handy functions, to use these open up the console, type in the function with appropriate parameters and press enter. The console doesn't seem to be case-sensitive.

<table cellpadding="5" cellspacing="0" border="1">
<tr>
<td>Chanwindow.canMove = 1;
</td>
<td>Allows you to move the chat window, for a permanent solution and resizing the window see: [http://j.mp/iYa6Jy](http://j.mp/iYa6Jy).
</td></tr>
<tr>
<td>testSnapCam();
</td>
<td>Plays the current match without pausing per turn, also zooms in such a way that every vatform is on screen.
</td></tr>
<tr>
<td>$timescale = [number];
</td>
<td>Decreases or increases the gamespeed, default is 1.
$timescale = 0.5; for instance makes the game run at half speed.
</td></tr>
<tr>
<td>echo($version);
</td>
<td>Display the version number you are currently using. This number gets updated when Omroth feels like it, not when a new version of the software gets compiled.
</td></tr>
<tr>
<td>loadeditor();
</td>
<td>Starts the [[level-editor.md|Level Editor]].
</td></tr>
</table>

<!-- 
NewPP limit report
Preprocessor node count: 3/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:257-0!*!0!*!*!*!* and timestamp 20140722083816 -->