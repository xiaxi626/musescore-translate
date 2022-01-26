The __Score Properties__ dialog contains document meta tags such as "workTitle," "Composer," "Copyright" etc. To view the dialog:

1. Make sure that the applicable score or instrument part is the active tab;
2. From the menu, select <samp>File</samp> &rarr; <samp>Score Properties</samp>.

Several meta tags are generated automatically when you create a score using the [node:278622,fragment="create-new-score",title="New Score Wizard"], and others may be added later. Meta tags can also be incorporated into a header or footer if required—see [below](#header-footer).

### Edit meta tags {#modify-tag}

1. Make sure that the applicable score or instrument part is the active tab;
2. From the menu, select <samp>File</samp> &rarr; <samp>Score Properties</samp>;
 [inline:Score Properties.png=Score Properties] 
3. Edit the text of the various meta tags as required;
4. To add another meta tag, click on the <kbd><samp class="button">New</samp></kbd> button. Fill in the "New tag name" field and press <kbd><samp class="button">OK</samp></kbd>;
 [inline:Input tag name.png=Input tag name] 

### Pre-existing meta tags {#default-tags}

Every score displays the following fields in __Score Properties__:

* __File Path__: The score file's location on your Computer.
* __MuseScore Version__: The version of MuseScore the score was last saved with.
* __Revision__: The revision of MuseScore the score was last saved with.
* __API-Level__: The file format version.
* __arranger__: (empty)
* __composer__: This is initially set to the same text as "Composer" on the first page of the [node:278622,title="New Score Wizard",fragment="create-new-score"].
* __copyright__: This is initially set to the same text as "Copyright" on the first page of the [node:278622,title="New Score Wizard",fragment="create-new-score"] (if you need a copyright symbols, copy/paste this: &copy;).
* __creationDate__: Date of the score creation. This could be empty, if the score was saved in test mode (see [node:278640,title="Command line options"]).
* __lyricist__: This is initially set to the same text as "Lyricist" on the first page of the [node:278622,title="New Score Wizard",fragment="create-new-score"].
* __movementNumber__: (empty)
* __movementTitle__: (empty)
* __originalFormat__: This tag exists only if the score is imported (see [node:278612,title="file formats"]).
* __platform__: The computing platform the score was created on. This might be empty if the score was saved in test mode.
* __poet__: (empty)
* __source__: May contain a URL if the score was downloaded from or [node:278595,title="saved to MuseScore.com"].
* __translator__: (empty)
* __workNumber__: (empty)
* __workTitle__: This is initially set to the same text as "Title" on the first page of the [node:278622,title="New Score Wizard",fragment="create-new-score"].

#### Entering Work / Movement / Part metadata {#enter-work-movement-metadata}

* __workNumber__ is the number of the larger work (e.g. 8—for "The Four Seasons," Op. 8, by Vivaldi).
* __workTitle__ is the title of the larger work (e.g  "The Four Seasons,").
* __movementNumber__ is the number of the movement in the larger work (e.g. 3 for Autumn).
* __movementTitle__ is the title of the movement in the larger work (e.g.“Autumn”).

It is customary, when using the New Score Wizard, to create a work with the __movementTitle__ as title (even though it ends up in __workTitle__ then) and, directly after creating the score, amending this information in the Score Properties dialogue.

Every __part__ additionally has the following meta tag, generated and filled on part creation:

* __partName__: The name of the part as given on part creation (which is also used to fill the corresponding part name text in the top vertical frame—_be aware that later changes to one are not reflected in the other_).

This meta tag is not present in the main score and thus is not available for use in its header/footer or in an added part name box in the top vertical frame, unless manually added as a new tag to its score properties.

### Header/Footer {#header-footer}

To show the content of one or more meta tags in a header or footer for your score/part:

1. Make sure that the correct score or instrument part is the active tab;
2. From the menu, select <samp>Format</samp> &rarr; <samp>Style...</samp> &rarr;  <samp>Header, Footer</samp>:
   [inline:Header_Footer_dialog.png=Style / Header, Footer] 
If you hover with your mouse over the Header or Footer text region, a list of macros will appear, showing their meaning, as well as the existing meta tags and their content.
  [inline:Tooltip.png=Style / Header, Footer] 
In this list $I and $i are only available in extracted, linked parts, because the  __partName__ score property is only defined there unless, as described above, it is manually added to the main score properties.  Not shown in this tooltip, but available likewise, is the <samp>$:partName:</samp> meta tag.
3. Add tags (e.g. <samp>$:workTitle:</samp>, note the leading and trailing colons) and macros (e.g. <samp>$M</samp>, no colons) to the appropriate boxes, as required;
4. Click <kbd><samp class="button">Apply</samp></kbd> to see how the header or footer looks in the score. Make corrections to the dialog if required;
5. If an instrument part is in the active tab, click <kbd><samp class="button">Apply to all parts</samp></kbd>, if you want to apply these settings to all the score parts;
5. Click <kbd><samp class="button">OK</samp></kbd> to assign the header or footer and exit the dialog.

### See also {#see-also}

* [node:278570,title="Layout and formatting: Header and footer",fragment="style-header-footer"]
* [node:278640,title="Command line options: Test mode"]