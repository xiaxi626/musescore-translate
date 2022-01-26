A number of useful commands can be found in the <samp class="menu">Tools</samp> menu.

### Transpose {#transpose}

This opens the [node:278571,fragment="automatic-transpose",title="Transpose"] dialog with various options for transposing passages of music.

See [node:278571,fragment="automatic-transpose",title="Automatic transposition"].

### Explode {#explode}

The __explode__ command allows you to select a passage of music _in a single staff_ and split (explode) the chords into their constituent notes or voices as follows:

* If the passage is all in voice 1, the top note of the chord is retained on the top staff, while the lower notes are moved to subsequent staves.
* If the passage contains multiple [node:278602,title="voices"], voice 1 notes are retained on the top staff, while other voices are moved to subsequent staves. All exploded voices are now in voice 1.

__To explode a section of the score__:

1. Ensure that there are enough staves underneath the source staff to receive the exploded notes. Create extra staves if necessary using the [node:278622,fragment="create-new-score-adjustments-after-creation",title="Instruments"] dialog.
2. Choose one of two options:
      *  [node:278652,fragment="range-select",title="Select"] a range of measures in the source staff: this allows all notes to be exploded if there are enough staves available.
      *  [node:278652,fragment="range-select",title="Select"] a range of measures that includes both the  source staff and also extends downwards to include one or more destination staves: This limits the number of exploded notes/voices to the number of selected staves.
4. Choose <samp class="menu">Tools</samp>&rarr;<samp class="menuentry">Explode</samp>.

__Notes__: (1) If the selection is all in voice 1, MuseScore will discard the lowest note(s) of any chord that contains more notes than the number of staves in the selection. (2) If the selection is all in voice 1, and If a given chord has fewer notes than the number of destination staves, then notes will be duplicated as needed so that every staff receives a note. (3) Any existing music in the destination staves is overwritten. (4) If you select a partial measure, the explode command will automatically expand it to a full measure.

### Implode {#implode}

The __Implode__ command works in the opposite way to "explode":

* With _one staff_ selected, all notes in voices 1–4 are combined into voice 1.
* With _multiple staves_ selected, the notes in the _second staff_ are copied to the first available voice in the _top staff_, the notes in the _third staff_ are copied to the next available voice in the _top staff_ and so on.

#### Apply implode to a single staff {#implode-single-staff}

1.  [node:278652,fragment="range-select",title="Select"] a range of measures in the desired staff.
2. Choose <samp class="menu">Tools</samp>&rarr;<samp class="menuitem">Implode</samp>.

All selected notes in the staff are now displayed in voice 1.

#### Apply implode to multiple staves {#implode-multiple-staves}

1. Ensure that there is only one voice in each staff.
2. [node:278652,fragment="range-select",title="Select"] a range of measures in the _destination staff_ and extend this selection downwards to include the other staves to be imploded.
2. Choose <samp class="menu">Tools</samp>&rarr;<samp class="menuitem">Implode</samp>.

### Voices {#voices}

This allows you to swap the voices of a selected measure-range of notes. See [node:278602,fragment="exchange-voices",title="Exchange voices"].

### Measure {#measure}

Join or split measures. See [node:278611,fragment="split-join",title="Measure operations: Split and join"].

### Remove selected range {#timewise-delete}

This command is used to completely _remove_ an element, or range of elements from the score.

__To remove measures (including partial measures)__:

1. Select a [node:278652,fragment="range-select",title="range of notes/rests"], or a [node:278611,fragment="select",title="range of measures"];
2. Use one of the following methods:
 * Press <kbd><kbd>Ctrl</kbd>+<kbd>Del</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Del</kbd></kbd>).
 * Select <samp class="menu">Tools</samp>&rarr;<samp class="menuitem">Remove selected range</samp>.

__Note__: If the selected range includes only _part_ of a measure, the result will include a measure of smaller duration than the indicated [node:278579,title="Time Signature"]. This is indicated by a small - (minus) sign just above the system.

__To join measures__:

1. Select (i.e. click on) a barline;
2. Use one of the following methods:
 * Press <kbd><kbd>Ctrl</kbd>+<kbd>Del</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Del</kbd></kbd>).
 * Select <samp class="menu">Tools</samp>&rarr;<samp class="menuitem">Remove selected range</samp>.

The following table is a comparative summary of the _Delete_ and _Remove selected Range_ commands when applied to _single_ elements:

|Selected Element|Apply Delete|Apply Remove selected range|
-|-|-
|__Note__|Replaces with rest|Removes score section|
|__Rest (voice 1)__|No effect|Removes score section|
|__Rest (voices 2-4)__|Deletes rest|Removes score section|
|__Barline__|No effect|Deletes barline and joins measures|
|__Measure__|Replaces contents with rest|Removes measure|

__Note__: To _insert_ notes, see [node:278675,fragment="timewise",title="Insert"].

### Fill with slashes {#fill-with-slashes}

This command fills the selection with slashes, one per beat:

1. [node:278611,fragment="select",title="Select"] one or more measures;
2. From the menu, select <samp class="menuitem">Tools</samp>&rarr;<samp class="menuentry">Fill With Slashes</samp>.

If a measure is empty the slashes are added to voice 1, full-sized and centered on the middle line of the staff:

[inline:Slash_notation.png=Slash notation]

__Notes__: (1) If there are already notes in a measure in the selection, the command will put the slashes into the _first available empty voice_.  (2) Voice 2 slashes are full-sized and centered on the middle line of the staff; voices 3 slashes appear _small_ and _above_ the staff; voice 4 slashes are _small_ and _below_ the staff. (3) If a measure contains notes in all 4 voices, voice 1 will be overwritten. (4) All slashes are set to not transpose or playback.

### Toggle rhythmic slash notation {#toggle-rhythmic-slash-notation}

This command toggles selected notes between normal notes and rhythmic slash notation:

1. [node:278652,fragment="range-select",title="Select"] a range of notes or measures (_Note_: use the [node:278613,title="selection filter",fragment="selection-filter"] if you need to exclude certain voices);
2. From the menu, select <samp class="menu">Tools</samp>&rarr;<samp class="menuentry">Toggle Rhythmic Slash Notation</samp>.

The selected noteheads are changed to _slash noteheads_ which do not transpose or playback.

[inline:Rhythmic slash_notation.png=Rhythmic slash notation]

Slash-notehead notes in _voices one or two_ are fixed to the middle staff line; those in _voices three or four_ are small ("accent" notation) and fixed above or below the staff:

[inline:accent-slash-notation.png=Accent notation]

In _percussion staves_, notes in voices 3 and 4 are not converted to small slashes but to small notes above or below the staff.

[inline:Rhythmic Slash - percussion.png=Rhythmic slash - percussion]

### Respell pitches {#respell-pitches}

Corrects accidentals to fit in with the current key signature. See [node:278589,fragment="respell-pitches",title="Accidentals: Respell pitches"].

### Regroup Rhythms {#regroup-rhythms}

This option corrects note [node:278616,title="ties"], durations and [node:278579,fragment="change-default-beaming",title="beaming"] so that they are grouped according to standard music notation practice. For example:

Before:
 [inline:regroup_rhythms_before.png]
After:
  [inline:regroup_rhythms_after.png] 

Any notes that are tied and are the same length as a dotted note will be changed to the dotted note with two limitations. (i) Only the last note of a group of tied notes will have a single dot. Notes with more than one dot are not produced using this option. (ii) Dotted notes will not span from one group of beamed notes to another unless their duration is the same as all of the beam groups it covers. Any notes with more than one dot will be regrouped according to the above rules.

To apply:

1. [node:278652,title="Select"] the section of the score you want to reset. If nothing is selected, the operation will apply to the whole score;
2. Select <samp class="menu">Tools</samp>&rarr;<samp class="menuitem">Regroup Rhythms</samp>.

__Note__: This is an experimental feature and there are known bugs. Articulations and ornaments are deleted and some pitches respelled. Ties across barlines may be lost on UNDO.

### Resequence rehearsal marks {#resequence-rehearsal-marks}

The __Resequence Rehearsal Marks__ command allows you to re-order the numbering/lettering of [node:278647,title="rehearsal marks"] if, for any reason, they have got out of sequence. For details see [node:278647,fragment="resequence-rehearsal-marks",title="Automatically resequence rehearsal marks"].

### Unroll Repeats (version 3.1 and above) {#unroll-repeats}

This command creates a copy of the score (in a new tab), eliminates the [node:278591,title="repeat barlines"] and notates the repeat sections in full instead. 

### Copy lyrics to clipboard {#copy-lyrics-to-clipboard}

This command copies _all_ the lyrics of the score to the clipboard:

* From the menu, select <samp class="menu">Tools</samp>&rarr;<samp class="menuentry">Copy Lyrics to Clipboard</samp>.

### Image capture {#image capture}

Take a snapshot of a selected part of the document window. PNG, PDF and SVG formats are supported. See [node:278563,title="Image capture"].

### Remove empty trailing measures {#remove-empty-trailing-measures}

This automatically removes any blank measures at the end of the score.
<!--
### Script recorder {#script-recorder}

To be added …
-->
### See also {#see-also}

* [node:278620,title="Breaks and spacers"]
* [node:278647,title="Rehearsal marks"]

### External links {#external-links}

* [node:12345,title="How to merge/combine/implode two staves in one with two voices"] (MuseScore HowTo)