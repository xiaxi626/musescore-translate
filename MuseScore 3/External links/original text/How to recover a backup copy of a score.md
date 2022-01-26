![bck%20copy.png](../images/bck%2520copy.png)

If one of your scores becomes lost, corrupted, or cannot be opened, there's a chance that MuseScore saved a copy somewhere on your computer.

MuseScore creates two different types of backups of your files:

#### 1. Last saved version

Every time you save an existing file for the first time in a session, MuseScore creates a file named "`.filename.mscz,`" (starting with a dot, ending with a comma). This backup file will not be modified during your session, and if MuseScore crashes, it should contain the score as it was at the _start_ of the session. 

__Note 1__: Backup files are hidden, by default, on __Linux__ and __Mac OS X__ systems because the file name starts with a dot; and on __Windows__ because MuseScore sets the "Hidden" [file attribute](https://en.wikipedia.org/wiki/File_attribute). To make these hidden files visible, refer to the relevant OS documentation.

Once you locate this file, rename it and __remove the trailing comma__ (this is the vital part) and the leading dot; on Windows, it is also advisable to unset the _hidden_ attribute. Now, you should be able to open the resulting file in MuseScore.

__Note 2__: As of MuseScore 3.5 these backup scores are stored in a separate folder, named `.mscbackup`, which too is hidden (see above), but allows these score to get opened directly via File > Open.

#### 2. Autosaved version

Every X minutes during a session (the time period is customizable in [node:278648,title="Preferences"]—default is 2 minutes), _and_ when you close MuseScore, _all_ open files will be auto-saved to the session directory. Browse this directory to locate a backup of your file. Each file will have an auto-generated name, "`sc*.mscz`"— sorting the list by modification time may help you to find the file more quickly.

The session directory depends on the OS (and on Windows also its language version). For MuseScore 3, you can find it as follows:

* __Windows__: `%LOCALAPPDATA%\MuseScore\MuseScore3\`

(Windows Vista or later: `C:\Users\'USERNAME'\AppData\Local\MuseScore\MuseScore3\`

Windows XP or earlier: `C:\Documents and Settings\'USERNAME'\Local Settings\Application Data\MuseScore\MuseScore3\`)

 See also ["How to see hidden files in Windows"](http://www.bleepingcomputer.com/tutorials/how-to-see-hidden-files-in-windows/) and ["How to show file extensions in Windows"](http://www.bleepingcomputer.com/tutorials/how-to-show-file-extensions-in-windows/)

* __Mac OS X__: `~/Library/Application Support/MuseScore/MuseScore3/`

  _Note:_ The "`~`" in the path above is required to access the Library directory in your Home folder. `/Library/Application Support/` (without "`~`" at the beginning) will take you to a separate folder location where you will not find the MuseScore folder you need.

* __Linux__: ` ~/.local/share/data/MuseScore/MuseScore3/`

__Note:__ You can also use [MuseScore.com](http://musescore.com) to create backup copies of your score, regardless of completion stage. See [node:278595,title="Share scores online"].

<!--ToDo: this section needs improvement-->

Sometimes—under not-fully-understood circumstances—MuseScore stores a file at a so-called virtual store (on Windows) or in some temporary directory outside the user's home. The containing directory is most likely named "`/tmp`" on Mac and Linux systems, and with a filename representing the full original pathname with all (back)slashes ('`\`' resp.  '`/`') replaced by underscores ('`_`'). See for example [node:278673,title="recovered files"].

You may need to search your entire hard disk for all filenames ending with "`.mscz`" to find those.
