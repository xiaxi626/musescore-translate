A __voice__ is a musical line or part which can have its own rhythm independently of other voices on the _same_ staff. Voices are sometimes called "layers" in other notation software.

You can have up to 4 __voices__ on _each_ staff line. In a polyphonic measure, __voice 1__ (and 3) usually takes the _up-stem notes_ and __voice 2__ (and 4) takes the _down-stem_ notes.

[inline:Voices_Diagram_en.png=Staff with several voices]

__N.B.__ Be careful not to confuse the concept of MuseScore voices (1, 2, 3, 4) with the order of voices found in SATB vocal scores:

* In __Open score SATB__ (where four staves are used for the four voices), use (MuseScore) voice 1 in each staff.
* In __Close/Closed score SATB__ (where two staves are used for the four voices, e.g., as in hymnals), use only (MuseScore) voices 1 and 2 for both upper _and_ lower staves.
* There is no need to use (MuseScore) voices 3 and 4 unless there are more than two parts in the _same_ _staff_. This means that in the bass clef of a “close score”, the tenor is voice 1 and the bass is voice 2—beginners often without thinking assign the bass to 1, resulting in stem-direction confusion, or assign tenor to voice 3 and bass to voice 4, which then leads to confusing rests appearing in voice 1 (which cannot be deleted).

### How voices are displayed

[node:278652,title="Selecting"] a section of the score highlights each voice in a different color: voice 1 blue, voice 2 green, voice 3 orange and voice 4 purple.

 [inline:VoicesColoured.png=Voices colored] 

### When to use voices {#using-voices}

  - If you need stems pointing in opposite directions within a chord, on a single staff.
  - If you need notes of different durations within a single staff, played simultaneously.

### How to enter notes in different voices {#instructions}

The following instructions show you how to notate a passage of music in two voices:

1. __Enter voice 1 notes first__: Make sure you are in _[node:278615,fragment="note-input-mode",title="note input mode"]_ :  the Voice 1 button becomes highlighted in blue in the toolbar. [inline:Button-Voice_Selector.png=Voice selector] Enter the notes in the top voice first. On inputting, some notes may have down-stems, but these will flip automatically when the second voice is added. 

 The following excerpt shows a treble staff with just the voice 1 notes entered:

 [inline:voices0.png=Voice 1 notes]

2. __Move cursor back to start of section__: When you have finished entering a section of voice 1 notes, press the <kbd><kbd>&larr;</kbd></kbd> key repeatedly to move the cursor, note-by-note, back to the first note of the section; or alternatively use <kbd><kbd>Ctrl</kbd>+<kbd>&larr;</kbd></kbd> (Mac:<kbd><kbd>Cmd</kbd>+<kbd>&larr;</kbd></kbd>) to move the cursor back one measure at a time. Or else you can simply exit _note input mode_ (press <kbd><kbd>Esc</kbd></kbd>) and click directly on the first note.

3. __Enter voice 2 notes__: Make sure you are in note-input mode and that the voice 1 note at the beginning of the section is selected. Click on the "Voice 2" button [inline:Button-Voice_2.png=Voice 2 button] (on the right of the toolbar), or use the shortcut <kbd><kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>2</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Alt</kbd>+<kbd>2</kbd></kbd>). Enter all the lower voice notes (down-stem).
 
 The following image shows the above example after the addition of voice 2 notes:
 [inline:voices2.png=Voices 1 and 2]

### Deleting and hiding rests {#delete-hide-rests}

All rests can be made [node:278642,fragment="element",title="invisible"], if required: select the desired rest(s) and press <kbd><kbd>V</kbd></kbd>, or uncheck the "Visible" checkbox in the [node:278642,fragment="element",title="Inspector"]. Rests in voices 2, 3 or 4 (but _not_ voice 1) can also be _deleted_ (by selecting them and pressing <kbd><kbd>Delete</kbd></kbd>) but it is not recommended: make them invisible instead.

A voice 1 rest can only be deleted by removing that part of the measure from the score as well: see  [node:278656,fragment="timewise-delete",title="Remove selected range"]; or [node:278611,fragment="delete",title="Delete measure(s)"].

#### Restoring deleted rests {#restoring-deleted-rests}

If a rest has been deleted in voices 2-4, you will need to restore it before you can enter a note on that beat in that voice (the problem may arise, for example, in imported [node:278612,fragment="musicxml",title="XML"] or   [node:278612,fragment="midi",title="MIDI"] files). The easiest way to fix such a measure is to exchange that voice with voice 1 twice. For the exact method, see [Exchange voices of notes](#exchange-voices) (below).

### Exchange voices of notes {#exchange-voices}

To swap the notes between any two voices:

1. [node:278611,fragment="select",title="Select"] one or more continuous measures (or a [node:278652,fragment="range-select",title="range"] of notes);
2. From the Menu bar, select <samp>Tools</samp> &rarr; <samp>Voices</samp>;
3. Select the option for the two voices you want to exchange.

__Notes__: (a) The selection can encompass content of any voice, but only two will be processed at once. (b) If you select a partial measure the operation will still apply to the whole measure.

### Move notes to another voice (without swapping) {#change-voice}

You can also move notes from one voice to another (without note-swapping):

1. Ensure you are not in _note input mode_.
2. Select one or more noteheads (in any voice).
3. Click on the destination voice in the [node:278641,fragment="toolbars",title="Note Input toolbar"] or use the shortcut <kbd><kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>1–4</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Alt</kbd>+<kbd>1-4</kbd></kbd>).

__Note__: For a successful move, the following conditions need to be met:

* The chord in the destination voice must be the same duration as the note to be moved there.
* Alternatively, if the destination voice is occupied by a rest, it must be of sufficient duration to accommodate the moved note.
* Notes should _not_ be [node:278616,title="tied"].

### Navigate between voices {#navigate-between-voices}

To select a note in a _higher_-numbered voice than the current one:

1. Use <kbd><kbd>Alt</kbd></kbd> + <kbd><kbd>↓</kbd></kbd>, to move the selection to the bottommost note in the current voice;
2. Press <kbd><kbd>Alt</kbd></kbd> + <kbd><kbd>↓</kbd></kbd>, to move to the higher-numbered voice;
3. Repeat any of the above steps, as necessary, until the desired note is selected.

To select a note in a _lower_-numbered voice than the current one:

1. Use <kbd><kbd>Alt</kbd></kbd> + <kbd><kbd>↑</kbd></kbd>, to move the selection to the topmost note in the current voice;
2. Press <kbd><kbd>Alt</kbd></kbd> + <kbd><kbd>↑</kbd></kbd>, to move to the lower-numbered voice.
3. Repeat any of the above steps, as necessary, until the desired note is selected.

### See also {#see-also}

- [node:278609,fragment="voices",title="Keyboard shortcuts: Voices "]
- [node:278661,fragment="shared-noteheads",title="Noteheads: Shared noteheads"]

### External links {#external-links}

  - [node:12345,title="How to merge/combine/implode two staves in one with two voices"] (MuseScore HowTo)
  - [node:8640,title="How to input multiple notes on a staff with different durations"] (MuseScore HowTo)
  - [Video tutorial: How To Write Two Parts On One Staff: Voices](http://www.youtube.com/watch?v=R_BA-hjjJ0g)
