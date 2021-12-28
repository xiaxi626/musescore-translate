When a musician is required to double on a different instrument for a section of a piece, the instruction to switch instruments is generally placed above the staff at the beginning of that section. A return to the primary instrument is handled in the same manner.
 
MuseScore enables users to insert a special class of text called __Change Instrument__ text for this purpose. This class of text is different from either [node:278674,fragment="staff-text",title="Staff"] or [node:278674,fragment="system-text",title="System"] text in that it links the text to the playback and changes the sound to the new instrument. 

### Effect of instrument change {#instrument-change-effect}

When an instrument change is made:

* The sound played will be changed to that of the new instrument from that point onward, but the [node:278583,title="mixer"] display remains unchanged.
* Subsequent notes are automatically adjusted to indicate the correct [node:278651,title="written pitch"] for the new instrument (but the new [node:278573,fragment="add",title="key signature"] still needs to be added manually—see [below](#add-instrument-change)).
* The new instrument name will be displayed in front of the following systems.

### Add an instrument change {#add-instrument-change}
 
1. Select the start point of the change by clicking on a note or rest;
2. Open the main palette by typing F9 (or from the [node:278641,fragment="show-panels",title="View menu"]), and click on __Text__ to open the text sub-palette:
 [inline:Change-instrument-Text_en.png=Text palette] 
3. A click on the __Change Instr__  text in the palette opens the dialog (double-click in versions prior to 3.4)
The top box shows the current instrument, the bottom the list of selectable instruments;
 [inline:Change-instrument-Select_en.png=Select instrument change]
4. Choose the instrument, then click OK. When an instrument is selected and the OK button is pressed, the text indicating which instrument the player will use appears in the score.
5. [node:278573,fragment="add",title="Insert a new key signature"], if required, at the change, for the staff in question.

__Note__: Mid-staff instrument changes are limited to the _same type of staff_. For example, you cannot change between a percussion staff and a pitched instrument staff or vice versa.

### See also {#see-also}
 
* [node:278564,fragment="change-instrument",title="Change instrument"]
* [node:278583,fragment="mid-staff-change",title="Mid-staff sound change"]

### External links {#external-links}

* [node:50196,title="How to change instrument sound (e.g. pizz., con sordino) midway through score"] (MuseScore HowTo)