+++
title = "48 Andrew Glass"
date = "2010-05-19"
upstream_url = "https://list.indology.info/pipermail/indology/2010-May/034454.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2010-May/034454.html)

> It's possible that these instructions may help with other keyboard-handlers too, I don't know.

Dominik is correct about this, the UAC controls in Vista and Windows 7 block some keyboard handlers from reaching into the text stack to intercept key strokes - this is for a good reason, key logging malware can be used to record a user's password and report it to a remote machine so that someone can hack into your bank account. Therefore I wouldn't recommend turning this protection off.

Rather one can right click on the installation file and select "Run as administrator". I have used this technique to successfully install the Keyman software (version 5) that Ken reported having problems with. One caveat is that this software is 32 bit and will not work on 64 bit versions of Windows even with the above technique. You can check which version of Windows you have by looking in the control panel:
Control Panel\System and Security\System


Andrew



