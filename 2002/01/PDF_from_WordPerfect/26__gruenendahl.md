+++
title = "26 gruenendahl"
date = "2002-01-14"
upstream_url = "https://list.indology.info/pipermail/indology/2002-January/026560.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2002-January/026560.html)

There are various ways of creating PDF files from the DOS versions of
WordPerfect (5.1 and 6.0), some of which have been sketched in
earlier messages.

For full details see:
http://www.columbia.edu/~em36/wpdos/pdfprint.html
which is part of " WordPerfect for DOS Updated":
http://www.columbia.edu/~em36/wpdos
a real life-saver for WordPerfect users.

The basic steps in short:
- install a PostScript printer driver in WP. It can be any driver
(e.g.  "QMS 810" ), if  you don't actually HAVE a PostScript pinter;
if you do, install another PS-printer driver (preferably with a
different name) to modify it for the present purpose.

- change  the port definition from "LPT1" to "OTHER" so that WP
will print the file on your  harddisk ; define a name with the
extension ".PS", e.g.:   C:\TEMP\WPPRINT.PS

- open the document you want to convert to PDF and select your
modified PS printer (eventually you will now have to select one of
the PostScript fonts available for that printer).

- "print" the file in the usual way (Shift-F7 etc.); this will
create/overwrite the PostScript file on your harddisk  (in the above
example "C:\TEMP\WPPRINT.PS")

- handle this PostScript file with Acrobate Distiller (or
the freeware / shareware alternatives you will find on "WordPerfect
for DOS Updated"), Ghostview etc.,
OR send it directly to the other party, assuming that they will know
how to handle it  :-)

**********************************************

This converts all WordPerfect characters, including diacritics form
the "International" character set, as well as "overstrike" characters
(in German: Zeichenkombinationen) that you may have defined for
diacritics not defined in WP (like "underdot").

By the way, you can work around this limitation of WP by adding
the missing characters to a PostScript softfont of your choice
(NOT the internal fonts of your printer) with a font editing
programme. ... (Anyone still listening?)


Best regards

Reinhold Grünendahl


********************************************************************

Dr. Reinhold Gruenendahl
Niedersaechsische Staats- und Universitaetsbibliothek
Fachreferat sued- und suedostasiatische Philologien
(Dept. of Indology)

37070 Göttingen, Germany
Tel (+49) (0)5 51 / 39 52 83
Fax (+49) (0)5 51 / 39 23 61
gruenen at mail.sub.uni-goettingen.de

FACH-INFORMATIONEN INDOLOGIE, GOETTINGEN:
http://www.sub.uni-goettingen.de/ebene_1/fiindolo/fiindolo.htm
In English:
http://www.sub.uni-goettingen.de/ebene_1/fiindolo/fiindole.htm

GRETIL - Goettingen Register of Electronic Texts in Indian Languages
http://www.sub.uni-goettingen.de/ebene_1/fiindolo/gretil.htm



