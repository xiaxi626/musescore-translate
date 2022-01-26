---
title: Viewing and navigation
date: 2022-01-09 12:53:52
---
This chapter describes the options available in the  __View__ Menu, and in the __Zoom__ and  __Page View/Continuous View__ menus (located in the toolbar above the score). It also details the various navigation commands and functions.

### View menu {#view-menu}

#### Show sidebars/panels {#show-panels}

* [node:278614,title="Palettes"]: <kbd><kbd>F9</kbd></kbd>
* [node:278649,title="Master palette"]: <kbd><kbd>Shift</kbd>+<kbd>F9</kbd></kbd> (Mac: <kbd><kbd>Fn</kbd>+<kbd>Shift</kbd>+<kbd>F9</kbd></kbd>)
* [node:278642,title="Inspector"]: <kbd><kbd>F8</kbd></kbd> (Mac: <kbd><kbd>Fn</kbd>+<kbd>F8</kbd></kbd>)
* [node:278585,fragment="play-panel",title="Play Panel"]: <kbd><kbd>F11</kbd></kbd> (Mac: <kbd><kbd>Fn</kbd>+<kbd>F11</kbd></kbd>)
* [Navigator](#navigator)
* [node:278676,title="Timeline"]: <kbd><kbd>F12</kbd></kbd>
* [node:278583,title="Mixer"]: <kbd><kbd>F10</kbd></kbd> (Mac: <kbd><kbd>Fn</kbd>+<kbd>F10</kbd></kbd>)
* [node:278660,title="Synthesizer"]
* [node:278613,fragment="selection-filter",title="Selection filter"]: <kbd><kbd>F6</kbd></kbd> (Mac: <kbd><kbd>Fn</kbd>+<kbd>F6</kbd></kbd>)
* [node:278615,fragment="virtual-piano-keyboard",title="Piano keyboard"]: <kbd><kbd>P</kbd></kbd>
* [node:281267,title="Score comparison tool"]

#### Zoom in/out {#zoom}

There are several ways to zoom the score in or out:

* __Keyboard shortcut__:
 * Zoom In: <kbd><kbd>Ctrl</kbd>+<kbd>+</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd> +<kbd>+</kbd></kbd>)
 * Zoom Out: <kbd><kbd>Ctrl</kbd> +<kbd>-</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd> +<kbd>-</kbd></kbd>).

* __View menu__:
 * Zoom In: <samp class="menu">View</samp>&rarr;<samp class="menuitem">Zoom In</samp>
 * Zoom Out: <samp class="menu">View</samp>&rarr;<samp class="menuitem">Zoom Out</samp>.

* __Mouse__
 * Zoom In: Scroll _up_ with the mouse wheel while holding down <kbd><kbd>Ctrl</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd></kbd>)
 * Zoom Out: Scroll _down_ with the mouse wheel while holding down <kbd><kbd>Ctrl</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd></kbd>).

* __Drop-down menu__: To set a specific zoom, use the dropdown menu in the standard toolbar to set the view magnification of the score (25–1600 %) or display it using the options "Page Width", "Whole Page", or "Two Pages".

 [inline:Zoom.png=Zoom]
You may type a custom zoom % into the dropdown field if your desired zoom level isn't available by default.

* __To return to 100% zoom__: Use the shortcut <kbd><kbd>Ctrl</kbd>+<kbd>0</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>0</kbd></kbd>).

#### Toolbars {#toolbars}

The __Toolbar__ area is located between the __Menu bar__ and the __document window__.

[inline:toolbar_area_en.png=Toolbar area]

It contains the following toolbars:

* __File Operations__: New score, Load score, Save, Print, Undo, Redo.
* __Zoom__/__Page View__.
* __Playback controls__: Enable MIDI, Rewind, Play/Stop, Loop, Play Repeats, Metronome.
* __Concert Pitch__: Displays score in written or concert (sounding) pitch.
* __Image Capture__: Allows you to take a [node:278563,title="snapshot"] of part of the score.
* __Note Input__: Note entry mode, Duration, Tie, Rest, Accidentals, Flip stem direction, Voice (1, 2, 3, 4).

##### Show/hide toolbars {#hide-show-toolbars}

To show or hide certain toolbars:

* Select <samp class="menu">View</samp>&rarr;<samp class="menuitem">Toolbars</samp>, and tick/untick the options as required.
* Alternatively, right-click on an empty space in the toolbar area, or the title bar of the Inspector, and, from the menu, check or uncheck the required options.

_Note_: This option also allows you to show or hide the Timeline, Score Comparison Tool, Script Recorder,  Piano Keyboard, Selection Filter, and Drumset Tools. 

##### Customize toolbar area {#customize-toolbars}

* Select <samp class="menu">View</samp>&rarr;<samp class="menuitem">Toolbars</samp>, and click on "Customize Toolbars…"

 [inline:customise_toolbars_en.png=Customize toolbars dialog]

The dialog shows the toolbars that can be customized on the left, the current tool buttons for the selected toolbar in the middle, and the buttons that can be added on the right. When you have selected a toolbar in the left panel, you can do any of the following actions:

* __Remove a toolbutton__: Select the button in the middle panel, and press <kbd><samp class="button">&rarr;</samp></kbd>.
* __Add a toolbutton__: Select the button in the right panel, and press <kbd><samp class="button">&larr;</samp></kbd>.
* __Move a toolbutton__: Select the button in the middle panel, and move it up or down using <kbd><samp class="button">&uarr;</samp></kbd>  or <kbd><samp class="button">&darr;</samp></kbd>.

_Note_: The toolbar cannot be customized unless a custom workspace is selected (see below).

#### Workspaces {#workspaces}

Select this option to [node:281353,fragment="create-custom-workspace",title="create a custom workspace"] or to [node:281353, fragment="edit-workspace",title="edit an existing workspace"].

#### Show Status bar {#status-bar}

The __Status bar__, at the bottom of the screen, gives information about selected score elements. Tick/untick this option to display or hide. 

#### Split display {#display}

It is possible to split the document display so as to view two documents at once, or to view two different parts of the same document. Tabs allow you to choose which document to display in each view. You can drag the barrier separating the two scores to adjust the amount of space in the window devoted to each:

* __Documents Side by Side__: Divides the window vertically into two score views.
* __Documents Stacked__: Divides the window horizontally into two score views, one above the other.

[inline:split_display.png=Split display]

#### Visibility options {#visibility-options}

This section allows you to display or hide various non-printing elements:

* __Show Invisible__: View/hide elements that have been made [node:278642,fragment="element",title="invisible"] for printing and export. If this option is ticked, invisible elements are shown in the score window as light gray.
* __Show Unprintable__: View/hide [node:278620,title="breaks and spacer"] symbols.
* __Show Frames__: View/hide the dotted outlines of [node:278605,title="frames"].
* __Show Page Margins__:  View/hide [node:278663,fragment="page-margins",title="Page Margins"].

#### Mark irregular measures {#mark-irregular-measures}

A dash at the top right of a measure indicates that its duration differs from that set by the time signature.

#### Full screen {#full-screen}

Full Screen mode expands MuseScore to fill your screen so more content is visible.

### Page/Continuous View {#viewing-modes}

You can switch between different views of the score using the drop-down list in the [toolbar](#toolbars) area:

[inline:Page view.png=Viewing Modes]

To scroll the score:

* __Vertically__: Move the mouse wheel up or down.
* __Horizontally__: Press <kbd><kbd>Shift</kbd></kbd> and move the mouse wheel up or down.

#### Page View {#page-view}

In __Page View__, the score is formatted as it will appear when printed or exported as a PDF or image file: that is, page by page, with margins. MuseScore applies system (line) and page [node:278620,fragment="breaks",title="breaks"] automatically, according to the settings made in [node:278663, title="Page settings"] and [node:278570,fragment="style",title="Style…"]. In addition, you can apply your own system (line), page or section breaks.

To choose between __horizontal__ or __vertical__ page scrolling, see [node:278648,fragment="canvas",title="Preferences: Canvas (Scroll pages)"].

#### Continuous View {#continuous-view}

In __Continuous View__, the score is shown as one unbroken system. Even if the starting point is not in view,  measure numbers, instrument names, clefs, time and key signatures will always be displayed on the left of the window.

_Note_: Because the layout is simpler, MuseScore may perform faster in Continuous View than Page View.

#### Single Page View {#single-page-view}

In __Single Page View__ the score is shown as a single page with a header but no margins, and with an infinite page height. System (line) [node:278620,fragment="breaks",title="breaks"] are added automatically, according to the settings made in [node:278663, title="Page settings"] and  [node:278570,fragment="style",title="Style…"]. In addition, you can apply your own system (line) or section breaks.

### Side panels {#side-panels}

The __workspaces__, __Inspector__ and __Selection filter__ are conveniently displayed as __side panels__ to the left and right of the score window. To undock a side panel use one of the following methods:

* Drag the panel;
* Click on the double chevron at the top of the panel;
* Double-click in the title area at the top of the panel.

To dock a panel use one of the following procedures:

* Drag the panel to the top/bottom of an existing side panel and it will stack vertically above/below that panel.
* Drag the panel to the middle of an existing side panel and it will overlay that panel. Both panels can then be accessed by tabs.

Alternatively, double-clicking the title bar of the panel will restore it to its previously docked position.

### Navigation {#navigate}

#### Commands {#nav-commands}

Various commands are available to help you navigate more easily through the score. These are listed under [node:278609,fragment="score-navigation",title="Keyboard shortcuts: Navigation"].

#### Navigator {#navigator}

The __Navigator__ is an optional panel which displays page thumbnails of the score at the bottom or to the right of the document window.

* To view or hide the Navigator, select <samp class="menu">View</samp>&rarr;<samp class="menuitem">Navigator</samp>; or use a customized [node:278648,fragment="shortcuts",title="shortcut"].

[inline:Navigator_bar_en.png=Navigator]

The Navigator appears at the bottom of the document window if scrolling pages horizontally; or on the right  if scrolling pages vertically (see [node:278648,fragment="canvas",title="Preferences: Canvas"]).

The blue box represents the area of the score that is currently visible in the document window: drag the box, or click directly on the navigator panel to bring another part of the score into view. You can also drag the scrollbar.

#### Timeline {#timeline}

The __Timeline__ panel provides a detailed overview of the score, with expanded possibilities for navigation and interaction.

* To display the __Timeline__, press <kbd><kbd>F12</kbd></kbd>; or select <samp class="menu">View</samp>&rarr;<samp class="menuitem">Timeline</samp>.

For details, see [node:278676,title="Timeline"].

#### Find / Go to {#find}

The __Find__ / __Go to__ function allows you to speedily navigate to a specific measure, [node:278647,title="rehearsal mark"] or page number in the score:

1. Press <kbd><kbd>Ctrl</kbd>+<kbd>F</kbd></kbd> (Mac: <kbd><kbd>Cmd</kbd>+<kbd>F</kbd></kbd>), or select <samp class="menu">Edit</samp>&rarr;<samp class="menuitem">Find</samp></kbd>. This opens the __Find__ (or __Go to__) __bar__ at the bottom of the workspace.
2. Use one of the following options:
 * __To go to a numbered measure__: enter the measure number (counting every measure, starting with 1, irrespective of [node:278611,fragment="irregular",title="pickup measures"], [node:278620,fragment="section-break",title="section breaks"] or manual changes to measure number offsets).
 * __To go to a numbered page__: enter the page number using the format pXX (where XX is the page number).
 * __To go to a numerical rehearsal mark__: enter the number using the format rXX (where XX is the name of the rehearsal mark).
 * __To go to a  rehearsal mark starting with a letter__: enter the name of the [node:278647,title="rehearsal mark"] (the search is case insensitive).

 __N.B.__: It is best to avoid naming rehearsal marks with the single letters "R," "r," "P", "p," or one of these letters with an integer (e.g. "R1" or "p3"), as this can confuse the search algorithm. 

### See also {#see-also}

* [node:278643,title="Save/Export/Print"]
* [node:278612,title=" File format"]
* [node:278570,title="Layout and formatting"]