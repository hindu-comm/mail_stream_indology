+++
title = "110 Fitzgerald, James"
date = "2010-05-19"
upstream_url = "https://list.indology.info/pipermail/indology/2010-May/034469.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2010-May/034469.html)

Except for grep I don't use cygwin much at all these days and have never heard of "curl" before now. For what it may be worth (NOT a one-line solution, and evidently superceded), the last time I tried to download anything from the DLI I used the technique described below in a note I wrote for a student. The "575" in the third script was determined by manual inspection of the files on the DLI ahead of tiime. Later attempts to download other books from the DLI consistently failed to display even one page in the browser, so I gave up on it completely. I'm glad to hear it's up and "running" again.

Regards, Jim Fitzgerald

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Be in the directory where you want the files to end up.
Prepend c:\cygwin\wget  to the Dos PATH variable

These commands can only be run in sets in which the "width" [=number of decimal places] of the variable are the same [1,2, or 3, or more]
Consequently, must run the command once for the first 9, once for 10-99, then once for 100-999.
The "set" construct [following the "in"] must be altered for each decimal place in the page-number variable; remember to change the number of places in the filename-string for the size of the %P variable.

The URL in the examples below were for vol. 1 of the 1997 Pandurang edition of the Srimad Bhagavatam

for /L %P in (1,1,9) do wget http://www.new.dli.ernet.in/data/upload/0030/525/PTIFF/0000000%P.tif
for /L %P in (10,1,99) do wget http://www.new.dli.ernet.in/data/upload/0030/525/PTIFF/000000%P.tif
for /L %P in (100,1,575) do wget http://www.new.dli.ernet.in/data/upload/0030/525/PTIFF/00000%P.tif


This is the URL that shows up in the browser address bar:

http://www.new.dli.ernet.in/scripts/FullindexDefault.htm?path1=/data/upload/0030/526&first=1&last=526&barcode=1010010030521

Eliminate the "Fullindex..." string.  snip that to /data. . .  cut everything after 526 & append /PTIFF/[filenumber starting from 00000001].tif

But NB, above URL formula is NOT universal.

http://www.new.dli.ernet.in/rawdataupload/upload/0095/766/PTIFF/00000012.tif


+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

> -----Original Message-----
> From: Indology [mailto:INDOLOGY at liverpool.ac.uk] On Behalf Of 
> Dominik Wujastyk
> Sent: Wednesday, May 19, 2010 12:06 PM
> To: INDOLOGY at liverpool.ac.uk
> Subject: Re: [INDOLOGY] wget (was: Re: Abhandlungen der Köni 
> gliche n Ak ademie der Wissensch aften zu Berli)
> 
> Thank you Patrick!  That's the best yet, I think.  curl is 
> new to me.  I've just checked CygWin, though, and it is 
> indeed included there.  Could be the best answer for everyone.
> 
> Best,
> Dominik
> 
> 2010/5/19 patrick mc allister <patrick.mcallister at univie.ac.at>
> 
> > * Dominik Wujastyk <wujastyk at GMAIL.COM> [2010-05-19 13:49]:
> > > The whole difficulty is to get the right number of 
> leading zeros in 
> > > the
> > tif
> > > filenames (e.g., "00000001.tiff" .. "00009999.tiff").  
> Your solution
> > doesn't
> > > do this.
> > >
> >
> > A one line solution is to use curl (using v. 7.20.1 in my case) 
> > itself, saving the files under "img-NUMBER.tif":
> >
> > curl
> > 
> http://www.new.dli.ernet.in/data/upload/0048/903/PTIFF/[00000001-397].
> > tif-o img-#1.tif
> >
> > or, to see that the padding of the leading zeros works:
> >
> > curl
> > 
> http://www.new.dli.ernet.in/data/upload/0048/903/PTIFF/[00000099-101].
> > tif-o img-#1.tif
> >
> > I'm not sure if curl is included in cygwin, though.
> >
> > --
> > patrick mc allister
> >
> > long term email: pma at rdorte.org
> > current office email: patrick.mcallister at univie.ac.at
> > homepage: http://homepage.univie.ac.at/patrick.mcallister/
> >
> > -----BEGIN PGP SIGNATURE-----
> > Version: GnuPG v1.4.10 (GNU/Linux)
> >
> > iEYEARECAAYFAkvz9fAACgkQN5RlYmr8acRqvwCeLCYfJfDSDrV8bXZLHCj4tJYA
> > QcEAnRAs8TgKR4lg3E96Um5籖晹
> > =jU9v
> > -----END PGP SIGNATURE-----
> >
> >
> 



