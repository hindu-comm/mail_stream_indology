+++
title = "87 Simon Wiles"
date = "2012-06-13"
upstream_url = "https://list.indology.info/pipermail/indology/2012-June/036722.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2012-June/036722.html)

Dear Professor Karp,

I happen to have been doing some limited research on digital Sinhala
script just last week (I was writing a Sinhala <-> Roman
transliterator), and I think the following may be of help to you:


On Mon, 2012-06-11 at 20:02 +0200, Artur Karp wrote:
> Unfortunately, the Sinhalese fonts I have at my disposal (Potha,
> Iskool Pota, Kandy & Kaputa Unicode) do not allow one to create
> ligatures ( sucha sa: kva, kṣa, ñña, ddha, dva, tva, nda, etc.). The
> same goes for grafemes with adscript consonants (r-, -r, -y: ṛṇa, rya,
> dra, dya, kya, tya, vya).

As you know, there are several different kinds of ligatures in Sinhala
script, and to get them to be displayed in a given environment requires
three things:

1) font support (the font must contain the necessary graphemes and
glyphs, and must have the necessary ligature tables);

2) software support (the rendering engine of the software platform you
are using must invoke and apply the correct ligature substitutions); and

3) the akṣaras you're using must be encoded correctly.

Since many (I think all?) of the fonts you mention can do at least the
non-vocalic -y (yaṃsaya යංසය) and -r (rakārāṃsaya රකාරාංසය) strokes (and
the rendering engines of modern word-processors shouldn't be a problem),
I think you might not have correctly encoded akṣaras.

The problem is that many ligatures in Sinhala script are optional, and
so the Unicode standard for Sinhala is capable of representing different
forms.  Generally, you need to add the Unicode "Zero Width Joiner" (ZWJ,
U+200D) in the right place (usually after the Sinhala virāma, aka hal
kirīma or al-lakuna, U+0DCA) to specify that you want the rendering
engine to render the ligature form, if its available in the font.

Standard combining ligatures (bæn̆di akuru බැඳි අකුරු), including r-
(repaya), are optional and few of them are commonly used in modern
Sinhalese, as I understand it.  As such, in the absence of the ZWJ after
the virāma they will be rendered with the explicit virāma visible
(although if this is intentional, the use of an explicit ZWNJ, U+200C,
is strongly recommended by Unicode PR-96[1]).  I think this is what you
must be seeing?

[1] http://unicode.org/review/pr-96.html

"Touching" ligatures (sparśa akuru ස්පර්‍ශ අකුරු), which I believe are
only found in classical and Buddhist texts, are specified by placing the
ZWJ _before_ the virāma.


> The Web has a lot of examples of such ligatures, but always inserted
> in the text as graphic files.
> 
> Does anyone, by any chance, know of a downloadable Sinhala font that
> would show these elements? Or - of such ligatures emebedded in some
> document - but not as graphics?

I created a document showing a range of different kinds of ligatures,
how they are constructed in Unicode, and how they are rendered by
different fonts.  You can take a look here:

http://simonwiles.net/files/sinhala_fonts_and_ligatures.pdf

The only freely-available font I could find which renders all of them
"correctly" is BhashitaComplex, which you can get from here:

http://www.locallanguages.lk/sinhala_unicode_converters

and the most useful documentation on Unicode Sinhala I could find last
week was this document:

http://www.siyabas.lk/files/Sri_Lanka_Standard_Sinhala_Character_Code_for_Information_Interchange_SLS_1134_-_2004.pdf                         
[ alt. link: http://tinyurl.com/6rqz37n ]


Disclaimer:  I don't really read Sinhala script (and certainly not
Sinhalese), and this information took a whole afternoon to track down
and assemble from different sources, so I would appreciate corrections,
clarifications or comments!

I hope this information is useful to you.


Take care,

simon



