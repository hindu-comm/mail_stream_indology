+++
title = "38 Peter Wyzlic"
date = "2008-05-06"
upstream_url = "https://list.indology.info/pipermail/indology/2008-May/031684.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2008-May/031684.html)

Am 06.05.2008 um 23:03 schrieb Deshpande, Madhav:

> I tried setting the character-encoding to UTF-8 on Firefox and  
> Opera, the two browsers I have on my Mac, but it does not seem to  
> be doing the trick on either browser.  Must be something else I  
> need to do.

The same effect appears with Firefox on my Linux box.

When I open the source code of the HTML page (start page) I see e.g.
"MahÄbhÄá&sup1;£ya" for  
"Mahābhāṣya" (mahAbhAzya). That means, no UTF code but some  
obviously wrong html entities (Ä stands for big case umlaut-A,  
i.e. Ä, á for á, £ for the British Pound symbol and so  
on).  If this shows up correctly on other systems, there must happen  
something behind the scenes that works differently depending on the  
platform of the browser. Perhaps some kind of scripting code, or so,  
I guess. Does it work with Internet Explorer on Windows?

All the best
Peter Wyzlic

--
Peter Wyzlic
pwyzlic at uni-bonn.de



