+++
title = "108 patrick mc allister"
date = "2010-05-19"
upstream_url = "https://list.indology.info/pipermail/indology/2010-May/034470.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2010-May/034470.html)

* Dominik Wujastyk <wujastyk at GMAIL.COM> [2010-05-19 13:49]:
> The whole difficulty is to get the right number of leading zeros in the tif
> filenames (e.g., "00000001.tiff" .. "00009999.tiff").  Your solution doesn't
> do this.
> 

A one line solution is to use curl (using v. 7.20.1 in my case)
itself, saving the files under "img-NUMBER.tif":

curl http://www.new.dli.ernet.in/data/upload/0048/903/PTIFF/[00000001-397].tif -o img-#1.tif

or, to see that the padding of the leading zeros works:

curl http://www.new.dli.ernet.in/data/upload/0048/903/PTIFF/[00000099-101].tif -o img-#1.tif

I'm not sure if curl is included in cygwin, though.

-- 
patrick mc allister

long term email: pma at rdorte.org
current office email: patrick.mcallister at univie.ac.at
homepage: http://homepage.univie.ac.at/patrick.mcallister/



