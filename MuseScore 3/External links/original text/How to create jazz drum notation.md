In the drum part of a jazz ensemble arrangement, it is common to indicate that the basic groove is to continue using slash notation in the staff, while indicating above the staff what rhythms or rhythmic accents the rest of the band are playing. It is hoped that the drummer will exercise his or her judgment in deciding how to interpret or set up those rhythm or accents, and which pieces of the drum kit to employ in doing so.

To accomplish this in MuseScore, you will need to create a rhythm on a [node:36086,title="percussion staff"] and use the [node:42631,title="Fill With Slashes",fragment="fill-with-slashes"] and [node:42631,title="Toggle Rhythmic Slash Notation",fragment="toggle-rhythmic-slash-notation"] tools. You'll want to use them both as follows:

1. Enter the "accents" (that is, the rhythms that are meant to go above the staff) in voice 3. For a percussion staff, here are two ways to do this:

    * One way to achieve this is to enter the rhythms into voice 1 on the snare drum then use Edit &rarr; Voices &rarr; Exchange Voice 1-3.

    * Another method, assuming that the desired rhythms already exist on a different staff, is to copy and paste the passage from there into the drum staff, and then use Edit &rarr; Voices &rarr; Exchange Voice 1-3. The pitches of the original melody are unimportant and will be ignored.

2. Select the range containing the notes you want converted. (In fact, you will already have selected this range to perform the Exchange Voice 1-3 command in the previous step.)

3. Invoke Edit &rarr; Tools &rarr; Toggle Rhythmic Slash Notation. This converts any selected notes to slash notation - on the staff for voice 1, above for voice 3. The rhythms in voice 3 will ordinarily have slash noteheads, except in the case of a percussion staff, where they'll be given ordinary noteheads.

4. With that range still selected, Edit &rarr; Tools &rarr; Fill With Slashes

If you wish to change the noteheads used, then after step 3, right click a note, Select  &rarr; All Similar Elements in Range Selection, and use the Inspector to make the change. That would also be a time you could adjust the amount by which they "float" above the staff.  The "Chord / Vertical offset" defaults to -0.50 to float slight above standard staves, but defaults to 0.00 to sit directly on top of the staff for percussion staves.
