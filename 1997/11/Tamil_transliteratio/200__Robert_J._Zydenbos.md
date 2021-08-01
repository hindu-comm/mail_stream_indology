+++
title = "200 Robert J. Zydenbos"
date = "1997-11-17"
upstream_url = "https://list.indology.info/pipermail/indology/1997-November/009878.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/1997-November/009878.html)

N. Ganesan suggested:

>  IF {
>      n occurs in the beginning of words
>       .OR.
>      n is followed by t
>        .OR.
>      occasionally, dental n is explicitly needed
>        in some places like sanskrit loans,}
>
>    THEN { n = dental n}
>  ELSE
>       n = alveolar n
>
>
>   What do you think of this? This way, n and N can be used in most
> situations.
>  No need to distinguish between dental and alveolar n in Roman
> transliteration.
>  Only occasionally in a Roman transliterated Tamil text, we will
> have to use a
>  separate symbol for dental n.

I believe that this depends largely on the aim of the system of
transliteration. The algorhythm looks reasonable for modern Tamil,
although in Sanskrit loans I have seen dental and alveolar n listed
as alternatives in dictionaries. If you intend to integrate the
algorhythm in a computer program, you will have a problem, since
you will have to inform the program about what words are Sanskrit
loans.

If your aim is to transliterate old Tamil texts, you will have
still other problems. Occasionally an initial n or t becomes _n or
_r in sandhi, and then you will have to decide whether to be true
to the manuscript and preserve those signs or not; if you want to
preserve them, whether you want to split the writing (since the
mss. leave no spaces between words) or not. If you do not want to
split up the stream of characters, then the algorhythm will almost
function; but this may mean that you cannot print a piece of poetry
in lines, since (rarely) an initial n / t at the beginning of a
prosodic line has been changed to _n / _r by the final phoneme of
the preceding line.

Personally, I prefer another sign for the alveolar n. In this way
we keep the details of transliteration in our own hands and
maintain a higher degree of adaptibility to the texts which we
intend to transliterate.

RZ



