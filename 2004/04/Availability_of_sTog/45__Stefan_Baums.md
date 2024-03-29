+++
title = "45 Stefan Baums"
date = "2004-04-29"
upstream_url = "https://list.indology.info/pipermail/indology/2004-April/028361.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2004-April/028361.html)

> I haven't worked a lot with TIFF-data; could you perhaps spell
> out some of the things one could do with these TIFF-files

TIFF is a great archiving format for scanned images because it is
lossless, and because it enjoys extremely broad support and can
easily be converted to just about any other format.  In contrast
with this, the compression that is used for embedding images in
PDF files is to the best of my knowledge always lossy.  So it is
not only complicated to extract images from a PDF (depending on
your software), but you also lose quality in the process.

Another consideration is filesize.  Precisely because it is lossy,
a PDF file might be smaller than a collection of non-lossy
compressed TIFFs, but black-and-white images tend to be a special
case where the tradeoff might actually be the other way around.

Thirdly, since you mention XPDF, one problem that I experience
with recent versions of that program is that while outline text
rendering seems to have become faster, rendering of full-page
embedded images is now unbearably slow (on a 700 MHz computer),
making it practically useless for any real work with a document.

For my own scanning projects, I now use the DjVu format, which
combines the advantages of PDF (easy navigation) with that of TIFF
(lossless compression of black-and-white images and easy
conversion to other formats), has small file sizes and renders
very fast indeed.  DjVu has an open specification and a complete
free software implementation is available:

   http://www.djvuzone.org/
   http://djvu.sourceforge.net/
   http://www.planetdjvu.com/

One could argue that PDF is designed for real digital text content
(with proper encoding of characters and outline glyphs), while
DjVu is the technically superior solution for written documents
scanned as images.

I was made aware of DjVu by Bill Mahony’s 7 November announcement
to this list of the Muktabodha archive, which uses this format, as
apparently do a large number of other libraries and archives.

Best regards,
Stefan Baums

--
Stefan Baums
Asian Languages and Literature
University of Washington



