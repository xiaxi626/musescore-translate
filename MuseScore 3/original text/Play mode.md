---
title: Play mode
date: 2021-12-30 01:01:00
---
### Playback toolbar {#playback-toolbar}

Basic playback functions are accessed from the __Play toolbar__ located above the document window:

[inline:playback_toolbar.PNG=Playback toolbar] 

From left to right, the icons are:

* __Toggle 'Midi input'__:
* __Rewind to start position__: Playback returns to the beginning of the score, or to the start of the loop (if one is set).
* __Start or stop playback__: See [Start/stop playback](#start-stop-play).
* __Toggle loop playback__: See [Loop playback](#loop).
* __Play repeats__: Turn off if you want playback to ignore repeats.
* __Pan score during playback__: Turn off if you want the score to remain stationary.
* __Play metronome__: Toggles metronome ON and OFF.

### Playback commands {#play-commands}

#### Start/stop playback {#start-stop-play}

To start playback:

1. Click on a note, rest or the blank part of a measure to establish the starting point. __Note__: If no selection is made, playback returns to the place it left off; or, if no previous playback, to the start of the score.
2. Press the __Play__ button; or press <kbd><kbd>Space</kbd></kbd>.

During playback you can jump to a specific note or rest in the score by simply clicking on it. 

To stop playback:

* Press the __Play__ button; or press <kbd><kbd>Space</kbd></kbd>.

#### During playback {#during-playback}

Once playback has started, the following commands are available:

* Go back to previous chord: <kbd><kbd>&larr;</kbd></kbd>
* Advance to next chord: <kbd><kbd>&rarr;</kbd></kbd>
* Go back to start of previous measure: <kbd><kbd>Ctrl</kbd>+<kbd>&larr;</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>&larr;</kbd></kbd>)
* Advance to start of next measure: <kbd><kbd>Ctrl</kbd>+<kbd>&rarr;</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>&rarr;</kbd></kbd>)
* Rewind to start of score: <kbd><kbd>Home</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Home</kbd></kbd>); or press the __Rewind__ button (playback toolbar).

During playback you can still use [node:278641,fragment="show-panels",title="keyboard shortcuts"] to open and close [node:278641,fragment="show-panels",title="panels"], such as Play, Synthesizer, Mixer etc.

#### Loop playback {#loop}

* Playback should be __off__, and the "Loop playback button"  __on__.
* [node:278652,title="Select"] the desired region of the score for loop playback.
* Press the playback button.

Playback will now cycle within the region marked by the blue flags.

* Use the "Loop playback" button to toggle the loop on or off.

See also: [Play Panel](#play-panel) (below).

### Play panel {#play-panel}

To open the Play Panel use one of the following options:

* Press <kbd><kbd>F11</kbd></kbd>  (Mac: <kbd><kbd>Fn</kbd>+<kbd>F11</kbd></kbd>).
* From the menu bar, select <samp class="menu">View</samp> &rarr; <samp class="menuitem">Play Panel</samp>.

 [inline:play_panel_en.png=Play Panel]

The Play Panel allows you to make temporary changes to tempo and volume, to loop playback between specified points etc.

* __Loop playback__: Select a start note and click on the __Loop in__ button; select an end note and click on the __Loop out__ button. Press __Play__ to hear the loop. The controls also work _during_ playback.
* __Rewind, Play__: Playback controls. 
* __Metronome__: Toggle metronome playback ON or OFF.
* __Count in__: (Conductor icon) Adds a count-in when you start playback at the start of a measure. Extra beats are added if you start mid-measure. Toggles ON and OFF.
* __Tempo__: Make temporary change to tempo. This is displayed as a percentage and as a bpm (beats per minute). Double-click to reset. (Note: Permanent changes to __tempo__ should be made using [node:278604,title="tempo text"])
* __Volume__: Make temporary change to volume (resets when program is reopened). Note: To change the default __playback volume__ of the score, see [node:278660,title="Synthesizer"].