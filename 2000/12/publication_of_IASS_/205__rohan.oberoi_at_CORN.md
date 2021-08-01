+++
title = "205 rohan.oberoi at CORNELL.EDU"
date = "2000-12-16"
upstream_url = "https://list.indology.info/pipermail/indology/2000-December/024464.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2000-December/024464.html)

Robert Zydenbos wrote:

>If you work with Linux or FreeBSD, the Acrobat writer software is not
>even necessary for producing PDFs. You write your text (with
>StarOffice, TeX, anything), but instead of printing it on paper you
>print it to a PostScript file. With the free program "ps2pdf" this
>can be converted to the PDF format.  In that other discussion, it was
>mentioned that also under Windows it should be possible to generate
>PDF's using the LaTeX distribution for Windows called 'MikTeX.'

Robert, you don't need Linux or FreeBSD to print to PostScript or
convert that to PDF.  On Windows, you can install a local printer
entry (choosing the Apple LaserWriter or the HP LaserJet 4/4M PS
driver is recommended) and check the "Print to File" checkbox when
printing to this phantom printer from any application.  The file will
be created as a .PRN file, but it's really a .PS file which the ps2pdf
utility (available for Windows as part of GhostScript, from
www.cs.wisc.edu/~ghost) will happily convert to PDF.

1.  You can also choose FILE: instead of LPT1: when installing the
    printer entry, but I think the file dialogue it then gives you is
    less capable;

2.  I haven't tried this on a Mac, though -- has anyone?

3.  Of course, if you have the money and don't want the aggravation,
    you may as well just buy Acrobat.

Regards,
Rohan.



