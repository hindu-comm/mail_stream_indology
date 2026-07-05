+++
title = "61 Tyler Neill"
date = "2024-08-20"
upstream_url = "https://list.indology.info/pipermail/indology/2024-August/059554.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2024-August/059554.html)

Quick Skrutable follow-up: I pushed fixes for both of these input issues
(and migrated to a new server). Tests ok for me so far. I updated the
changelog <https://www.skrutable.info/updates> too.

Please let me know if you spot any issues, I’m happy to take a look.

Tyler

On Sat, Jul 20, 2024 at 11:01 AM Tyler Neill <tyler.g.neill at gmail.com>
wrote:

> Hi transliterators,
>
> I am still supporting Skrutable, so feel free to ask me for improvements.
>
> For doing large amounts of text, there are two bugs I know about, and here
> are the workarounds (I hope to eventually fix them):
> 1. Don't attempt too much in the UI input box. After about 2–3 thousand
> characters (depends on the input scheme), it will fail. Instead, use the
> "whole-file upload" button after choosing settings.
> 2. For "whole-file upload", if the filename has diacritics (e.g.
> "tēst.txt" or "तेस्त.txt"), it will fail. Eliminate these and it should
> work. If you're starting with IAST, one quick way to do this is to use
> Skrutable's "IASTreduced" scheme (e.g.,
> "śāntarakṣita_vādanyāyaṭīkā" becomes "santaraksita_vadanyayatika").
>
> Also, don't forget about https://www.aksharamukha.com/converter, which
> not only does whole files, too, but also just works great and supports lots
> of scripts/schemes.  It seems to also struggle with #1 above, but #2 is not
> a problem.
>
> Yours,
> Tyler
>
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20240820/218e1bb8/attachment.htm>
