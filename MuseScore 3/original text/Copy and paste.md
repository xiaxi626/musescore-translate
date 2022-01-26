MuseScore supports standard __copy__, __cut__, __paste__ and __swap with clipboard__ operations. These commands can be applied to a range of:

* __Musical notes__: e.g. to repeat a section of music, or shift a passage by a beat or a measure.
* __Other score elements__: such as articulations, staff text, dynamics, fingering etc.

Copy/cut/paste/swap commands are accessed in three ways:

* From the __Edit menu__ (above the document window).
* From the menu displayed by __right-clicking__ on an element or range of elements.
* Using one of the standard __keyboard shortcuts__.

### Summary of commands {#command-summary}

Command | Kbd Shortcut (Win) | Kbd Shortcut (Mac) |  Right-click menu | Main menu
-|-|-|-|-
__Cut__ | <kbd><kbd>Ctrl</kbd>+<kbd>X</kbd></kbd> | <kbd><kbd>Cmd</kbd>+<kbd>X</kbd></kbd> | Cut | Edit &rarr; Cut
__Copy__ | <kbd><kbd>Ctrl</kbd>+<kbd>C</kbd></kbd> | <kbd><kbd>Cmd</kbd>+<kbd>C</kbd></kbd> | Copy |Edit &rarr; Copy
__Paste__ | <kbd><kbd>Ctrl</kbd>+<kbd>V</kbd></kbd> | <kbd><kbd>Cmd</kbd>+<kbd>V</kbd></kbd> | Paste |Edit &rarr; Paste
__Swap with clipboard__ | <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>X</kbd></kbd> | <kbd><kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>X</kbd></kbd> | Swap with Clipboard | Edit &rarr; Swap with clipboard

__Note__: Before carrying out a copy, cut, paste or swap procedure, you should be in [node:278598,fragment="normal-mode",title="normal mode"]. Press the <kbd><kbd>Esc</kbd></kbd> key to exit into normal mode.

### Notes {#notes}

You can cut, copy, paste or swap notes as follows:

#### Copy or cut {#copy-or-cut-notes}

__To copy/cut a _single_ chord__

1. Hold down <kbd><kbd>Shift</kbd></kbd> and click on a note in the chord.
2. Apply a __Copy__ or __Cut__ option (see [table](#command-summary) above).

__To copy/cut a _range_ of chords__

1. <kbd><samp class="mousebutton">Click</samp></kbd> on the first note or measure that you want to select.
2. <kbd><kbd>Shift</kbd>+<samp class="mousebutton">Click</samp></kbd> on the last note or measure that you want to select. A blue rectangle highlights the region you selected. 
3. Apply a __Copy__ or __Cut__ option (see [table](#command-summary) above).

#### Paste {#paste-notes}

1. <kbd><samp class="mousebutton">Click</samp></kbd> on the note or measure where you want your pasted selection to begin.
2. Apply a __Paste__ option (see [table](#command-summary) above).

#### Swap with Clipboard {#swap-notes}

The __swap with clipboard__ operation combines two commands into one: (1) First it overwrites a selected part of the score with the contents of the clipboard, just like the _paste_ command; (2) Secondly, it transfers the overwritten part of the score _back to_ the clipboard, just like the _copy_ command.

It can be used, for example, to swap two equal-length sections of a score, __A__ and __B__:

1. Select section __A__, then apply the [cut](#command-summary) command;
2. Clear the selection (by pressing <kbd><kbd>Esc</kbd></kbd> or clicking on a blank area of the document window);
3. Press <kbd><kbd>Shift</kbd></kbd> and click on a note at the start of section __B__. Or, if __B__ begins at the start of a measure, you can also simply [node:278611,fragment="select",title="select"] the measure;
4. Apply a __Swap with clipboard__ option (see [table](#command-summary) above).
5. Section __B__ is now in the clipboard. [Paste](#command-summary) it back to the blank area of score left by step "1."

#### Copy pitch of a single note only {#copy-pitch-only}

It is possible to copy the _pitch_ of a note _only_ (and no other properties), by clicking on the notehead and applying the standard copy and paste, or copy and swap procedure. The pitch of the destination note changes to match that of the copied note but the duration remains the same.

### Other elements {#other-elements}

Some elements such as staff text, dynamics, fingering, etc. can be cut, copied and pasted only _one at a time_. However, other elements support "[node:278652,fragment="list-select",title="multiple-selection"]" cut/copy/paste: such as  [node:278662,title="articulations"] (sforzato, staccato etc.),  [node:278639,title="fretboard diagrams"], and [node:278623,title="chord symbols"].

__Note__: The Swap with clipboard command is only intended for use with sections of music and not other score elements.

#### Copy or cut {#copy-or-cut-elements}

1. [node:278652,title="Select"] the element (or elements).
2. Apply a __Copy__ or __Cut__ option (see [table](#command-summary) above).

#### Paste {#paste-elements}

1. <kbd><samp class="mousebutton">Click</samp></kbd> on the note where you want your pasted selection to begin.
2. Apply one of the __Paste__ options (see [table](#command-summary) above).

In the case of articulations, they are pasted to the destination notes in exactly the same order (continuous or intermittent) as they were in the initial selection.

### Quick repeat {#quick-repetition}

To quickly copy and paste a note, measure, or passage:

1. Select a chord, measure, or passage as described [above](#copy-or-cut-elements).
2. Press <kbd><kbd>R</kbd></kbd> .

MuseScore copies and pastes the selected notation to a point immediately after the last note in the selection. Any existing music in the destination range is replaced.

### Duplicate {#duplicate}

To instantaneously copy and paste a text element, line, or other object:

1. Hold down <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Shift</kbd></kbd>), click on the element and drag it anywhere in the score.
2. Release the mouse button, and the selected element is cloned to the new location.

### Paste half/double duration (version 3.1 and above) {#paste-half-double-duration}

These commands allows you to copy/cut a section of the score, then paste it back anywhere with all the note durations either halved or doubled.

1. In Normal mode, [node:278652,fragment="shift-click-selection",title="select a range of notes"] in the score;
2. [node:278613,title="Cut or copy"] the range;
3. Select a destination note (or measure);
4. From the menu, select one of the following:
 * <samp class="menu">Edit</samp>&rarr;<samp class="menuitem">Paste Half Duration</samp>.
 * <samp class="menu">Edit</samp>&rarr;<samp class="menuitem">Paste Double Duration</samp>.

### Selection filter {#selection-filter}

The __Selection Filter__ allows you to choose _exactly_ which voices and elements you want to include in your selection. 

* To display the Selection filter, press <kbd><kbd>F6</kbd></kbd> (Mac: <kbd><kbd>Fn</kbd>+<kbd>F6</kbd></kbd>); or from the menu, choose <samp class="menu">View</samp>&rarr;<samp class="menuitem">Selection Filter</samp>.

The Selection Filter appears by default below the [node:278614,title="Palettes"]. To change the viewing location, see [node:278641,fragment="side-panels",title="Viewing and Navigation: Side panels"].

__Example__: Suppose you want to copy measures 1 and 2 in the following passage (see image), to give measures 3 and 4:

 [inline:selection_filter_example.png=Selection filter example] 

1. Make sure the Selection Filter is displayed (see above);
2. Uncheck the "Articulations & Ornaments" and "Slurs" tickboxes;
3. Copy and paste the desired measures (in this example, 1-2 into 3-4).
  
__Note__: The Selection Filter works with the [swap with clipboard](#swap-notes) command as well.

### See also {#see-also}

If you want to change notes without altering the rhythm, you may combine [node:278675,fragment="repitch",title="re-pitch mode"] with copy and paste.

### External links {#external-links}

* [node:314674,title="How To Paste Special - Changing note duration"] (MuseScore HowTo)
* [Video tutorial: Lyrics, copying & dynamics](http://www.youtube.com/watch?v=e55-YnhSk-s)