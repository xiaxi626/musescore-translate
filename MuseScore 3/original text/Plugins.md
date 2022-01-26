### What are Plugins? {#what-are-they}

Plugins are small pieces of software that add a particular feature to MuseScore. By enabling a plugin, a new menu option is appended to the __Plugins menu__: subsequently, when this option is selected, the plugin performs a particular task in the score. <!--Plugin development is a way for users with minimal programming skills to add features to the software. To develop plugins, checkout the [node:4497,title="documentation"].-->

Some plugins come pre-installed with MuseScore—see [Plugins installed by default](#plugins-installed-by-default) (below). You can find many more plugins in the [plugin repository](/plugins): some work with MuseScore 3, others only with older versions of MuseScore, and some work with either. To tell one from the other: MuseScore 3.x and 2.x plugin code files have an extension of `.qml`; for older versions, it is `.js`.

__Warning__: Plugins can potentially contain bad or malicious code, which can compromise or damage your scores or system. Plugins are entirely unvetted (except for those that are [installed by default](#plugins-installed-by-default)). You either need to trust the author or check the code yourself.

### Installation {#installation}

__Note__: Some plugins may require the installation of other components (fonts, e.g.) to work. Check the plugin's documentation for more information.

Most plugins are provided as ZIP archives: download the plugin's .zip file and uncompress (unzip) it to one of the directories mentioned below (depending on your OS). If the plugin is provided directly as an uncompressed .qml file, simply download it and place into one of the same directories.

Once a plugin is installed, it needs to be enabled in the __Plugin Manager__ in order to use it—see [Enable/disable Plugins](#enable-disable-plugins).

#### Windows {#windows}

On Windows, new plugins should be installed into `%HOMEPATH%\Documents\MuseScore3\Plugins`. Alternatively, specify a different folder in MuseScore's [node:278648,title="Preferences"].

[Pre-installed plugins](#plugins-installed-by-default) can be found in `%ProgramFiles%\MuseScore 3\Plugins` (or `%ProgramFiles(x86)%\MuseScore 3\Plugins` for the 32-bit versions) and in `%LOCALAPPDATA%\MuseScore\MuseScore 3\plugins` on Windows <!--Vista, -->7 and later<!-- or `C:\Documents and Settings\USERNAME\Local Settings\Application Data\MuseScore\MuseScore 3\plugins` (adjusted to your language version) on XP-->. These folders should not be modified.

#### macOS  {#mac-os-x}

On macOS, new plugins should be installed into `~/Documents/MuseScore3/Plugins`. Alternatively, specify a different folder in MuseScore's [node:278648,title="Preferences"].

[Pre-installed plugins](#plugins-installed-by-default) can be found in the MuseScore bundle in `/Applications/MuseScore 3.app/Contents/Resources/plugins` (to reveal files in the app bundle, right-click on `MuseScore 3.app` and choose "Show package contents"), and in `~/Library/Application Support/MuseScore/MuseScore 3/plugins`. These folders should not be modified.

#### Linux {#linux}

On Linux, new plugins should be installed into `~/Documents/MuseScore3/Plugins`. Alternatively, specify a different folder in MuseScore's [node:278648,title="Preferences"].

[Pre-installed plugins](#plugins-installed-by-default) can be found in `/usr/share/mscore-3.x/plugins` and in `~/.local/share/data/MuseScore/MuseScore3/plugins`. These folders should not be modified.

The directory names might be slightly different, depending on your operating system's language.

### Enable/disable plugins {#enable-disable-plugins}

To be able to access the installed plugins from the Plugins menu, they need to be enabled in the __Plugin Manager__:

 [inline:Plugin_Manager_en.png=Plugin manager]

You do this simply by checking the appropriate tick box. This adds the name of the plugin to the list in the __Plugins menu__.

### Create/edit/run plugins

It is possible to create new or edit existing plugins and run them via the __Plugin Creator__:

 [inline:Plugin_Creator_en.png=Plugin creator]

Documentation of all available elements can also be found here.

### Plugins installed by default {#plugins-installed-by-default}

Some plugins come pre-installed with MuseScore, but they are not enabled by default. See [Enable/disable plugins](#enable-disable-plugins) (above) to enable plugins.

#### ABC Import {#abc-import}

This plugin imports [ABC](http://abcnotation.com) text from a file or the clipboard and converts it to [node:278612,fragment="musicxml",title="MusicXML"]. Internet connection is required, because it uses an [external web-service](http://abc2xml.appspot.com/) for the conversion.

#### Notes &rarr; Color Notes {#color-notes}

This demo plugin colors notes in the selected range (or the entire score), depending on their pitch. It colors the note head of all notes in all staves and voices according to the Boomwhackers convention. Each pitch has a different color. C and C♯ have a different color. C♯ and D♭ have the same color.
To color all the notes in black, just run that plugin again (on the same selection). You could also use the [node:4773,title="'Remove Notes Color' plugin"] for this.

#### Create Score {#create-score}

This demo plugin creates a new score. It creates a new piano score with 4 quarter notes: C, D, E, F. It's a good start to learn how to make a new score and add notes from a plugin.

#### helloQml {#helloqml}

This demo plugin demonstrates some basic tasks.

#### Notes &rarr; Note Names {#note-names}

This plugin names notes in a selected range or for the entire score. It displays the names of the notes (as [node:278581#text-types,title="staff text"]) according to MuseScore's [node:278654,title="language settings"]: voices 1 and 3 notes above the staff; voices 2 and 4 notes below the staff; and chord notes in a comma separated list, starting with the top note.

#### Panel {#panel}

This demo plugin creates a GUI panel.

#### random/random2 {#random}

Creates a random score.

#### run {#run}

This demo plugin runs an external command. Probably this will only work on Linux.

#### scorelist {#scorelist}

This test plugin iterates through the score list.

#### ScoreView {#scoreview}

Demo plugin to demonstrate the use of a ScoreView

#### Walk {#walk}

This test plugin walks through all elements in a score

### See also {#see-also}

- [node:278656,title="Tools"]

### External links {#external-links}

- [node:256531,title="Plugins for 3.x"]