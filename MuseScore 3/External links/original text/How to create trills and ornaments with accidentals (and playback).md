Create trills and ornaments that have modified pitches for notes other than the main notated note.
It is sometimes necessary to modify the notes of an ornament, e.g. sharpening the bottom note of the mordent:

![Modified ornament](../images/Modified_ornament.png)

To do this in MuseScore, you need to use staff text for the accidental and an invisible, non-playing note to influence playback. The procedure is as follows:

1. Select the note and enter the ornament or trill from the appropriate [node:278614,title="palette"].
2. Ensure the note is still selected and add a [node:278674,title="staff text",fragment="staff-tex"] to it.
3. Add the appropriate symbol from the [node:278590,title="special characters window",fragment="symbols-and-special-characters"].
4. [node:278664,title="Move",fragment="adjust-text-position"] the text and the trill or ornament around to make it look correct. (I needed to move the lower mordent up 1.0 sp to make space for the text and then move the text around to get the layout as in the image above.)

The appearance should now be correct on paper. Now we need to start to work on the playback. To make the ornament play back correctly, we need to have had at least one note previously in the measure (bar) that has the same pitch and spelling. E.g. if we are in the key of G major and have a lower mordent on A as in the image above and we want the bottom note to be a G#, we need a G♯ a half step below the A *before* the A in the same measure, instrument and staff. If you had a G♯ in the same measure, instrument and staff already, your job is done here. However, if you didn't have a G♯ yet, here is what you should do:

1. Enter e.g. a G♯ *on or before* the beat of the ornament in a [node:278602,title="voice"] you will not use in the same measure, instrument and staff as your note with the ornament.
2. Make all the components of the note you just entered [node:278642,title="invisible",fragment="element"].
3. Make sure that you set the note you just entered to be [node:278642,title="silent",fragment="note"].

Congratulations! You're done!