+++
title = "169 Jaap Pranger"
date = "1999-06-18"
upstream_url = "https://list.indology.info/pipermail/indology/1999-June/017808.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/1999-June/017808.html)

On Thu, 10 Jun 1999 Jaap Pranger wrote:


>Windows and Mac versions of the CSX+ fonts seem to have
>identical encodings, in contrast to what is usual.
>
>Data based on CSX+ fonts, when exchanged across platforms
>through email, gets scrambled due to the usual automagical
>MIME re-encoding.
>
>Any workarounds for this problem?


Andreas Prilop provided me with an elegant solution that works
quite well with the Eudora mail client on a Mac.


<Andreas Prilop>

Get Eudora Standard Tables
  info-mac/comm/inet/mail/edr/eudora-standard-tables.hqx
from any Info-Mac mirror.

For outgoing mail, deselect any transcoding ("transliteration").
For incoming mail, select "Repair ISO-Latin-1".

For background information, see also
<http://www.hf.uib.no/smi/files/eudtab.html>

</Andreas Prilop>



This is the table that does the trick:

# "Repair ISO-Latin-1"
Repair (i.e. restore) an incoming message that has been converted
automatically but incorrectly from ISO-Latin-1 to MacRoman.


Jaap Pranger

--



