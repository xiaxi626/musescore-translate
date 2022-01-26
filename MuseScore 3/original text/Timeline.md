### Introduction

The timeline was developed as part of the Google Summer of Code 2017, and is included for the first time in MuseScore 3.0.

### Overview

The timeline is a navigation tool that displays an abstraction of the score to the order of measure numbers and instrument names. There are four parts to the timeline: 

#### Meta labels

This is found in the top left corner of the timeline. These are the names of the meta rows.

#### Instrument labels

This is found in the bottom left corner of the timeline. These are the names of the rows in the main grid.

#### Meta rows

This is found in the top right corner of the timeline. These hold the meta values of the score.

#### Main grid

This is found in the bottom right corner of the timeline. This holds multiple 'cells' (a specific measure and staff in the score represented as a square)

#### Meta

Meta are elements found on the score that are not notes, but are still important to the score (key signature, time signature, tempo, rehearsal marks, bar lines, and jumps and markers).
 [inline:handbooktimeline.PNG=Timeline] 

### Basic interaction

#### Select a measure

To select a measure in the timeline, press the mouse button on the cell. A blue box will appear around the selected cell and the respective measure in the score will be selected. The score view will place the selected measure in view.

#### Select multiple measures

##### Drag selection

Holding <kbd><kbd>Shift</kbd></kbd> and holding the left mouse button and dragging the mouse over the main grid will create a selection box. Upon releasing the mouse button, all the cells underneath the selection box will be selected, as well as all the measures in the score.

##### [Shift] selection

If a cell is already selected, holding <kbd><kbd>Shift</kbd></kbd> and selecting another cell in the timeline will stretch the selection to that new cell, similar to how the score does

##### [Ctrl] selection

If no cells are currently selected, holding <kbd><kbd>Ctrl</kbd></kbd> and selecting a cell will select the entire measure

#### Clearing selection

To clear selection, holding <kbd><kbd>Ctrl</kbd></kbd> and clicking anywhere on the grid or the meta rows will clear any current selection.

#### Meta values selection

Selecting the meta values on the timeline will attempt to select the respective meta values in the score.

### Scrolling

#### Standard scrolling

Scrolling the mouse wheel up or down will move the grid and instrument labels down or up respectively. The meta labels and rows do not move.

#### [Shift] scrolling

Holding <kbd><kbd>Shift</kbd></kbd> and scrolling the mouse wheel up or down will move the grid and meta rows left or right respectively. The meta labels and instrument labels do not move.

#### [Alt] scrolling

Holding <kbd><kbd>Alt</kbd></kbd> and scrolling the mouse wheel up or down will move the grid and meta rows left or right respectively, faster than <kbd><kbd>Shift</kbd></kbd> scrolling. The meta labels and instrument labels do not move.

#### Dragging

To drag the contents of the timeline, hold the left mouse button and move it around.

### Labels interaction

#### Rearranging meta labels

All meta labels besides the measures meta may be rearranged in any way. By moving the mouse cursor onto one of the meta labels, small up and down arrows will appear. Click the left mouse button on the up arrow to swap the meta label with the one above it. Click the left mouse button on the down arrow to swap the meta label with the one below it.

#### Collapsing the meta labels

In order to hide all the meta labels while keeping all the meta information on the timeline, there is an arrow that appears on the measures meta when the mouse is over it. Click the left mouse button on the large up arrow to collapse all the currently visible meta rows into one row, where the meta values are staggered in that row. Click the left mouse button on the large down arrow to expand the meta rows again.
 [inline:collapsedmetahandbook.PNG=Timeline collapsed] 

#### Hiding instruments

All instruments--hidden or not--will be displayed on the timeline. To start this interaction, the mouse cursor is moved over an instrument label. A small eye will appear on the right side of the label that is open if the instrument is visible on the score, and closed if the instrument is hidden. Click the left mouse button on the eye to toggle between the two options.
 [inline:hiddeninstrumenthandbook.PNG=Hidden instrument] 

### Zooming

To zoom in or out of the score, hold <kbd><kbd>Ctrl</kbd></kbd> and scroll the mouse wheel up or down respectively (Mac: <kbd><kbd>Cmd</kbd></kbd> + scroll).

### Context menus

To bring up a context menu, right-click on the timeline. There are three context menus found in these locations: meta labels, instrument labels, and meta rows.

#### Meta labels context menu

Upon clicking the right mouse button on the meta labels, a context menu appears that displays all possible meta labels as well as two options: "Hide all" and "Show all." Next to each meta label in the menu, there is a check box that shows if the meta label is currently being shown on the timeline. To show or hide one of the meta labels, select the box of the meta label in the context menu. Selecting "Hide all" will hide all meta labels except for the measures meta. Selecting "Show all" will display all meta labels.

#### Meta rows context menu

Clicking the right mouse button on the meta rows will display the same context menu as the meta labels.

#### Instrument context menu

Clicking the right mouse button on the instrument labels will display a context menu with the option to "Edit Instruments." Selecting this will bring you to the same dialog as Edit > Instruments... or pressing <kbd><kbd>I</kbd></kbd> for the shortcut.