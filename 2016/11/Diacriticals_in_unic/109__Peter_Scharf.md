+++
title = "109 Peter Scharf"
date = "2016-11-18"
upstream_url = "https://list.indology.info/pipermail/indology/2016-November/044695.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2016-November/044695.html)

Dear list members,
The Sanskrit Library transcoding facility on line at
http://sanskritlibrary.org/transcodeText.html does indeed transcode to
Romanization using the preferred Unicode composites of characters plus
diacritics.  Our off-line transcoding software

   - TranscodeFile (Java program)
   <http://sanskritlibrary.org/software/transcodeFile.html>

 which is downloadable from http://sanskritlibrary.org/downloads.html has a
large array of transcoders one of which transcodes to Romanization using
precomposed Unicode characters that include diacritics.  The problem with
searching that Harry Spier mentions is just one of a number of reasons why
Malcolm Hyman and I designed the Sanskrit Library phonetic encoding for all
our linguistic programming, including both the encoding of texts and
searching, and use Unicode only for display, and data input if desired
(though for the latter purpose SLP and most other meta-encodings are
preferable).  Our book *Linguistic Issues in Encoding Sanskrit* available
at http://sanskritlibrary.org/publications.html discusses the issues
comprehensively.

Yours,
Peter

On Fri, Nov 18, 2016 at 6:28 PM, Harry Spier <hspier.muktabodha at gmail.com>
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



-- 
*******************
Peter M. Scharf
scharfpm7 at g <peter.scharf at univ-paris-diderot.fr>mail.com
*******************


-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20161118/819a0e60/attachment.htm>
