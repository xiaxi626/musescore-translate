This How-To walks through a number of scenarios for creating and modifying complex chord diagrams via the Inspector, by starting with the Fretboard Diagrams palette (in the Advanced Workspace).
### Overview {#overview}

The Fretboard Diagrams [node:278614,title="palette"] in the Advanced Workspace provides a set of 21 common chord diagrams for the guitar (see: [node:278639,title="Fretboard Diagrams"]). This palette consists of a single example of a major, minor, and seventh chord for each diatonic scale tone (CDEFGAB). These 21 chords are adequate for many simple pop or folk music scores. 

When these standard chords are not enough, they can be used as a starting point for creating modified chord diagrams, via the [node:278642,title="Inspector"]. This technique enables the use of chord extensions, alterations, different voicings, and different positions, versus the 21 standard diagrams. Alternatively, users may prefer to begin with a blank diagram and create their chords "freehand."

This How-To considers a number of usage scenarios. 

### Stylistic decisions {#stylistic-decisions}

Regardless of the type of use, incorporating chord diagrams requires some style/format choices. The Fretboard Diagrams mechanisms supports chord diagrams and symbols of varying appearance. There is no publishing standard for such diagrams: many formats are and have been in use. Some users might choose to follow a particular publisher's or educator's practices. Such decisions would typically be made early in the creation of a score, and reflect its intended use.

* Beginners may refer to chord diagrams as a form of instruction, as a way to help learn unfamiliar chords.

* Intermediate and advanced performers will generally rely just on the chord names in deciding what to play. However, they may refer to chord diagrams as clues to recommended voicing and fingering, or (in the case of unusual chords) how a given chord might be played.

Several stylistic factors are listed below:

* __Number/completeness of chords__. Simplified scores might only show guitar chords at important harmonic changes, and omit passing chords, approach chords, etc. Experienced performers will reharmonize and substitute chords as a matter of course, and refer to such diagrams and symbols as visual hints to tonal centers, phrasing, etc. More complex or educational material might go into more depth, showing one or more chords per measure with extensions and options.

  simple: ![Simple diagram example](../images/How%20to%201%20352.jpg)
  more complex: ![Complex chord example](../images/How%20to%202%20320.jpg)
  
* __Restriction to "simple" chords__. Simplified scores will often avoid certain chords or types of chords, and in particular they may exclude or or limit the use of barre chords.

  standard diagrams: ![Simple diagram example](../images/How%20to%203.jpg)
  simplified diagrams without barres: ![Complex chord example](../images/How%20to%204.jpg)

* __Size of diagrams and their elements__. Diagram size is a function of their intended use. A simplified score for beginners might show large diagrams. Small diagrams may suffice if they are just voicing clues.

* __Use and appearance of chord symbols__. Diagrams and chord symbols can be used together in different ways. Most commonly, named chord diagrams replace textual chord symbols, and serve the same purpose. In other cases, diagrams that incorporate small chord symbols are used in addition to full-size chord symbol text, and these all coexist on the same page. This may be done in an educational context, where guitar chord voicings are superimposed on an existing lead sheet or other score to show how the guitar chords relate to the piano harmonly. It will also be done when the diagrams show a rhythm guitar part that is different from underlying material on the staff, and may utilize simpler or different chords.

  ![Different chord symbols example](../images/How%20to%205.jpg)
  
* Use of __mute/open string indicators__. The 21 chords in the standard palette incorporate symbols showing mute and open strings (X or O above a string with no fretted notes). This is a traditional part of chord diagrams, particularly in an educational context; but for visual simplicity, published scores often omit these symbols except when significant. All guitarists realize that, when playing a D major chord on open strings, the sixth open string is not played. Similarly, all guitarists realize that, playing a non-barre movable chord shown on the 7th fret, the non-fretted strings should be muted. The usefulness of these symbols is a function of the score's intended audience.

  ![Mute/open string example](../images/How%20to%206.jpg)



### Scenario 1: Piano/Vocal/Guitar scores {#1-piano-vocal-guitar-scores}

Perhaps the most familiar use of published chord diagrams is in the many lead sheets and songbooks sold for popular music and artists. Guitar chords (or chords for ukulele, banjo, or other instruments) are displayed above a grand staff containing a piano part and vocals. Many of these scores are intended for casual players.

The chord diagrams are often simplifications of the harmony present on the staff. Well-edited scores feature useful chord voicings that are both appropriate to the music and comfortable to play. Not all publications achieve this goal.

To create MuseScore scores in this style, it is generally necessary to create some custom chord diagrams. The 21 standard diagrams provided (in the Fretboard Diagrams [node:278614,title="palette"] in the Advanced Workspace) will indeed suffice for some simple tunes. However, most users will need to go further, to cover the many additional standard chords used by beginning-to-intermediate players.

#### Scores being created by guitarists {#scores-by-guitarists}

When such a score is created by an experienced player of guitar (or other fretted instrument), a typical work process is to play through each phrase, decide which chord fingerings/voicings are most appropriate for the score's target audience, and insert the appropriate diagrams. 

* When the desired chord happens to match one of those in the standard palette, it can be placed directly; see [node:278639,fragment="add-fretboard-diagram",title="To add a Fretboard Diagram"]. As each Fretboard Diagram is placed on the score, an associated [node:278623,title="chord symbol"] is also created, using the palette cell's chord name. (Note: This behavior is absent in the initial 3.1 release.)

* When the desired chord is not present in the palette, a custom chord must be created (see [node:278639,fragment="edit-fretboard-diagram",title="To edit a Fretboard Diagram"]) either by:

  o Adding and then modifying a standard chord diagram, or
  o Creating a new chord diagram from a blank grid.

[node:278623,title="Chord symbols"] are an important feature of Fretboard Diagram use. Users must decide which [node:278623,fragment="chord-symbol-style",title="symbol style"] will be used, the size and placement of the symbols, etc. Chord diagram customiztion will not be reflected in the associated symbol, of course; symbols are just text fields.

Copying and pasting a diagram will not copy the associated chord symbol. A new chord symbol can be added to a diagram that does not have one: select the diagram and use <samp class="menu">Add</samp>&rarr;<samp class="menuitem">Text</samp>&rarr;<samp class="menuitem">[node:278623,title="Chord Symbol"]</samp> or the shortcut <kbd><kbd>Ctrl</kbd></kbd><kbd><kbd>K</kbd></kbd>. 

Note: It is possible for a given note to be associated with all three of the following: a) chord symbol, b) Fretboard Diagram, and c) separate chord symbol associated with the Fretboard Diagram.

Regular users of Fretboard Diagrams often create a [node:278614,fragment="custom-palettes",title="custom palette"] in a private workspace, to hold frequently-used chords missing from the standard palette, movable chords, and blank chord grids of various dimensions.

#### Scores being created by non-guitarists {#scores-by-non-guitarists}

Users without fretted instrument expertise may, with discretion, use the standard chord diagram palette to incorporate guitar chords in their scores. This will be most effective with simple folk melodies in the keys of C, D, or G major, and in their relative minors. 

The lack of standard Fretboard Diagram palette entries for Bb, C#m, etc. will make working in other keys difficult. Similarly, limitations result from the lack of major 7th, 9th, suspended, and other common chord forms. The missing chords can be created by modifying standard entries; but some instrument knowledge is needed to make correct fingering and voicing choices. Intermediate-level guitarists have a working knowledge of a hundred or more chords; advanced guitarists recognize and construct thousands of chord forms.

### Scenario 2: Lead sheets with guitar chords {#2-lead-sheets-guitar-chords}

The basic issues described above for piano/vocal/guitar scores in [Scenario 1](#1-piano-vocal-guitar-scores) also apply to guitar-specific lead sheets. 

However, since guitar-oriented scores are created for (and typically by) experienced guitarists, they usually make less use of the 21 standard diagrams, and make greater use of custom chord diagrams. These scores are often created for educational purposes (for example, in transcriptions or exercises in which a particular choice of fingering or voicing is important).

A common approach for creating guitar-oriented scores is to start with a conventional lead sheet score that already contains chord symbols. The user then adds Fretboard Diagrams below each symbol. This may be done for every chord in the score, or only for those chords where unusual choices are being made. 

To create these custom diagrams, most users will start by adding blank grids, and then add the notes as desired as [node:278639,fragment="edit-fretboard-diagram",title="described in the Handbook"]. Since a given piece will often use the same chord voicings repeatedly, copy/paste can save time in creating the diagrams needed for a score.

### Scenario 3: Ted Greene style lead sheets {#3-ted-greene-lead-sheets}

The legendary guitarist and educator __Ted Greene__ developed a system of chord notation that has remained popular with generations of his followers and students. This notation system has a number of differences from the traditional chord diagrams found in pop music books, as described above in [Scenario 1](#1-piano-vocal-guitar-scores). The most important difference is the use of multiple symbols on the fretboard grid, indicating a sequence of notes over time.

The difficulty of creating these diagrams via notation software has, in the past, led many guitarists to create and publish scores using handwritten chord diagrams. The MuseScore Fretboard Diagrams interface supports most of the features necessary to create these diagrams for electronic publication and distribution.

#### Purpose of this technique {#ted-green-purpose}

This type of score is primarily used to support the needs of guitar educators, composers, and arrangers, and to help them exchange written material in a form that has proven effective. It is an alternative to conventional notation, as used with classical guitar, and to tablature, as used with many popular music styles. Adherents to the chord grid approach are often passionate about its use, and many use it primarily or exclusively.

These grids were originally (and are still often) used without any conventional notation. A page covered with grids shows a series of chords and single notes, with each grid usually representing one or two beats.

![Grids without notation example](../images/How%20to%207.jpg)

By superimposing these grids on a conventional lead sheet, it is possible to tie together the guitaristic voicing and fingering choices with a song's underlying melody and harmony. This hybrid approach has proven helpful and popular among users of this notation style.

![Grids with notation example](../images/How%20to%208.jpg)

#### Differences from traditional chord grids {#ted-green-differences}

The following points summarize the principal differences between the __Ted Greene chord grid__ approach to scores, versus the more traditional pop-music chord digrams.

1. __Simple, compact grids__. Grids are simple and (to the extent practical) uniform. Lines have uniform thickness. Extraneous information is omitted.

2. __Multiple grids per measure__. A separate grid is generally provided for each beat or two beats.

3. __Multiple symbols denote movement__. Different symbols are used on the grids to show events over time. (The normal sequence of symbols is dot&rarr;X&rarr;square&rarr;delta. Usage varies, but scores generally spell out the order implied by their symbols.) Some grids include symbols for optional notes. Some grids show digits indicating fingering or chord tones. With MuseScore 3.1, four symbols (dot, X, square, delta) are available within diagrams, which can be used in to mean whatever the user chooses. In the future, additional symbols such as digits may also be supported. 

4. __Starting fret__. A digit to the left of the fretboard shows the starting fret. With MuseScore 3.1, this digit is always shown next to the first fret displayed. An option to display the digit at a different position may become available in the future. (Ted Greene style grids traditionally often show the digit next to either: the lowest fretted note, the lowest note on the lowest string, or the lowest root tone in the chord.)

5. __Small chord name__. A small chord name (chord symbol) is generally displayed above the grid. In cases where a grid shows only one or two notes, this name may be omitted, or it may show the implied harmony. Optional chords or other annotations sometimes appear here as well.

6. __Other elements__. Additional notations, lines, arrows, etc. are sometimes used to show related fingering, held notes, and similar elements. There is no direct support for this in MuseScore 3.1, but existing text and symbols can be used to address similar needs.

#### Creating grid-oriented scores {#ted-greene-score-creation}

1. __Start with a lead sheet__. As in [Scenario 2](#2-lead-sheets-guitar-scores), the logical starting point is with a conventional lead sheet containing chord symbols. (Note: Users who are familiar with chord grid usage, but less familiar with MuseScore, will need to take some time to become familiar with its use for the entry and editing of conventional notation.) If you don't have a lead sheet prepared, it will generally be faster to create this first, before adding Fretboard Diagrams. Note that many standards are available for free download at [MuseScore.org](http://Musescore.org).

2. __Insert blank grids__. With a score available, the user would then typically insert a blank chord grid over each note where a diagram is needed. (This corresponds to the traditional method of creating grid scores on paper, i.e. using a blank template preprinted with rows and columns of chord grids.) If you don't have a blank grid in your palette, then create one as follows: Add any chord from the Fretboard Diagrams [node:278614,title="palette"] in the Advanced Workspace, select it, and use the "Clear" button to remove all the dots. You can then copy/paste this blank grid. 

3. __Enter some chords__. Select the first blank grid and use the [node:278642,title="Inspector"] to enter a chord, [node:278639,fragment="edit-fretboard-diagram",title="as described in the handbook"]. Do this for a few grids.

4. __Consider overall grid appearance__. After entering a few chord grids, consider the overall appearance of the score.

  * Are the grids the correct size?
  * Are the grids placed at a reasonable position above the staff?
  * Are the fret numbers the correct size?
  * Are the dots, symbols, barres etc. on the grids the correct size?
  * Are the chord symbols (chord names) above the grids the correct size?
  * Is the enough space on each line to show all the needed grids?

  All of these appearance factors can be adjusted. There are numerous global style settings that can simplify your formatting tasks:

  * Many of the propertes of Fretboard Diagrams have style-wide defaults that can be set via the [node:278642,title="Inspector"] (look for the "S" buttons).
  * Global diagram settings are found in [node:278570,fragment="style",title="Style"] submenu: select <samp class="menu">Format</samp>&rarr;<samp class="menuitem">Style…</samp>&rarr;<samp class="menuitem">[node:278570,fragment="style-fretboard-diagrams",title="Fretboard Diagrams"]</samp>
  * Global chord symbol settings are found in [node:278570,fragment="style",title="Style"] submenu: select <samp class="menu">Format</samp>&rarr;<samp class="menuitem">Style…</samp>&rarr;<samp class="menuitem">[node:278570,fragment="style-chord-symbols",title="Chord symbols"]</samp>

5. __Continue entering grids and fine-tuning their appearance__. Once you get your style settings the way you want them, you can resume entering chords. You may still need to adjust the position of some diagrams and chord names manually. You do this by:

  * First turning off the item's "automatic placement" in the [node:278642,title="Inspector"]
  * Then clicking on the item
  * Then dragging the item where you want it

6. __Consider printed/online appearance__. After further entry progress, consider printing the score, or exporting it to a PDF. Be sure the diagrams are clear and readable, and if necessary adjust the formatting.

7. __Copy/paste repeated chords__. In the process of creating these custom chord grids, you will no doubt find that some chords are direct repetitions from earlier. In those cases, simply delete the blank grid, and copy and paste the earlier diagram to the note in question. 

8. __Create a custom palette if useful__. If you find that some chords are being copied/pasted often, consider creating a custom workspace and adding a [node:278614,fragment="custom-palettes",title="custom chord palette"] (or modifying the standard palette). You can save common chords there, along with blank grids, movable chords, and other elements that you find you reuse often. Some users will find they have much repetition. Others will constantly be using new chords and new voicing and may not experience much benefit versus starting with a blank grid every time.

 
## External links

* [www.TedGreene.com/teaching](http://www.TedGreene.com/teaching), with extensive free downloadable examples of complex diagram use