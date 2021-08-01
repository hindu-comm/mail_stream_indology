+++
title = "16 Dominik Wujastyk"
date = "2011-12-12"
upstream_url = "https://list.indology.info/pipermail/indology/2011-December/036124.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2011-December/036124.html)

Dear Adriano,

A few points:
1. don't use the Devanagari package any more.  Move to XeTeX, and then you
can just use a font like Sanskrit 2003 (one of my favourites) and type your
input in Unicode.  You can type Devanagari directly, or you can type using
the Velthuis encoding (aasiidraajaa, k.r.s.na.h), or standard scholarly
romanisation (IAST).  The Velthuis or IAST can be converted automatically
into Devanagari by XeTeX itself.

Because XeTeX can accept Velthuis-style input, your legacy documents made
with the Devanagari package will still be perfectly okay, and you won't
have to retype anything.

Making this move to XeTeX will greatly simplify your working, and make your
documents easier to write, maintain, and process.

2. Your difficulty with the stanza environment in LEDMAC is a TeX problem,
not an indological one, and you'll have much more luck with responses if
you send your question to the main TeX discussion forum, called
comp.text.tex <https://groups.google.com/forum/#%21forum/comp.text.tex>.
Questions about LEDMAC are commonly asked and answered there (e.g.,
here<https://groups.google.com/forum/#%21searchin/comp.text.tex/stanza$20ledmac/comp.text.tex/JKG5_Pq8ChI/WqLGQPfKyy4J>
).

3. There's also a mailing list specifically for XeTeX where people discuss
special issues that relate to unusual languages and XeTeX
(here<http://tug.org/mailman/listinfo/xetex>).
Sanskrit sometimes gets discussed there, LEDMAC less so.

4. The current maintainer of LEDMAC is Maïeul
Rouquette<http://www.ctan.org/author/id/rouquette>to whom you can
write for help if you think you've found a bug.

Best wishes,
Dominik Wujastyk

On 11 December 2011 19:29, Adriano Aprigliano <aprigliano at usp.br> wrote:

> Dear list members,****
>
> ** **
>
> I’ve been trying to use the devanagari package together with ledmac and
> ledpar to produce facing page output and it works fine for prose texts
> (though I have some doubts on how many text chunks should be handled at
> each Pages environment) , but when a I try to write verse ---either with
> the \stanza or {astanza} environments---, it doesn’t work. Could anyone
> give me a hand on that?****
>
> Best wishes****
>
> Adriano Aprigliano****
>
> ** **
>
> Universidade de São Paulo****
>
> São Paulo/SP****
>
> Brasil ****
>


-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20111212/a1bd60d7/attachment.htm>
