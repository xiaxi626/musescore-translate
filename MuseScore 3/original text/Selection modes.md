Objects in the score—such as notes, measures, articulations etc.—can be selected in several ways: (1) [one at a time](#select-single-object), (2) as a continuous [range](#range-select), or (3) as a [list](#list-select).

Selection is invariably used before applying commands such as [node:278615,fragment="delete-notes",title="delete"], [node:278613,title="copy/cut and paste"], [node:278571,title="transpose"] and so on.

### Select a single object {#select-single-object}

Most score objects can be selected by simply clicking on them in [node:278598,fragment="normal-mode",title="Normal mode"].

#### Select a single note {#select-note}

* In [node:278598,fragment="normal-mode",title="Normal mode"], click on a notehead.

__Note__: Selecting a single note then copying and pasting it, will only copy and paste the pitch—not duration or other properties (such as stemless). To copy the entire note, including all properties, you need to hold down <kbd><kbd>Shift</kbd></kbd>—as for chord selection (below).

#### Select a chord {#select-chord}

* In [node:278598,fragment="normal-mode",title="Normal mode"], press and hold <kbd><kbd>Shift</kbd></kbd>, then click on a notehead in the chord. 

#### Select a single measure {#select-measure}

* Click on a blank space within the measure.

__Note__: To select a range of consecutive measures, see [Shift selection](#shift-selection) and [Shift + click selection](#shift-click-selection) (below).

### Select an overlapping element {#select-overlapping-element}

To select an element from a group of overlapping elements:

* Hold <kbd><kbd>Ctrl</kbd></kbd> and click until the desired element is selected.

### Select a continuous range of objects {#range-select}

There are several ways to select a _continuous_ range of notes, chords or measures etc.:

#### 1. Shift + click selection {#shift-click-selection}

To select a range of __notes__ or __rests__:

1. Make sure you are in [node:278598,fragment="normal-mode",title="Normal mode"];
2. Click on the first note or rest in the range;
3. Press and hold <kbd><kbd>Shift</kbd></kbd>, then click on the last desired note or rest.
 
__Note__: The final selected element can be in the same staff or in staffs above or below the initial note/rest. All selected elements will be enclosed in a blue rectangle, including associated lines and articulations (but not voltas). You can repeat the operation to extend the selected range as required.

##### Select chord symbols, lyrics etc. (as of version 3.5) {#select-chords-lyrics}

As of MuseScore 3.5, the shift + click method has been refined to make it easier to select a continuous range of items such as chord symbols, lyrics etc. For example:

1. Click on the first chord symbol in the desired range.
2. <kbd><kbd>Shift</kbd></kbd> + click on the last chord symbol in the range.

_Result_ All chord symbols in that range are selected, and nothing else.

##### Select a range of measures {#select-measure-range}

1. Click on a blank space in the first desired measure;
2. Hold down <kbd><kbd>Shift</kbd></kbd>, then click on a space in the last measure of the desired range.

__Note__: As with selecting notes, the range can be extended vertically as well as horizontally. 

#### 2. Shift selection {#shift-selection}

1. Make sure you are in [node:278598,fragment="normal-mode",title="Normal mode"];
2. Select the first [note](#select-note), [chord](#select-chord), rest or [measure](#select-measure) in the range. You can extend the selection up or down to adjacent staves, if needed, using <kbd><kbd>Shift</kbd>+<kbd>↑</kbd></kbd> or <kbd><kbd>↓</kbd></kbd>;
3. Then choose one of the following options:
 * To advance the selection one chord at a time to the right: Press <kbd><kbd>Shift</kbd>+<kbd>→</kbd></kbd>.
 * To advance the selection one chord at a time to the left:  Press <kbd><kbd>Shift</kbd>+<kbd>←</kbd></kbd>.
 * To advance the selection one measure at a time to the right: Press <kbd><kbd>Shift</kbd>+<kbd>Ctrl</kbd>+<kbd>→</kbd></kbd> (Mac: <kbd><kbd>Shift</kbd>+<kbd>Cmd</kbd>+<kbd>→</kbd></kbd>).
 * To advance the selection one measure at a time to the left: Press <kbd><kbd>Shift</kbd>+<kbd>Ctrl</kbd>+<kbd>←</kbd></kbd> (Mac: <kbd><kbd>Shift</kbd>+<kbd>Cmd</kbd>+<kbd>←</kbd></kbd>).
 * To advance the selection to the beginning of the line: Press <kbd><kbd>Shift</kbd>+<kbd>Home</kbd></kbd> (Mac:  <kbd><kbd>Shift</kbd>+<kbd>Fn</kbd>+<kbd>←</kbd></kbd>).
 * To advance the selection to the end of the line: Press <kbd><kbd>Shift</kbd>+<kbd>End</kbd></kbd> (Mac:  <kbd><kbd>Shift</kbd>+<kbd>Fn</kbd>+<kbd>→</kbd></kbd>).
 * To extend the selection to the beginning of the score: Press <kbd><kbd>Shift</kbd>+<kbd>Ctrl</kbd>+<kbd>Home</kbd></kbd> (Mac: <kbd><kbd>Shift</kbd>+<kbd>Cmd</kbd>+<kbd>Fn</kbd>+<kbd>←</kbd></kbd>).
 * To extend the selection to the end of the score: Press <kbd><kbd>Shift</kbd>+<kbd>Ctrl</kbd>+<kbd>End</kbd></kbd> (Mac: <kbd><kbd>Shift</kbd>+<kbd>Cmd</kbd>+<kbd>Fn</kbd>+<kbd>→</kbd></kbd>).

#### 3. Drag selection {#drag-selection}

This method can be used to select notes or rests, or, independently, to select non-note symbols such as staccato dots, lyrics etc.:

* Press and hold <kbd><kbd>Shift</kbd></kbd>, then drag the cursor across the desired range.

#### 4. Select All {#select-all}

This method selects the _whole_ musical score including notes, rests and associated elements. Use one of the following options:

* Press <kbd><kbd>Ctrl</kbd>+<kbd>A</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>A</kbd></kbd>).
* From the menu bar, select <samp class="menu">Edit</samp> &rarr; <samp class="menuitem">Select All</samp>.

#### 5. Select section {#section-select}

This method is used to select a __section__—a region of the score starting and/or ending with a [node:278620,fragment="section-break",title="section break"]:

1. Click on an empty space in a measure in the section;
2. From the menu bar, select <samp class="menu">Edit</samp> &rarr; <samp class="menuitem">Select Section</samp>. 

#### 6. Selection Filter {#selection-filter}

The Selection Filter allows you include or exclude certain types of elements within a range selection. See [node:278613,title="Copy and paste: Selection filter",fragment="selection-filter"] 

### Select a list of objects {#list-select}

To select a _list_ (or discontinuous range) of score elements:

1. Click on the first element;
2. Hold down <kbd><kbd>Ctrl</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd></kbd>) and successively click on the desired additional elements.

__Note__: This method cannot be used to select measures. Use [single](#select-measure) or [range](#shift-click-selection) selection instead.

### Modify an existing selection (as of version 3.5) {#modify-selection}

You can also use the Ctrl + click method to add to, or subtract from, an existing selection. For example:

1. Make a selection in the score using any of the methods above.
2. To add a non-selected element to the selection, press <kbd><kbd>Ctrl</kbd></kbd> and click on it. Repeat as required.
3. To remove an already-selected element from the selection, press <kbd><kbd>Ctrl</kbd></kbd> and click on it. Repeat as required.

### Select all similar {#all-similar-selection}

To select all elements of a specific type (e.g., all barlines, all text elements, all staccato markings):

* Click on the first object of the type of element you want to match. Then shift-click the last similar element you want included. This creates a List Selection that includes the clicked element, the shift-clicked element and all similar elements in-between.  *NOTE: If you shift-click on a dissimilar element then only that element becomes selected. If you use this technique on notes or rests you'll invoke a Range Selection.*

— OR —

* Right-click on the type of element you want to match and choose <samp>Select…</samp> from the contextual menu; 
Several options will appear in the submenu:
 * __All Similar Elements__
      To select all similar elements in the entire score:
           Right-click the element; 
           then choose *Select … All Similar Elements*
 * __All Similar Elements in Same Staff__
      To select all similar elements within a particular staff:
           Right-click the element;
           then choose *Select …  All Similar Elements in Same Staff*
 * __All Similar Elements in Range Selection__: 
       NOTE: This only applies if a range has been selected. 
               Within an established range selection, 
               right-click the element you want to match similarly; 
               then choose *All Similar Elements in Range Selection*
 * __More...__: opens a dialog that lets you fine-tune more options. For example, if you have a notehead selected, the dialog will look something like this: 
 [inline:select_notes.png= Dialog: Select / More...]
 __Select__
 * Same notehead: In this example, only noteheads of the same [node:278661,fragment="notehead-groups",title="group"] will be selected;
 * Same pitch: Only noteheads of the same pitch will be selected;
 * Same string: (tablature only) selects fretmarks on same string.
 * Same type: All noteheads (of any [node:278661,fragment="notehead-groups",title="group"]) will be selected;
 * Same duration: Only noteheads of same duration will be selected;
 * Same note name: Noteheads of that name in all octaves will be selected;
 * Same staff: Only noteheads on the same staff will be selected.
 * Same voice: Selects all notes of same voice.
 * In selection:
 * Same system:
  __Action__
 * Replace selection: The default option—starts the selection from scratch;
 * Add to selection:  Keeps everything you have already selected, and adds the current selection to it;
 * Search in selection:
 * Subtract from selection: Keep everything you have already selected, but takes away the current selection.

### What selections are useful for

* [node:278613,title="Copy and paste"]
* [node:278587,title="Edit mode"] 
* [node:278642,title="Inspector and object properties"]
* [node:278656,title="Tools"]

### See also {#see-also}

* [node:278627,title="Basics"] chapter, esp. [node:278615,title="Note input"] 
* [node:278628,title="Notation"] chapter, esp. [node:278589,title="Accidental"] 
* [node:278586,title="Text"] chapter, esp. [node:278590,title="Text editing"] and [node:278569,title="Grid-based movement of symbols and staff text"]