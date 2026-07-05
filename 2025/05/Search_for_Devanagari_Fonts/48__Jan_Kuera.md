+++
title = "48 Jan Kučera"
date = "2025-05-10"
upstream_url = "https://list.indology.info/pipermail/indology/2025-May/060597.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2025-May/060597.html)

Dear Harry,

I completely agree with you. My point was that for OCR, you do not care about codepoints or typing experience. You just extract the “images” from the font and use them for training. The Unicode fonts contain the same conjunct “images” as the non-Unicode fonts do, they just don’t have them accessible directly through codepoints.

The task here is not to construct Devanagari texts. I – not only as a chair of script encoding at Unicode – certainly would not encourage anyone to produce texts in any font that is not Unicode compliant!

Thanks,
Jan

From: Harry Spier <vasishtha.spier at gmail.com>
Sent: sobota 10. května 2025 13:09
To: Jan Kučera <jan.kucera at ujca.cz>
Cc: Sebastian Nehrdich <nehrdbsd at gmail.com>; Indology List <indology at list.indology.info>; Kurt Keutzer <kurt.keutzer at gmail.com>
Subject: Re: [INDOLOGY] Search for Devanagari Fonts

Dear Jan,
You wrote:
Actually, for training an OCR, it doesn’t matter whether the fonts are Unicode or not,  . . .. It needs a bit of extra work to map the shapes to the correct classes,

My experience with non-unicode fonts  to construct devanagari text (many fonts over many years) is that it is extremely time consuming.

Its not that there will be one codepoint for one letter.  Ligatures will have their own separate codepoint and vowels will have one codepoint for word initial vowels and another for word internal vowels and some letters, especially metrically long syllables will be constructed from 2 or more codepoints. So typing sanskrit text with non-unicode fonts  is more like typesetting than just typing text in. This is especially true with older non-unicode fonts which will be 8 bit fonts (only 256 codepoints). And each non-unicode font will use its own mapping so you have to set up your keyboard (or make a chart to use) for each individual non-unicode font.

Thanks,
Harry Spier

-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20250510/b025c336/attachment.htm>
