This is a draft. Feel free to help review this tutorial

---

This short tutorial guides you through the process of entering notes in MuseScore with the NVDA screen reader. If you are a screen reader user new to MuseScore and you have not already read the tutorial on [creating a new score in MuseScore with NVDA](https://musescore.org/en/node/113581), it is recommended you read this first.

This tutorial assumes you have MuseScore 3.5.0 or above, and [NVDA 2016.1](http://www.nvaccess.org/download/) or later installed. If you have a Braille display, it is suggested that you use this as well.

### Preparing to input notes

With a new score open in MuseScore, ensure that focus is placed where you wish to start entering notes. If you wish to start at the beginning of the score press <kbd><kbd>Ctrl</kbd>+<kbd>Home</kbd></kbd>. Alternatively use <kbd><kbd>Ctrl</kbd>+<kbd>F</kbd></kbd> to bring up a dialog box from where you can enter a bar number.

In order to enter notes into your score you must first switch to Note Input mode. You can do this by pressing <kbd><kbd>N</kbd></kbd>. This function works as a toggle, so pressing <kbd><kbd>N</kbd></kbd> again or pressing <kbd><kbd>Esc</kbd></kbd> will exit note input mode.

Note that NVDA will not currently confirm the entry or exit of Note Input mode. You can check this by going to the Note menu with <kbd><kbd>Alt</kbd>+<kbd>N</kbd></kbd> where the first item is Note Input. NVDA will announce “checked” if this is active, and nothing if it is not. Sighted users will see a flashing cursor appear to the left of the stave in Note Input mode.

### Selecting the duration of notes/rests

Before you enter notes and rests, MuseScore needs to know their duration. This can be selected by using the number row or number pad. 1 gives the shortest length of a hemidemisemiquaver (64th note), with each number doubling the length, up to 8 for double breve. 5 gives a crotchet (quarter note). Pressing the full stop (dot) adds a duration dot to a note. Pressing it again removes the duration dot. All notes and rests entered subsequently will be of the same duration until you alter this.

Note that NVDA will only announce the selected duration when not in Note Input mode.

If you choose a duration longer than the remaining space in the current bar, MuseScore will fill the bar with the longest possible duration.

### Selecting pitch

With Note Input mode turned on, the notes C, D, E, F, G, A, and B can be input using the qwerty keyboard equivalents. MuseScore will enter the note closest in pitch to the previous note. Once entered, you can:

*   Move the note up and down by a semitone by pressing <kbd><kbd>Up</kbd></kbd> and <kbd><kbd>Down</kbd></kbd> arrow.
*   Move the note up and down using only notes in the key signature by pressing <kbd><kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>Up</kbd></kbd> and <kbd><kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>Down</kbd></kbd>.
*   Move the note up and down by an octave by pressing <kbd><kbd>Ctrl</kbd>+<kbd>Up</kbd></kbd> and <kbd><kbd>Ctrl</kbd>+<kbd>Down</kbd></kbd>.

To select the enharmonic equivalent, use the letter <kbd>J</kbd>. This will change the selected note between, for example, C sharp and D flat.

To input a rest with the currently selected duration, press <kbd><kbd>0</kbd></kbd>.

To repeat the last note or rest entered, press <kbd><kbd>R</kbd></kbd>.

If you make a mistake, it is best either to use **Undo** by pressing <kbd><kbd>Ctrl</kbd>+<kbd>Z</kbd></kbd>, or simply to arrow back onto the incorrect note and correct it.

### Navigating through a score

Once you have entered notes into your score, you can use the <kbd>Left</kbd> and <kbd>Right</kbd> arrow keys to move through one note or rest at a time. Use <kbd><kbd>Ctrl</kbd>+<kbd>Right</kbd></kbd> and <kbd><kbd>Ctrl</kbd>+<kbd>Left</kbd></kbd> to move forwards and backwards one bar at a time. 

To move between the different voices and staves, press <kbd><kbd>Alt</kbd>+<kbd>Up</kbd></kbd> and <kbd><kbd>Alt</kbd>+<kbd>Down</kbd></kbd>.

As you move around your score, the screen reader will give details of the note or rest that you navigate to.

### Score Playback

To play your piece, press <kbd>Space</kbd>. Press <kbd>Space</kbd> again to stop.

### Altering the duration of notes/rests already entered

With note input mode turned off, arrow to the note or rest to be altered. Then choose the duration using the number row. If you choose a longer note or rest, this will override notes/rests already in the bar. If you choose a shorter note/rest, additional rests will be added to complete the bar.

### Entering Chords

To enter a chord (two or more notes of the same duration), input the first note as above, then input the remaining notes in the chord whilst holding down the <kbd><kbd>Shift</kbd></kbd> key. The first note you enter will be the lowest note in the chord.

### Working in Voices

Where two or more independent parts are printed on one stave, these are known as ‘voices’. When working in a score with two or more voices, input the first voice part for a complete bar. Then press <kbd><kbd>Esc</kbd></kbd> to leave Note Input mode. With focus on the first note of the bar in voice 1, press <kbd><kbd>N</kbd></kbd> to enter Note Input mode, then <kbd><kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>2</kbd></kbd> to select voice 2 and input the notes for voice 2. You can cycle between voices using <kbd><kbd>Alt</kbd>+<kbd>1</kbd></kbd>, <kbd><kbd>Alt</kbd>+<kbd>2</kbd></kbd> etc.

### Deleting notes/rests

There are several ways to delete notes you no longer want. Within MuseScore, the <kbd><kbd>Backspace</kbd></kbd>, <kbd><kbd>Del</kbd></kbd> and <kbd><kbd>Ctrl</kbd>+<kbd>Z</kbd></kbd> retain their standard Windows functions.

### Further information

The online handbook available from the MuseScore Help menu gives comprehensive details of working in MuseScore. 