To open the __Measure__ dialog, select <samp class="menu">Format</samp>&rarr;<samp class="menuitem">Style...</samp>&rarr;<samp class="menuitem">Measure</samp>.

This allows you to adjust the distance between various items within measures.

### Introduction {#introduction}

If you change a __measure style__ property, MuseScore automatically adjusts the score to maintain the correct spacing between notes and rests according to best music engraving practice. It will also correctly reposition any _elements_ attached to notes or rests, such as fingerings, dynamics, lines etc.

All settings related to measure width and note spacing are _minimum_ values. Measures are automatically stretched, if necessary, to maintain existing [node:278663,fragment="page-margins",title="page margins"].

All the properties listed below use the __staff space__ (abbreviated to "sp") as the basic unit of measurement. See [node:278663,fragment="scaling",title="Page settings: Scaling"] for more details.

### Options {#options}

* __Minimum measure width__: Sets the minimum horizontal length of measures. In measures containing very little content (e.g., a single whole note or whole measure rest), the measure will only shrink as far as this minimum.

* __Spacing (1=tight)__: Condenses or expands the space _after_ notes or rests. This setting thus affects not only space between notes but also between the last note and the ending barline. For the space between the _beginning_ of the measure and the first note or rest, see __Note left margin__ (below).

* __Note left margin__: Sets the distance from the start barline to the first note.

* __Barline to grace note distance__:  Sets the distance between a barline and a grace note that occurs before the first actual note in a measure (independently of the "Note left margin" setting).

* __Barline to accidental distance__:  Sets the distance between a barline and an accidental placed before the first note in a measure (independently of the "Note left margin" setting).

* __Note to barline distance__:  Sets the distance from the  last note to the following barline.

* __Minimum note distance__:  Specifies the smallest amount of space MuseScore will allow after each note (depending on other factors, _more_ space may be allowed).

* __Clef left margin__:  Sets the distance between the very beginning of each line and the clef. (This option is rarely needed.)

* __Key signature left margin__:  Sets the distance between the beginning of the measure and a key signature.

* __Time signature left margin__:  Sets the distance between the beginning of the measure and a time signature (if there is no key signature in between).

* __Time signature to barline distance__: To be added

* __Clef/key right margin__:  Sets the distance between a mid-staff clef or key signature and the following note or rest.

* __Clef to barline distance__: Sets the distance between a barline and a clef change preceding it.

* __Clef to key distance__: Sets the distance from the clef to a key signature following it.

* __Clef to time signature distance__: Sets the distance from the clef to the time signature following it (if there is no key signature in between).

* __Key to time signature distance__: Sets the distance from a key signature to the following time signature.

* __Key to barline distance__: To be added..

* __System header distance__: Sets the distance from a clef or key signature at the beginning of a system to the first note or rest.

* __System header with time signature distance__: Sets the distance from a time signature at the beginning of a system to the first note or rest.

* __Multimeasure rest margin__:  Sets the distance between a [node:278572,fragment="multimeasure-rest",title="multimeasure rest"] and the barlines on either side.

* __Staff line thickness__:  Sets the thickness of the lines of the staff, which allows you to make the staff thicker and darker, if you need greater visibility on your printouts.

 __Note__: Changes to an individual measure's __Stretch__ (using <samp class="menu">Format</samp>&rarr;<samp class="menuentry">Stretch</samp> &rarr; <samp class="menuentry">Increase/Decrease Layout Stretch</samp>) are calculated after, and proportional to, the global  __Spacing__ setting.