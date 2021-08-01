+++
title = "21 Dominik Wujastyk"
date = "2010-02-08"
upstream_url = "https://list.indology.info/pipermail/indology/2010-February/033980.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2010-February/033980.html)

In the bash shell I posted a little while ago, the first line should read
#!/bin/bash,
not
#!bin/sh
as I posted.

I shall be sending ten Euros to each of you who wrote to tell me of this
error (before today).

corrected version:
---------- cut here -----------

> #!/bin/bash
>
> # fetch Kapadia_Desc.Cat.Govt.Colls.MSS.BORI-Jaina
> # Literature and Philosophy XIX.1 Svetambara Works_1957
>
> for i in {00000001..397..1}
>        do
>                wget
> http://www.new.dli.ernet.in/data/upload/0048/903/PTIFF/$i.tif
>        done
> ---------- cut here -----------
>



