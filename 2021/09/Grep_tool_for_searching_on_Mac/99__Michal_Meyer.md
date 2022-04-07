+++
title = "99 Michaël Meyer"
date = "2021-09-18"
upstream_url = "https://list.indology.info/pipermail/indology/2021-September/055227.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2021-September/055227.html)

Dear list members,

I wrote a search tool to improve on Grep, which I currently use to look for
parallels in all the available E-texts (Gretil, Muktabodha, Sarit and Titus
combined). The tool takes care of various encoding issues, notational
conventions and oddities commonly found in Sanskrit E-texts. It also knows
about sandhi (e.g. looking for "smṛtes" will match "smṛteḥ" and "smṛter
api", see the screenshot below).

[image: Screenshot_20210918_212859.png]

The tool is written in such a way that missing a textual parallel is
extremely less likely than with Grep and such. However, it tends to
over-generate matches, which I believe is an acceptable trade-off when
searching for textual parallels. Contrarily to Prof. Kulkarni's Gaveṣika,
it doesn't use a parser, which makes it resilient to "difficult" or corrupt
texts, typos, etc.

I haven't made the tool public so far, because this would require a lot of
additional work on my part. I however intend to do it as soon as I find
enough time.

Best regards,
Michaël Meyer

Le ven. 17 sept. 2021 à 13:18, Krishnaprasad G via INDOLOGY <
indology at list.indology.info> a écrit :

> Dear all
> Is there any readymade tool for using the Grep command for Sanskrit text
> string for multiple files?
>
> Thanks
>
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info
> https://list.indology.info/mailman/listinfo/indology
>
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20210918/55e1224d/attachment.htm>
-------------- next part --------------
A non-text attachment was scrubbed...
Name: Screenshot_20210918_212859.png
Type: image/png
Size: 128354 bytes
Desc: not available
URL: <https://list.indology.info/pipermail/indology/attachments/20210918/55e1224d/attachment.png>
