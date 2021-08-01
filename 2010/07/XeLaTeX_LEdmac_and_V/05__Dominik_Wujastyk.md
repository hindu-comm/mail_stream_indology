+++
title = "05 Dominik Wujastyk"
date = "2010-07-05"
upstream_url = "https://list.indology.info/pipermail/indology/2010-July/034564.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2010-July/034564.html)

http://cikitsa.blogspot.com/2010/07/xelatex-for-sanskrit.html

At the link above, I've knocked up a
XeLaTeX<http://en.wikipedia.org/wiki/XeTeX>input file that exemplifies
a few features that Sanskritists like.  This is
all based on the work of others, esp. Somdev Vasudev, Zdenek Wagner, Daniel
Stender, and of course Jonathan Kew (who wrote XeTeX).

The main points are:

   1. Live in the Unicode world.  Then, very good things become possible ...
   2. You can type your files in romanisation and get either Romanisation or
   Devanagārī output, as you wish, without retyping the text.
   3. You can type Devanāgarī input and get Devanāgarī output.
   4. Devanāgarī hyphenates automatically, and reasonably well.
   5. You can use any Roman or Devanāgarī fonts that are available to you,
   and switch between them easily. (As long as they are Unicode.)

DW



On 3 July 2010 13:24, Lubin, Tim <lubint at wlu.edu> wrote:
> Dear Dominik (and anyone else who might be able to help):
>
> Your message to Indology (below) made me wonder about a couple of things.
 I am still in the process (!) of trying to set a short Sanskrit critical
edition using plain TeX with Edmac and the Velthuis font package.  It is the
publisher's desire to stick with Velthuis, which (last time I checked) works
only with plain TeX.  But everywhere I look, when I run into a difficulty,
TeX-savvy people are scoffing at the very notion of using plain TeX, yet
also still saying that various portings of Edmac to LaTeX are iffy and
imperfect (though I myself succeeded in using Ledmac for an edition set in
transliteration).
>
> In your message, you say you are using XeLaTeX with UTF-8, but also Edmac
and Velthuis -- something I would like to do as well, but am behind in
latest developments.
>
> Are you using some newer form of Edmac or Ledmac for this?
>
> Is there a new, improved Velthuis, or Velthuis-look-alike that can work
with Ledmac?
>
> And for godsake has Velthuis ever "learned" how to print a conjunct for
/chra/ or /.dra/ ??  Even Word can do that now!
>
> Tim
> ________________________________________
> From: Indology [INDOLOGY at liverpool.ac.uk] On Behalf Of Dominik Wujastyk [
wujastyk at GMAIL.COM]
> Sent: Wednesday, May 19, 2010 4:59 AM
> To: INDOLOGY at liverpool.ac.uk
> Subject: Re: [INDOLOGY] AW: [INDOLOGY] OCR for Romanized Sanskrit with
Diacritics
>
> On 18 May 2010 18:32, Kellner, Birgit <
kellner at asia-europe.uni-heidelberg.de
>> wrote:
>
>>
>> I am wondering whether Acrobat recognizes diacritics like ṇ, ṭ, ś or ṣ
and
>> properly selects the fitting Unicode letters. I've never tried - does it,
>> Dominik?
>>
>> Best,
>>
>> Birgit
>>
>
>
> I did some simple tests this morning, and I was startled at how bad the
> results were.  I scanned a page of a Brill book on indology at 300dpi.  I
> then ran the resulting jpeg through the ORC of Acrobat 9, using both
"exact
> image" and "Clearscan".  (The latter creates vector fonts on the fly,
> matching the look of the fonts in the document. Very clever.)
>
> After selecting and copying all the text from the resulting PDFs, and
> examining them in a plain-text editor (UTF8-aware), the results were
> dreadful.  Many, many errors, and certainly no diacritcal marks.
>
> So my earlier impression that current off-the-shelf OCR was mature in
> recognising accented characters was completely wrong.  And I was rather
> shocked at how bad the OCR was even for non-accented text.
>
> Acrobat 9 is quite a complicated product, and it is possible that there
are
> settings I am not aware of that could improve the OCR.  I had a quick
search
> through the Preferences to see if one could set character sets for the
OCR,
> but I couldn't find anything relevant.  The basic OCR menu contains a
single
> language setting, which I had set appropriately.
>
> I think my "residual memory" of OCR being good on diacritics was a
> mis-remembering based on  the scenario that when I copy and paste text
from
> the PDFs produced by my TeX system, as I occasionally do, all the
diacritics
> are correct, and properly coded in UTF8.  I'm using XeLaTeX (with the
> xunicode package).
>
> Best,
> Dominik
>
> !SIG:4bf3a8dd171391969810401!



