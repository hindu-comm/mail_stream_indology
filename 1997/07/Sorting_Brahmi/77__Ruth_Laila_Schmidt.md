+++
title = "77 Ruth Laila Schmidt"
date = "1997-07-10"
upstream_url = "https://list.indology.info/pipermail/indology/1997-July/008787.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/1997-July/008787.html)

Dear Martin Bemman,
>
>We are using Prof. Emmerick's fonts for WordPerfect 5.1 (DOS) since many
>years for our publications of Brahmi and Kharosthi inscriptions. All the
>volumes published so far contain complete indices of the inscriptions
>and the single words or syllables as well. Now we are planning to put
>those indices together for a register volume.
>Is there any (database-)software available sorting entries according to
>the sanskrit alphabet?
>
I have sort handle functions for Hindi, Nepali and Shina which are almost
certainly of no use to you as they are written in an dead language (SNOBOL,
using Optsort). What I discovered may be of use however, and that is that
defining a sort handle for Devanagari (and thus probably also for Brahmi)
is a snap, *provided* that the font is phonetically based (because it has a
limited number of ASCII characters to sort). If it is keystroke-based it is
extremely difficult, maybe impossible. My Shina sort handle has only 57
characters to deal with, but if I translate that into a keystroke based
font I might have over a thousand character combinations to reckon with,
when the ligatures are taken into account. I know this because I helped to
write a filter (in Pascal) to convert a phonetically based  Devanagari font
for Nepali (Sarasvati) into a keystroke based one (Jaipur). As least in
1989, the keystroke based font was not sortable.

As long as your Brahmi font has a limited number of character combinations
to manage, then one or more of the utilities recommended by Dominik would
be used. One has only to define the desired sort order of the characters.

With best wishes,

Ruth Schmidt


***********************************************
Ruth Laila Schmidt
Dept of East European and Oriental Studies
University of Oslo
P.O. Box 1030 Blindern
N-0315 Oslo, Norway
Phone: (47) 22 85 55 86
Fax: (47) 22 85 41 40
Email: r.l.schmidt at easteur-orient.uio.no






