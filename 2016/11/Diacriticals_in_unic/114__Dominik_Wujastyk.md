+++
title = "114 Dominik Wujastyk"
date = "2016-11-24"
upstream_url = "https://list.indology.info/pipermail/indology/2016-November/044763.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2016-November/044763.html)

On this issue of combining accents or single pre-combined glyphs, Andrew
Ollett has already stated the issues.  The Unicode Consortium's
documentation about this business is at

   - http://unicode.org/reports/tr15/

As Andrew said, the terminology is "Normalization Form," and there are
several of these, and quite a few points to consider when writing programs
to work with Unicode.  The Unicode consortium makes available algorithms
for dealing with all this, and modern text-processing software libraries
for Unicode are commonly aware of Normalization Forms and "do the right
thing," so the end-user doesn't have to worry.

This doesn't always work, though.  I find that when I cut-n-paste from
WorldCat, for example, into JabRef, all the accented letters are retained
in NFD format, and it's annoying.

Mostly, when we talk about typing IAST with pre-composed, single-glyph
characters like ā, we're doing what the Unicode people call "Normal Form
Composed" or NFC.  The files in SARIT and elsewhere are in this format.

Best,
Dominik





--
Professor Dominik Wujastyk <http://ualberta.academia.edu/DominikWujastyk>
,

Singhmar Chair in Classical Indian Society and Polity
,

Department of History and Classics <http://historyandclassics.ualberta.ca/>
,
University of Alberta, Canada
.

South Asia at the U of A:

sas.ualberta.ca



On 18 November 2016 at 05:58, Harry Spier <hspier.muktabodha at gmail.com>
wrote:

> Dear list members,
>
> In unicode you can write characters with diacriticals with either a single
> glyph or you can combine the character with the diacritical writing it in
> two glyphs.
>
> This is a problem when one searchs sanskrit etexts.
>
> For example, the letters with diacriticals in the Muktabodha digital
> library are written with one glyph and as far as I can see GRETIL does the
> same thing.  But the transcoding utility at  "The Sanskrit Library"
> http://sanskritlibrary.org/transcodeText.html
> combines letters with their diacriticals in two glyphs.
>  So if you used the Sanskrit Library utility to create a transliterated
> word such as for example: *śākti* and then searched texts from either
> GRETIL or Muktabodha for that word your search wouldn't find anything.
>
> Thanks,
> Harry Spier
>
>
>
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info
> indology-owner at list.indology.info (messages to the list's managing
> committee)
> http://listinfo.indology.info (where you can change your list options or
> unsubscribe)
>


-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20161124/b09c8b7c/attachment.htm>
