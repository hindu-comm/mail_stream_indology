+++
title = "49 Jan Kučera"
date = "2025-05-10"
upstream_url = "https://list.indology.info/pipermail/indology/2025-May/060598.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2025-May/060598.html)

Thank you, Kurt, for the clarification, we haven’t really been given any information about the methodology or any details on the project, and it looks like my assumption project was incorrect. If you are learning on generated texts, then it makes sense that you want to avoid non-Unicode fonts.

Looking forward to learning about the results.

Regards,
Jan

From: Kurt Keutzer <kurt.keutzer at gmail.com>
Sent: neděle 11. května 2025 0:05
To: Jan Kučera <jan.kucera at ujca.cz>
Cc: Harry Spier <vasishtha.spier at gmail.com>; Sebastian Nehrdich <nehrdbsd at gmail.com>; Indology List <indology at list.indology.info>
Subject: Re: [INDOLOGY] Search for Devanagari Fonts

Jan,
I still wonder if our methodology is clear here. We want to generate synthetic data for training OCR of devanāgarĪ. This can be done efficiently by taking Sanskrit texts in unicode and rendering the same text in as wide a variety of "unique looking" fonts as possible. The challenge with non-unicode fonts is that we will need to convert the unicode "mother" text to the format that each font is expecting, for each non-unicode font. This is a lot of extra work and, in my experience, with Tibetan at least, these conversion programs are idiosyncratic and error prone. As "management" is all about applying limited resources most effectively, I hesitate to invest time in using non-unicode fonts.

None of that negates what you say that it is the images of the text, not the codepoint representation, that is what is desired.

kind regards, Kurt

On Sat, May 10, 2025 at 5:17 AM Jan Kučera <jan.kucera at ujca.cz<mailto:jan.kucera at ujca.cz>> wrote:
Dear Harry,

I completely agree with you. My point was that for OCR, you do not care about codepoints or typing experience. You just extract the “images” from the font and use them for training. The Unicode fonts contain the same conjunct “images” as the non-Unicode fonts do, they just don’t have them accessible directly through codepoints.

The task here is not to construct Devanagari texts. I – not only as a chair of script encoding at Unicode – certainly would not encourage anyone to produce texts in any font that is not Unicode compliant!

Thanks,
Jan

From: Harry Spier <vasishtha.spier at gmail.com<mailto:vasishtha.spier at gmail.com>>
Sent: sobota 10. května 2025 13:09
To: Jan Kučera <jan.kucera at ujca.cz<mailto:jan.kucera at ujca.cz>>
Cc: Sebastian Nehrdich <nehrdbsd at gmail.com<mailto:nehrdbsd at gmail.com>>; Indology List <indology at list.indology.info<mailto:indology at list.indology.info>>; Kurt Keutzer <kurt.keutzer at gmail.com<mailto:kurt.keutzer at gmail.com>>
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
URL: <https://list.indology.info/pipermail/indology/attachments/20250510/16dd0203/attachment.htm>
