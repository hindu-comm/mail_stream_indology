+++
title = "86 Birgit Kellner"
date = "2004-11-24"
upstream_url = "https://list.indology.info/pipermail/indology/2004-November/028812.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2004-November/028812.html)

Dominik Wujastyk wrote:

> Dear Birgit,
>
> I'm in the middle of doing a small critical edition myself at the moment,
> using Ledmac. Would it be useful for me to send you my Ledmac input file,
> and a PDF of the output? It's only half done, so it's a bit scrappy, but
> the important bits about the use of Ledmac are all okay.
>
> Best,
> Dominik

Dear Dominik,

thank you for your offer; indeed it would be very helpful to have your 
Ledmac and PDF files.

I still have to digest Richard Mahoney's suggestion, which is a little 
bit too advanced for me as a LaTeX neophyte.

Off-list, I also received some very helpful answers from Jürgen 
Hanneder. The unwanted separation of letters with virAma can be overcome 
by a different approach to separating strings in ledmac:

Instead of:
\edtext{\Nag{adhigamād}}{\Bfootnote{some variant reading for 
adhigamāt}}arthasiddhiḥ

use:
\edtext{\Nag{adhigamāda}}{\lemma{adhigamāt}{\Bfootnote{some variant 
reading for adhigamāt}}}rthasiddhiḥ

The drawback is that the text then gets cut up beyond belief, and that 
it becomes rather cumbersome to search in it - unless there is some tool 
that allows you to search in LaTeX source files ignoring all control codes.

I also had difficulties with certain consonants and ligatures; they 
would just not get processed. Jürgen found out that these problems arise 
because the file uses both the devnag and the babel-german package, both 
of which make use of " as a special character. For the time being, it 
seems that I have to do without German hyphentation in critical 
editions, which is actually a negligible evil.

Many thanks for all replies,

best regards,

Birgit Kellner



