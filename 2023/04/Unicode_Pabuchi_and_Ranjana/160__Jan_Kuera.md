+++
title = "160 Jan Kučera"
date = "2023-04-27"
upstream_url = "https://list.indology.info/pipermail/indology/2023-April/057648.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2023-April/057648.html)

Unicode does require a font from authors that can be used during production of code charts, however it does not need to have conjuncts or other dynamic functionality. Encoding is really what you need for interchange, then you can have a font created. I wouldn't wait for system vendors to include a built-in font for all the scripts, that might not happen at all. There is also Google Fonts project trying to cover all encoded scripts with open-source fonts. With newly encoded scripts you rarely need updates to the rendering engine other than giving it new Unicode data, again thanks to Andrew who developed the Universal Shaping Engine.

As for the Unicode process, it really depends on the individual proposal. Sometimes more evidence is needed which might be difficult to source, sometimes we cannot get in touch with the community, sometimes there is a disagreement within the community, sometimes someone says hold on, we will submit a response/feedback and then they never come back, sometimes governments get involved. There are also cases though where the encoding is relatively straightforward and fast, especially when the proposal is well prepared. The demand or urgency from community or scholars can also help move things forward.

Matthew,

Thank you for the photos of a manuscript, I will pass your feedback to the group and author.

Thanks,
Jan

-----Original Message-----
From: INDOLOGY <indology-bounces at list.indology.info> On Behalf Of Stefan Baums
Sent: Thursday, April 27, 2023 2:23 PM
To: Charles DiSimone via INDOLOGY <indology at list.indology.info>
Subject: Re: [INDOLOGY] Unicode: Pabuchi and Ranjana

Dear Charlie,

> how long does it usually take to get a new unicode font approved?

Unicode only defines script encodings, not fonts. Once an encoding enters Unicode, another indeterminate and possibly long time can pass until fonts, rendering engines and input methods for that script are created.

To take the Kharoṣṭhī script as an example, Andrew Glass and I had our encoding for it included in Unicode in 2004 (after an unusually speedy standardization process of two years), but only a few years ago did the first fully functional font become available (as part of Segoe UI Historic), and that only because Andrew created it. The next version of the Emacs text editor (29) will have the first convenient Kharoṣṭhī input method, written by me, so all in all 21 years passed from our first designs to actual practical support in this case.

That said, it depends on what already exists, of course. In the case of Rañjanā, maybe there is a good non-Unicode font that could be adapted, speeding things up.

All best,
Stefan

--
Stefan Baums, Ph.D.
Institut für Indologie und Tibetologie
Ludwig‐Maximilians‐Universität München

_______________________________________________
INDOLOGY mailing list
INDOLOGY at list.indology.info
https://list.indology.info/mailman/listinfo/indology

