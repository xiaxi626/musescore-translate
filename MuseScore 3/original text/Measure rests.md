---
title: Measure rests
date: 2022-01-10 16:21:35
---
### Full measure rest {#full-measure-rest}

A __whole rest__, centered within a measure (shown below), is used to indicate that an entire measure (or a voice within a measure) is silent, regardless of time signature.

[inline:full-measure-rest.png=Full measure rest]

#### To create one or more full measure rests {#create-measure-rests}

Use the following method if all selected measures are "standard"—i.e. with no [node:278611,fragment="duration",title="custom durations"]:

1 [node:278652,title="Select"] a measure, or [node:278652,fragment="range-select",title="range"] of measures.
2. Press <kbd><kbd>Del</kbd></kbd>.

If one or more of the measures contains a [node:278611,fragment="duration",title="custom duration"], use the following method instead:

1. [node:278652,title="Select"] a measure, or [node:278652,fragment="range-select",title="range"] of measures.
2. Press <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>Del</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>Del</kbd></kbd>).

#### To create a full measure rest in a _particular_ voice {#measure-rest-other-voices}

1. In the appropriate voice, enter a rest that extends for the full measure.
2. Make sure the rest is selected, then press <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>Del</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>Del</kbd></kbd>).

### Multimeasure rest {#multimeasure-rest}

A __Multimeasure rest__ indicates a period of silence for an instrument: the number of measures is shown by the number above the staff. 

[inline:multimeasure-rests.png=Multimeasure rest]

Multimeasure rests are automatically interrupted at important points, such as double barlines, [node:278647,title="rehearsal marks"], key- or time signature changes, [node:278620,fragment="section-break",title="section breaks"] etc. and also at measures that are set to [node:278611,fragment="break-multimeasure-rests",title="break multimeasure rests"].

#### To display multimeasure rests {#display-multimeasure-rests}

To turn multimeasure rests on or off:

* Press <kbd><kbd>M</kbd></kbd> on your keyboard.

Alternatively:

1. From the menu, choose <samp class="menu">Format</samp>&rarr;<samp class="menuitem">Style…</samp>.
2. Click on the "Score" tab, if it is not already selected;
3. Tick/untick "Create multimeasure rests". Here you can also set the minimum of empty measures to combine into a multimeasure rest (see also [node:278570,title="Layout and formatting: Score",fragment="style-score"]).

__Note__: It is recommended that you enter all notes in the score first _before_ enabling multimeasure rests.

#### Break multimeasure rest {#break}

You may want to have a multimeasure rest divided into two multimeasure rests:

1. Ensure that the option to display multimeasure rests in the score is _off_ (see [above](#display-multimeasure-rests)).
2. Right-click on the measure where you want the second multimeasure rest to start;
3. From the menu, choose <samp class="menu">Measure Properties</samp> and tick "Break multimeasure rest."
3. Enable multimeasure rests again

See also: [node:278611,title="Measure operations: Break multimeasure rest",fragment="other"].