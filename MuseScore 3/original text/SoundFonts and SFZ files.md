Audio playback is provided by MuseScore's onboard [node:278660,title="synthesizer"], which houses a large selection of __virtual__ (or __software__) __instruments__—including percussion and sound effects.

MuseScore supports virtual instruments in two formats:

* [SoundFont](#soundfonts) (.sf2/.sf3): A single file containing one or more virtual instruments.
* [SFZ](#sfz) (.sfz): A set of audio and definition files containing one or more virtual instruments.

### SoundFonts {#soundfonts}

MuseScore comes with its own GM ([General MIDI](http://en.wikipedia.org/wiki/General_MIDI)) SoundFont, __MuseScore_General.sf3__, containing over 128 instruments, sound effects and various drum/percussion kits.

GM (General MIDI) is a universal format, so once your score is set up for correct playback using MuseScore's native Soundfont, you should be able to [node:278643,fragment="export",title="export"] it in a [node:278612, title="format"] of your choice and have it play back on any other user's computer.

Many different Soundfonts are available on the Internet: some free, some commercial. For a list of free soundfonts, see [below](#list).

#### Install a SoundFont {#install}

After finding and decompressing a SoundFont (see &rarr;[below](#list)), double-click to open it. In most cases, the SoundFont file type will already be associated with MuseScore, and MuseScore will start and a dialog will appear asking if you want to install the SoundFont. Occasionally an application other than MuseScore will be associated with the SoundFont file type; if this is the case, you will need to right-click or <kbd><kbd>Ctrl</kbd></kbd>-click on the file, so as to display a menu from which you can choose to open the file in MuseScore. In either case, when the dialog appears asking if you want to install the SoundFont, click "Yes" to place a copy of the SoundFont file in MuseScore's SoundFonts directory. This directory can be viewed or changed in MuseScore's Preferences, but the default location is:

- Windows: `%HOMEPATH%\Documents\MuseScore3\Soundfonts`

- macOS and Linux: `~/Documents/MuseScore3/Soundfonts`

In contrast to user-added SoundFonts, the initial default SoundFont installed with MuseScore is located in a system directory, meant only for that purpose, which should _not_ be modified. This directory and its default SoundFont file is:

- Windows x86 (32-bit) / MuseScore x86: `%ProgramFiles%\MuseScore 3\sound\MuseScore_General.sf3`
- Windows x64 (64-bit) / MuseScore x86: `%ProgramFiles(x86)%\MuseScore 3\sound\MuseScore_General.sf3`
- Windows x64 (64-bit) / MuseScore x86_64: `%ProgramFiles%\MuseScore 3\sound\MuseScore_General.sf3`

- macOS: `/Applications/MuseScore 3.app/Contents/Resources/sound/MuseScore_General.sf3`

- Linux (Ubuntu): `/usr/share/mscore-xxx/sounds/MuseScore_General.sf3` (with `xxx` being the MuseScore version)

#### Uninstall {#uninstall}

To uninstall a SoundFont, simply open the folder where its file is installed and delete it.

### SFZ  {#sfz}

An SFZ is a collection of files and directories, an SFZ file and a bunch of actual sound files in WAV or FLAC format, with the SFZ file being a text file that basically describes what sound file is located where and to be used for what instrument and pitch range.

#### Install an SFZ {#install-sfz}

After downloading an SFZ (see &rarr;[below](#list)), you need to manually extract all the files that belong to the SFZ (the SFZ file(s) and all the sub-directories and other files) into the directory listed [above](#install). Leave the sub-directories and their contents as they are.  Note, however, that on occasion, an SFZ file in its folder may seek the actual WAV sound files inside the SFZ sub-directory itself, usually in a folder labeled "Libs".  If the SFZ zip file you download has a Libs folder in it, move it into the main SFZ sub-directory.

#### Uninstall {#uninstall-sfz}

To uninstall an SFZ, simply open the folder where its files are installed (see [above](#install)) and delete them all.

### Synthesizer {#synthesizer}

Once a SoundFont has been [installed](#install) on your system, it also needs to be loaded into the [node:278660,title=Synthesizer"]. See [node:278660,fragment="load-soundfont",title="To load a soundfont"]. 

### Mixer {#mixer}

The Mixer allows you to easily change the sounds for each staff (even while the score is playing). For further details, see [node:278583,title="Mixer"].

### List of downloadable soundfonts {#list}

#### GM SoundFonts {#gm_soundfonts}

The following sound libraries conform to the General MIDI (GM2) standard. This specification gives you a sound set of 128 virtual instruments, plus percussion kits.

<!-- - [Fluid R3 GM](http://musescore.org/download/fluid-soundfont.tar.gz) (141 MB uncompressed)
License: released under the MIT license (included in the archive)
_MuseScore's default SoundFont is based on Fluid R3._-->
- [GeneralUser GS](http://schristiancollins.com/soundfonts/GeneralUser_GS_1.442-MuseScore.zip) (29.8 MB uncompressed)
  Courtesy of [S. Christian Collins](http://schristiancollins.com/generaluser.php)
- [Magic Sound Font, version 2.0](http://www.personalcopy.com/sfarkfonts1.htm) (67.8 MB uncompressed)
- [Arachno SoundFont, version 1.0](http://www.arachnosoft.com/main/download.php?id=soundfont-sf2) (148MB uncompressed)
  Courtesy of [Maxime Abbey](http://www.arachnosoft.com)
- MuseScore 1 came with [TimGM6mb](https://sourceforge.net/p/mscore/code/HEAD/tree/trunk/mscore/share/sound/TimGM6mb.sf2?format=raw) (5.7 MB uncompressed)
  License: GNU GPL, version 2
  Courtesy of [Tim Brechbill](http://ocmnet.com/saxguru/Timidity.htm#sf2)
- MuseScore 2 (up to version 2.1) came with [`FluidR3Mono_GM.sf3`](https://github.com/musescore/MuseScore/raw/2.1/share/sound/FluidR3Mono_GM.sf3) (13.8 MB).
- MuseScore 2 (as of version 2.2) and 3 come with [`MuseScore_General.sf3`](https://ftp.osuosl.org/pub/musescore/soundfont/MuseScore_General/MuseScore_General.sf3) (35.9 MB) ([`SF2 version`](https://ftp.osuosl.org/pub/musescore/soundfont/MuseScore_General/MuseScore_General.sf2) (208 MB)) and are being updated from time to time (see the [Changelog](https://ftp.osuosl.org/pub/musescore/soundfont/MuseScore_General/MuseScore_General_Changelog.md)).
  License: released under the [MIT license](https://ftp.osuosl.org/pub/musescore/soundfont/MuseScore_General/MuseScore_General_License.md)
  Courtesy of [S. Christian Collins](/user/62809)
  MuseScore 3 on top offers an HQ version of that soundfont as an [node:278654,fragment="install-extension",title="extension"]
- [Timbres of Heaven, version 3.2](http://midkar.com/soundfonts/) (369 MB uncompressed)
  Courtesy of Don Allen
- [Soundfonts4U](https://sites.google.com/site/soundfonts4u/) (12MB up to 1GB, depending on which package you choose)
  Collection of beautifully sounding acoustic guitars as well as pianos, basses, strings, harps and many more.

#### Orchestral soundfonts {#orchestral-soundfonts}

- Sonatina Symphonic Orchestra (503 MB uncompressed)  
  Downloads: [SoundFont](http://ftp.osuosl.org/pub/musescore/soundfont/Sonatina_Symphonic_Orchestra_SF2.zip) | [SFZ format](http://sso.mattiaswestlund.net)  
  License: Creative Commons Sampling Plus 1.0
- [Aegean Symphonic Orchestra](https://sites.google.com/view/hed-sounds/aegean-symphonic-orchestra)
  Courtesy of [ Ziya Mete Demircan](/user/230181) (352 MB uncompressed)

#### Piano soundfonts {#specialised}

##### SF2 Pianos {#sf2_piano}

<!--- [Yamaha C5 Grand - A beautiful sounding 6 velocity-layer-sampled Yamaha Salamander C5 Grand](https://drive.google.com/file/d/1AUn3lGaUyCyA12btdKYgeHGdo44M88T6/view)-->
- [Acoustic grand piano, release 2016-08-04](http://freepats.zenvoid.org/Piano/YDP-GrandPiano/YDP-GrandPiano-SF2-20160804.tar.bz2)
  Description: Yamaha Disklavier Pro Grand Piano, sf2 format, 36MiB compressed, 113MiB uncompressed, 121 samples, 5 velocity layers
  More information: [http://freepats.zenvoid.org/](http://freepats.zenvoid.org/) including other soundfonts.
  License: Creative Commons Attribution 3.0
  Courtesy of [Roberto Gordo Saez](https://web.archive.org/web/20190914132427/http://freepats.zenvoid.org/sf2/acoustic_grand_piano_ydp_20080910.txt)
- [Salamander C5 Light](https://sites.google.com/view/hed-sounds/salamander-c5-light)
  Courtesy of [ Ziya Mete Demircan](/user/230181) (24.5 MB uncompressed)

##### SFZ Pianos {#sf2_piano}

- Salamander Grand Piano
  Downloads: [version 2](http://download.linuxaudio.org/lau/SalamanderGrandPianoV2/) | [version 3](http://freepats.zenvoid.org/Piano/acoustic-grand-piano.html)  
  Description: Yamaha C5, 48kHz, 24bit, 16 velocity layers, between 80 MB and 1.9 GB uncompressed
  License: Creative Commons Attribution 3.0
  Courtesy of Alexander Holm
- [Detuned Piano](http://download.linuxaudio.org/musical-instrument-libraries/sfz/detuned_piano.tar.7z) (244 MB uncompressed)  
  License: Creative Commons Attribution-ShareAlike 3.0
- [Plucked Piano Strings](http://download.linuxaudio.org/musical-instrument-libraries/sfz/plucked_piano_strings.tar.7z)
  Description: 44.1kHz, 16bit, stereo, 168 MB uncompressed
  License: Creative Commons Attribution-ShareAlike 3.0
- [The City Piano](http://bigcatinstruments.blogspot.ca/2015/09/all-keyboard-instruments.html)
  Description: Baldwin Baby Grand, 4 velocity layers, 696 MB uncompressed
  License: Public domain
  Courtesy of Big Cat Instruments
- [Kawai Upright Piano, release 2017-01-28](http://freepats.zenvoid.org/Piano/acoustic-grand-piano.html#KawaiUpright)
  Description: 68 samples, 44KHz, 24bit, stereo, 2 velocity layers, 58MiB uncompressed
  License: GNU General Public License version 3 or later, with a [special exception](http://freepats.zenvoid.org/licenses.html#GPL_exception)
  Courtesy of Gonzalo and Roberto

#### Unzipping downloaded soundfonts {#compressed-file-formats}

Since soundfonts are large, they are often zipped (compressed) into a variety of formats, including .zip, .sfArk, and .tar.gz. You need to unzip (decompress) these files before they can be used.

- ZIP is standard compression format supported by most operating systems.

- sfArk is a compression format designed especially for compressing SoundFont files. To decompress it, use [Polyphone](https://www.polyphone-soundfonts.com/en) (cross-platform software); or this online service: https://cloudconvert.com/sfark-to-sf2

- .tar.gz is a popular compression format for Linux. Windows users can use [7-Zip](http://www.7-zip.org); Mac users can use [The Unarchiver](http://unarchiver.c3.cx/unarchiver), or macOS' built-in Archive Utility. Note that if using 7-Zip, you will need to apply decompression twice—once for GZip and once for TAR.

### Troubleshooting {#troubleshooting}

If the toolbar play panel is greyed out, or not visible, follow the instructions below to get your sound working again:

1. Right-click on the menu bar and make sure there is a check mark next to the <samp class="menuitem">Playback Controls</samp> menu item. If this step does not solve your problem, go to Step 2.
2. If the play panel disappears after changing the SoundFont, go to <samp class="menu">Edit</samp> &rarr; <samp class="menuitem">Preferences...</samp> &rarr; <samp class="tab">I/O</samp> tab and click OK without making any changes. After restarting MuseScore, the play panel should reappear.

If you are setting up a SoundFont for the first time, please use one of the recommended SoundFonts listed above.

If playback stutters, then your computer may not be able to handle the SoundFont being used. The following advice may help:

* Reduce the amount of RAM (memory) used by MuseScore by using a smaller SoundFont. See the [list](#list) above for suggestions.
* Increase the amount of RAM available for MuseScore by quitting all applications except MuseScore. If you still have problems and a large SoundFont is important to you, consider more RAM for your computer.

### See also {#see-also}

- [node:278660,title="Synthesizer"]
- [node:278583,title="Mixer"]

### External links {#external-links}

- [node:50721,title="How to change the SoundFont or add another"] (MuseScore HowTo)
- [The SFZ Format](http://www.sfzformat.com/legacy/) (for details about the sfz specification)
