+++
title = "17 Michael Slouber"
date = "2011-12-12"
upstream_url = "https://list.indology.info/pipermail/indology/2011-December/036126.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2011-December/036126.html)

Dear Adriano and list members,

I second Dominik's recommendations about XeTeX.  There is also an email list specifically for Ledmac and Ledpar: <https://lists.berlios.de/mailman/listinfo/ledmac-users>.  I will send Adriano and any other interested party an example file using Ledpar for a parallel edition of verses.  Please write to me off-list.  

Best,

Michael Slouber
Visiting Adjunct Instructor
Religious Studies
Brown University

Ph.D. Candidate
South and Southeast Asian Studies
UC Berkeley




On Dec 11, 2011, at 9:36 PM, Dominik Wujastyk wrote:

> Dear Adriano,
> 
> A few points:
> 1. don't use the Devanagari package any more.  Move to XeTeX, and then you can just use a font like Sanskrit 2003 (one of my favourites) and type your input in Unicode.  You can type Devanagari directly, or you can type using the Velthuis encoding (aasiidraajaa, k.r.s.na.h), or standard scholarly romanisation (IAST).  The Velthuis or IAST can be converted automatically into Devanagari by XeTeX itself.
> 
> Because XeTeX can accept Velthuis-style input, your legacy documents made with the Devanagari package will still be perfectly okay, and you won't have to retype anything.
> 
> Making this move to XeTeX will greatly simplify your working, and make your documents easier to write, maintain, and process.
> 
> 2. Your difficulty with the stanza environment in LEDMAC is a TeX problem, not an indological one, and you'll have much more luck with responses if you send your question to the main TeX discussion forum, called comp.text.tex.  Questions about LEDMAC are commonly asked and answered there (e.g., here).
> 
> 3. There's also a mailing list specifically for XeTeX where people discuss special issues that relate to unusual languages and XeTeX (here).  Sanskrit sometimes gets discussed there, LEDMAC less so.
> 
> 4. The current maintainer of LEDMAC is Maïeul Rouquette to whom you can write for help if you think you've found a bug.
> 
> Best wishes,
> Dominik Wujastyk
> 
> On 11 December 2011 19:29, Adriano Aprigliano <aprigliano at usp.br> wrote:
> Dear list members,
> 
>  
> 
> I’ve been trying to use the devanagari package together with ledmac and ledpar to produce facing page output and it works fine for prose texts (though I have some doubts on how many text chunks should be handled at each Pages environment) , but when a I try to write verse ---either with the \stanza or {astanza} environments---, it doesn’t work. Could anyone give me a hand on that?
> 
> Best wishes
> 
> Adriano Aprigliano
> 
>  
> 
> Universidade de São Paulo
> 
> São Paulo/SP
> 
> Brasil
> 
> 



-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20111212/d3d89803/attachment.htm>
