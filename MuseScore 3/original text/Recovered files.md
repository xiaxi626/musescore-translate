If MuseScore or your computer should crash, or if power is lost, a pop-up message upon restarting MuseScore will ask if you wish to restore the previous session:

[inline:Restore_session_dialog_en.png=Restore session dialog]

Click <kbd><samp class="button">Yes</samp></kbd>, to initiate attempted recovery of files from the interrupted session. Or click <kbd><samp class="button">No</samp></kbd> to ignore message.

### Saving after session recovery {#behavior-after-session-recovery}

When MuseScore recovers files after a crash, it renames them with the full path name added in front of the original file name. This very long name will appear in the tab(s) above the active score window.

_To ensure that the file is saved in its original location_. You should immediately save the restored file using the **<samp class="menuitem">"Save As..."</samp>** option: this will open a window to allow you to navigate to the correct folder and directory. If you use the "Save" command instead, the file will be saved in its current location which is unlikely to be the original one.

### Finding recovered files {#finding-recovered-files}

In the event that <samp class="menuitem">"Save"</samp> is used instead of <samp class="menuitem">"Save As..."</samp> with a recovered file, you will have to find the files in your computer. The actual location of those files will vary, depending on your operating system, and in which directory MuseScore is installed.

For Windows 7, with a default installation of MuseScore to the program files directory, recovered files are auto-saved to `C:\Program Files\MuseScore 3\bin` (actually `%ProgramFiles%\MuseScore 3\bin`).

For Windows 10, look in `C:\Users\[User Name]\AppData\Local\VirtualStore\Program Files\MuseScore 3\bin` (actually` %LOCALAPPDATA%\VirtualStore\%ProgramFiles:~3%\MuseScore 3\bin`).

You may need to run a system-wide search in order to find files saved directly after a session recovery. Use keywords from the original file name as well as wildcards, and specify the date modified.

### See also {#see-also}

[node:278643,title="Save/Export/Print"]

### External links {#external-links}

[node:52116,title="How to recover a backup copy of a score"] (MuseScore HowTo)
