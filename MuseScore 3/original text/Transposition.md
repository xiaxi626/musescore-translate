__Transposition__ is the act of raising or lowering the pitch of a selection of notes by the same [node:278598,fragment="interval",title="interval"]. You can choose to transpose notes either [manually](#manual-transpose) or by using the [Transpose dialog](#automatic-transpose).

### Manual transposition {#manual-transpose}

1. [node:278652,title="Select"] the notes that you wish to transpose;
2. Use any of the following options:
 * __To transpose chromatically__ (i.e. one semitone at a time): Press <kbd><kbd>↑</kbd></kbd> or <kbd><kbd>&darr;</kbd></kbd>. Repeat as required.
 * __To transpose diatonically__ (i.e. one scale degree at a time): Press <kbd><kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>&uarr;</kbd></kbd> or <kbd><kbd>&darr;</kbd></kbd>. Repeat as required.
 * __To transpose by an octave__: Press <kbd><kbd>Ctrl</kbd></kbd>+<kbd><kbd>&uarr;</kbd></kbd> or <kbd><kbd>&darr;</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>&uarr;</kbd></kbd> or <kbd><kbd>&darr;</kbd></kbd>).

### Automatic transposition {#automatic-transpose}

MuseScore's  __Transpose__  dialog gives you more options for transposing notes.

[inline:transpose_dialog_en.png=Transpose Dialog]

__Note__: By default this dialog opens from the __Tools__ menu, but you can also choose to open it using a keyboard shortcut (see [node:278648,fragment="shortcuts",title="Preferences"]).

#### Transpose Chromatically {#transpose-chromatically}

##### To Key {#To-key}

To transpose notes up or down to the desired key:

1. [node:278652,title="Select"] the notes you want to transpose; no selection equals "select all.".
2. From the menu bar, choose <samp class="menu">Tools</samp> &rarr; <samp class="menuitem">Transpose…</samp>.
3. Tick "Transpose Chromatically" and "To key".
4. Tick/untick "Transpose key signature" and "Transpose chord symbols" if required
5. Tick one of "Closest", "Up" or "Down" and select a destination key signature from the drop-down menu.
6. Click OK.

##### By Interval {#by-interval}

To transpose selected notes up or down in semitone increments:

1. [node:278652,title="Select"] the notes you want to transpose; no selection equals "select all".
2. From the menu bar, choose <samp class="menu">Tools</samp> &rarr; <samp class="menuitem">Transpose…</samp>.
3. Tick "Transpose Chromatically" and "By Interval".
4. Tick/untick "Transpose key signature" and "Transpose chord symbols" if required.
5. Tick "Up" or "Down"; and select a transposition interval from the drop-down menu.
6. Click OK.

#### Transpose Diatonically {#transpose-diatonically}

To transpose selected notes up or down by a diatonic interval:

1. [node:278652,title="Select"] the notes you want to transpose; no selection equals "select all".
2. From the menu bar, choose <samp class="menu">Tools</samp> &rarr; <samp class="menuitem">Transpose…</samp>.
3. Tick "Transpose Diatonically".
4. Tick/untick "Keep degree alteration" and "Transpose chord symbols" if required.
5. Tick "Up" or "Down;" and select a transposition interval from the drop-down menu.
6. Click OK.

#### Options {#Options}

Two options are available for both Chromatic and Diatonic transposition mode in the options area:

 * __Transpose chord symbols__, if required.
 * And the choice of __Use Double ♯ and ♭__ or __Single ♯ and ♭ Only__

### Transposing instruments {#transposing-instruments}

__Transposing instruments__, such as the B-flat trumpet or E-flat alto sax, sound lower, or higher than their written pitch. MuseScore has a number of features to facilitate the scoring of these instruments.

#### Concert pitch {#concert-pitch}

 MuseScore's default viewing mode shows the musical notation in __written pitch__, but you can choose to display the score in [node:278651,title="concert pitch"] instead. In the latter mode, the musical notation of _all_ instruments matches the actual pitches that you hear on playback.

* __To change the view to concert pitch__: Press the <kbd><samp class="button">[node:278651,title="Concert Pitch"]</samp></kbd> button to highlight it.

You should ensure that the Concert pitch button is OFF before printing the main score or any parts.

#### Change staff transposition {#change-staff-transposition}

Instrument transpositions are already set up in MuseScore. However, if you want a rare instrument or transposition that is not available in MuseScore, you may need to edit the instrument transposition manually.

1.  Right-click an empty part of the instrument staff and select <samp class="menuitem">Staff/Part Properties…</samp>.
2.  At the bottom of the window, select the interval of transposition, any octave shifts, and whether the interval is "Up" (sounds higher than written) or "Down" (sounds lower than written).

You can also use the <kbd><samp class="button">Change Instrument…</samp></kbd> button in the Staff/Part Properties window to automatically change the transposition to that of a different standard instrument.

### External links {#external-links}

 - [node:11708,title="How to transpose"] (MuseScore How-To)
 - [node:75466,title="Concert pitch or not?"] (forum discussion)
 - [node:260491,title="How to change enharmonic key signatures for transposing instruments"] (MuseScore How-To)