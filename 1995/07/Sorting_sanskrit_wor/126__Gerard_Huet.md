+++
title = "126 Gerard Huet"
date = "1995-07-25"
upstream_url = "https://list.indology.info/pipermail/indology/1995-July/002838.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/1995-July/002838.html)

With regards to David Dargie's message:

The proposed scheme, of encoding each transliteration code into a unique
ASCII character in the alphabetical order, will work only if the anusvAra
is used solely its its "original" role. When the anusvAra is used as a
substitute for a nasal, the alphabetical order of this nasal ought to be used,
and this information is context-sensitive. A similar difficulty occurs with
the visarga, which ought to be sorted as the corresponding sibilant when
it denotes a sibilant attenuation.

I would thus recommend that roman transliterations use the anusvAra and the
visarga ONLY when they are original, in which case they have their own
alphabetical order, between the diphtongs and the consonants. If their
non-original use is required, this may be effected by a further processing
pass on the text, by a set of pattern-matching rules looking at some
context (typically a vowel followed by a nasal followed by a consonant).

Another care must be taken when the roman transliteration scheme uses a 
notation for the accent, or a notation for the origin of a long vowel
in a compound word, like in Monier-Williams: such notation ought to be erased
from the source text before the sorting operation.

It would be nice if indology scholars would agree on a standard non-ambiguous
one-to-one encoding of devanagari into ASCII characters, from which all usual 
transliteration schemes could be easily macro-generated in linear time by 
finite automata transducers available in most computer systems or text editors.

Gerard Huet



> From P.Friedlander at wellcome.ac.uk 25 95 Jul EDT 13:50:00
Date: 25 Jul 95 13:50:00 EDT
From: P.Friedlander at wellcome.ac.uk
Subject: re: Sorting Devanagari text
Reply-To: P.Friedlander at wellcome.ac.uk
Mime-Version: 1.0
Content-Type: text/plain; charset=US-ASCII

The sorting of Devanagari text into dictionary order is a subject I had to 
address in work I have done on creating catalogues of Hindi manuscripts.

I also translated the text into an artificial third party transliteration 
where I found that each 'letter' in the sort needed to represent three 
aspects of the letter, the sort sequences of: its base value, initial vowel 
or consonant, a mAtrA value and a nasality value. Using these values for 
each aksara in the Devanagari a sort string can be generated which can be 
sorted normally.

I wrote a Turbo Pascal utility program that sorts Hindi text in Devanagari 
(Typed in a Devanagari font called MaharastriMedium from BrahmiType) into 
dictionary order. If anyone else happens to use this font and wants to sort 
Hindi (and *maybe* it would work for Sanskrit) text I'd be happy to make the 
utility available to them.

However, it is clear that sorting Sanskrit may present more difficulties, as 
mentioned by Gerard Huet, than sorting Hindi.

Also as we all seem to use different Devanagari fonts (and encodings) and 
different Roman transliteration font encodings it seems that the problem of 
how to sort Devanagari will be around for a long time!

Peter Friedlander





