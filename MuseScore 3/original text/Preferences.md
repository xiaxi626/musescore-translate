You can customize many of MuseScore's default behaviors via the menu: <samp class="menu">Edit</samp>&rarr;<samp class="menuitem">Preferences...</samp> (Mac: <samp class="menu">MuseScore</samp>&rarr;<samp class="menuitem">Preferences...</samp>).

The Preferences dialog has multiple tabs:

 [inline:Preferences_Window_tabs_en.png=Tabs in Preferences dialog] 

<kbd><samp class="button">Reset All Preferences to Default</samp></kbd> will reset all preferences to the ones MuseScore had when you installed it. <kbd><samp class="button">Ok</samp></kbd> will save the settings and close the dialog. <kbd><samp class="button">Cancel</samp></kbd> will close the dialog without applying changes. <kbd><samp class="button">Apply</samp></kbd> will make changes take effect without closing the dialog.

### General {#general}

[inline:Preferences-General_en.png=General Preferences] 

Here you can define:

* __Program Start__: Specify whether to start the session empty or to display a score. The options are one of the following: _Start empty_ (no score) / _Continue last session_ / _Start with new score_ (i.e. New Score Wizard automatically opens) / _Start with score_ (the program default, or one of your own choosing).

 You can also choose which panels to display. This can be any combination of: _Splash screen_, _[node:278585,fragment="play-panel",title="Play Panel"]_, _[node:278641,fragment="navigator",title="Navigator"]_, or _[node:278622,fragment="start-center",title="Start Center"]_. Also select if _[node:279732, fragment="tours",title="Tours"]_ will be active.

* __Folders__: Specify the default folders for score files, [node:278570,fragment="save-and-load-style",title="style files"], custom score [node:278622,fragment="templates",title="templates"], [node:278601,title="plugins"], additional [node:278624,title="SoundFonts"], [node:278563,title="images"], and [node:278654,fragment="install-extension",title="extensions"].

* __Language__: Choose the language used by the program. Translations may be updated from here too. Note that language translation updates can also be done via the menu: <samp class="menu">Help</samp>&rarr;<samp class="submenu">Resource Manager</samp>.

* __Telemetry__: Tick/untick to authorize MuseScore to collect usage data. The type of data collected is listed, and updated as needed, in [node:300080,title="telemetry"].

* __Appearance__: Specify a dark or light theme, and the width and height of icons. Set display "Font face" and "Font size".

* __Auto Save__: How frequently the program autosaves.

* __OSC Remote Control__

### Canvas {#canvas}

[inline:Preferences-Canvas_en.png=Canvas Preferences]

Use Canvas to set your preferred color and wallpaper for the score background and paper. The default "Background" is dark blue (RGB 20, 36, 51; Alpha 255) and the default "Paper," white.

* __Background__: Use this to set the color or background _around_ the score pages. Select "Color" then click on the bar to the right and make a choice from the color picker; or select "Wallpaper," click on the file icon and set a background image.

* __Paper__: Sets the color or background of the score pages. Controls identical to "Background" (above). You can also tick/untick "Use the same color in palettes".

* __Zoom__: This defines the Default zoom level and keyboard/mouse zoom precion.

* __Scroll Pages__: This defines the way that the pages are laid out in the score. Choose "Horizontally" for a row layout, or "Vertically" for a column layout. To limit scrolling, tick "Limit scroll area to page borders".

* __Miscellaneous__: "Draw antialiased" (the default option) makes diagonal lines and edges of shapes look smoother.  "Proximity for selecting elements" controls the distance the mouse may be from an object and still act on it.  Smaller numbers require more precision, making it harder to click on small objects.  Larger numbers are less precise, making it harder not to click on nearby objects unintentionally.  Choose a comfortable working value.

### Note input {#note-input}

[inline:Preferences-Note_Input_en.png=Note Input Preferences]

On this tab there are note input and MIDI remote control preferences. Here the following can be set:

#### Note Input {#input}

* __Enable MIDI Input__: Leave checked to allow MIDI input of notes.

* __Color notes outside of usable pitch range__: For details, see [node:278615,fragment="coloring-of-notes-out-of-range",title="Coloring of notes outside an instrument's range"] and [node:278564,fragment="common-staff-properties-options",title="Usable pitch range"]  (Staff properties: all staves).

* __Delay between notes in automatic real-time mode__: See [node:278675,fragment="realtime-auto",title="Real-time (automatic)"].

*  __Play notes when editing__: When ticked, MuseScore _sounds_ the note when it is entered or selected. Tick "Play whole chord when adding note," if you want to hear _all_ the notes of a chord when it is added to. You can also edit the "Default duration".

#### MIDI Remote Control {#midi-remote-control}

__Midi Remote Control__ allows you to use certain keys on your MIDI keyboard to enter notes and rests _and_ to select note durations, without involving the computer mouse or (computer) keyboard. The default setting is off.

__To assign a command to a MIDI key__:

1. Ensure that "MIDI Remote Control" is checked (your MIDI keyboard should be connected before opening the program).

2. Click the red button next to the option you wish to assign a MIDI key to: the red button now lights up.

3. Press a MIDI keyboard key. The red button becomes unlit and the green button lights up instead. The MIDI key has now been assigned to the desired option.

4. Repeat "2" and "3" to assign other keys.

Once you have defined your key settings you can use the MIDI keyboard to control note input operations.  You can verify your key settings by observing the MuseScore [node:278641,fragment="toolbars",title="Note Input toolbar"] while pressing the MIDI keys.

To temporarily deactivate Midi Remote Control: uncheck "Midi Remote Control": all MIDI input key action buttons are now greyed out.  _Note_: Your key assignments are always saved between MuseScore sessions and are not affected by deactivation.

__Notes__: (1) The "Clear" option turns off all the green buttons for the _current_ MuseScore session but all the user-recorded MIDI key settings are retained and will be reloaded on the next session. (2) A MIDI key setting that is activated cannot afterwards be turned off, and the green button will always remain lit: however it can be overwritten with a different MIDI key by using the red button again. (3) If the same MIDI key is accidentally assigned to more than one option, then all the associated green buttons remain lit although only one will work. To fix, see "(2)".

### Score {#score}

[inline:Preferences-Score_en.png=Score Preferences]

Score preferences include:

#### Default Files {#default-files}

* __Instrument list 1__:  Default instrument list file one

* __Instrument list 2__:  Default instrument list file two

* __Score order list 1__:  Default score order list file one (used for instrument ordering)

* __Score order list 2__:  Default score order list file two

* __Style__:  Default style for score

* __Style for part__:  Default style for parts

See also [node:278570,title="Load/Save Style",fragment="save-and-load-style"]

#### View {#view}

* __Show MIDI controls in mixer__:  Enable this option to show MIDI controls by default in the mixer.

### I/O {#i-o}

[inline:Preferences-IO_en.png=I/O Preferences]

#### PortAudio (API / Device) {#api-device}

This enables you to set the audio interface (API) and specify the device to be used for audio playback: e.g. built-in speakers/headphones, USB headset, wireless, etc.

#### MIDI Input/Output/Output Latency {#midi-in-out}

When an external MIDI input device is connected, its identifier appears in __MIDI Input__. When the device is connected _for the first time_, you also need to select the correct __MIDI Output__ option in order to enable note input and correct audio playback  (e.g. in Windows, this might be "MMS&lt;device name&gt;"): then close and reopen the program to confirm the changes.

#### Jack Audio Server {#jack}

Check these options as required if using the [JACK](http://jackaudio.org/) Audio Connection Kit. <!--more details needed-->

#### Audio Engine {#audio-engine}

In case of lost communication between your audio device or your MIDI keyboard and MuseScore (no sound output or MIDI action), click on <kbd><samp class="button">Restart Audio and MIDI Devices</samp></kbd> to restore them.

### Import {#import}

[inline:Preferences-Import_en.png=Import Preferences]

These settings determine how files from other sources are imported:

* __Style Used for Import__: Use either the built in MuseScore style or a style you choose (see [node:278570,title="Load/Save Style",fragment="save-and-load-style"])

* __MusicXML__: Set the MusicXML import options

* __Character Set Used When Importing Binary Files__: Character Set used for Binary Files (Guitar Pro and Overture character sets)

* __MIDI__: Define the shortest note when importing MIDI files

* __When opening scores from older MuserScore versions__: When enabled, you will be prompted if you want to apply the new default engraving and style settings or not when opening a score created with a version before 3.6.

### Export {#export}

[inline:Preferences-Export_en.png=Export Preferences]

These settings determine how various files are exported from MuseScore:

* __PNG__: PNG/SVG image resolution (in DPI) and whether to use transparent background.

* __MIDI__: Whether to expand repeats in exported MIDI files.

* __PDF__: PDF resolution (in DPI).

* __Audio__: Set audio sample rate, MP3 bitrate, and whether to "normalize" exported audio.

* __MusicXML__: Whether to export the layout and how to export system and page breaks to MusicXML.

### Shortcuts {#shortcuts}

[inline:Preferences-Shortcuts_en.png=Shortcuts Preferences]

This tab lists all the commands in MuseScore and any keyboard shortcuts associated with them.  Shortcuts listed in preferences also appear next to their associated commands in the menus.

* __To search for a particular command__: Enter its name in the "Search" box near the bottom of the window.

* __To create a new shortcut for a command__:

 1. Select an existing entry in the list.

 2. Click <kbd><samp class="button">Define...</samp></kbd>; or just double-click the entry.

 3. Enter the new shortcut using up to four keys. Press <kbd><samp class="button">Clear</samp></kbd> if you need to re-enter the shortcut.

 4. Press <kbd><samp class="button">Replace</samp></kbd> to change the existing shortcut; or <kbd><samp class="button">Add</samp></kbd>, to keep the old shortcut _and_ add the new one.

 __Note:__ Some shortcuts, including default ones, may not work with some keyboards.

* __To reset a shortcut to its system default__: Select a command in the list and press <kbd><samp class="button">Reset Shortcut to Default</samp></kbd>.

* __To save the shortcuts list__: Press <kbd><samp class="button">Save</samp></kbd> and save to a file name of your choice.

* __To load a saved shortcut list__: Press <kbd><samp class="button">Load</samp></kbd> etc.

* __To clear all shortcuts for an entry__: Select the entry and press <kbd><samp class="button">Clear</samp></kbd>.

* __To print out the shortcuts list__ (incl. export to pdf): Press <kbd><samp class="button">Print</samp></kbd> etc.

### Update {#update}

[inline:Preferences-Update_en.png=Update Preferences]

This sets whether MuseScore will check for updates and extensions at startup. 

Updates may be checked manually in <samp class="menu">Help</samp>&rarr;<samp class="submenu">Check for updates</samp>.

### Advanced {#advanced}

 [inline:Preferences-Advanced_en.png=Advanced Preferences] 

Allows you to control specific settings for  "application, "export", "i/o" and "user interface", as well as color settings.

### See also {#see-also}

* [node:278609,title="Keyboard shortcuts"]

* [node:278654,title="Language settings and translation updates"]

* [node:278655,title="Update checking"]

