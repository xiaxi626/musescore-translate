---
title: Swing
date: 2021-12-30 01:06:35
---
MuseScore's __swing__ feature allows you to change the playback of your score from a straight to a swing rhythm. Swing can be applied globally or only to a section of the score, and is fully variable.

### Apply swing to a score section {#setup}

To apply swing to _all_ staves in a system:

1. Click on the note where you want swing to start;
2. Click __Swing__ in the Text palette (double-click in versions prior to 3.4);
 This inserts a System Text object which affects all staves in the system with a default swing percentage of 60%.

3. [node:278590,title="Edit"] the Swing text as required;
4. If you need to vary swing from the default setting, right-click the Swing text and select <samp class="menuitem">System text properties...</samp> Click on the "Swing Settings" tab and adjust note duration and "Swing ratio" as required.

 [inline:Swing_Settings_EN.png=Swing properties] 

To apply swing only to _specific_ staves in a system:

1. Click on the note where you want swing to start;
2. Add [node:278674,title="Staff text"];
3. [node:278590,title="Edit"] the appearance of the text as required;
4. Right-click on the text, select <samp class="menuitem">Staff Text Properties...</samp>, and click on the "Swing settings" tab. Modify as required;
5. Repeat steps 1–4 for other staves if needed.

Swing text can be [node:278590,title="edited"] and [node:278664,fragment="text-formatting",title="formatted"] just like any other text object.

#### Triplet in tempo marking {#triplet}

Often this notation is used to indicate swing:

 [inline:swing_markings.png=Swing markings] 

MuseScore does not have a way to include a triplet in text as a tempo marking, but there is an easy workaround:

1. Add Swing text as described [above](#setup) and make it invisible (shortcut <kbd><kbd>V</kbd></kbd>, or untick "Visible" in the [node:278642,fragment="element",title="Inspector"]);
2. Add an appropriate [node:278596,title="Image"] of the required tempo marking to the score. These can be downloaded from the bottom of the "How To" page: [node:266325,title="How to create a visual swing marking"].
3. Resize and reposition the image as required.

### Return to straight rhythm {#swing-off}

If you want playback to return to straight time after a swing section, use one of the following options:

__From version 3.4__:

* Add __Straight__ text from the "More" field of the Workspace's text palette to the first note or rest of the "straight" section (see [above](#setup)).

__Prior to version 3.4__:

 1. Add __Swing__ text to the first note or rest of the "straight" section  (see [above](#setup)).
 2. [node:278590,title="Edit"] the text to indicate a return to straight time: e.g. "Straight."
 3. Right-click on the text and select <samp class="menu">System Text Properties…</samp>. Click on the "Swing Settings" tab and set "Swing to "Off."

### Apply swing globally {#global-swing-settings}

If you wish to apply swing to the whole score, you can do so from the menu:

1. Select <samp class="menu">Format</samp> &rarr; <samp class="submenu">Style...</samp> &rarr; <samp class="tab">Score</samp></kbd>.
2. In the "Swing Settings" section, set the desired note value and "swing ratio."

 [inline:Style_Score_EN.png=Format Style Score] 

### External links  {#external-links}

* [node:266325,title="How to create a visual swing marking"] (MuseScore HowTo)
* [Swing (jazz performance style)](https://en.wikipedia.org/wiki/Swing_(jazz_performance_style)) (Wikipedia)