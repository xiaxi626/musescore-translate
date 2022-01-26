The Mixer allows you to change instrument sounds, adjust volume and panning, and make other adjustments to the playback for each staff.

### Opening the Mixer {#open-mixer}

To display/hide the mixer, use one of the following:

* Press <kbd><kbd>F10</kbd></kbd> (Mac: <kbd><kbd>Fn</kbd>+<kbd>F10</kbd></kbd>).
* From the main menu, select <samp class="menu">View</samp>&rarr;<samp class="menuitem">Mixer</samp>.

The Mixer is split into a [Details Area](#details-area) on the top and a [Track Area](#track-area) below.

[inline:mixerPanel_en.png=Mixer Pannel] 

### Track Area {#track-area}

The track area is at the bottom and displays the [Master Gain](#master-gain) as well as a row of tracks. The Track Area displays allows you to adjust the volume of the instruments used by your staves.  Clicking on one of the panels selects it, and also allows you to edit other instrument parameters, such as choice of instrument, name, pan, chorus, reverb, etc. in the Details area.

MuseScore creates one "part track" for each staff in your score.  These part tracks can be further subdivided into "channel tracks" corresponding to the different sounds used within the staff.  While many staves only need a single channel track, others require multiple channels so that the instrument can play more than one  [sound](#mid-staff-change) (e.g. a violin which can play in arco, tremolo or pizzicato voices); or because of a [node:278644,title="Mid-staff instrument change"].  These extra channel tracks can be shown or hidden by clicking the arrow button on top of the track control.

[inline:channelsExpanded.png=Channels expanded] 
_Expanded part track, showing the child tracks in pink._

#### Master Gain {#master-gain}

The Master Gain controls the overall output volume. To adjust it, click and drag the slider handle or enter a value in the box underneath.

#### Channel display arrow {#channel-display-arrow}

Every __part track__ has a button on the top with an arrow on it, enabled, when that instrument has multiple channels, like e.g. violin (for arco, pizzicato, tremolo), disabled otherwise.  When clicked, this will toggle whether the channel tracks of the staff are displayed next to it. __Channel tracks__ do not have an arrow button.  Instead, the name of the track they are a part of is displayed.

#### Mute and Solo {#mute-solo}

At the top of each track is a green __solo__ button and a red __mute__ button: each can be toggled on or off.  If any Solo button is checked then only tracks that have solo lit will play.  If no solo is lit, all parts can potentially play.  Mute does the opposite: any track that has mute lit will not play.  By using a combination of mute and solo buttons, you can control which instruments are heard during playback.

#### Pan {#pan}

The dial below the mute button controls panning left and right.  You can click and drag on the dial to change the pan value. __Note__: MuseScore does not yet support pan values for the part track, so the part track displays the pan value of the first channel instead.  Setting the pan value of the part track will automatically set all of its children to the same value as well.

#### Volume {#volume}

The slider in the middle of the track controls the playback volume. __Note__: MuseScore does not yet support volume values for the part track, so the part track displays the volume value of the first channel instead.  Setting the volume value of the part track will automatically set all of its children to the same value as well.

#### Track name {#track-name}

The text box at the bottom of the track contains the current name of the track's part or channel.

### Details Area {#details-area}

The details area displays and provides finer control of the currently selected track.

 [inline:detailsArea_en.png=Detail area] 

#### Name {#track-name}

The name of the part this track is associated with.  Both part tracks and channel tracks display the part name. __Note__: The part name is editable, but this only have effect for the Mixer. The channel name is not editable.

#### Channel {#channel}

If a channel track is selected, the channel name is displayed here.

#### Drumset {#drumset}

Indicates if this part represents a melodic instrument or a drumkit. For regular melodic instruments, each pitch in the same patch usually has the same timbre, while drumkit patches usually have different timbres for each pitch.

#### Sound (formerly Patch) {#patch}
 
To change the sound in a track:

1. Click on the desired track so that its details appear in the [Details area](details-area).
2. Click on the "Sound" dropdown list and select another instrument.

The "Sound" drop-down menu lists every instrument supported by your current [node:278624,title="SoundFont"]. If you have multiple SoundFonts loaded in the [node:278660,title="Synthesizer"], all the patches from all the SoundFonts (and/or SFZ files) will appear in the order set in the Synthesizer.

__Tip__: To find an instrument, click on the "Sound" list and type the first letter of the instrument name. Repeat as required.

#### Volume {#volume}

The overall loudness with which the sound is played.

#### Pan {#pan}

The panning applied to the part.

#### Track color {#track-color}

To change the change the color of the track area:

* Click the colored rectangle to enter the color palette, and make the desired changes.

Setting the color of a part track will automatically change the colors of all its child tracks as well.

### MIDI controls

#### Port and Channel {#port-and-channel}

The output MIDI port and channel the part is played on.

#### Reverb / Chorus {#reverb-and-chorus}

The reverb/chorus value sent to MIDI out.  This is information sent to MIDI devices and will not affect MuseScore's built in audio playback

#### Mute Voice {#mute-voice}

This allows you to mute individual voices within each staff.  Each row represents a different staff within a part.  So pressing '2' on the top row will mute the second voice on the first staff of the part.

#### Hide Details Button {#hide-details}

At the bottom of the detail area is a wide button with a tiny triangle on it.  Clicking this button will hide the detail area to give you more room.  Clicking on it again will restore the detail area.

__Note__: From Preferences > Score it is possible to check the box Show MIDI controls in the Mixer to preset it expanded when opening the Mixer.

### Mid-staff sound change (pizz., con sordino, etc.) {#mid-staff-change}

Some instruments come with multiple channels in the Mixer that can be used to change sounds midway through a score. For example, a staff for a stringed instrument (violin, viola, cello etc.) is allocated _three_ channels: one for "arco" (or "normal"), another for "pizzicato" and another for "tremolo." A trumpet staff will have one channel for "normal" and another reserved for "mute," and so on.

The following instructions use pizzicato strings as an example, but the same principle can be applied to any other instrument staff that allows sound changes.

1. Select the first note of the section you want to be pizzicato;
2. From the main menu, choose <samp class="menu">Add</samp>&rarr;<samp class="submenu">Text</samp>&rarr;<samp class="menuitem">Staff Text</samp> or use the shortcut <kbd><kbd>Ctrl</kbd>+<kbd>T</kbd></kbd>;
3. Type "pizz." This text is for visual reference only and does not affect playback;
4. Right-click on the applied staff text and select <samp class="menuitem">Staff Text Properties…</samp>;
5. In the "Change Channel" tab of the "Staff Text Properties" dialog, select one or more voices on the left;
6. From the dropdown menu, select <samp>pizzicato</samp>;

 [inline:Staff_text_properties_en.png=Staff text properties] 

7. Click <kbd><samp>OK</samp></kbd> or press <kbd><kbd>&crarr;</kbd></kbd> (Return) to return to the score.

Every note after the staff text you added now sounds pizzicato. To return to a normal strings sound later in the piece, follow the same guidelines as above except type "arco" in step 3 and select <samp>arco</samp></kbd> in step 6.

Most of the time is it far easier to just apply the corresponding text (pizz., tremolo, arco, mute, open, etc) from the Text Palette.

### See also {#see-also}

* [node:278624,title="SoundFont"]
* [node:278660,title="Synthesizer"]
* [node:278564,fragment="change-instrument",title="Change instrument"]

### External links {#external-links}

* [node:50196,title="How to change instrument sound (e.g. pizz., con sordino) midway through score"] (MuseScore HowTo)