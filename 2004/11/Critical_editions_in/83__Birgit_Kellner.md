+++
title = "83 Birgit Kellner"
date = "2004-11-21"
upstream_url = "https://list.indology.info/pipermail/indology/2004-November/028792.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2004-November/028792.html)

Dear list-members,

inspired by the recent thread on Devanagari, I (once again) looked for
possibilities to typeset critical editions in Devanagari, preferably
with LaTeX.

The packages utf-skt and ledmac had been recommended to me, the former
for producing Devanagari from Unicode transliteration, the latter for
the layout required for critical editions (multiple apparati, combination of verse and prose, line- and verse- numbering, and such).

(Thanks to all those who contributed to making these packages available, by the way!)

I have reached the point where I can produce text output in Devanagari,
with appropriate annotation - in principle, that is, because I'm stuck
with certain problems.

Ledmac requires encoding critical notes in the following fashion:
\edtext{This is the text to which the note belongs, and whose
line-number is placed in the apparatus}{\lemma{Lemma in the critical
note, optional, otherwise the lemma will be the content of
"edtext"}{\Afootnote{This is the critical note, belonging to apparatus A}}}

Of all this material, only the content of "edtext" really needs to be in
Devanagari. This is printed as the main text, and also, unless a special
lemma is given, as a lemma in the apparatus.

The content of "edtext" can be converted to Devanagari through enclosure
with \Nag{ ... }, but in many cases this proves impractical because
whatever Devanagari text ends up printed after the code for the critical
note gets separated - not surprisingly, a word-final consonant at the
end of  \edtext{ } receives a virAma, and this is not always how it
should be.

I have uploaded .tex and .dvi sample files to show what I mean:
http://homepage.univie.ac.at/Birgit.Kellner/ledmac_utfskt_test/ledmac_utfskt_test.dvi
http://homepage.univie.ac.at/Birgit.Kellner/ledmac_utfskt_test/ledmac_utfskt_test.tex

The problem is that a critical note interrupts the Devanagari
"stream". From a logical viewpoint this could be avoided if ledmac did
its processing first, before utfskt sets in, and if utfskt per default
combined adjacent \Nag-tags into one continuous "stream", but I have no
idea whether this can be done technically. (It might also lead to
problems because Devanagari text occupies more space than roman text,
and the assignment of critical notes to lines in the main text might be
imprecise if they are computed before Devanagari is processed.)

Oh well ... I would greatly appreciate any hints towards either a
solution with these two packages, or solutions with other packages - but ideally, with these two, since I'd really like to keep my source files in Unicode.

Thanks, and best regards,

Birgit Kellner



