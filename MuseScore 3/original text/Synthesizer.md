---
title: Synthesizer
date: 2021-12-30 01:08:04
---
### Overview {#overview}

To display the __Synthesizer__: from the menu, select <samp class="menu">View</samp>&rarr;<samp class="menuitem">Synthesizer</samp>.

The Synthesizer controls MuseScore's sound output and allows you to:

* Load and organize different sound sample libraries to play back the music.
* Apply [node:278660, fragment="effects",title=" effects"] such as reverb and compression.
* Adjust overall  [node:278660, fragment="tuning",title="tuning"].
* Alter the output volume.
* Select Midi Continuous Controllers to use with Single Note Dynamics (versions 3.1 and above).

The Synthesizer window is divided into the following sections/tabs:

* __Fluid__: A software synthesizer that plays SF2/SF3 [node:278624,title="SoundFont"] sample libraries.
* __Zerberus__: A software synthesizer that plays SFZ format sample libraries.
* __Master Effects__: Used to apply [multi-effects](#effects) to the score.
* __Tuning__: Used to adjust overall playback [tuning](#tuning).
* __Dynamics__ (versions 3.1 and above): Used to configure Single Note Dynamics Midi controllers.

### Save/Load Synthesizer settings {#synth-settings}

The buttons at the bottom of the Synthesizer window have the following functions:

|Button|Function|
|-|-|
|<kbd><samp class="button">Set as Default</samp></kbd>| Saves _all_ current synthesizer settings as the _default_ settings. These are automatically applied to the Synthesizer when you open MuseScore.|
|<kbd><samp class="button">Load Default</samp></kbd>|Loads the last saved _default_ settings to the Synthesizer.|
|<kbd><samp class="button">Save to Score</samp></kbd>|Saves _all_ current synthesizer settings to the _current_ score only.|
|<kbd><samp class="button">Load from Score</samp></kbd>|Loads the settings from the _current_ score to the synthesizer.|

__Notes__: (1)  "Synthesizer settings" include the order of SoundFonts and SFZ files, effects set-up, master tuning and volume. (2) Only one set of Synthesizer settings can be in effect at a time—i.e. if multiple scores are open at once, it is not possible to make changes to the Synthesizer in one score and leave other scores' settings untouched. (3) Changes to synthesizer settings will not be heard in exported [node:278612,fragment="audio",title="audio files"] unless saved to the score first (see table, above). See also [Tuning](#tuning) (below).

### Fluid {#fluid}

Click on the __Fluid__ tab to access the control panel for SF2/SF3 [node:278624,fragment="soundfonts",title="SoundFont"] sample libraries. By default, the SoundFont `MuseScore_General.sf3` should already be loaded.

[inline:Synthesizer_Fluid_3.3.3_EN.png=Fluid in Synthesizer]

You can load, rearrange and delete soundfonts as required. Playback can be shared between any combination of different soundfonts (and/or SFZ files). The order of soundfonts in __Fluid__ is reflected in the _default_ order of instruments in the [node:278583,title="mixer"].

#### To load a soundfont {#load-soundfont}

1. Click on the <kbd><samp class="button">Add</samp></kbd> button
2. Click on a soundfont in the list.

To be able to load the soundfont, it first needs to be [node:278624,fragment="install",title="installed"] in your __Soundfonts folder__. This will ensure that it appears in the list in step 2 (above).

#### To reorder the soundfonts {#reorder-soundfonts}

1. Click on a soundfont
2. Use the up/down arrows (on the right-hand side) to adjust the order.
3. Repeat with other soundfonts in the list if required.
4. Or use the double up arrow (on the top right-hand side) to move any SoundFont to the top of the list.

The order of virtual instrument sets in the Synthesizer is reflected in the order of instruments listed in the [node:278583,title="Mixer"]. So, if playback of a score depends on a mix of instrument sets, it is advisable to save the Synthesizer configuration to the score in question by pressing the <kbd><samp class="button">Save to Score</samp></kbd> button. When you next wish to play back the score, press the <kbd><samp class="button">Load from Score</samp></kbd> to load the same configuration. However, remember this only sets the _order_ of instruments—not the instruments themselves, which should be in place on your computer.

#### To remove a soundfont {#remove-soundfont}

1. Click on the name of the soundfont
2. Click on the <kbd><samp class="button">Delete</samp></kbd> button.

This removes the soundfont from the synthesizer but does not [node:278624,fragment="uninstall",title="uninstall"] it from the Soundfonts folder: it will still be available if you wish to reload it later.

### Zerberus {#zerberus}

Click on the __Zerberus__ tab to access the control panel for [node:278624,fragment="sfz",title="SFZ"] sound sample libraries. You can [add](#load-soundfont), [delete](#remove-soundfont) or [reorder](#reorder-soundfonts) files in a similar way to the [Fluid](#fluid) tab. Note that, as with Fluid, the SFZ files must first be [node:278624,fragment="install",title="installed"] in your __soundfonts__ folder before they can be loaded into the synthesizer.

### Volume {#volume}

The slider on the right of the Synthesizer controls the playback volume: any changes made here last only to the end of the session, unless saved to the score or set as the new default.

### Effects {#effects}

The __Master Effects__ tab of the Synthesizer allows you to add [reverb](#zita1) and [compression](#sc4) to your score.

[inline:MasterEffects-Zita1-SC4_en.png=Master Effects in Synthesizer Zita1 and SC4] 
_Master Effects with Zita1 Reverb and SC4 Compressor._

To turn an effect on or off:

* Select an option from the drop-down list next to __Effect A__ or __Effect B__ (the effects are applied in series, A &rarr; B). 

To store and load effects configurations, use the buttons at the bottom of the Synthesizer window. See [Synthesizer settings](#synth-settings) (above) for details.

#### Zita 1 reverb {#zita1}

The __Zita 1__ stereo reverb module allows you to simulate the ambience of anything from a small room to a large hall. The pre-delay, reverb time and tone of the reverb can be finely tuned using the controls provided:

* __Delay__: Set a pre-delay for the reverb from 20-100 ms.
* __Low RT60__ (Low frequency reverb time): Use the grey control to adjust the center frequency (50–1000 Hz) of the low frequency band which you want to affect: the green control adjusts the reverb time (1–8 secs) of this frequency band.
* __Mid RT60__ (Mid-range reverb time): Adjust the reverb time (1–8 secs) of the mid-range frequency band.
* __HF Damping__: Adjusts the high frequency component of the reverb. Increasing this value increases the frequency of the cut-off point and makes the reverb appear brighter and longer.
* __EQ1__: Allows you to cut or boost (-15 to +15) a frequency band (center = 40 Hz - 2 KHz) in the _lower_ part of the spectrum. 
* __EQ2__: Allows you to cut or boost (-15 to +15) a frequency band (center = 160 Hz - 10 KHz) in the _higher_ part of the spectrum.
* __Output__: Controls the amount of effect applied. "Dry" is no effect. "Wet" indicates 100% reverb. "Mix" is a 50/50 balance of wet/dry signal.

__Note__: EQ1 and EQ2 affect the tone of the reverb only, _not_ the dry (unprocessed) signal.

To quickly set up an effects patch, set "Output" to "Mix" and adjust the "Mid RT60" control to the desired reverb time. Then fine tune the effect as explained above.

#### SC4 compressor {#sc4}

The __SC4__ stereo compressor gives you fine control over the playback's dynamic range, reducing the volume variation between loud and soft sounds. It offers the following controls:

* __RMS__: Adjusts the balance between RMS (0) and Peak (1) compression. In the former, the compressor responds to averaged-out levels in the signal; in Peak mode, the compressor responds to peak levels.
* __Attack__: (1.5–400 ms) The length of time it takes for compression to engage fully after the signal exceeds the threshold level. 
* __Release__: (2–800 ms) The time it takes for compression to return to zero after the signal falls below the threshold level.
* __Threshold__: (in dB) The signal level  above which compression starts to take effect. Lowering the threshold increases the amount of signal that is compressed.
* __Ratio__: The amount of compression applied to the signal above the threshold. The higher the ratio, the greater the compression. Varies between 1:1 and 20:1.
* __Knee__: Allows you to select a range between "soft knee" and "hard knee". The softer the knee, the more gradual the transition between uncompressed and compressed signal.
* __Gain__: Compression tends to lower the volume, so use this control to boost the signal as required.

To quickly set-up, try setting RMS = 1, Threshold = -20 db, Ratio = 6. Increase Gain to restore the lost volume. Then fine-tune as explained above.

### Tuning {#tuning}

The __Tuning__ tab is where you can adjust the program's __master tuning__. For Concert Pitch instruments, A4 = 440 Hz by default. 

[inline:Tuning_en.png=Tuning in Synthesizer] 

To change the Master tuning:

* Enter a new value in the __Master tuning__ field, then press <kbd><samp class="button">Change Tuning</samp></kbd>.

__Notes__: (1) This tuning applies to all scores in the _current_ session only. To make this the program default or to store it to a particular score, see [Save/Load Synthesizer settings](#synth-settings). (2) To apply the new tuning to exported audio files (WAV, MP3, OGG), press <samp>Save to Score</samp> before exporting.

### Dynamics (versions 3.1 and above) {#dynamics}

Click on the __Dynamics__ tab to access the control panel for Single Note Dynamics:

 [inline:MasterEffects-Dynamics_en.png=Dynamics in Synthesizer] 

* __Dynamics method:__ You can choose either between 1) Default (single-note dynamics and velocity), 2) Velocity only (no single-note dynamics), 3) CC events only (constant velocity).
* __CC to use__: Depending on the SoundFont you use, you may have to choose the Continuous Controller to use, 1) CC 1, 2) CC 2 (default), 3) CC 4, 4) CC 11.

In the __Advanced Settings__ box, you can choose to enable or disable the Expression Controller for Instruments Sound:

* __Switch all patches__: Select 1) To Expressive (to enable for all instruments sounds), 2) To Non-Expressive (to disable for all instruments sounds), 3) Reset All (Reset all instruments sounds to defaults)

### See also {#see-also}

* [node:278624,title="SoundFont"]
* [node:278583,title="Mixer"]

### External links {#external-links}

* [node:290616,title="How To: Using Single Note Dynamics (SND)"] (MuseScore HowTo)