+++
title = "09 Michael Slouber"
date = "2012-01-01"
upstream_url = "https://list.indology.info/pipermail/indology/2012-January/036172.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2012-January/036172.html)

Dear Bob,

You could try the XeTeX email forum <http://tug.org/mailman/listinfo/xetex>.  Your example compiled perfectly on my end, but I changed the mapping file to RomDev since I don't have the Velthius map, and the main font to Times just because my system was having trouble finding IndUni-P even though I have it installed.

All the best,

Michael Slouber
Visiting Adjunct Instructor
Religious Studies
Brown University

Ph.D. Candidate
South and Southeast Asian Studies
UC Berkeley




On Jan 1, 2012, at 10:50 AM, Robert A. Hueckstedt wrote:

> I have a little problem with a ligature, if that's the proper term, while composing in Devanagari via xeLaTeX. I remember someone mentioning there was a newsgroup devoted exclusively to Devanagari composition questions, but I have not been successful in finding it. Can anyone direct me?
> 
> Gratefully,
> Bob Hueckstedt
> 
> PS: If you're interested, the problem has to do with j~na. It comes out fine in regular text, but it does not come out fine in footnotes.
> 
> Here's a sample file:
> 
> \documentclass{article}
> \usepackage{fontspec}
> \usepackage{xunicode}
> \usepackage{xltxtra}
> \setmainfont{IndUni-P}
> 
> \newcommand\dn{\catcode`\~=12
>    \fontspec[Script=Devanagari,Mapping=velthuis-sanskrit]{Sanskrit2003}}
> 
> \begin{document}
> {\dn j~nAna}\footnote{The meaning of this is {\dn j~nAna}.} {\dn vidyA}
> \end{document}



-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20120101/8f5916b9/attachment.htm>
