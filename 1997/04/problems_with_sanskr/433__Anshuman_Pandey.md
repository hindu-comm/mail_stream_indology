+++
title = "433 Anshuman Pandey"
date = "1997-04-22"
upstream_url = "https://list.indology.info/pipermail/indology/1997-April/007924.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/1997-April/007924.html)


On Tue, 22 Apr 1997, Anand Venkt Raman wrote:

> I am trying to typeset a page in TeX with with some sanskrit text on
> it using Charles Wikner's sanskrit package.  However, although I am
> certain I got the entire package (fonts/sanskrit.gz), dvips gives me
> the following error about a missing file skt10.  Any help in solving
> this urgent problem would be greatly appreciated.

Are the skt*.mf and skt*.tfm files placed in the appropriate directories?
They should be in the directories where other *.mf and *.tfm files are
kept. Dvips looks in these directories for these files and if they are not
there, then it returns an error. Lastly, if you placed them elsewhere, did
you remember to append that directory to your fonts path?

Regards,
Anshuman Pandey






