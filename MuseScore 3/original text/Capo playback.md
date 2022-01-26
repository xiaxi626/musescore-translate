---
title: Capo playback
date: 2021-12-30 01:30:28
---
MuseScore allows you to transpose the playback of a staff, without affecting the music notation. This simulates the effect of a [capo](https://en.wikipedia.org/wiki/Capo) (Wikipedia) on the instrument.

### Add capo to a single staff {#single-staff}

1. [node:278664,title="Add"] [node:278674,title="staff text"] to the note/rest from which you want capo playback to start;
2. Click on "Properties" in the "Staff Text" section of the [node:278642,title="Inspector"], or right-click on the staff text and  select <samp class="menu">Staff Text Properties...</samp>; then click on the __Capo Settings__ tab;
3. Check the "Capo Settings" checkbox, and set __Capo fret__ to the fret number you wish to apply the capo at (each fret increases the pitch by a semitone);
4. Click <kbd><samp class="button">Ok</samp></kbd> to apply your changes;
5. [node:278590,title="Edit"] the wording of the text as desired.

### Add capo to linked staff/tablature {#linked-staves}

* Same method as above, but in step 1, add the staff text to the music staff only.

### Add capo to unlinked staff/tablature {#unlinked-staves}

* Same method as above, but apply the staff text to both staff and tablature.

__Note__: Capo playback will apply from the note that the staff text is attached to, until either the next staff text with "Capo Settings" enabled, or until the end of the score.

### Remove capo {#remove-capo}

To remove capo playback from a staff, returning the instrument to its normal tuning:

* Add staff text with a "Capo fret" setting of "No capo".