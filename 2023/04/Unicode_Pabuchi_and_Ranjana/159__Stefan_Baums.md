+++
title = "159 Stefan Baums"
date = "2023-04-27"
upstream_url = "https://list.indology.info/pipermail/indology/2023-April/057645.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2023-April/057645.html)

Dear Charlie,

> how long does it usually take to get a new unicode font
> approved?

Unicode only defines script encodings, not fonts. Once an encoding
enters Unicode, another indeterminate and possibly long time can
pass until fonts, rendering engines and input methods for that
script are created.

To take the Kharoṣṭhī script as an example, Andrew Glass and I had
our encoding for it included in Unicode in 2004 (after an
unusually speedy standardization process of two years), but only a
few years ago did the first fully functional font become available
(as part of Segoe UI Historic), and that only because Andrew
created it. The next version of the Emacs text editor (29) will
have the first convenient Kharoṣṭhī input method, written by me,
so all in all 21 years passed from our first designs to actual
practical support in this case.

That said, it depends on what already exists, of course. In the
case of Rañjanā, maybe there is a good non-Unicode font that could
be adapted, speeding things up.

All best,
Stefan

-- 
Stefan Baums, Ph.D.
Institut für Indologie und Tibetologie
Ludwig‐Maximilians‐Universität München
