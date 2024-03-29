+++
title = "01 Arlo Griffiths"
date = "2010-07-04"
upstream_url = "https://list.indology.info/pipermail/indology/2010-July/034561.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2010-July/034561.html)


Dear Tim,
I am not sure which publisher you are dealing with, but the expressed preference for Velthuis may be due to his ignorance of other available options. I personally find Devangari MT more elegant, and I believe it is more in conformity of the shape of letters expected by an Indian readership.
There is nothing wrong with plain TeX in itself: it will just make things harder because plain TeX wizards are few and far between, and you are bound to run into situations where you need to call on technical advice. I would strongly disadvise launching a project based on plain TeX if you do not have a very helpful plain-TeXie near at hand. Anyhow, Velthuis certainly does work with LaTeX, so I believe that factor is no reason to reject the combination Velthuis-LEDMAC.
Shilpa Sumant and I have been having rather positive experiences with XeLaTeX and LEDMAC for our Karmapa~njikaa edition, using the Devanagari MT font that is native to Mac OS. We started working directly in Devanagari, which means that now that we have substantial part of text in edited form, we face the problem of extracting an easily searchable romanized text from the Devanagari. I heard from Somdev Vasudeva that with some simple tricks, one can keep working in romanized transliteration or in code (as with Velthuis), to get the Devanagari only at the output stage. This might have been a better procedure for us in hindsight.
This is all the perspective of a technical simpleton. Dominik and others will be able to give you sophisticated technical advice.
Good luck!
Arlo

----------------------------------------
> Date: Sat, 3 Jul 2010 07:24:38 -0400
> From: lubint at WLU.EDU
> Subject: [INDOLOGY] (Xe)(La)TeX, (L)Edmac, and Velthuis query
> To: INDOLOGY at liverpool.ac.uk
>
> Dear Dominik (and anyone else who might be able to help):
>
> Your message to Indology (below) made me wonder about a couple of things. I am still in the process (!) of trying to set a short Sanskrit critical edition using plain TeX with Edmac and the Velthuis font package. It is the publisher's desire to stick with Velthuis, which (last time I checked) works only with plain TeX. But everywhere I look, when I run into a difficulty, TeX-savvy people are scoffing at the very notion of using plain TeX, yet also still saying that various portings of Edmac to LaTeX are iffy and imperfect (though I myself succeeded in using Ledmac for an edition set in transliteration).
>
> In your message, you say you are using XeLaTeX with UTF-8, but also Edmac and Velthuis -- something I would like to do as well, but am behind in latest developments.
>
> Are you using some newer form of Edmac or Ledmac for this?
>
> Is there a new, improved Velthuis, or Velthuis-look-alike that can work with Ledmac?
>
> And for godsake has Velthuis ever "learned" how to print a conjunct for /chra/ or /.dra/ ?? Even Word can do that now!
>
> Tim
> ________________________________________
> From: Indology [INDOLOGY at liverpool.ac.uk] On Behalf Of Dominik Wujastyk [wujastyk at GMAIL.COM]
> Sent: Wednesday, May 19, 2010 4:59 AM
> To: INDOLOGY at liverpool.ac.uk
> Subject: Re: [INDOLOGY] AW: [INDOLOGY] OCR for Romanized Sanskrit with Diacritics
>
> On 18 May 2010 18:32, Kellner, Birgit 
>> wrote:
>
>>
>> I am wondering whether Acrobat recognizes diacritics like ṇ, ṭ, ś or ṣ and
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
> results were. I scanned a page of a Brill book on indology at 300dpi. I
> then ran the resulting jpeg through the ORC of Acrobat 9, using both "exact
> image" and "Clearscan". (The latter creates vector fonts on the fly,
> matching the look of the fonts in the document. Very clever.)
>
> After selecting and copying all the text from the resulting PDFs, and
> examining them in a plain-text editor (UTF8-aware), the results were
> dreadful. Many, many errors, and certainly no diacritcal marks.
>
> So my earlier impression that current off-the-shelf OCR was mature in
> recognising accented characters was completely wrong. And I was rather
> shocked at how bad the OCR was even for non-accented text.
>
> Acrobat 9 is quite a complicated product, and it is possible that there are
> settings I am not aware of that could improve the OCR. I had a quick search
> through the Preferences to see if one could set character sets for the OCR,
> but I couldn't find anything relevant. The basic OCR menu contains a single
> language setting, which I had set appropriately.
>
> I think my "residual memory" of OCR being good on diacritics was a
> mis-remembering based on the scenario that when I copy and paste text from
> the PDFs produced by my TeX system, as I occasionally do, all the diacritics
> are correct, and properly coded in UTF8. I'm using XeLaTeX (with the
> xunicode package).
>
> Best,
> Dominik
>
> !SIG:4bf3a8dd171391969810401!

_________________________________________________________________
New Windows 7: Find the right PC for you. Learn more.
http://windows.microsoft.com/shop



