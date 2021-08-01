+++
title = "60 Thomas B. Ridgeway"
date = "1993-06-30"
upstream_url = "https://list.indology.info/pipermail/indology/1993-June/000582.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/1993-June/000582.html)

Dominik writes:
> I have tested wnrir___.* under OS/2, which has ATM built into it.  However
> there is a small problem.  The fonts have the "/Encoding StandardEncoding
> def" line in them.  OS/2 takes this quite seriously, and does a whole lot of
> remapping, trying to build the currently loaded codepage.  After all this
> helpful fiddling about by OS/2, the displayed charset is not CSX at all.  
  righto; virtually any environment ( ? except X-windows ?) which will
  support these outlines is going to be hostile to a pure CSX encoding
  (which explains why they are starting out as an expanded-CSX/ANSI hybrid.
> 
> The issues involved and the differences between Windows's and OS/2's
> handling of font encodings is well described in Birnbaum's new section on
> OS/2 fonts in Norm Walsh's FAQ for comp.fonts
> (ibis.cs.umass.edu:/pub/norm/comp.fonts, part 4).
> 
> Apparently the key is to tell the font that its encoding is not
> "StandardEncoding" but "FontSpecific".  If Fontographer is being used, then
> the trick is apparently to set the font to have a "Symbol" character set.
> Then OS/2 will leave it alone, and the characters will be displayed in
> their proper places.
  and, unfortunately, saying symbol (or OEM) torches the font for windows-
  truetype.  I suspect that until unicode (a 'real' character set---except it
  doesn't support CSX) arrives in force, anyone with odd character tastes
  is going to need to keep font manipulation utilities at hand because there
  will be no across the board solutions.

cheers,
Tom


-- 





