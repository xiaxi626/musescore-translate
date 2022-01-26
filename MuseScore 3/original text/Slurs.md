A __slur__ is a curved line between two or more notes indicating that they are to be played _legato_—smoothly and without separation. Not to be confused with [node:278616,title="Ties"], which join two notes of the same pitch.

There are a number of ways to add a slur to a score, and all may be useful depending on the context (adding a slur from the [node:278592,title="lines palette"] is also possible but not recommended).

### Add slur in note-input mode {#note-input-mode}

1. While in <samp class="mode">[node:278615,fragment="note-input-mode",title="Note input mode"]</samp>, type in the first note in the slurred section;
2. Press <kbd><kbd>S</kbd></kbd> to begin the slurred section;
3. Type in the remaining notes in the slurred section;
4. Press <kbd><kbd>S</kbd></kbd> again to end the slurred section.

### Add slur in Normal mode {#normal-mode}

#### Method 1 {#first-method}

1. Make sure you are in [node:278598,fragment="normal-mode",title="Normal mode"];
2. Select the note where you want the slur to start:

    [inline:Slur1.png=First note selected]

3. Press <kbd><kbd>S</kbd></kbd> to add a slur extending to the next note:

    [inline:Slur2.png=Slur to adjacent note]

4. (Optional) Hold <kbd><kbd>Shift</kbd></kbd> and press <kbd><kbd>&rarr;</kbd></kbd> (right arrow key) to extend the slur to the next note. Repeat as required:

    [inline:Slur3.png=Three-note slur]

5. (Optional) Press <kbd><kbd>X</kbd></kbd> to flip the slur direction:

    [inline:Slur4.png=Slur above note stems]

6. Press <kbd><kbd>Esc</kbd></kbd> to exit <samp class="mode">[node:278587,title="edit mode"]</samp>:

    [inline:Slur5.png=Slur no longer in edit mode]

#### Method 2 {#second-method}

1. Make sure you are in [node:278598,fragment="normal-mode",title="Normal mode"];
2. Select the note where you want the slur to start;
3. Choose one of the following options:
 * To add a slur to one voice _only_: Hold down <kbd><kbd>Ctrl</kbd></kbd>  (Mac: <kbd><kbd>Cmd</kbd></kbd>) and select the last note that you want the slur to cover.
 * To add slurs to _all_ voices: Hold down <kbd><kbd>Shift</kbd></kbd>  (Mac: <kbd><kbd>Cmd</kbd></kbd>) and select the last note that you want the slurs to cover.
4. Press <kbd><kbd>S</kbd></kbd>.

### Adjust slur {#adjustments}

If you only want to adjust the _position_ of a slur:

1. Select the slur;
2. Use any of the following methods:
 * Drag the slur.
 * Adjust the horizontal and vertical offset values in the [node:278642,fragment="element",title="Inspector"].

To adjust _all_ the properties of a slur (length, shape and position):

1. Make sure you are _not_ in <samp class="mode">note input mode</samp>;
2. Go into <samp class="mode">[node:278587,title="Edit mode"]</samp> on the slur;
3. Click on a handle to select it, or use <kbd><kbd>Tab</kbd></kbd> to cycle through the handles;
4. To move the _left and right handles_ from note to note, use the following shortcuts:
 * <kbd><kbd>Shift</kbd>+<kbd>&rarr;</kbd></kbd>: Move to next note.
 * <kbd><kbd>Shift</kbd>+<kbd>&larr;</kbd></kbd>: Move to previous note.
 * <kbd><kbd>Shift</kbd>+<kbd>&uarr;</kbd></kbd>: Move to lower voice (voice 2 to voice 1 etc.).
 * <kbd><kbd>Shift</kbd>+<kbd>&darr;</kbd></kbd>: Move to higher voice (voice 1 to voice 2 etc.).
5. To adjust the position of _any_ handle, use any of the following methods:
 * Drag the handle.
 * Use the arrow keys for fine adjustment (0.1 [node:278598,fragment="spatium",title="sp."] at a time). For larger adjustments (1 [node:278598,fragment="spatium",title="sp."] at a time) use <kbd><kbd>Ctrl</kbd>+<kbd>&rarr; &larr; &uarr; &darr;</kbd></kbd>.
6. Press <kbd>Esc</kbd></kbd> to exit <samp class="mode">edit mode</samp>.

__Note__: The two outer handles adjust the start and end of the slur, whilst the three handles on the curve adjust the contour. The middle handle on the straight line is used to move the whole slur up/down/left/right.

### Extended slurs {#extended-slurs}

A slur can span several systems and pages. The start and end of a slur is anchored to a note/chord or rest.  If the notes are repositioned due to changes in the layout, stretch or style, the slur also moves and adjusts in size. 

This example shows a slur spanning from the bass to the treble clef. Using the mouse, select the first note of the slur, hold down <kbd><kbd>Ctrl</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd></kbd>) and select the last note for the slur, and press <kbd><kbd>S</kbd></kbd> to add the slur.

[inline:Slur_between_2_staves.png=Slur across staves]

<kbd><kbd>X</kbd></kbd> flips the direction of a selected slur.

### Dotted/dashed slurs {#dotted}

Dotted slurs are sometimes used in songs where the presence of a slur varies between stanzas. Dotted slurs are also used to indicate an editor's suggestion (as opposed to the composer's original markings). To change an existing slur into a dotted or dashed slur, select it and then in Inspector (<kbd><kbd>F8</kbd></kbd>) change `Line type` from `Continuous` to `Dotted` or `Dashed`.

### See also {#see-also}

* [node:278616,title="Tie"]
* [node:278587,title="Edit mode"]
* [node:278615,title="Note input"]