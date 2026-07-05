+++
title = "64 Alex Watson"
date = "2022-09-21"
upstream_url = "https://list.indology.info/pipermail/indology/2022-September/056776.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2022-September/056776.html)

Dear Colleagues

A question about XeLaTeX and the font Devanagari MT.

In order to produce Sanskrit editions in devanāgarī script with several
layers of apparatus, I use XeLaTeX.

My font of choice is Devanagari MT, but running XeLaTeX on an input file
that calls this font does not always produce good ligatures.  It sometimes
uses a virāma under the first consonant instead of joining it with the
subsequent one.

I have found, with help from Dominic Goodall, the XeTeXglyph numbers for
almost all of the problematic cases.  For example a correct devanāgarī ddva
is produced by typing \XeTeXglyph286.  But these are the remaining
problematic cases I have:

dba
ṅna
ṅga
ṅka

Would anyone happen to know what the XeTeXglyph numbers are for these?  Or
know how I could find out?

Yours
Alex
-- 
Alex Watson
Professor of Indian Philosophy
Ashoka University
*https://ashokauniversity.academia.edu/AlexWatson
<https://ashokauniversity.academia.edu/AlexWatson>*
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20220921/dea90975/attachment.htm>
