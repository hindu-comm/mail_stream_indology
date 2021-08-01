+++
title = "186 Anshuman Pandey"
date = "1998-04-17"
upstream_url = "https://list.indology.info/pipermail/indology/1998-April/011785.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/1998-April/011785.html)

Hello,

For those interested, a DOS executable of Charles's SKT preprocessor is
available from <http://weber.u.washington.edu/~apandey/skt2-exe.zip>. This
executable has been updated with the bug fixes. In addition to the
executable, files in the archive include the updated and fixed skt.c,
skt.sty, sktdoc.skt, and a PostScript version of sktdoc.skt.

Regards,
Anshuman Pandey

On Thu, 16 Apr 1998, Charles Wikner wrote:

> Greetings,
>
> For users of the SKT-series of devanagari fonts:
>
> Ten bug reports and fixes have been added to the \language\sanskrit
> subdirectory on CTAN.
>
> A brief description of the bugs are:
>
> BUG01:  Added feature: pass the five characters [`!'] through to
>         roman from within {\skt }.
>
> BUG02:  Improve treatment of sa.myoga "gj~n", e.g. in samyagj~naana.
>
> BUG03:  Column separators misplaced in pages 23 thru 35 of docs.
>
> BUG04:  Poor sa.myoga vertical alignment in bold and feint devanaagarii.
>
> BUG05:  Svarita accent fouls the bindu above ~m with option 47 enabled.
>
> BUG06:  The preprocessor program exits with code 1 instead of code 0
>         when there are no errors.
>
> BUG07:  Newer versions of LaTeX than I have available (1995/06/01)
>         complain about the use of accents <u> and <^>, specifically
>         in producing the docs.
>
> BUG08:  Version 2 of relsize.sty (Mar 15, 1995) gives warning messages
>         that the size requested is too small when using SaamaVeda accents
>         in transliteration.
>
> BUG09:  Nasalised-l, -v, -y use wrong diacritic in transliteration.
>
> BUG10:  Problems using SKT with fragile LaTeX commands, e.g. \markboth.
>
> The changes fortunately do not affect the font files, but affect skt.sty
> and skt.c (which will need re-compiling).
>
> Regards,
> Charles Wikner.
>
>



