+++
title = "06 Stefan Baums"
date = "2004-11-11"
upstream_url = "https://list.indology.info/pipermail/indology/2004-November/028737.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2004-November/028737.html)

> But it uses private/corporate use area of the unicode.  So,
> while it does not pollute the area meant for other scripts,
> documents prepared with Sanskrit 2003 in mind will not work
> without that font.

Only if a document explicitly uses the PUA codepoints.  On any
system capable of handling OpenType fonts, however, one would use
sequences of the basic Unicode Devanagari characters, and the
OpenType features of the Sanskrit 2003 font will automatically map
from them to the conjuncts in the PUA.  Any text produced this way
(and this is what one gets using any of the input methods
mentioned earlier) will display fine on other Unicode-Devanagari-
capable systems.

If, after all this theoretical discussion, anyone should in doubt
whether or not his/her computer can handle Unicode, here is verse
one of the Bhagavadgita in Unicode Devanagari:

   धर्मक्षेत्रे कुरुक्षेत्रे समवेता युयुत्सवः ।
   मामकाः पाण्डवाश्चैव किमकुर्वत संजय ॥

If that doesn't look right, it's maybe just your email program.
You could try saving this email to disk, then opening it in your
favourite word-processor (maybe specifying "UTF-8 encoding"
explicitly).  Alternatively, have a look at the BBC Hindi page
(which is in Unicode):

   http://www.bbc.co.uk/hindi/

Best regards,
Stefan Baums

-- 
Stefan Baums
Asian Languages and Literature
University of Washington



