---
title: Repeats and jumps
date: 2022-01-06 00:21:56
---
 ### Simple repeats {#simple-repeats}

You can create a __simple repeat__ by placing a __start__ and an __end repeat__ [node:278593,title="barline"] at the beginning and end of a passage. These can be applied from the _Barlines_ or _Repeats & Jumps_ palette.

 [inline:simple_repeat.png=Simple repeat] 

__Note__: If the start of a repeat coincides with the _beginning_ of a piece or [node:278620,fragment="section-break",title="section"], the start repeat barline can be omitted if desired. Similarly, an end repeat barline can be omitted at the _end_ of a score or section.

 [inline:simple_repeat_start.png=Simple repeat at start]

### 1st and 2nd endings {#first-second-endings}

First create a simple repeat (as shown above), then apply the first and second time endings—see [node:278580,title="Voltas"].

### Playback {#playback}

#### Turn repeat playback on/off {#turn_on_off}

* Toggle the "Play Repeats" [inline:Button-Play_Repeats.png="Play Repeats" icon] button on the toolbar.

#### Adjust repeat section playback {#adjust_repeat_playback}

[Simple repeats](#simple-repeats), such as the ones illustrated above, or "1, 2" volta sections, usually play back correctly first time. More complex repeats may need further adjustment as follows:

1. Ensure that the start and end barlines are correctly positioned. For a volta section, ensure that each volta, except the last one, terminates with an end repeat barline.
2. __In the case of a simple repeat__, where more than one repeat is needed, right-click on the measure containing the end repeat barline and select [node:278611,fragment="properties",title="Measure properties"]. Adjust [node:278611,fragment="play-count",title="Play count"] so that it is equal to the number of times you want the section to play back.
2. __In the case of a complex volta section__, such as the following:
 [inline:volta_example.png] 
Make sure that the volta "Repeat list" is set up correctly—see [node:278580,fragment="volta-properties",title="Volta properties"]. Right-click on the measure containing the end repeat barline and select [node:278611,fragment="properties",title="Measure properties"]. Adjust [node:278611,fragment="play-count",title="Play count"] so that it is one greater than the number of measures listed in the Volta "Repeat list." In this case, since 5 measures are listed, the "Play count" needs to be set to 6.

### Repeat symbols and text {#repeat-symbols-and-text}

Text and symbols related to repeats are located in the "__Repeats & Jumps__" [node:278614,title="palette"] (in the Basic and Advanced workspaces). This palette contains:

* Symbols for measure repeat, Segno, Segno Variation (Serpent), Coda, and Coda Variation (Codetta)
* D.S., D.C., al Coda, al Fine, To Coda, and Fine text
* Repeat barlines

[inline:Palette-Repeats.png=Repeats palette]

To add a __repeat__ symbol to the score use either of the following:

* Select a measure, then click the desired repeat symbol in the palette (double-click in versions prior to 3.4).
* Drag and drop a repeat symbol from the palette _onto_ (not above!) the desired measure (so the measure changes color).

### Jumps {#jumps}

__Jumps__ are symbols in the score which tell the musician to skip to a named [marker](#markers) (see below). Jumps include the various kinds of D.C. (Da Capo) and D.S. (Dal Segno) text.

To set correct playback of jumps:

* Make sure that the "Play Repeats" [inline:Button-Play_Repeats.png="Play Repeats" icon] button on the toolbar is selected. This is a toggle, so you can turn off playback by clicking the same button.
* _After_ the jump, and following established convention, only the last round of any simple repeat section is played back. If you want playback to take these repeats in full:
 1. Select the applicable jump symbol;
 2. In the "Jump" section of the Inspector, check "Play Repeats".

 __Note__: Jumps are taken only after all simple repeats in the section are played through. 

If you click on a _jump_, some text boxes and a checkbox are displayed in the __Jump__ section of the [node:278642,title="Inspector"]. These have the following effects on playback:

* __Jump to__: Playback jumps to the [marker](#markers) whose "Label" is the same as the "Jump to" tag.
* __Play until__: Playback continues until it reaches a [marker](#markers) whose "Label" is the same as the "Play until" tag.
* __Continue at__: Playback jumps to the next [marker](#markers)  whose "Label" is the same as the "Continue" tag.
* __Play repeats__: Ticking this box tells MuseScore to play repeats after D.C. (Da Capo) or D.S. (Dal Segno) jumps. If this option is not ticked then [simple Repeats](#simple-repeats) are not taken after jumps and playback works as if it were the last repeat.

 __Note__: The tags _start_ and _end_, referring to the beginning and end of a score or [node:278620,fragment="section-break",title="section"], are _implicit_ and don't need to be added by the user.

### Markers {#markers}

__Markers__ are the places referred to by the [jumps](#jumps). A list of markers (in addition to the implicit "start" and "end") follows:

* [inline:dal_segno.png=Segno]: Segno (tag: _segno_)
* [inline:dal_segno_var.png=Segno variation.]: Segno Variation (tag: _varsegno_)
* [inline:coda.png=Coda]: Coda (tag: _codab_)
* [inline:coda_var.png=Coda variation]: Coda Variation (tag: _varcoda_)
* __Fine__: (tag: _fine_)
* __To Coda__: (tag: _coda_)

If you click on a marker, the following properties appears in the __Marker__ section of the Inspector:

* __Marker type__: This can be changed from the dropdown list, if required.
* __Label__: This is the (identifier) tag associated with the marker. See also, [Jumps](#jumps) (above).

### Examples of jumps {#examples}

* __Da Capo (D.C.)__: At the "D.C." sign, playback jumps to the start (i.e. to the implicit _start_ tag) and plays the entire score or section again (i.e. up to the implicit _end_ tag).
* __Da Capo (D.C.) al Fine__: At the "D.C. al Fine" sign, playback jumps to the start (i.e. to the implicit _start_ tag) and plays the score up to the __Fine__ (i.e. the _fine_ tag).
* __Dal Segno (D.S.) al Fine__: At the "D.S. al Fine" sign, playback jumps to the __Segno__ symbol (i.e. the _segno_ tag) and then plays up to the __Fine__ (i.e. the _fine_ tag)
* __Dal Segno (D.S.) al Coda__: At the "D.S. al Coda" sign, playback jumps to the __Segno__ symbol (i.e. the _segno_ tag) and then plays up to the __To Coda__ (i.e. the _coda_ tag). Playback then continues at the __Coda__ symbol (i.e. the _codab_ tag).

__Note__: The properties (i.e. the tag names) of jumps and markers can be set via the [node:278642,title="Inspector"].  

 [inline:multiple jumps.png] 

You need to modify them if using multiple jumps and markers.

### See also {#see-also}

* [node:278593,title="Barlines"]
* [node:278580,title="Volta"]

### External links {#external-links}

* [MuseScore in Minutes: Repeats and Endings, part 2](https://youtu.be/07uPDU11Gi4?list=PLTYuWi2LmaPGb4SKXHm9JULQ-0CH8KpUk) (video tutorial)
* [node:11368,title="How to separate a coda from the rest of the score"] (MuseScore HowTo)
* [node:103336,title="How to create a 2-measure repeat sign with playback"] (MuseScore HowTo)
* [node:291062,title="How to use Jumps and Repeats"] (MuseScore HowTo)