title: Extracting player statistics

<div class="thumb tright"><div class="thumbinner" style="width:202px;">[![Meneth-stats.png](/images/thumb/7/72/Meneth-stats.png/200px-Meneth-stats.png)](/wiki/File:Meneth-stats.png)  <div class="thumbcaption"></div></div></div>

It is possible to extract the statistics for any player (even aggregate statistics) from the game. This will likely appeal to those who like spreadsheets, those who are looking into game (im)balance or simply want to analyse an opponent.

A sample completed spreadsheet (not including the data) is displayed on the right.



## <span class="mw-headline" id="The_Steps"> The Steps </span>

There are three steps to creating a spreadsheet of a player's statistics. The steps below will reference a **destination folder** where you will be copying files. It doesn't matter what folder this is. It can be your desktop, your downloads folder or a USB stick, as long as you are consistent it doesn't matter.

It should also be noted that the statistics of any player can be extracted, the player will simply be referred to as **the player** below.

### <span class="mw-headline" id="Extracting_the_statistics_from_the_game"> Extracting the statistics from the game </span>

1.  Start Frozen Synapse and log in to the server the player plays on most often.

2.  Perform a search for the player's profile

3.  Click on "Match History"

4.  Open a file browser (not in Frozen Synapse) and go to your game's folder. This folder can vary depending on how it was installed (Steam or non-steam), and of course your operating system.

5.  In the _psychoff_ folder find _ppAllGamesRec.txt_ and copy that file to your destination folder. It is also recommended you make a copy of this file, so you can re-use it later if something goes wrong. It makes sense to name the file as yyyy-mm-dd_Player_name.txt, makes it easy to find later.

### <span class="mw-headline" id="Reformatting_the_statistics_as_a_spreadsheet"> Reformatting the statistics as a spreadsheet </span>

Once you have the text file in your destination folder, you need to reformat the file. The recommended steps here are different depending on your OS. Note that using Lu-Tze's FSParser may work in OS X and Linux using the Mono package, and the awk steps are confirmed to work in Windows with [gawk](http://gnuwin32.sourceforge.net/packages/gawk.htm) (see [this forum post](http://forums.mode7games.com/viewtopic.php?f=20&amp;t=3251#p12433)).

#### <span class="mw-headline" id="Lu-Tze.27s_FSParser_.28Windows.29"> Lu-Tze's FSParser (Windows) </span>

1.  Download [Lu-Tze's FSParser](http://ompldr.org/vOWJiaQ)

2.  Extract the rar archive

3.  Run the exetuable (may require .NET frameworks)

4.  Optionally select an output directory (default is your desktop)

5.  Click Go! and find the ppAllGamesRec.txt file

#### <span class="mw-headline" id="awk_.28OS_X_and_Linux.29"> awk (OS X and Linux) </span>

1.  Save the [this file](http://dl.dropbox.com/u/166696/fs/fs-stats-extract.awk) as fs-stats-extract.awk in your destination directory

2.  Open the terminal

3.  <tt>cd</tt> to your destination directory

4.  Enter: <tt>awk -f fs-stats-extract.awk &lt; ppAllGamesRec.txt &gt; player_name.csv</tt>

### <span class="mw-headline" id="Importing_the_data_into_a_more_complete_spreadsheet"> Importing the data into a more complete spreadsheet </span>

Whichever method was used above you should now have a CSV file. A CSV file, or a comma separated values file, is a very basic type of spreadsheet. It can contain data, but doesn't support any types of formalae or charts. As such it's useful to import this data into a ready made spreadsheet. Meneth has created such a spreadsheet.

1.  Download Meneth's spreadsheet from [http://dl.dropbox.com/u/7731438/Meneth.ods](http://dl.dropbox.com/u/7731438/Meneth.ods)

2.  If you use an office suite which cannot read ODS files (such as Microsoft Office or Numbers (?)), use [Zamzar](http://www.zamzar.com/) to convert the spreadseet to a format you can use

3.  Open the spreadsheet

4.  Also open the CSV in your spreadsheet application. You may be prompted for the CSV settings, ensure the comma character is the field seperator

5.  In Meneth's spreadsheet, delete all data in columns A to I, make sure to leave the column headers

6.  In the CSV, copy the data in columns A to I from row 2 down (ignoring the column headers)

7.  In Meneth's spreadsheet, select the cell A2 and paste. This will fill in all the data from the CSV

8.  Close the CSV spreadsheet, that file is no longer needed

9.  Scroll down to the bottom of your data

10.  Drag the columns J to S down to cover all your fields, or, if you've played less games than Meneth, delete the extra rows. Basically you want all rows to be complete.

11.  The graphs and summary areas (coloured cells) should automatically update with your data.

## <span class="mw-headline" id="Notes"> Notes </span>

Viewing a player's game histories is computationally expensive for the server. Therefore it's recommended you keep a copy of the ppAllGamesRec.txt file on your computer so you can restart the process if something goes wrong without re-exporting the file from the game. This is also the reason the [[api.md|API]] does not have a feature to extract game histories, or create the CSV.

If you wish to extract aggregate data from multiple players, run steps 1 and 2 for each player creating multiple CSV files (please spread your extractions over some time). Then, in any text editor, open all the CSV files and append them all into one big file. Make sure you remove the header from all but the first file.

## <span class="mw-headline" id="See_Also"> See Also </span>

This page originated as a [forum thread](http://forums.mode7games.com/viewtopic.php?f=20&amp;t=3251). If you are having problems it may make sense for you to read that thread, or post there.

<!-- 
NewPP limit report
Preprocessor node count: 31/1000000
Post‐expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
-->

<!-- Saved in parser cache with key fs_error420_com:pcache:idhash:240-0!*!0!!en!2!* and timestamp 20140722081529 -->