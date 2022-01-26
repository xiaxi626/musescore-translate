A __tie__ is a curved line between two notes of the _same_ pitch, indicating that they are to be played as one combined note (see [external links](#external-links) below). Ties are normally created between adjacent notes in the same [node:278602,title="voice"], but MuseScore also supports ties between non-adjacent notes and between notes in different [node:278602,title="voices"].

In [node:278615,fragment="note-input-mode",title="note-input mode"], if you specify a tie immediately after entering a note or chord, the program automatically generates the correct destination notes to go with the ties. Or, you can simply create ties "after the fact," between existing notes. 

__Note__:  Ties, which join notes of the _same_ pitch, should not be confused with [node:278617,title="slurs"], which join notes of _different_ pitches and indicate _legato_ articulation.

### Add ties in Note Input mode {#add-ties-note-input}

The following command adds an identical tied chord to the selected chord.

1. Ensure that a note is selected (i.e. highlighted). This can be a single note, or part of a chord.
2. Select a new [node:278615,fragment="duration",title="note duration"] for the following note(s), if required (but see "Note" below).
3. Press <kbd><kbd>+</kbd></kbd> or the tie button, [inline:tie_button.png=tie button].

__Note__: This shortcut works, as described above, only if there is no chord following the selected note. If there is, then the duration is ignored and the tied note is added instead to the following chord.

### Add ties in Normal mode {#add-ties-normal-mode}

#### Method 1

1. [node:278652,title="Select"] one or more noteheads in the "_start_" chord.

  [inline:tie1.png=First note selected]

2. Press <kbd><kbd>+</kbd></kbd>, or the toolbar tie button, [inline:tie_button.png=tie button]:

  [inline:tie2.png=Tie to adjacent note].

Ties will be created between the selected note(s) and the next available note(s) of the same pitch. 

To remove ties, as of MuseScore 3.3.3, use the same command (toggle)

#### Method 2

This method ties all notes in the "_start_" chord (where possible):

1. [node:278652,title="Select"] the stem of the "_start_" chord;
2. Press <kbd><kbd>+</kbd></kbd>, or click on the toolbar __tie button__ [inline:tie_button.png=tie button].

Ties will be created between all the notes in the selected chord and the following notes of the same pitches.

To remove ties, as of MuseScore 3.3.3, use the same command (toggle).

### Add extra tied notes to a previously tied chord {#add-extra-tied-notes}

Occasionally you may need to return to an existing tied chord in order to add one or more extra tied notes. In this case a different command is used. For example:

[inline:add_tied_notes_1.png=Tied notes 1] 

1. Add the extra notes to the first chord. e.g.
   [inline:add_tied_notes_2.png=Tied notes 2] 
2. In Note input mode, and with any of the notes in the first chord selected, press <kbd><kbd>Alt</kbd>+<kbd>+</kbd></kbd>. Corresponding notes are added to the following chord and the extra notes are tied:
 [inline:add_tied_notes_3.png=Tied notes 3] 

### Add ties to unison notes {#ties_unison_notes}

A workaround is required to create ties between unison notes:

1. Create the first note as usual;
2. Any additional unison notes should be added at an interval _other_ than unison: e.g. 2nd, 3rd, 4th etc.
3. Create a tied chord (as shown [above](#add-ties-normal-mode)): e.g. 
 [inline:unisons_1.png=tied non-unisons] 
4. [node:278615, fragment="move-notes-up-down",title="Move"] the unison note(s) into position: e.g.
  [inline:unisons_2.png=tied unisons] 

### Flip a tie {#flip-tie}

<kbd><kbd>X</kbd></kbd> flips the direction of a selected tie, from above the note to below the note, or vice-versa.

### See also {#see-also}

[node:278617,title="Slur"]

### External links {#external-links}

* [node:267614,title="How to create ties leading into a 2nd ending"] (MuseScore HowTo)
* [Ties (music)](http://en.wikipedia.org/wiki/Tie_(music)) at Wikipedia 
