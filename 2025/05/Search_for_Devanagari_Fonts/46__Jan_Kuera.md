+++
title = "46 Jan Kučera"
date = "2025-05-10"
upstream_url = "https://list.indology.info/pipermail/indology/2025-May/060595.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2025-May/060595.html)

>> 3) If it's fonts you are looking for, is it unicode fonts you want.  The reason I'm asking is that the bulk of the literature (older than the last 20 years or so)  typeset by computer would be in non-unicode fonts.
> We really are interested in eveyrthing, while unicode is the best we might invest time to make other fonts work if needed.

Actually, for training an OCR, it doesn’t matter whether the fonts are Unicode or not, because they work as input and you are interested in the shapes in them, not to which numbers they are assigned. It needs a bit of extra work to map the shapes to the correct classes, but in general the more shapes you can get, the better. I would encourage people to share non-Unicode fonts too. The output of OCR is text, which will presumably be text in Unicode, so any Unicode font would work to display them.

You could theoretically use OCR to convert the non-Unicode literature to Unicode one, but I would argue that is very convoluted, slow and error-prone approach – you have to convert text to image and then the OCR has to “guess” how to split it back and what letters they are. You will get faster and more correct results if you convert them as text to text, as it already contains the information about which shapes are used.

Best Regards,
Jan Kučera
ल Institute of South and Central Asia Students, Prague


-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20250510/a459accb/attachment.htm>
