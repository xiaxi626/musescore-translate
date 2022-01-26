MuseScore allows you to choose from any of several note input modes. [Step-time](#step-time) (see below) is the default, but others can be accessed by clicking the small dropdown arrow next to the note entry button on the [node:278641,fragment="toolbars",title="note input toolbar"].

  [inline:note_input_modes_3.3.4_EN.png=Note Input Modes]

### Step-time {#steptime}

This is the default method of note input and involves entering notes one at a time: first by selecting a note duration using the mouse or computer keyboard, then choosing a pitch using the mouse, computer keyboard, MIDI keyboard or [node:278615,fragment="virtual-piano-keyboard",title="virtual piano keyboard"].

For details see [node:278615,fragment="basic-note-entry",title="Basic note entry"].

### Re-pitch {#repitch}

Re-pitch mode allows you to correct the pitches of a sequence of notes while leaving their durations unchanged (not to be confused with [node:278589,title="Accidental: Respell pitches",fragment="respell-pitches"]).

1. Select a note as your starting point;
2. Select the __Re-Pitch__ option from the  __Note input__ drop-down menu; or use the keyboard shortcut, <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>I</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>I</kbd></kbd>).
3. Now enter pitches using the computer keyboard, MIDI keyboard or [node:278615,fragment="virtual-piano-keyboard",title="virtual piano keyboard"].

You can also use the __Re-pitch__ function  to create a new passage from an existing one of the same sequence of durations—by copying and pasting the latter, then applying Re-pitch.

### Rhythm {#rhythm}

Rhythm mode allows you to enter durations with a single keypress. Combining Rhythm and Re-pitch modes makes for a very efficient method of note entry.

1. Select your starting point in the score and enter Rhythm mode.
2. Select a duration from the note input toolbar, or press a duration shortcut (numbers 1-9) on your computer keyboard. A note will be added to the score with the selected duration. In contrast to [node:278615,fragment="basic-note-entry",title="Basic note entry"], pressing the <kbd><kbd>.</kbd></kbd> key will toggle dotting or not dotting all subsequent durations. All following rhythms will be dotted until the <kbd><kbd>.</kbd></kbd> key is pressed again. Unlike [node:278615,fragment="basic-note-entry",title="Basic note entry"], the dot is to be pressed prior to entering the rhythm.
3. Entering rests is similar to adding dotted notes. Press the <kbd><kbd>0</kbd></kbd> key to toggle entering rests. All rhythms entered will be rests until the <kbd><kbd>0</kbd></kbd> key is pressed again. This can be used concurrently with dotted notes.
4. Continue pressing duration keys to enter notes with the chosen durations.
5. Now use [Re-pitch mode](#repitch) to set the pitches of the notes you just added.

### Real-time (automatic) {#realtime-auto}

The Real-time modes basically allow you to perform the piece on a MIDI keyboard (or MuseScore's [node:278615,fragment="virtual-piano-keyboard",title="virtual piano keyboard"]) and have the notation added for you. However, you should be aware of the following limitations which currently apply:

* It is not possible to use a computer keyboard for Real-time input
* You cannot enter tuplets or notes shorter than the selected duration
* You cannot enter notes into more than one voice at a time

However, these restrictions mean that MuseScore has very little guessing to do when working out how your input should be notated, which helps to keep the Real-time modes accurate.

In the automatic version of Real-time input, you play at a fixed tempo indicated by a metronome click. You can adjust the tempo by changing the delay between clicks from the menu: <samp class="menu">Edit</samp> &rarr; <samp class="menuitem">Preferences...</samp> &rarr; <samp class="menuitem">Note Input</samp> (Mac: <samp class="menu">MuseScore</samp> &rarr; <samp class="menuitem">Preferences...</samp> &rarr; <samp class="menuitem">Note Input</samp>).

1. Select your starting position in the score and enter Real-time (automatic) mode.
2. Select a duration from the note input toolbar.
3. Press and hold a MIDI key or virtual piano key (a note will be added to the score).
4. Listen for the metronome clicks. With each click the note grows by the selected duration.
5. Release the key when the note has reached the desired length.

The score stops advancing as soon as you release the key. If you want the score to continue advancing (e.g. to allow you to enter rests) then you can use the [Real-time Advance shortcut](#realtime-advance) to start the metronome.

### Real-time (manual) {#realtime-manual}

In the manual version of Real-time input, you have to indicate your input tempo by tapping on a key or pedal, but you can play at any speed you like and it doesn't have to be constant. The default key for setting the tempo (called "Real-time Advance") is <kbd><kbd>Enter</kbd></kbd> on the numeric keypad (Mac: <kbd><kbd>Fn</kbd>+<kbd>Return</kbd></kbd>), but it is highly recommended that you change this to a MIDI key or MIDI pedal (see [below](#realtime-advance)).

1. Select your starting position in the score and enter Real-time (manual) mode.
2. Select a duration from the note input toolbar.
3. Press and hold a MIDI key or virtual piano key (a note will be added to the score).
4. Press the Real-time Advance key. With each press the note grows by the selected duration.
5. Release the note when it has reached the desired length.

#### Real-time Advance shortcut {#realtime-advance}

The Real-time Advance shortcut is used to tap beats in manual Real-time mode, or to start the metronome clicks in automatic Real-time mode. It is called "Real-time Advance" because it causes the input position to move forward, or "advance", through the score.

The default key for Real-time Advance is <kbd><kbd>Enter</kbd></kbd> on the numeric keypad (Mac: <kbd><kbd>Fn</kbd>+<kbd>Return</kbd></kbd>), but it is highly recommended that you assign this to a MIDI key or MIDI pedal via MuseScore's MIDI remote control. The MIDI remote control is available from the menu: <samp class="menu">Edit</samp> &rarr; <samp class="menuitem">Preferences...</samp> &rarr; <samp class="menuitem">Note Input</samp> (Mac: <samp class="menu">MuseScore</samp> &rarr; <samp class="menuitem">Preferences...</samp> &rarr; <samp class="menuitem">Note Input</samp>).

Alternatively, if you have a USB footswitch or computer pedal which can simulate keyboard keys, you could set it to simulate Enter on the numeric keypad.

When the notes are entered they will be placed just before the selected starting element, which will be highlighted with a square blue marker. The start element and any subsequent notes or rests within the same measure will be shifted forward. You can move the insertion point forward and backward using the arrow keys  <kbd><kbd>&rarr;</kbd></kbd> or <kbd><kbd>&larr;</kbd></kbd>, and the new insertion point will then be highlighted.

### Insert {#timewise}

__Insert__ Input mode (called __Timewise__ in versions prior to 3.0.2) allows you to insert and delete notes and rests within measures, automatically shifting subsequent music forwards or backwards. [node:278611,fragment="duration",title="Measure duration"] is automatically updated as you go.

1. Make sure you are in [node:278615,fragment="note-input-mode",title="Note input mode"], and that you have the element selected where you want to start inserting notes/rests;
2. Click on the arrow next to the Note input icon, and select __Insert__ (or if Insert is the current default, just press <kbd><kbd>N</kbd></kbd>);
3. Enter a note or rest as you would in [Step-Time](#steptime) mode. Each note is inserted before the current cursor position;
4. Move the cursor forward and backward if required (using the arrow keys), to change the insertion point.

Alternatively, if you have only one or two notes to insert, you may prefer to use a shortcut:

* Press <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Shift</kbd></kbd>) while adding the note by Mouse-click or keyboard  shortcut (A-G).

If, at any time, the total duration of the notes and rests within the measure does not match the [node:278579,title="time signature"], a small + or - sign will be shown above the measure.

 [inline:Irregular_measure_en.png=Irregular measure]

See also: [node:278656,fragment="timewise-delete",title="Remove selected range"] (Tools).

### Normal mode {#normal-mode}

To leave Note Input mode, click on the Note Input tool button, press <kbd><kbd>N</kbd></kbd>, or press <kbd><kbd>Esc</kbd></kbd>. This puts you in __Normal mode__, in which you can change durations and delete notes or rests as follows:

* If you select a note and press <kbd><kbd>Del</kbd></kbd> the note will be replaced by a rest of the same duration.
* If you select a note or rest and press <kbd><kbd>Ctrl</kbd>+<kbd>Del</kbd></kbd> the note/rest will be deleted, and subsequent notes moved backward (see [node:278656,fragment="timewise-delete",title="Remove selected range"]).
* If you reduce the duration of a note or rest  the remaining duration will be filled with rests.
* If you increase the duration of a note or rest it will subtract duration from the subsequent notes/rests to make up the duration. If this is done on the last note/rest in the measure, a note or rest with the required duration will be inserted in the start of the following measure, and the two will be tied together.

### See also {#see-also} 

* [node:278615,title="Note input"]
* [node:278613,title="Copy and paste"]

### External links {#external-links}

* [Video: Semi-Realtime MIDI Demo Part 1: New note entry modes](https://www.youtube.com/watch?v=SanyFSOI-Xs)
* [Introduction to the new Repitch Mode](https://www.youtube.com/watch?v=hgEKbX-xJJM) (YouTube)