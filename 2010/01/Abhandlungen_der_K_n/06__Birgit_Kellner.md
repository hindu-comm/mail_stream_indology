+++
title = "06 Birgit Kellner"
date = "2010-01-12"
upstream_url = "https://list.indology.info/pipermail/indology/2010-January/033879.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2010-January/033879.html)

Jonathan Silk wrote:
> I have a feeling I may be an idiot (well, I'm sure in other respects, but in
> this case...): I learn from Indologica that we can find online the
> *Abhandlungen
> der Königlichen Akademie der Wissenschaften zu Berlin. *
>
> When I go, however, for example to
> http://bibliothek.bbaw.de/bibliothek-digital/digitalequellen/schriften/anzeige/index_html?band=07-abh/1844&seite:int=711,
> I can only get one page at a time; is there not a way to download an entire
> article?
>
> Thanks for your advice!  Jonathan
>
>   
The interface unfortunately doesn't offer the possibility to download 
several pages at once (as a PDF, for instance), no.

There is a workaround, but it's a bit time-consuming:

1.) Click on a page image with the desired size ("large", for instance). 
You see the JPG file and get a link like this in the browser's URL line:

http://bibliothek.bbaw.de/thumbnail?band=07-abh/1844&aufloesung:int=2&img=DAS_jpg/07-abh/1844/jpg-1000/00000002.jpg&seite:int=2

This means that the image file is stored in this directory:

http://bibliothek.bbaw.de/DAS_jpg/07-abh/1844/jpg-1000/

2.) If you have the wonderful little tool wget installed, run

wget -r http://bibliothek.bbaw.de/DAS_jpg/07-abh/1844/jpg-1000/

from the command line.

This gets you all images for the volume in question to a local folder. 
You can then create a PDF file with these images (even run OCR on them 
before), with, for instance Adobe Acrobat Pro (on Windows); I gather on 
a recent Mac OS, there should already be tools available in the 
operating system for the job.

I trust the real geeks on the list can provide further advice :-)

Best,

b



