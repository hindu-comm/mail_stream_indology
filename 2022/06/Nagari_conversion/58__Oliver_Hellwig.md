+++
title = "58 Oliver Hellwig"
date = "2022-06-09"
upstream_url = "https://list.indology.info/pipermail/indology/2022-June/056340.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2022-June/056340.html)

Thanks a lot, Harry, for explaining the technical background. This
definitely explains the strange encoding. For the time being, re-OCRing
it seems to be one manageable approach (already pointed out by Tim
Cahill), so I will try the Google cloud SDK which works in the
background of SanskritCR.

Best, Oliver

On 09/06/2022 16:40, Harry Spier wrote:
> Oliver,
> When I open the link you gave, in a browser it gives the file name in
> the upper left corner as drahyayana_shrauta_sutra.qxd . The extension
> qxd is for QuarkXpress files. QuarkXpress is publishing software. When
> I download the file, it downloads as a pdf but when I look at the
> properties, the fonts in the file are embedded Type 1 postscript fonts.
>
> MSTT315b9a0609O15504302
>
> MSTT319c623cc2O17006000
>
> MSTT31ab77a7ccO21306200
>
> MSTT31b3f9fa67O15204300
>
> So it looks like QuarkXpress has disguised the names of the fonts it
> used in creating the pdf.
>
>
> So as far as I can see, this is a (probably quite old) pdf file created
> from a QuarkXpress file. Since the fonts aren't unicode fonts, and the
> names of the fonts are disguised, the only thing I can think of is to
> make a jpeg of each page and enter it into SanskritCR
> https://ocr.sanskritdictionary.com/
> <https://ocr.sanskritdictionary.com/> and then manually correct the errors.
>
> Quite laborious but less laborious than typing the whole thing by hand
> again.
> Harry Spier
>
>
> On Thu, Jun 9, 2022 at 12:32 AM Oliver Hellwig via INDOLOGY
> <indology at list.indology.info <mailto:indology at list.indology.info>> wrote:
>
>     Dear all,
>
>     I came across this digitized version of the Drahyayana Srauta Sutra:
>
>     http://www.hinduonline.co/vedicreserve/kalpa/shrauta/drahyayana_shrauta_sutra.pdf
>     <http://www.hinduonline.co/vedicreserve/kalpa/shrauta/drahyayana_shrauta_sutra.pdf>
>
>     Everything seems fine, but when I try to copy-paste the text, the result
>     for the first line looks like:
>
>     {;Á;y,≈*tsU]m
>
>     (This should be the name of the text.)
>
>     Does anybody know how to obtain readable Devanagari from this kind of
>     custom encoding?
>
>     Best, Oliver
>
>     ---
>     Oliver Hellwig, IVS Zürich/ILI Düsseldorf
>
>     _______________________________________________
>     INDOLOGY mailing list
>     INDOLOGY at list.indology.info <mailto:INDOLOGY at list.indology.info>
>     https://list.indology.info/mailman/listinfo/indology
>     <https://list.indology.info/mailman/listinfo/indology>
>
