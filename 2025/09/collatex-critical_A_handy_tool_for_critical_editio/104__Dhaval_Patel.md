+++
title = "104 Dhaval Patel"
date = "2025-09-26"
upstream_url = "https://list.indology.info/pipermail/indology/2025-September/061171.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2025-September/061171.html)

Dear friends,
Many of us work in the field of digital humanities, philology, critical
edition etc.
A tedious task in the field of manuscript editing is to create a critical
edition with apparatus.
Collatex <https://collatex.net/> is a text collation tool which is
available for quite some time. It outputs text differences in ASCII table,
XML, JSON, SVG, or HTML.
Whereas for publication or sharing in scholarly communities and for easy
reading, the preferred output formats are markdown, HTML, PDF or TEX.

collatex-critical <https://github.com/drdhaval2785/collatex_critical> is a
trial in that direction. It utliises the JSON output of collatex and
prepares an edition with majority / priority reading as the main text and
the rest of the readings as apparatus in the footnote / endnote.

It is also designed to transliterate the edition to as many transliteration
schemes as one pleases. Usually Western scholars would like to read the
work in IAST and Indian scholars would like to read the work in Devanagari.
As the changes occur in only the plain text witnesses, generating multiple
transliteration of the critical edition should not be a difficult task.
Currently Devanagari, IAST and SLP1 are supported. It can be extended to as
many transliteration schemes as indic-transliteration
<https://github.com/indic-transliteration/indic_transliteration_py> supports.
The transformation from one file format to another is carried out by pandoc
<https://pandoc.org/>.

I understand that scholars would need to have a much fine grained control
over the generated result, but for preparing a visual comparision of
collated data, the tool will still be a good companion. The core idea is to
have the full flow from the witnesses to the collated PDF automated and to
support multiple transliteration schemes.

A PDF generated from test data is attached for reference.

As usual, bug reports and feature requests are welcome.
Do give it a try with your data and raise issues at
https://github.com/drdhaval2785/collatex_critical if required.

I hope it will be of interest to the scholarly world.

-- 
Dr. Dhaval Patel, I.A.S.
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20250927/ce9eebc7/attachment.htm>
-------------- next part --------------
A non-text attachment was scrubbed...
Name: collated.pdf
Type: application/pdf
Size: 34901 bytes
Desc: not available
URL: <https://list.indology.info/pipermail/indology/attachments/20250927/ce9eebc7/attachment.pdf>
