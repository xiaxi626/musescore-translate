MSCORE(1) — General Commands Manual Page

### NAME

**mscore**, **MuseScore3** — MuseScore 3 sheet music editor

### SYNOPSIS

You can launch MuseScore from the command line by typing

* <samp class="code">mscore [*options*] [*filename* …]</samp> (Mac and Linux/BSD/Unix)
* <samp class="code">musescore [*options*] [*filename* …]</samp> (Linux/BSD/Unix)
* <samp class="code">mscore-portable [*options*] [*filename* …]</samp> (Linux AppImage)
* <samp class="code">MuseScore3.exe [*options*] [*filename* …]</samp> (Windows)

<samp class="code">[*options*]</samp> and <samp class="code">[*filename*]</samp> are optional. For this to work the MuseScore executable must be in `%PATH%` (Windows) resp. `$PATH` (Mac and Linux). If it is not, see [node:278582,title="Revert to factory settings",fragment="Via-command-line"] for detailed instructions on how and where to find and execute the MuseScore executable from the command line on the various supported platforms.

A more detailed synopsis follows:

**mscore** \[**-deFfhIiLmnOPRstvw**]
 \[**-a**&nbsp;|&nbsp;**-&#45;use&#45;audio**&nbsp;*driver*]
 \[**-b**&nbsp;|&nbsp;**-&#45;bitrate**&nbsp;*bitrate*]
 \[**-c**&nbsp;|&nbsp;**-&#45;config&#45;folder**&nbsp;*pathname*]
 \[**-D**&nbsp;|&nbsp;**-&#45;monitor&#45;resolution**&nbsp;*DPI*]
 \[**-d**&nbsp;|&nbsp;**-&#45;debug**]
 \[**-E**&nbsp;|&nbsp;**-&#45;install&#45;extension**&nbsp;*extension file*]
 \[**-e**&nbsp;|&nbsp;**-&#45;experimental**]
 \[**-F**&nbsp;|&nbsp;**-&#45;factory&#45;settings**]
 \[**-f**&nbsp;|&nbsp;**-&#45;force**]
 \[**-h**&nbsp;|&nbsp;**-?**&nbsp;|&nbsp;**-&#45;help**]
 \[**-I**&nbsp;|&nbsp;**-&#45;dump&#45;midi&#45;in**]
 \[**-i**&nbsp;|&nbsp;**-&#45;load&#45;icons**]
 \[**-j**&nbsp;|&nbsp;**-&#45;job**&nbsp;*file.json*]
 \[**-L**&nbsp;|&nbsp;**-&#45;layout&#45;debug**]
 \[**-M**&nbsp;|&nbsp;**-&#45;midi&#45;operations**&nbsp;*file*]
 \[**-m**&nbsp;|&nbsp;**-&#45;no&#45;midi**]
 \[**-n**&nbsp;|&nbsp;**-&#45;new&#45;score**]
 \[**-O**&nbsp;|&nbsp;**-&#45;dump&#45;midi&#45;out**]
 \[**-o**&nbsp;|&nbsp;**-&#45;export&#45;to**&nbsp;*file*]
 \[**-P**&nbsp;|&nbsp;**-&#45;export&#45;score&#45;parts**]
 \[**-p**&nbsp;|&nbsp;**-&#45;plugin**&nbsp;*name*]
 \[**-R**&nbsp;|&nbsp;**-&#45;revert&#45;settings**]
 \[**-r**&nbsp;|&nbsp;**-&#45;image&#45;resolution**&nbsp;*DPI*]
 \[**-S**&nbsp;|&nbsp;**-&#45;style**&nbsp;*style*]
 \[**-s**&nbsp;|&nbsp;**-&#45;no&#45;synthesizer**]
 \[**-T**&nbsp;|&nbsp;**-&#45;trim&#45;image**&nbsp;*margin*]
 \[**-t**&nbsp;|&nbsp;**-&#45;test&#45;mode**]
 \[**-v**&nbsp;|&nbsp;**-&#45;version**]
 \[**-w**&nbsp;|&nbsp;**-&#45;no&#45;webview**]
 \[**-x**&nbsp;|&nbsp;**-&#45;gui&#45;scaling**&nbsp;*factor*]
 \[**-&#45;diff**]
 \[**-&#45;long&#45;version**]
 \[**-&#45;no&#45;fallback&#45;font**]
 \[**-&#45;raw&#45;diff**]
 \[**-&#45;run&#45;test&#45;script**]
 \[**-&#45;score&#45;media**]
 \[**-&#45;score&#45;meta**] 
 \[**-&#45;score&#45;highlight&#45;config**] 
 \[**-&#45;score&#45;mp3**]
 \[**-&#45;score&#45;parts**]
 \[**-&#45;score&#45;parts&#45;pdf**]
 \[**-&#45;score&#45;transpose**]
 \[**-&#45;source&#45;update**]
 \[**-&#45;template&#45;mode**]
 \[*file&nbsp;...*]

### DESCRIPTION

**MuseScore** is a Free and Open Source WYSIWYG cross-platform multi-lingual music composition and notation software, released under the GNU General Public Licence (GPLv2).

Running **mscore** without any extra options launches the full graphical MuseScore program and opens any files specified on the command line.

The options are as follows:

**-a** | **-&#45;use&#45;audio** *driver*

: Use audio driver: one of **jack**, **alsa**, **portaudio**, **pulse**

**-b** | **-&#45;bitrate** *bitrate*

: Set MP3 output bitrate in kbit/s

**-c** | **-&#45;config&#45;folder** *pathname*

: Override configuration and settings directory

**-D** | **-&#45;monitor&#45;resolution** *DPI*

: Specify monitor resolution (override autodetection)

**-d** | **-&#45;debug**

: Start MuseScore in debug mode

**-E** | **-&#45;install&#45;extension** *extension file*

: Install an extension file; soundfonts are loaded by default unless **-e** is also specified

**-e** | **-&#45;experimental**

: Enable experimental features, such as [node:301598,title="layers"]

**-F** | **-&#45;factory&#45;settings**

: Use only the standard built-in presets (“factory settings”) and delete user preferences; compare with the **-R** option (see also [Revert to factory settings](https://musescore.org/en/node/278582))

**-f** | **-&#45;force**

: Ignore score corruption and version mismatch warnings in “converter mode”

**-h** | **-?** | **-&#45;help**

: Display an overview of invocation instructions (doesn’t work on Windows)

**-I** | **-&#45;dump&#45;midi&#45;in**

: Display all MIDI input on the console

**-i** | **-&#45;load&#45;icons**

: Load icons from the filesystem; useful if you want to edit the MuseScore icons and preview the changes

**-j** | **-&#45;job** *file.json*

: Process a conversion job (see [*EXAMPLES*](#EXAMPLES) below)

**-L** | **-&#45;layout&#45;debug**

: Start MuseScore in layout debug mode

**-M** | **-&#45;midi&#45;operations** *file*

: Specify MIDI import operations file (see [*EXAMPLES*](#EXAMPLES) below)

**-m** | **-&#45;no&#45;midi**

: Disable MIDI input

**-n** | **-&#45;new&#45;score**

: Start with the New Score wizard regardless whether it’s enabled or disabled in the user preferences

**-O** | **-&#45;dump&#45;midi&#45;out**

: Display all MIDI output on the console

**-o** | **-&#45;export&#45;to** *file*

: Export the given (or currently opened) file to the specified output *file*. The file type depends on the extension of the filename given. This option switches to “converter mode” and avoids the graphical user interface.

**-P** | **-&#45;export&#45;score&#45;parts**

: When converting to PDF with the **-o** option, append each part’s pages to the created PDF file. If the score has no parts, all default parts will temporarily be generated automatically.

**-p** | **-&#45;plugin** *name*

: Execute the named plugin

**-R** | **-&#45;revert&#45;settings**

: Use only the standard built-in presets (“factory settings”) but do not delete user preferences; compare with the **-F** option

**-r** | **-&#45;image&#45;resolution** *DPI*

: Set image resolution for conversion to PNG files. Default: 300 DPI (actually, the value of “Resolution” of the PNG option group in the [Export tab of the preferences](https://musescore.org/en/node/278648#export))

**-S** | **-&#45;style** *style*

: Load a style file first; useful for use with the **-o** option

**-s** | **-&#45;no&#45;synthesizer**

: Disable the integrated software synthesizer

**-T** | **-&#45;trim&#45;image** *margin*

: Trim exported PNG and SVG images to remove whitespace surrounding the score. The specified *margin*, in pixels, will be retained (use `0` for a tightly cropped image). When exporting to SVG, this option only works with single-page scores.

**-t** | **-&#45;test&#45;mode**

: Set test mode flag for all files, includes **-&#45;template-mode**

**-v** | **-&#45;version**

: Display the name and version of the application without starting the graphical user interface (doesn’t work on Windows)

**-w** | **-&#45;no&#45;webview**

: Disable the web view component in the Start Center

**-x** | **-&#45;gui&#45;scaling** *factor*

: Scale the score display and other GUI elements by the specified *factor*; intended for use with high-resolution displays

**-&#45;diff**

: Print a conditioned diff between the given scores

**-&#45;long&#45;version**

: Display the full name, version and git revision of the application without starting the graphical user interface (doesn’t work on Windows)

**-&#45;no&#45;fallback&#45;font**

: Don’t use Bravura as fallback musical font

**-&#45;raw&#45;diff**

: Print a raw diff between the given scores

**-&#45;run&#45;test&#45;script**

: Run script tests listed in the command line arguments

**-&#45;score&#45;media**

: Export all media (except MP3) for a given score as a single JSON document to stdout

**-&#45;highlight&#45;config**

: Set highlight to svg, generated from a given score

**-&#45;score&#45;meta**

: Export score metadata to JSON document and print it to stdout

**-&#45;score&#45;mp3**

: Generate an MP3 for the given score and export it as a single JSON document to stdout

**-&#45;score&#45;parts**

: Generate parts data for the given score and save them to separate mscz files

**-&#45;score&#45;parts&#45;pdf**

: Generate parts data for the given score and export it as a single JSON document to stdout

**-&#45;score&#45;transpose**

: Transpose the given score and export the data to a single JSON file, print it to stdout

**-&#45;source&#45;update**

: Update the source in the given score

**-&#45;template&#45;mode**

: Save files in template mode (e.g. without page sizes)

MuseScore also supports the [automatic Qt command line options](http://doc.qt.io/qt-5/qguiapplication.html#supported-command-line-options).

### Batch conversion job JSON format

The argument to the **-j** option must be the pathname of a file comprised of a valid JSON document honoring the following specification:

*	The top-level element must be a JSONArray, which may be empty.

*	Each array element must be a JSONObject with the following keys:
 *	`in`: Value is the name of the input file (score to convert), as JSONString.
 *	`plugin`: Value is the filename of a plugin (with the `.qml` extension), which will be read from either the global or per-user plugin path and executed before the conversion output happens, as JSONString. Optional, but at least one of `plugin` and `out` *must* be given.
 *	`out`: Value is the conversion output target, as defined below. Optional, but at least one of `plugin` and `out` *must* be given.

*	The conversion output target may be a filename (with extension, which decided the format to convert to), as JSONString.

*	The conversion output target may be a JSONArray of filenames as JSONString, as above, which will cause the score to be written to multiple output files (in multiple output formats) sequentially, without being closed, re-opened and re-processed in between.

*	If the conversion output target is a JSONArray, one or more of its elements may also be, each, a JSONArray of two JSONStrings (called first and second half in the following description). This will cause part extraction: for each such two-tuple, all extant parts of the score will be saved *individually*, with filenames being composed by concatenating the first half, the name (title) of the part, and the second half. The resulting string must be a valid filename (with extension, determining the output format). If a score has no parts (excerpts) defined, this will be silently ignored without error.

*	Valid file extensions for output are:

	`flac`
	: Free Lossless Audio Codec (compressed audio)

	`metajson`
	: various score metadata (JSON)

	`mid`
	: standard MIDI file

	`midi`
	: standard MIDI file

	`mlog`
	: internal file sanity check log (JSON)

	`mp3`
	: MPEG Layer III (lossy compressed audio)

	`mpos`
	: measure positions (XML)

	`mscx`
	: uncompressed MuseScore file

	`mscz`
	: compressed MuseScore file

	`musicxml`
	: uncompressed MusicXML file

	`mxl`
	: compressed MusicXML file

	`ogg`
	: OGG Vorbis (lossy compressed audio)

	`pdf`
	: portable document file (print)

	`png`
	: portable network graphics (image) — Individual files, one per score page, with a hyphen-minus followed by the page number placed before the file extension, will be generated.

	`spos`
	: segment positions (XML)

	`svg`
	: scalable vector graphics (image)

	`wav`
	: RIFF Waveform (uncompressed audio)

	`xml`
	: uncompressed MusicXML file

See below for an example.

### ENVIRONMENT

`SKIP_LIBJACK`
: Set this (the value does not matter) to skip initialization of the JACK Audio Connection Kit library, in case it causes trouble.

`XDG_CONFIG_HOME`
: User configuration location; defaults to `&#126;/.config` if unset.

`XDG_DATA_HOME`
: User data location; defaults to `&#126;/.local/share` if unset.


Note that MuseScore also supports the normal Qt environment variables such as `QT_QPA_GENERIC_PLUGINS`, `QT_QPA_PLATFORM`, `QT_QPA_PLATFORMTHEME`, `QT_QPA_PLATFORM_PLUGIN_PATH`, `QT_STYLE_OVERRIDE`, `DISPLAY`, etc.

### FILES

`/usr/share/mscore-3.0/` contains the application support data (demos, instruments, localization, system-wide plugins, soundfonts, styles, chords, templates and wallpapers). In the Debian packages, system-wide soundfonts are installed into `/usr/share/sounds/sf2/`, `/usr/share/sounds/sf3/` or `/usr/share/sounds/sfz/`, respectively, instead.

The per-user data (extensions, plugins, soundfonts, styles, templates) and files (images, scores) are normally installed into subdirectories under `&#126;/MuseScore3/` but may be changed in the configuration. Note that snapshot, alpha and beta versions use `MuseScore3Development` instead of `MuseScore3` in all of these paths.

`$XDG_CONFIG_HOME/MuseScore/MuseScore3.ini` contains the user preferences, list of recently used files and their locations, window sizes and positions, etc. See above for development version paths.

`$XDG_DATA_HOME/data/MuseScore/MuseScore3/` contains updated localization files downloaded from within the program, plugin information, cached scores, credentials for the *musescore.com* community site, session information, synthesizer settings, custom key and time signatures and shortcuts. See above for development version paths.

### EXAMPLES

#### Convert a score to PDF from the command line

	mscore -o 'My Score.pdf' 'My Score.mscz'

#### Run a batch job converting multiple documents

	mscore -j job.json

This requires the file `job.json` in the current working directory to have content similar to the following:

	[
	  {
	    "in": "Reunion.mscz",
	    "out": "Reunion-coloured.pdf",
	    "plugin": "colornotes.qml"
	  },
	  {
	    "in": "Reunion.mscz",
	    "out": [
	      "Reunion.pdf",
	      [ "Reunion (part for ", ").pdf" ],
	      "Reunion.musicxml",
	      "Reunion.mid"
	    ]
	  },
	  {
	    "in": "Piece with excerpts.mscz",
	    "out": [
	      "Piece with excerpts (Partitura).pdf",
	      [ "Piece with excerpts (part for ", ").pdf" ],
	      "Piece with excerpts.mid"
	    ]
	  }
	]

The last part of the job would, for example, cause files like “`Piece with excerpts (part for Violin).pdf`” to be generated alongside the conductor’s partitura and a MIDI file with the full orchestra sound, whereas the equivalent part of the Reunion conversion will be silently ignored (because the Reunion piece (a MuseScore demo) has no excerpts defined).

#### MIDI import operations

The attached [`midi_import_options.xml`](https://musescore.org/sites/musescore.org/files/midi_import_options_0.xml) is a sample MIDI import operations file for the **-M** option.

### DIAGNOSTICS

The **mscore** utility exits&#160;0 on success, and&#160;&gt;0 if an error occurs.

### SEE ALSO

fluidsynth(1), midicsv(1), timidity(1), qtoptions(7)

*https://musescore.org/handbook*

: Online Handbook, full user manual

*https://musescore.org/forum*

: Support Forum

*https://musescore.org/en/node/278582*

: Reverting to factory settings (troubleshooting)

*https://musescore.org/project/issues*

: Project Issue Tracker — Please check first to if the bug you’re encountering has already been reported. If you just need help with something, then please use the [support forum](https://musescore.org/forum) instead.

*http://doc.qt.io/qt-5/qguiapplication.html#supported-command-line-options*

: Documentation of automatic Qt command line options

### STANDARDS

MuseScore attempts to implement the following standards:

*	MusicXML 3.1 (score interchange format)
*	SF2 (SoundFont 2.01)
*	SF3 (SoundFont with OGG Vorbis-compressed samples)
*	SFZ (Sforzato soundfont)
*	SMuFL (Standard Music Font Layout 1.20)

### HISTORY

MuseScore was split off the MusE sequencer in 2002 and has since become the foremost Open Source notation software.

### AUTHORS

MuseScore is developed by **MuseScore BVBA** and others.

This manual page was written by _mirabilos_ &lt;tg@debian.org&gt;.

### CAVEATS

The automatic Qt command line options are removed from the argument vector before the application has a chance at option processing; this means that an invocation like `mscore -S -reverse` has no chance at working because the `-reverse` is removed by Qt first.

### BUGS

* MuseScore does not honor */etc/papersize*.

* Probably some more; check the project’s bug tracker (cf. [*SEE ALSO*](#SEE_ALSO)).

MuseScore — January 12, 2021