+++
title = "298 Dominik Wujastyk"
date = "1998-05-20"
upstream_url = "https://list.indology.info/pipermail/indology/1998-May/012363.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/1998-May/012363.html)

On Mon, 18 May 1998, Gerard Huet wrote:

> Hello. While we are discussing changes to Velthuis Devanagari fonts,
> I encountered problems with certain ligatures, whose horizontal space must
> be somehow wrongly computed; it concerns kt, kl, ~nc, ~nj, j~n and ky.
> Whenever such combination letters appear, TeX justification and alignments
> are wrongly computed.

In many years of using Velthuis's font, I have not observed this problem.
Can you post the minimum file which demonstrates the problem clearly?

This sort of thing can arise if you use TFM files which don't match the MF
files; Velthuis's font did undergo an upgrade some years ago when the
hyphenation feature was added.  At that time it became necessary to delete
the old fonts altogether, and the TFMs, and reinstall the new fonts.  If
you have a hybrid old/new system, you might get unpredictable results.

All the best,
Dominik

--
Dr Dominik Wujastyk,                FAX:        +44 171 611 8545
Wellcome Institute for              URL:        http://www.ucl.ac.uk/~ucgadkw/
  the History of Medicine,          Email:      d.wujastyk at ucl.ac.uk
Wellcome Trust, 183 Euston Road,    Trust URL:  http://www.wellcome.ac.uk
London NW1 2BE, England.

First Rule of History:
  History doesn't repeat itself -- historians merely repeat each other.



