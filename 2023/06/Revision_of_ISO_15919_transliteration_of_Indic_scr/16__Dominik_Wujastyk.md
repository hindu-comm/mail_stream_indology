+++
title = "16 Dominik Wujastyk"
date = "2023-06-12"
upstream_url = "https://list.indology.info/pipermail/indology/2023-June/057809.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2023-June/057809.html)

I would like to push back on Andrew's point 3.  Oh, and thank you Andrew
for the clear analysis, which is very helpful!

The issue you raise in point 3 is only a problem if strings in different
languages in a multilingual text are concatenated without language
tagging.  If a Polish author (Polish has ś) is writing about peace in
Sanskrit (śānti) then the point 3 problem might arise.  But it doesn't
arise in the real world because of readers' implicit knowledge that these
are different languages.  When encoding, we should make the implicit
explicit and say <polish>śląc</polish> <sanskrit>śānti</sanskrit>.  We
should also do this in order to get the right hyphenation and other
language features (spell-checking, and whatnot).  The language-tagging also
does the encoding-switching: ś in Polish is one thing, ś in Sanskrit is
another. In a tool like Aksharamukha, for example, the ś in śānti may
become श but the one in śląc may not.

Best,
Dominik
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20230612/168e9c34/attachment.htm>
