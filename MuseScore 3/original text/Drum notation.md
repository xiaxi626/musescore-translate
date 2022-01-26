---
title: Drum notation
date: 2022-01-10 16:17:10
---
Entering percussion notation is somewhat different to entering notation for pitched instruments (such as the piano or violin).

### Percussion staff types {#staff-types}

When you create a percussion staff using the [node:278622,fragment="create-new-score",title="New Score Wizard"] or the [node:278622,fragment="change-Instrument-setup",title="Instruments"] dialog, MuseScore automatically chooses the most appropriate staff type (1-, 3-, or 5-line) for the instrument: this can be changed, if required, using the "Staff type" column on the  [node:278622,fragment="instruments-and-voice-parts",title="Choose instruments / Instruments"] page. Any additional changes (e.g. to a 2-line staff) can be made from the score itself (see [node:278564,fragment="advanced-style-properties",title="Advanced Style Properties"]).

On a 5-line percussion staff, each instrument is assigned a vertical staff position (line or space) and a notehead shape. For a drumset, one or two [node:278602,title="voices"] can be used. If the latter, __voice 1__ (the upper voice) usually contains (up-stem) notes played by the hands while __voice 2__ (the lower voice) usually contains (down-stem) notes played by the feet (see image below).

[inline:drum1.png=Drum notation example showing the use of two voices]

### Note input methods {#note-input-methods}

You can add notes to a percussion staff from any of the following:

* External MIDI keyboard;
* Piano keyboard (virtual);
* Computer keyboard;
* Mouse.

These methods can be used in any desired combination:

#### MIDI keyboard {#midi-keyboard}

To add notes to a percussion staff from a __MIDI keyboard__:

1. Ensure that the MIDI keyboard is connected and functioning correctly.

 __Note__: If you click on the percussion staff without entering [node:278615,title="note input"] mode, you can _demo_ the percussion instruments from the MIDI keyboard.

2. Click on the note or rest where you want to start.
3. Enter [node:278615,title="note input"] mode.
4. Select the correct [node:278602,title="voice"]. For example, snares, sidesticks and all cymbals are normally added to voice 1; bass drum to voice 2.
5. Set [node:278615,fragment="duration",title="note duration"].
6. Press an instrument key to add a note to the score. To add another note at the same position, keep the first key held down while pressing the second key.

__Note__: Refer to a __GM2 drum map__ for details about which MIDI keyboard key corresponds to which percussion instrument. Some keyboards (e.g., Casio) display percussion symbols next to the keys as an aid to the user.

#### Piano keyboard {#piano-keyboard}

To add notes to a percussion staff from the virtual __Piano Keyboard__:

1. Ensure that the Piano keyboard is displayed. Press <kbd><kbd>P</kbd></kbd> (or select it from the menu, <samp class="menu">View</samp> &rarr; <samp class="menuitem">Piano Keyboard</samp>).

 __Note__: If you click on the percussion staff without entering [node:278615,title="note input"] mode, you can _demo_ the percussion instruments from the Piano keyboard.

2. Click on the note or rest where you want to start.
3. Enter [node:278615,title="note input"] mode.
4. Select the correct [node:278602,title="voice"]. For example, snares, sidesticks and all cymbals are normally added to voice 1; bass drum to voice 2.
5. Set [node:278615,fragment="duration",title="note duration"].
6. Click on a (virtual piano) key to add a note to the score. 
7. To add another note to an existing one, press <kbd><kbd>Shift</kbd></kbd> and hold it while pressing the new note (in versions before 2.1, use <kbd><kbd>Ctrl</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd></kbd>)).

__Note__: Refer to a __GM2 drum map__ for details about which piano key corresponds to which percussion instrument.

By default, the piano keyboard is docked at the bottom of the screen—to the left of the Drum input palette. However you can undock it by dragging, then dock the panel in several ways:

* Drag the panel downwards to the center and it will overlay the Drum input palette, full length. Both panels can then be accessed by Tabs.
* Drag the panel downwards to the right/left and it will dock to the right/left of the Drum input palette.

#### Computer keyboard {#computer-keyboard}

To enter notes on a percussion staff using your computer keyboard:

1. Click on the note or rest where you want to start.
2. Enter [node:278615,title="note input"] mode. The [Drum input palette](#drum-input-palette) now appears at the bottom of the screen (see [below](#drum-input-palette)).
3. Select the desired [node:278615,fragment="duration",title="note duration"].
4. Press the shortcut key (A–G) for the instrument that you wish to enter—refer to the Drum input palette window.
5. If you wish to add another note to an existing one in that voice, press <kbd><kbd>Shift</kbd>+[<kbd>A</kbd>–<kbd>G</kbd>]</kbd>.

__Note__: Voice allocation is determined by the color of the note in the drum input palette: blue for voice 1, green for voice 2.

#### Mouse {#mouse}

_To add a note to a percussion staff_

Use the following method to add a _new_ note or to replace an _existing_ [node:278598,fragment="chord",title="chord"].

1. Select the note or rest where you want to start. You can also select a [node:278611,fragment="select",title="measure"].
2. Press <kbd><kbd>N</kbd></kbd> to enter [node:278615,title="note input mode",fragment="note-input-mode"]. The [Drum input palette](#drum-input-palette) now appears at the bottom of the screen (see [below](#drum-input-palette)).
3. Set [node:278615,fragment="duration",title="note duration"].
4. Choose one of the following options:
 * Double-click a note in the [Drum input palette](#drum-input-palette).
 * Select a note (e.g. Bass drum, or Snare) in the [Drum input palette](#drum-input-palette), then click a note or rest in the score.

_To add a note to an existing chord in the percussion staff_

1. Ensure you are in [node:278615,title="note input mode",fragment="note-input-mode"].
2. Select a [node:278615,fragment="duration",title="note duration"] equal to the note you are adding to.
3. Click on the new note in the [Drum input palette](#drum-input-palette).
4. Click above or below the existing note in the percussion staff.

__Note__: Voice allocation is determined by the color of the note in the drum input palette: blue for voice 1, green for voice 2.

### Drum input palette {#drum-input-palette}

When a percussion staff is selected and [node:278615,title="note input"] mode is ON, a window opens at the bottom of the screen called the __Drum input palette__. This window is _essential_ for [mouse](#mouse) input, and displays shortcuts for [computer keyboard](#computer-keyboard) input, but can be ignored if using a [MIDI keyboard](#midi-keyboard) or the virtual [Piano Keyboard](#piano-keyboard).

Each note in the palette represents a percussion instrument: hovering the mouse pointer over the note displays the instrument name.

[inline:Drum_input_tool_en.png=Drum input palette]

The letters A–G (shown above certain notes in the palette) are designated as shortcuts for entering particular instruments (bass drum, snare, closed hi-hat etc.), rather than referring to note pitches. They can be changed or reallocated as desired in the [Edit Drumset](#drumset) window.

When the __Drum input palette__ is open, double-clicking a note in the palette or entering a shortcut letter will add that instrument note to the percussion staff. The color of the note in the palette shows the voice allocated for that note—blue for voice 1, green for voice 2. This can be changed in the [Edit Drumset](#drumset) dialog if required.

This voice allocation applies only to keyboard and mouse entry of notes: entry via a MIDI keyboard or the virtual Piano keyboard allows any voice to be used.

### Edit Drumset {#edit-drumset}

To open the __Edit Drumset__ window, use one of the following options:

* Click on the <kbd><samp class="button">Edit Drumset</samp></kbd> button at the left of the __Drum input palette__.
* Right-click on a percussion staff and select "Edit Drumset...".

[inline:edit_drumset_en.png=Edit Drumset dialog] 

The __Edit Drumset__ dialog displays the percussion instruments available and the MIDI notes/numbers to which they are allocated. It also determines how each instrument is displayed on the staff— its name, position, notehead type and note-stem direction. _Any changes made here are automatically saved in the parent MuseScore file_. 

Clicking on a row in the left-hand column allows you to edit the display properties for that note as follows:

__Name__: The name you want displayed in the Drum input palette when you mouse over the note. Leave empty to remove this note from the Drum input palette.
__Notehead group__: Choose a notehead for that instrument from a drop-down list of options (_Note_: choosing "Custom" activates "Edit noteheads" (below).
__Edit Noteheads__: Allows you to customize the display further by specifying the noteheads for particular note durations.
__Default voice__: Assign to one of four voices. This does not affect input from a MIDI keyboard or the virtual Piano keyboard.
__Staff line__: This number indicates the staff line/space on which the note is displayed. "0" means that the note is displayed on the top line of the 5-line staff. Negative numbers move the note upwards step by step, while positive numbers move it downwards in the same way.
__Shortcut__: Assign a keyboard shortcut to enter that note.
__Stem Direction__: Auto, Up or down.

The customized drumset can be saved as a .drm file by pressing <kbd><samp class="button">Save As...</samp></kbd>. You can also import a customized drumset using the <kbd><samp class="button">Load...</samp></kbd> button.

### Sticking {#sticking}

To enter sticking symbols (R, L):

1. Select a start note;
2. From the menu, select <samp class="menu">Add</samp>&rarr;<samp class="menuitem">Text</samp>&rarr;<samp class="menuitem">Sticking</samp>. Alternatively, set up a keyboard shortcut to do the same thing in [node:278648,fragment="shortcuts",title="Preferences"];
3. Input the symbol just as you would normal text. To move forward or backwards to the next note, use the same keyboard shortcuts as for [node:278623, fragment="commands",title="chord symbols"]. 
4. To exit, press <kbd><kbd>Esc</kbd></kbd>, or click on a blank section of the score.

### Add drum roll {#roll}

To create a drum roll, use a [node:278584,title="Tremolo"].

### External links {#external-links}

* [node:70431,title="How to create jazz drum notation"] [MuseScore How-To]
* [Video tutorial: MuseScore in Minutes: Lesson 7 - Tablature and Drum Notation](https://www.youtube.com/watch?v=wnXLaZW9uA8)
* [Drum Parts](http://www.youtube.com/watch?v=KFj7v5S4Akw) [video]
* [Editing the Drum Palette in MuseScore 1.1](http://www.youtube.com/watch?v=PvVBHW-O5Ww) [video]
* [Saving Drumset Changes in MuseScore 1.1](http://www.youtube.com/watch?v=RgsxPLJxZRM) [video]
* [Guide to Drum and Percussion Notation](http://web.mit.edu/merolish/Public/drums.pdf)