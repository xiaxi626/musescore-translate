__Dynamics__ are symbols indicating the relative loudness of a note or phrase of music. They can be found in the Dynamics [node:278614,title="palette"] in either the Basic or Advanced [node:278614,fragment="workspaces",title="workspace"].

[inline:Palette-Dynamics.png=Dynamics palette (Advanced)]

Additional dynamics are available in the [node:278649,title="Master Palette"] (<kbd><kbd>Shift</kbd>+<kbd>F9</kbd></kbd>).

__Note__:  if you wish to adjust the _overall_ playback volume of the score, use the volume slider in the [node:278585,fragment="play-panel",title="Play Panel"], or [node:278660,title="Synthesizer"].

### Add a dynamic {#dynamics-text}

__To apply a dynamic to the score__, use one of the following methods:

* Select a note and click a dynamic symbol in a palette (double-click in versions prior to 3.4).
* Drag a dynamic symbol from a palette onto a note.

__To create a crescendo or decrescendo__, see [node:278577,title="Hairpin"].

### Adjust properties {#adjust-properties}

The default dynamic of the score is ___mf___ (mezzoforte)—set at MIDI velocity 80 (out of 127). Depending on the dynamic governing a particular section of the score, velocity (and the resulting loudness) may be less than or greater than this.

#### To edit the velocity of a dynamic {#edit-velocity}

* Select the dynamic and, in the __Dynamic__ section of the [node:278642,title="Inspector"] edit the [node:278598,title="Velocity",fragment="velocity"] value—higher for louder, lower for softer.

 [inline:Velocity_speed.png] 

#### To adjust the range {#adjust-range}

_Note_: Range = the staves in the system affected by the dynamic.

* Select the dynamic, and in the __Dynamic__ section of the __Inspector__, choose an option from "Dynamic range". The default is "Part," which means that all staves for a particular instrument will be affected. "Staff" limits the effect to the staff attached to the dynamic. "System" means that all staves in the system will be affected by the dynamic.
<!--
#### To adjust the Change speed {#adjust-Change speed}

#### To adjust the Velocity change {#adjust-Velocity change}
-->
#### To change the placement (above or below stave) {#change-placement}

* For a single dynamic mark: select the dynamic, and type <kbd><kbd>X</kbd></kbd> to flip the placement or use the Inspector, see below.
* For all dynamic marks on a stave:
  1. Right-click on one dynamic, then choose _Select > All Similar Elements on Same Stave_
  2. In the __Dynamic__ section of the __Inspector__ choose the required option _Above_ or _Below_ from "Placement"
* For all dynamic marks in the score:
   See above, then use the "Set as Style" button of Inspector

### Customize a dynamic {#edit-a-dynamic}

Dynamics can be [node:278590,title="edited"] just like any other text object. [node:278590,fragment="special-character-shortcuts",title="Special character shortcuts"] can be used to add the following symbols:

* <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd></kbd>): __Piano _p___.
* <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>F</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>F</kbd></kbd>): __Forte _f___.
* <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>M</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>M</kbd></kbd>): __Mezzo _m___.
* <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>R</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>R</kbd></kbd>): __Rinforzando _r___.
* <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>S</kbd></kbd>: __Sforzando _s___.
* <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>N</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>N</kbd></kbd>): __Niente _n___.
* <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>Z</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>Z</kbd></kbd>): __Z _z___.

You can also edit the velocity and range etc. (see [above](#adjust-properties)). If desired, you can save the result for future use in a [node:278614,fragment="custom-palettes",title="custom palette"].

### Single Note Dynamics (SND) {#single-note-dynamics}

As of version 3.1, MuseScore supports [node:278598,fragment="single-note-dynamic",title="single note dynamics"]. In addition to [editing the velocity](#edit-velocity), you can also edit the velocity change in the inspector. Entering a number into this field will change the velocity of the note by approximately that amount after the initial velocity is played. A negative number can be used to lower the volume after the initial note and a positive number will make the note play louder after the initial volume. See links (below) for further details.

### External links {#external-links}

* [Video tutorial: Lesson 10 - Articulations, Dynamics and Text](https://www.youtube.com/watch?v=KnoKgja20fg)
* [node:290616,title="Using Single Note Dynamics (SND)"] (MuseScore HowTo)
* [node:277424,title="How to restore correct playback of dynamics and hairpins in an imported MIDI file"] (MuseScore HowTo)
* [Dynamics](https://en.wikipedia.org/wiki/Dynamics_%28music%29) (Wikipedia)