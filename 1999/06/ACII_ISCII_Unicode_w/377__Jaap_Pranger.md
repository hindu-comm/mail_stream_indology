+++
title = "377 Jaap Pranger"
date = "1999-06-15"
upstream_url = "https://list.indology.info/pipermail/indology/1999-June/017700.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/1999-June/017700.html)

On Son, 13 Jun 1999, John Smith wrote:

>On Sat, 12 Jun 1999, Jaap Pranger wrote:

>> BTW, John, last year in Conv-Dev you mentioned ACII.  You said: "ACII
>> is the name used for the full 8-bit character set comprising 7-bit ASCII
>> in the lower half and 7-bit ISCII in the upper half."
>> Is this charset in use anywhere? I can't imagine reasonable Nagari
>> coming out from a 7-bit subset.
>
>It is used in all of CDAC's products (ALP for DOS, iLeap for Windows, and
>others). The output Nagari (/Bengali/Gujarati/Tamil/etc.) is extremely
>good. This is because, like Unicode, an intermediate piece of software (a
>"renderer") handles conversion from logical character to actual glyph.

Repeating your statement: CDAC's products use a context sensitive
rendering engine, which means that the number of glyphs available in the
font can be much higher than the number of encoded characters.

I venture to disagree where you say "like Unicode". The Unicode standard
only deals with character codes, and takes no care of the rendering.

Context sensitive rendering will also be available through UniScribe
(the Windows Unicode Script Processor) in Windows NT 5.0, and through
Apple's ATSUI (Apple Type Services for Unicode Imaging) in MacOS 8.5
as soon as applications taking adventage of ATSUI will arrive.

A few questions remain:

What is the meaning of the acronym ACII?

Since ISCII is an 8-bit standard, may I conclude that the 7-bit
Devanagari part of ACII is a -limited- version (subset) of ISCII?


Your information was appreciated,
Thanks,

Jaap Pranger


--



