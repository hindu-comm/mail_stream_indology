+++
title = "33 dhaval patel"
date = "2016-03-16"
upstream_url = "https://list.indology.info/pipermail/indology/2016-March/042883.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2016-March/042883.html)

Respected sir,
Thank you for your feedback.
There were two coding errors in the segment you tested.
1. When adding the upasarga to the verb form, it had set $pada to 'pada'
from 'pratyaya'. That is why there was wrong application of 'jhalAM
jazo'nte'.
2. There was a space left in between wrongly which prevented application of
'iko yaNaci' to generate 'vya....'.

Both the errors have been corrected in this commit -
https://github.com/drdhaval2785/SanskritVerb/commit/b9c68ffba015e3e425721127409f90f02d6ea2fb
.
The issue discussion was lodged at -
https://github.com/drdhaval2785/SanskritVerb/issues/663.

The code on live server is updated for the correction now. Press F5 to
remove any old cache.
(N.B. Now there is an option to derive Nijanta forms too - in beta mode for
testing).


-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20160316/e1614784/attachment.htm>
