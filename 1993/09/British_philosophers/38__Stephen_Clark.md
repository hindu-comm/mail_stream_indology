+++
title = "38 Stephen Clark"
date = "1993-09-23"
upstream_url = "https://list.indology.info/pipermail/indology/1993-September/000697.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/1993-September/000697.html)

In response to Shailendra Mehta's post (we can take this off list very
soon, but maybe others would like to comment):

Yes, the apparent gap between life and philosophy was discussed (and
a paper on Rousseau read by Tim O'Hagan - unfortunately the Indians present
seemed not to want to discuss him!). Rousseau's excuse was that he would
have made a lousy father: I did raise the question why in that case he
was so sure that he wasn't a lousy adviser to fathers! Coincidentally,
the connection between life and philosophy was also discussed at a
Royal Institute of Philosophy conference in (you guessed) Liverpool two
years ago and published as *Philosophy, Religion and the Spiritual Life*,
ed.M.McGhee. It's perhaps also relevant that of the 9 British philosophers
6 are vegetarians, on philosophical grounds - so some of us, at least,
do believe in uniting theory and practice. The ones who weren't are also
more than technicians, even if none of us quite dare to call ourselves
philosophers in the strong, Epictetan sense.

Jaipur was a great relief after Delhi. I could almost imagine living there!
I understand that the University Philosophy dept would be interested in 
hiring someone to teach Greek philosophical texts, with a knowledge of
Greek.

Stephen Clark
Liverpool



> From KHARE at csvaxe.csuohio.edu 23 93 Sep EST 12:22:00
Date: 23 Sep 93 12:22:00 EST
From: Jitendra Khare <KHARE at csvaxe.csuohio.edu>

Hullo! I was hoping somebody might know of an anonymous ftp site where I
can find devanagari script fonts (preferably Windows based).
Thank you. Jitendra Khare




> From ECOLING at AppleLink.Apple.COM 23 93 Sep GMT 19:00
Date: 23 Sep 93 19:00 GMT
From: ECOLING at AppleLink.Apple.COM (Ecological Linguistics,Anderson,PRT)
Subject: matras combining characters ?

A note in Unicode 1.1 suggests the inclusion of Indic matras as "combining
characters" should be considered a "defect" in 10646 (and therefore should be
changed, presumably).

This note to the Indology list is to give my best understanding of the
situation, since I have not been able to get a technical justification for the
position referred to.

The original motivations for "combining characters" included at least that they
should not be isolated from their base characters at line breaks.  I think,
though am not absolutely certain, that some Unicoders want a class of
characters which have the combination of properties [combining; non-spacing;
overlapping only to the left (in left-to-right scripts) or to the right (in
right-to-left scripts)] and perhaps some other properties as well.

As contrasted with the prototypical Latin combining marks, Indic matras have
two differences: (a) they are not all non-spacing, and (b) in surface
rendering, they sometimes connect with something later in the text stream,
rather than only with something earlier in the text stream.  These two
differences are however not matters of "combiningness", they are separate
features.  The rule that "combining" characters may not be separated from their
"base" characters still holds.  So new character attributes can be added,
"zero-width" and "combines-to-the-right", but the old feature "combining"
should not be deleted.   Possibly it should be reinterpreted as "combines to
the left" unless an additional feature handles the left vs. right linking, but
since the "combines to the right" affects primarily renderings among the
standard Indic vowel matras, this may not matter.  The matra is linked to the
same base letter (conjunct) in either case, before or after matra-reordering to
the rendering form.

The Unicode 1.1 treatment of the diacritics over two letters, such as long and
short marks over double "oo" for phonetic dictionary entries for English,
places the code for the diacritic between the codes for the two base letters.
The approach considers such diacritics to be "combining to the left", but
"overlapping" to the right, whereas they are really equally combining in both
directions, so "combines to the left" and "combines to the right" would both be
attributes of these double-base diacritics.

Does anyone have further insight into what might make Indic matras different or
similar in any relevant attributes?  The chief cases I can locate for
combining-tothe-right, by the way, are Devanagari  repha (itself a result of
ligaturing "r" with virama non-finally), and Burmese "eng" which sits on top of
the consonant which logically follows the "eng" (itself a result of ligaturing
"ng" with a marker for conjuncting.

Lloyd Anderson, Ecological Linguistics.









