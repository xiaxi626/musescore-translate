__Note__: To ensure that [inserted](#insert) or [appended](#append) measures display correctly, [node:278572,fragment="display-multimeasure-rests",title="multimeasure rests"] should be set to off (toggle <kbd><kbd>M</kbd></kbd>).

### Select {#select}

#### Single measure {#single-measure}

* To [node:278652,title="select"] a single measure, click on a space within the measure.

#### Range of measures {#measure-range}

* To select a continuous range of measures, see [node:278652,fragment="select-measure-range",title="Shift + click selection"] and [node:278652,fragment="shift-selection",title="Shift selection"].

### Insert {#insert}

#### Insert an empty measure into the score {#insert-measure}

Use one of the following options:

* [Select](#select) a measure or a frame, then press <kbd><kbd>Ins</kbd></kbd> (Mac: <kbd><kbd>Shift</kbd>+<kbd>I</kbd></kbd>).
* Select a measure or a frame, then choose from the menu: <samp class="menu">Add</samp>&rarr;<samp class="submenu">Measures</samp>&rarr;<samp class="menuitem">Insert Measure</samp>.

#### Insert multiple measures {#insert-multiple-measure}

Use one of the following options:

* [Select](#select) a measure or a frame, then press <kbd><kbd>Ctrl</kbd>+<kbd>Ins</kbd></kbd> (Mac: <kbd><kbd>Shift</kbd>+<kbd>Del</kbd>+<kbd>I</kbd></kbd>); fill in the "Number of measures to insert" field and press <kbd><samp class="button">OK</samp></kbd>.
* Select a measure or a frame, then choose from the menu: <samp class="menu">Add</samp>&rarr;<samp class="submenu">Measures</samp>&rarr;<samp class="menuitem">Insert Measures...</samp>; fill in the "Number of measures to insert" field and press <kbd><samp class="button">OK</samp></kbd>.

### Append {#append}

#### Append an empty measure to the end of a score {#append-one-measure}

Use one of the following options:

* Press <kbd><kbd>Ctrl</kbd>+<kbd>B</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>B</kbd></kbd>).
*  Select from the menu: <samp class="menu">Add</samp>&rarr;<samp class="submenu">Measures</samp>&rarr;<samp class="menuitem">Append One Measure</samp>.

#### Append multiple measures to the end of a score {#append-multiple-measure}

Use one of the following options:

* Press <kbd><kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>B</kbd></kbd>; fill in the "Number of measures to append" field and press <kbd><samp class="button">OK</samp></kbd>.
* Select from the menu: <samp class="menu">Add</samp>&rarr;<samp class="submenu">Measures</samp>&rarr;<samp class="menuitem">Append Measures...</samp>; fill in the "Number of measures to append" field and press <kbd><samp class="button">OK</samp></kbd>.

### Remove {#delete}

#### Remove a single measure {#delete-single-measure}

1. [Select](#single-measure) the measure
2. Press <kbd><kbd>Ctrl</kbd>+<kbd>Del</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Del</kbd></kbd>).

#### Remove a range of measures {#delete-range}

1. [Select](#measure-range) a range of measures;
2. Press <kbd><kbd>Ctrl</kbd>+<kbd>Del</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Del</kbd></kbd>).

__Note__: In multistaff scores, measure deletion also removes all corresponding measures in the other staves of the system;

#### Remove empty trailing measures  {#delete-empty-trailing-measures}

To automatically remove any blank measures from the end of the score:

* From the menu, select <samp class="menu">Tools</samp>&rarr;<samp class="menuitem">Remove empty trailing measures</samp>.

### Delete measure contents {delete-measure-contents}

To delete _only_ the measure contents (and not the measure itself):

1. [Select](#measure-range) one or more measures;
2. Press <kbd><kbd>Del</kbd></kbd></kbd>.

### Properties {#properties}

To edit the properties of a measure, right-click an empty part of the measure and select <samp class="menuitem">Measure Properties...</samp>:

[inline:measure_properties_en.png=Dialog: Measure Properties]

You can use the [inline:Previous_Next Buttons.png=Previous/Next] buttons, at the bottom left of the dialog, to navigate to the previous or next measure.

#### Staves {#staves}

* __Visible__:  Check/uncheck to show/hide notes and staff lines for the selected measure.
* __Stemless__: Check/Uncheck to show/hide all note stems for the selected measure.

#### Measure duration {#duration}

This section of the dialog allows you to adjust the duration of a single measure independently of the displayed time signature. Use it to create a  __pickup measure__ (also known as _anacrusis_ or _upbeat_), __cadenza__, __ad lib__ section etc.

[inline:measure_duration.png=Measure duration]

* __Nominal__ is the _apparent_ time signature and cannot be edited.
* __Actual__ can be set to anything you like regardless of the _nominal_ time signature.
  

__Example__: In the image below, the quarter note _pickup measure_ has a _nominal_ time signature of 4/4, but an _actual_ time sig. of 1/4. The measures in the middle are in normal 4/4 time. The complementary measure at the end of the staff, with a dotted half note, has an _actual_ time sig. of 3/4.

[inline:Incomplete-Measures.png=Incomplete measures]

__Note__: A small <kbd><kbd>-</kbd></kbd> or <kbd><kbd>+</kbd></kbd> sign appears above the measure when its duration is different than indicated by the time signature (see image below). _This does not appear in any printed or PDF copy_. You can turn off these marks by unchecking "Mark Irregular Measures" in the [node:278641,fragment="view-menu",title="View menu"].
Pressing Ctrl+Del on a note or pause also reduces the duration of the measure, while via [node:278675,fragment="",title="insert mode"] you can increase the duration of the measure.

[inline:measure_altered_duration.png=Irregular measures] 

#### Other {#other}

##### Exclude from measure count {#irregular}

* __Exclude from measure count__: Tick to exclude the selected measure from measure numbering (e.g. a pickup measure).

##### Break multimeasure rests {#break-multimeasure-rests}

* __Break multimeasure rests__: Tick to prevent a [node:278572,title="multimeasure rest"] at the start of the selected measure. This option should be checked _before_ turning on _"Create multimeasure rests"_ in <samp class="menu">Format</samp>&rarr;<samp class="menuitem">Style...</samp>&rarr;<samp class="menuitem">Score</samp>. The default program setting for scores is _OFF_; for [node:278621,title="parts"] is _ON_.

_Note_: Multimeasure rests are broken, by default, at important breaks—such as rehearsal marks, time signature changes, double barlines, [irregular measures](#other), etc. 

##### Measure number mode {#measure-number-mode}

This allows you to control whether and how measure numbers display on the selected measure:

* __Auto__: Follows the setting in <samp class="menu">Format</samp>&rarr;<samp class="menuitem">Style...</samp>&rarr;<samp class="menuitem">Measure Numbers</samp>.
* __Always Show__: Forces display of number.
* __Always Hide__: Hides number.

##### Layout stretch {#layout-stretch}

* __Layout stretch__: Controls the amount of horizontal space between score elements (notes, rests, etc.).

This setting allows a more precise degree of control than offered by the [node:278570,title="Increase/Decrease Stretch",fragment="layout-stretch"] (<kbd><kbd>{</kbd></kbd> and <kbd><kbd>}</kbd></kbd>) commands.

##### Add to measure number {#add-to-measure-number}

* __Add to measure number"__: Enter a positive or negative number to change the number of the selected measure, and subsequent meaures.  A value of "-1" has the same effect as marking a measure to be excluded from measure count.

##### Play Count {#play-count}

* __Play count__: If a measure precedes an end repeat barline, this value controls the number of times that the entire repeat section plays back: see also, [node:278591,title="Repeats and jumps"].

### Numbering {#numbering}

By default, MuseScore numbers the first measure of each System (except for the first measure in a [node:278620,fragment="section-break",title="section"]), but other numbering options are available: see  <samp class="menu">Format</samp>&rarr;<samp class="submenu">Style...</samp>&rarr;<samp class="submenu">[node:278570,fragment="style-measure-numbers",title="Measure Numbers"]</samp>.

### Split and join {#split-join}

To make a measure longer or shorter in duration—without changing the time signature—you can adjust its [Measure Properties](#properties) (above). But it is also possible to join or split measures. 

#### Join measures {#join-measures}

__Method A__. To join _two measures only_:

* Select the barline between the two measures and press <kbd><kbd>Ctrl</kbd>+<kbd>Del</kbd></kbd>.

__Method B__. To join _any number of measures_:

1. [node:278652,title="Select"] the measures you want to join;
2. From the menu bar, select <samp class="menu">Tools</samp>&rarr;<samp class="submenu">Measure</samp>&rarr;<samp class="menuitem">Join Selected Measures</samp>.

__Notes__: (1) If you select measures on only one staff in a score with multiple staves, the same measures will be joined in each staff of the system. (2) Beaming may be automatically modified. (3) If you have generated parts already, this option is disabled.

#### Split a measure {#split-measure}

Choose one of the following methods:

* [node:278652,title="Select"] a note; then hold <kbd><kbd>Ctrl</kbd></kbd> and click a barline in a [node:278614,title="palette"] (double-click in versions prior to 3.4).
* Hold <kbd><kbd>Ctrl</kbd></kbd> and drag a barline (from a palette) to the note that starts the next measure.
* [node:278652,title="Select"] a note; then, from the menu bar, select <samp class="menu">Tools</samp>&rarr;<samp class="submenu">Measure</samp>&rarr;<samp class="menuitem">Split Measure Before Selected Note/Rest</samp>.

__Note__: If you select only one note from one staff, each staff of the system will be split at the same place.

### External links {#external-links}

* [node:8540,title="How to span a measure over multiple systems"] (MuseScore HowTo, 1.x)
* [node:23280,title="How to split a measure"] (MuseScore HowTo, 1.x)
* [node:20240,title="How to delete measures"] (MuseScore HowTo)
* [node:24449,title="How to get scores without time signature (and clef)"] (MuseScore HowTo)