---
title: Lyrics
date: 2022-01-09 11:40:21
---
### Enter a lyrics line {#enter-lyrics}

#### First line {#first-line}

1. Enter the notes of the melody line;
2. [node:278652,fragment="select-note",title="Select"] the note where you want to start entering lyrics;
3. To enter __lyrics mode__, type <kbd><kbd>Ctrl</kbd>+<kbd>L</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>L</kbd></kbd>); or from the main menu, select <samp class="menu">Add</samp>&rarr;<samp class="submenu">Text</samp>&rarr;<samp class="menuitem">Lyrics</samp>;
4. Type a syllable;
5. Use the following options to continue entering lyrics:
 * __Go to the next syllable__: Press <kbd><kbd>Space</kbd></kbd> (or <kbd><kbd>Ctrl</kbd>+<kbd>&rarr;</kbd></kbd> (Mac: <kbd><kbd>Alt</kbd>+<kbd>&rarr;</kbd></kbd>)) at the end of a syllable.
 * __Hyphen__ (to connect syllables): Press <kbd><kbd>-</kbd></kbd> at the end of a syllable. 
 * __Go to the previous syllable__: Press <kbd><kbd>Shift</kbd>+<kbd>Space</kbd></kbd> (or <kbd><kbd>Ctrl</kbd>+<kbd>&larr;</kbd></kbd> (Mac: <kbd><kbd>Alt</kbd>+<kbd>&rarr;</kbd></kbd>)).
 * __Move left__: Press <kbd><kbd>&larr;</kbd></kbd> (left arrow). If the cursor is at the beginning of a syllable, it will jump to the previous one.
  * __Move right__: Press <kbd><kbd>&rarr;</kbd></kbd> (right arrow). If the cursor is at the end of a syllable, it will jump to the next one.
  * __Move to the syllable below__: Press <kbd><kbd>&darr;</kbd></kbd> (down arrow). 
  * __Move to the syllable above__: Press <kbd><kbd>&uarr;</kbd></kbd> (up arrow).
 * __Start new lyrics line__: Press <kbd><kbd>&crarr;</kbd></kbd> (Return) at the end of an existing lyrics syllable (_Note_: Don't use the <kbd><kbd>Enter</kbd></kbd> key from the numeric keypad!).
6. To exit __lyrics mode__, press <kbd><kbd>Esc</kbd></kbd> or click outside of the text box.

#### Subsequent lines {#subsequent-line}

If you want to add another lyrics line to an existing one (e.g. a 2nd or 3rd verse etc.):

1. Choose one of the following options:
 * [node:278652,fragment="select-note",title="Select"] the note where you want to start the new lyrics line. Enter __lyrics mode__ as shown in step 3 ([above](#first-line)). The cursor moves to a new (blank) line.
 * Enter [node:278590,fragment="text-edit-mode",title="text edit mode"] on an existing syllable, go to the end of the syllable and press <kbd><kbd>&crarr;</kbd></kbd> (Return). The cursor moves to the next line.
2. Continue entering lyrics from step 4 ([above](#first-line)).

__Example__:

[inline:adeste.png=Sample lyrics: A-des-te fi-del-es]

#### Special characters {#special-characters}

In most cases, lyrics can be [node:278590,title="edited"] just like normal text. However, special keyboard shortcuts are required to enter the following characters:

* __Space character__: <kbd><kbd>Ctrl</kbd>+<kbd>Space</kbd></kbd> (Mac: <kbd><kbd>Alt</kbd>+<kbd>Space</kbd></kbd>).

* **- (hyphen)**: <kbd><kbd>Ctrl</kbd>+<kbd>-</kbd></kbd> (Mac: <kbd><kbd>Alt</kbd>+<kbd>-</kbd></kbd>).

* **_ (underscore)**: <kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>_</kbd></kbd> (Mac: <kbd><kbd>Alt</kbd>+<kbd>Shift</kbd><kbd>_</kbd></kbd>).

* __Line feed__: <kbd><kbd>Ctrl</kbd>+<kbd>&crarr;</kbd></kbd> (Mac: <kbd><kbd>Alt</kbd>+<kbd>Return</kbd></kbd>) or <kbd><kbd>Enter</kbd></kbd> (from the numeric keypad).

#### Verse numbers {#verse-numbers}

To number verses, simply type the number (e.g. 1.) and a [space](#special-characters) before the first syllable. MuseScore will automatically align the numbers and first syllable correctly.

#### Melisma {#melisma}

A __melisma__ is a syllable or word that extends over two or more notes. It is indicated by an underline extending from the base of a syllable to the last note of the melisma. The underline is created by positioning the cursor at the end of a syllable and pressing <kbd><kbd>Shift</kbd>+<kbd>_</kbd></kbd>: once for each note in the melisma. See the image below:

[inline:lyrics1.png=Syllable extension line, Melisma]

The above lyric was created in the following manner:

1. Type the letters, <kbd><kbd>s</kbd><kbd>o</kbd><kbd>u</kbd><kbd>l</kbd><kbd>,</kbd></kbd>. 
2. At the end of the word, press <kbd><kbd>Shift</kbd>+<kbd>_</kbd><kbd>_</kbd><kbd>_</kbd>.
3. Type the letters <kbd><kbd>T</kbd><kbd>o</kbd></kbd>, then press <kbd><kbd>Esc</kbd></kbd>.

For non-last syllables to extend, just use additional dashes <kbd><kbd>-</kbd></kbd>, usually only one of them will show (more when the distance between the syllables is large enough), and the syllable will right-align to the first note, similar to last syllables that got notated with a melisma, see above.

#### Elision (Lyric) slur / Synalepha {#elision}

Two syllables under a note can be joined with an __elision slur__, also known as a "lyric slur" or "synalepha". For example:

[inline:synalepha.png=Sample lyric slur under a note]

To create the example lyric text, starting with the syllable text "te":

1. Type <kbd><kbd>t</kbd><kbd>e</kbd></kbd>;
2.  Click on the keyboard icon [inline:Keyboard.png=Keyboard Icon] in the bottom-left corner of the screen, or press <kbd><kbd>F2</kbd></kbd> to open the [node:278590,fragment="symbols-and-special-characters",title="Special Characters"] palette;
3. Use one of the following options:
 * Double-click one of the three elision slurs in the "Common Symbols" tab: "Narrow elision", "Elision", or "Wide elision" (these can be found between the "C Clef" and the "___p___" dynamic—see image below):
 [inline:special_characters_elision_en.png=Elision in the Special Symbols palette] 
 * Double-click the elision slur found after the 7/8 fraction in the "Common Symbols" tab (next to last character in the image above). Depending on the font, add one or more spaces before/after the slur using <kbd><kbd>Ctrl</kbd>+<kbd>Space</kbd></kbd> (Mac: <kbd><kbd>Alt</kbd>+<kbd>Space</kbd></kbd>).

  __Note__: Not all fonts include the "undertie" character (U+203F ‿ "undertie", present in "Special Characters" mainly for compatibility with MuseScore 1.x scores). To find out which fonts on your computer support it, see "[fontlist](http://www.fileformat.info/info/unicode/font/fontlist.htm?text=te%20%CD%9C%20A)" (look for any font that shows a tie between "te" and "A" instead of a blank rectangle).

4. Type <kbd><kbd>A</kbd></kbd>.

As of 3.6: <kbd><kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>-</kbd></kbd> or <kbd><kbd>AltGr</kbd>+<kbd>-</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Alt</kbd>+<kbd>-</kbd></kbd>).

### Edit Lyrics {#edit-lyrics}

1. Enter [node:278590,fragment="text-edit-mode",title="text edit mode"] on an existing syllable;
2. Use standard [node:278590,title="text editing"] commands to make changes;
3. Continue entering lyrics (see [above](#first-line)); or exit __lyrics mode__ by pressing <kbd><kbd>Esc</kbd></kbd>.

### Adjust properties of lyrics {#adjust-lyrics-properties}

To make global adjustments to the [node:278570,fragment="style-lyrics",title="properties"] of all lyrics in the score:

1. From the menu, select <samp class="menu">Format</samp>&rarr;<samp class="menuitem">Style...</samp>&rarr;<samp class="menuitem">Lyrics</samp>;
2. Edit Placement, Line height, Margins, Dash and Melisma properties as required.

### Adjust position of individual lyrics lines {#adjust-lyrics-line}

To adjust the position of a _particular_ lyrics line:

1. [node:278652,fragment="all-similar-selection",title="Select"] the lyrics line: i.e. right-click on a word in the line, and (from the menu) choose <samp class="menu">Select</samp>&rarr;<samp class="submenu">More...</samp>; then check the relevant options, which should include "Same system";
2. Adjust the X and Y offsets in the Inspector.

### Copy lyrics to clipboard {#lyrics-to-clipboard}

To copy _all_ lyrics to the clipboard:

* From the menu bar, select <samp class="menuitem">Tools</samp>&rarr;<samp class="menuentry">Copy Lyrics to Clipboard</samp>.

### Paste lyrics from clipboard {#lyrics-from-clipboard}

To copy and paste lyrics from a text file (say) into a score:

1. Enter the notes in the score to which the lyrics will be attached.
2. Set up your lyrics in a text file, with appropriate spaces, hyphens, line-breaks etc.
3. Copy the lyrics from the text-file into the clipboard.
4. Select the start note in MuseScore, and press <kbd><kbd>Ctrl</kbd>+<kbd>L</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>L</kbd></kbd>) (step 3 under [node:278618,fragment="enter-lyrics",title="Enter lyrics in a score"]).
5. Repeatedly applying [node:278613,fragment="paste-notes",title="paste"] will enter successive words of the lyrics. You may need to enter melismas and make other corrections as you go along.

### See also {#see-also}

- [node:278586,title="Text"]
- [node:278623,title="Chord symbol"]

### External links {#external-links}

- [node:21522,title="How to insert Lyrics"] (MuseScore HowTo)
- [node:23764,title="How to move lyrics"] (MuseScore HowTo)
- [node:24475,title="How to add a block of text to a score"] (MuseScore HowTo)
- [node:54436,title="How to copy lyrics, or lyrics with rhythm"] (MuseScore HowTo)
- [node:286258,title="How to add lyrics in columns"] (MuseScore HowTo)
- [Video tutorial: MuseScore in Minutes: Lesson 6 - Text, Lyrics and Chords](https://www.youtube.com/watch?v=8nglDCxzfeA)