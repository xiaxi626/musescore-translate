<!-- Note: Don't use the ascii &l/r/u/darr; replacements for Left/Right/Up/Down as they are not readable for a screen reader -->
### Introduction {#introduction}

This document is written for blind and visually impaired users of MuseScore 3. It is not intended to provide a full description of all of the features of MuseScore; you should read this in conjunction with the regular MuseScore documentation.

MuseScore comes with support for the free and open source [NVDA screen reader](https://www.nvaccess.org) for Windows. You can also [install a script](https://github.com/MarcSabatella/Accessibility/releases) to enable support for [JAWS](https://www.freedomscientific.com/products/software/jaws/), or [install a script](https://github.com/MarcSabatella/Accessibility/tree/master/MuseScore/Orca) for [Orca](https://help.gnome.org/users/orca/stable/) on Linux.

Eventually we hope to support other screen readers such as [VoiceOver](https://en.wikipedia.org/wiki/VoiceOver) and [Narrator](https://support.microsoft.com/en-us/help/22798). Currently, unsupported screen readers will usually read menus and dialogs, but reading the score note by note currently requires one of the supported screen readers.

Beginning with MuseScore 3.3, most of the features of MuseScore are fully accessible, it is viable both as a score reader and editor. Previous versions were more limited with respect to editing.

### Initial setup {#setup}

When you run MuseScore for the first time, you will be asked some questions on startup. We recommend you accept the defaults, but answer "no" to the question about showing tours, since these unfortunately are not yet accessible.

When MuseScore starts, the first thing you normally see is the [node:278622,fragment="start-center",title="Start Center"] window. This shows you a list of recent scores that you can access via Shift+Tab and then using the left and right cursor keys. You may find it easier to open scores directly from the File menu, however so you can press <kbd><kbd>Esc</kbd></kbd> to close the Start Center if you prefer. In fact you may want to permanently disable it. After closing the Start Center, open the Edit menu (<kbd><kbd>Alt</kbd>+<kbd>E</kbd></kbd>), choose Preferences, and in the General tab, uncheck Show Start Center, then close the Preferences window.

MuseScore includes keyboard shortcuts for many of its commands, and others that do not have shortcuts defined by default can be customized later, in Edit, Preferences, Shortcuts.

### Finding your way around {#findingway}

The user interface in MuseScore works much like other notation programs or other document-oriented programs in general. It has a single main document window within which you can work with a score. MuseScore supports multiple document tabs within this window. It also supports a split-screen view to let you work with two documents at once, and you can have multiple tabs in each window.

In addition to the score window, MuseScore has a menu bar that you can access via the shortcuts for the individual menus:

* File: <kbd><kbd>Alt</kbd>+<kbd>F</kbd></kbd>
* Edit: <kbd><kbd>Alt</kbd>+<kbd>E</kbd></kbd>
* View: <kbd><kbd>Alt</kbd>+<kbd>V</kbd></kbd>
* Add: <kbd><kbd>Alt</kbd>+<kbd>A</kbd></kbd>
* Format: <kbd><kbd>Alt</kbd>+<kbd>O</kbd></kbd>
* Tools: <kbd><kbd>Alt</kbd>+<kbd>T</kbd></kbd>
* Plugins: <kbd><kbd>Alt</kbd>+<kbd>P</kbd></kbd>
* Help: <kbd><kbd>Alt</kbd>+<kbd>H</kbd></kbd>

Hint: once you have opened a menu, it may take several presses of the <kbd><kbd>Up</kbd></kbd> or <kbd><kbd>Down</kbd></kbd> keys before everything is read properly. Also, if at any point the screenreader stops responding, a useful trick to kickstart it again is to press <kbd><kbd>Alt</kbd></kbd> to move focus to the menu bar, then <kbd><kbd>Esc</kbd></kbd> to return to the score. Sometimes switching to another application then back can help as well.

In addition to the menu bar, there are also a number of toolbars, palettes, and sub-windows within MuseScore, and you can cycle through the controls in these using <kbd><kbd>Tab</kbd></kbd> (or <kbd><kbd>Shift</kbd>+<kbd>Tab</kbd></kbd> to move backwards through this same cycle). When you first start MuseScore, or load a score, focus should be in the main score window.

If nothing is selected (press Esc to clear any selection), pressing Tab takes you to a toolbar containing a series of buttons for operations like New, Open, Play, and so forth. Tab will skip any buttons that aren't currently active. The names and shortcuts (where applicable) for these buttons should be read by your screen reader.

Once you have cycled through the buttons on the toolbar, the next window Tab will visit is the Palettes. This is used to add various elements to a score (dynamics, articulations, and so forth).

If an element is selected in the score, the first window visited by Tab is the Inspector, which is used for making various manual adjustments in your score. Many of these features are based on the visual appearance of the score (although a few relate to playback).

If you have opened one of the additional optional windows, such as the Selection Filter, the Tab key will also visit these. You can close windows you do not need by going to the View menu and making sure none of the first set of checkboxes is selected (the windows that appear before the Zoom settings). By default, only the Palettes and Inspector should be selected. See [Initial Setup](#setup) for instructions for disabling the Start Center. <kbd><kbd>F9</kbd></kbd> can be used to toggle the Palettes while <kbd><kbd>F8</kbd></kbd> will toggle the Inspector.

To return focus to the score window after visiting the toolbar, or a subwindow, press Esc. If something was selected before visiting the other window, the selection is left intact, but pressing Esc once focus is in the score window clears the selection. The selection is automatically restored when you commence navigation using the accessibility commands described below.

### The score window {#scorewindow}

When you first start MuseScore 3 an empty example score is loaded by default. If you wish to experiment with editing features, this would be a good place to begin. Otherwise, you will probably want to start by loading a score. MuseScore uses the standard shortcuts to access system commands like <kbd><kbd>Ctrl</kbd>+<kbd>O</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>O</kbd></kbd>) to open a file, <kbd><kbd>Ctrl</kbd>+<kbd>S</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>S</kbd></kbd>) to save, <kbd><kbd>Ctrl</kbd>+<kbd>W</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>W</kbd></kbd>) to close, etc.

If you press <kbd><kbd>Ctrl</kbd>+<kbd>O</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>O</kbd></kbd>) to load a score, you are presented with a fairly standard file dialog. MuseScore can open scores in its own format (MSCZ or MSCX) as well as import scores in the standard MusicXML format, in MIDI format, or from a few other programs such as Guitar Pro, Capella, and Band-in-a-Box. Once you have loaded a score, it is displayed in a new tab within the score window. You can move between the tabs in the score window using <kbd><kbd>Ctrl</kbd>+<kbd>Tab</kbd></kbd> (does not apply for Mac). Hint: if the name of the score in the current tab is not read, ask your screen reader to read the title bar.

To read the score note by note, see below, but there are a few other interesting things you can do with a loaded score. You can press Space to have MuseScore play the score for you. You can use File / Export to convert to another format, including PDF, PNG, WAV, MP3, MIDI, MusicXML, etc. And of course, you can print it via File / Print or <kbd><kbd>Ctrl</kbd>+<kbd>P</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>P</kbd></kbd>).

If a score contains multiple instruments, it may already have linked parts generated. Linked parts are presented as part tabs within score tabs, but currently, there is no way to navigate these part tabs using the keyboard. The parts would not normally contain information different from the score; they would just be displayed differently (each part on its own page). If a score does not already have parts generated, you can do so through File / Parts, and that dialog is accessible. If you wish to print the parts, you can work around the inability of accessing part tabs individually by using the File / Export Parts dialog, which automatically exports PDF’s (or other formats) for all parts in one step.

### Score reading {#reading}

When you first load a score, the score window has the keyboard focus, but there will be nothing selected. The first step to reading a score is to select something, and the most natural place to begin is with the first element of the score. After a score is loaded, <kbd><kbd>Alt</kbd>+<kbd>Right</kbd></kbd> (Mac: <kbd><kbd>Alt</kbd>+<kbd>Right</kbd></kbd>) will select the literal first element, which is likely the title; <kbd><kbd>Ctrl</kbd>+<kbd>Home</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>Home</kbd></kbd>) will select the first "musical" element (usually a clef or an initial barline).

As you navigate between elements, your screen reader should give the name of the selected element. You will hear it read the name of the element (for example, “Treble clef”) and also give position information (for example, “Measure 1; Beat 1; Staff 1; Violin”). The amount of information read is optimized to not repeat information that has not changed. Pressing Shift currently interrupts the reading, which might also be useful.

Most navigation in MuseScore is centered around notes and rests only—it will skip clefs, key signatures, time signatures, barlines, and other elements. So if you just use the standard <kbd><kbd>Right</kbd></kbd> and <kbd><kbd>Left</kbd></kbd> keys to move through your score, you will only hear about notes and rests (and the elements attached to them). However, there are two special accessibility commands that you will find useful to gain a more complete summarization of the score:

* Next element: <kbd><kbd>Alt</kbd>+<kbd>Right</kbd></kbd> (Mac: <kbd><kbd>Alt</kbd>+<kbd>Right</kbd></kbd>)
* Previous element: <kbd><kbd>Alt</kbd>+<kbd>Left</kbd></kbd> (Mac: <kbd><kbd>Alt</kbd>+<kbd>Left</kbd></kbd>

These commands include clefs and other elements that the other navigation commands skip, and also navigate through all voices within the current staff, whereas other navigation commands such as <kbd><kbd>Right</kbd></kbd> and <kbd><kbd>Left</kbd></kbd> only navigate through the currently selected voice until you explicitly change voices. For instance, if you are on a quarter note on beat 1 of measure 1, and there are two voices in that measure, then pressing Right will move on to the next note of voice 1—which will be on beat 2—whereas pressing <kbd><kbd>Alt</kbd>+<kbd>Right</kbd></kbd> (Mac: <kbd><kbd>Alt</kbd>+<kbd>Right</kbd></kbd>) will stay on beat 1 but move to the note on voice 2.  Only once you have moved through all notes on the current beat on the current staff will the shortcut move you on to the next beat. The intent is that this shortcut should be useful for navigating through a score if you don’t already know what the contents are.

When you navigate to an element, your screen reader should read information about it. For notes and rests, it will also read information about elements attached to them, such as lyrics, articulations, chord symbols, etc. The accessibility commands will also navigate through those elements individually.

One important note: <kbd><kbd>Up</kbd></kbd> and <kbd><kbd>Down</kbd></kbd> by themselves, with <kbd><kbd>Shift</kbd></kbd>, or with <kbd><kbd>Ctrl</kbd> / <kbd>Cmd</kbd></kbd> are not useful shortcuts for navigation! Instead, they change the pitch of the currently selected note or notes. Be careful not to inadvertently edit a score you are trying to read. Up and Down should only be used with Alt if your intent is navigation only. See the list of navigation shortcuts below.

If you should lose track of your place in the score - or if you lose the selection completely - press <kbd><kbd>Shift</kbd>+<kbd>L</kbd></kbd> ("location") to get the current location.

#### Moving forwards or backwards in time

The following shortcuts are useful for moving “horizontally” through a score:

* Next element: <kbd><kbd>Alt</kbd>+<kbd>Right</kbd></kbd>
* Previous element: <kbd><kbd>Alt</kbd>+<kbd>Left</kbd></kbd>
* Next chord or rest: <kbd><kbd>Right</kbd></kbd>
* Previous chord or rest: <kbd><kbd>Left</kbd></kbd>
* Next measure: <kbd><kbd>Ctrl</kbd>+<kbd>Right</kbd></kbd>
* Previous measure: <kbd><kbd>Ctrl</kbd>+<kbd>Left</kbd></kbd>
* Go to measure: <kbd><kbd>Ctrl</kbd>+<kbd>F</kbd></kbd>
* First element: <kbd><kbd>Ctrl</kbd>+<kbd>Home</kbd></kbd>
* Last element: <kbd><kbd>Ctrl</kbd>+<kbd>End</kbd></kbd>

#### Moving between notes at a given point in time

The following shortcuts are useful for moving “vertically” through a score:

* Next element: <kbd><kbd>Alt</kbd>+<kbd>Right</kbd></kbd>
* Previous element: <kbd><kbd>Alt</kbd>+<kbd>Left</kbd></kbd>
* Next higher note in voice, previous voice, or staff above: <kbd><kbd>Alt</kbd>+<kbd>Up</kbd></kbd>
* Next lower note in voice, next voice, or staff below: <kbd><kbd>Alt</kbd>+<kbd>Down</kbd></kbd>
* Top note in chord: <kbd><kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Up</kbd></kbd>
* Bottom note in chord: <kbd><kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Down</kbd></kbd>

The <kbd><kbd>Alt</kbd>+<kbd>Up</kbd></kbd> and <kbd><kbd>Alt</kbd>+<kbd>Down</kbd></kbd> commands are similar to the <kbd><kbd>Alt</kbd>+<kbd>Right</kbd></kbd> and <kbd><kbd>Alt</kbd>+<kbd>Left</kbd></kbd> commands in that they are designed to help you discover the content of a score. You do not need to know how many notes are in a chord, how many voices are in a staff, or how many staves are in a score in order to move vertically through the score using these commands.

#### Filtering score reading {#filtering}

Excluding certain elements like lyrics, or chord names while reading the score is possible by using the Selection filter (<kbd><kbd>F6</kbd></kbd>). Uncheck those elements you don't want to read. However, this feature may not currently be implemented.

### Score playback {#playback}

The <kbd><kbd>Space</kbd></kbd> bar serves both to start and stop playback. Playback will start with the currently selected note if one is selected; where playback was last stopped if no note is selected; or at the beginning of the score on first playback.

MuseScore supports looped playback so you can repeat a section of a piece for practice purposes. To set the “in” and “out” points for the loop playback via the Play Panel (<kbd><kbd>F11</kbd></kbd>):

1. First select the note in the score window where the loop should start;
2. Go to the Play Panel and press the Set loop In position toggle button;
3. Back to the score window, navigate to the note where you want the loop to end;
4. Switch again to Play Panel, and press the Set loop Out position toggle button;
5. To enable or disable the loop, press the Loop Playback toggle button.

You can also control the loop playback and control other playback parameters, such as overriding the basic tempo of a score, using the View / Play Panel (<kbd><kbd>F11</kbd></kbd>).

### Score creation and editing {#editing}

While some advanced score editing techniques require visual inspection of the score, and a small number of commands may require the mouse, as of MuseScore 3.3 most score editing features are fully accessible.

You can enter music into the default empty score (a score with one staff, using a piano sound), or edit an existing score that you have opened already, or you can create a new score with the set of instruments you want.

#### Creating a new score {#creating}

To create a new score, use File, New or <kbd><kbd>Ctrl</kbd>+<kbd>N</kbd></kbd>. A wizard then walks you through the score creation process.

The first screen of the wizard has fields to enter the title, composer, and other information. The second allows you to select a template (predefined scores for common ensembles like choral SATB or jazz big band) or to select instruments. The third allows you to select an initial key signature and tempo. Sometimes this screen gets skipped, so if this happens, press the Back button to go back. To select a key, use <kbd><kbd>Up</kbd></kbd> and <kbd><kbd>Down</kbd></kbd>. The key signature control does not work well with some screenreaders, but if you give the "read current line" command (e.g., NVDA+L), it may read the currently-selected key. The next and final screen of the wizard allows you to select an initial time signature, pickup (anacrusis), and the number of measures to start with.

Once you have a score, you can begin editing it.

#### Note input {#note-input}

To enter notes, you need to be in note input mode. First, navigate to the measure in which you would like to enter notes, then press <kbd><kbd>N</kbd></kbd>. Almost everything about note input is designed to be keyboard accessible, and the standard documentation should be good to help you through the process. Bear in mind that MuseScore can either be in note input or normal mode, and it won’t always be clear which mode of these you are in. When in doubt, press Esc. If you were in note input mode, this will take you out. If you were in normal mode, you will stay there, although you will also lose your selection.

The basic process of note input is to first select a duration (for example, using shortcuts 4-5-6 for eighth, quarter, half), then enter a note by typing its letter name. Once a duration is selected you can enter multiple notes of the same duration. Press <kbd><kbd>0</kbd></kbd> to enter a rest.

The <kbd><kbd>Up</kbd></kbd> and <kbd><kbd>Down</kbd></kbd> keys raise or lower the pitch by a half step, adding or removing accidentals as necessary. To change enharmonic spelling of a note, press <kbd><kbd>J</kbd></kbd>.

To enter a tie, select the duration of the tied note then press <kbd><kbd>+</kbd></kbd>. To create triplets, select the total duration for the triplet, then press <kbd><kbd>Ctrl</kbd>+<kbd>3</kbd></kbd> (similarly for quadruplets and other tuplets). To enter music in multiple voices on a single staff, pressing <kbd><kbd>Ctrl</kbd>+<kbd>Alt</kbd></kbd> plus a number from 1 to 4 will switch to that voice (keep in mind, the first voice for each staff is always voice 1).

There is much more to note input in MuseScore. See for the [section on Note Input in the Handbook](https://musescore.org/en/handbook/3/note-input).

#### Selection {#selection}

MuseScore supports the usual keyboard shortcuts for selection. Navigating is the same as selecting for single elements. To select a range of elements, navigate to the first, press and hold Shift, then navigate to the second. <kbd><kbd>Ctrl</kbd>+<kbd>A</kbd></kbd> will select the entire score.

#### Palettes {#palettes}

As mentioned previously, many symbols other than notes are entered from the palettes window. The basic use model is, first select the element or elements in the score you want to apply the palette item to, then apply the palette element. There are a few different ways to select the palette element.

The simplest method to use at first is to simply browse the palettes window by keyboard. To reach the palettes window, press Shift+Tab. The screenreader may not specifically tell you that you are in the palettes window, but you will discover that you are as you navigate. Depending on whether you have used the palettes before, focus may be where you left off, or at the top. Press Tab a few times to get to the first palette within the window (Clefs). You can browse the list of palettes using the Up and Down cursor keys. The Right cursor key opens a palette, and then all four cursor keys can be used to navigate through the elements (they are arranged in a table). You can also use Tab to navigate the palette names and contents.

Once you have found a palette item you want to apply, press Enter to apply it to the currently-selected score elements and return focus to the score. The next time you press Shift+Tab to return to the palettes, the last-used palette item will still be selected, so Enter will apply it again.  The screenreader may stop responding after applying a palette item, even though focus has returned to the score, but the trick of pressing Alt followed by Esc should get it working again.

You can also use the palette search facility to quickly find a palette item. The search box is one of the first elements at the top of the palette, so you can navigate to it, or you can define a shortcut (Edit, Preferences, Shortcuts) for the "Palette search" command, which will subsequently take you directly to the search box.  Once you are in the box, type the first few characters of a search term, and only palette items matching that search will shown. You can then navigate to the search results and find the element you want. The Down cursor will take you directly to the first search result, then you can use Right after that.  However, on some systems MuseScore may crash when using the palette search function with a screen reader enabled.

Another way to reach the palettes window is with the <kbd><kbd>F9</kbd></kbd> shortcut, which toggles the palettes window on and off.  By default, the palettes window is open, so pressing F9 will close it, but then pressing it again opens the window and puts the cursor in the search box.

There is one other useful technique for palette accessibility, and that is the "Apply current palette element" command (for which you can define a shortcut). If you are in the score, this will apply the last-used palette element automatically (the equivalent of Shift+Tab followed by Enter).

#### Menus and Shortcuts {#shortcuts}

Some elements can be added or edited via menu commands or keyboard shortcuts. The Edit menu has standard copy and paste commands (and the usual shortcuts work too). The Add menu has commands to add notes, tuplets, measures, frames, text, and some lines. The Format menu has commands relating mostly to the visual appearance of the score (e.g., page and staff size, position and size of symbols, fonts used for text), which can be extremely useful in producing large print a.k.a. "modified stave notation" scores (see below). The Tools menu has a number of other useful commands, including ones to remove measures or other selected ranges, to transpose a selection, to join and split measures, and more. any of these commands have shortcuts defined by default that should be read by a screenreader. You can define custom shortcuts for most of the rest in Edit, Preferences, Shortcuts.

There are also shortcuts for a number of palette items, and the possibility to define others (although many palette items currently do not support this). Some useful shortcuts to remember include:

Ctrl+T: staff text
Alt+Shift+T: tempo
Ctrl+L: lyrics
Ctrl+K: chord symbol
Ctrl+M: rehearsal mark

S: slur
Shift+S: staccato
Shift+V: accent
Shift+N: tenuto
Shift+O: marcato
slash: grace note
less than: crescendo
greater than: diminuendo

### Customization {#customization}

You can customize the keyboard shortcuts by opening the Edit menu, selecting Preferences, then navigating to the Shortcuts tab. Once there, Tab will take you to the list of shortcuts, and you can navigate the list directly with the Up and Down cursor keys, but it is a very long list. You can instead hit Tab a few more times to reach the Search box, then type the first few characters of the command to filter the list, then navigate back to the list.

Once you have found the command you wish to customize, press Enter. You can then press the key combination you wish to be the shortcut. It can be a single key, a key with Shift, Ctrl, and/or other modifiers, or even a sequence or two or more keys pressed in succession. After entering the shortcut you wish, press Tab to get to the Add or Replace button (Tab is the only key that won't be interpreted as part of a shortcut sequence). If you reach Cancel without ever seeing Add or Replace, it means the shortcut you choose conflicts with another. Navigate back to the where you typed the shortcut and it will tell you the name of the command it conflicts with. Hit Tab to get to the Clear button to clear it, then try again with a different shortcut.

At some point, we may provide a set of special accessibility-optimized shortcuts. There is already a facility in the shortcut dialog to save and load shortcut definitions, so it is possible to share shortcut definitions with other users.

### External links {#external-links}

* [MuseScore Accessibility Demo (YouTube)](https://youtu.be/Ocl9gBxmeKg)
* [node:113581,title="Creating a New Score in MuseScore with NVDA"] (MuseScore Tutorial)
* [node:120426,title=“Inputting notes in MuseScore with NVDA“] (MuseScore Tutorial)
* [node:25135,title="Creating Modified Stave Notation in MuseScore“] (MuseScore Tutorial)