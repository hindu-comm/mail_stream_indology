+++
title = "164 Jan Kučera"
date = "2023-04-27"
upstream_url = "https://list.indology.info/pipermail/indology/2023-April/057653.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2023-April/057653.html)

Thank you for the discussion. I want to point out that the proposal for Ranjana/Lantsa that we are seeking feedback on is authored by Anshuman, so he is definitely involved.

Whether script has its own dandas or the ones in Devanagari block is decided on per-script basis. Contributing to the decision is how different the script dandas are from the existing dandas, the user community, the keyboard layouts commonly available in the region etc. We would nowadays expect proposals to justify the way they suggest dandas should be (or not be) encoded. The font file is not concerned with identity and politics, having danda in the Devanagari block is nothing but different numbers.

Thanks,
Jan

-----Original Message-----
From: INDOLOGY <indology-bounces at list.indology.info> On Behalf Of Stefan Baums
Sent: Thursday, April 27, 2023 8:30 PM
To: Paul Hackett via INDOLOGY <indology at list.indology.info>
Subject: Re: [INDOLOGY] Unicode: Pabuchi and Ranjana

Dear Paul,

>> I know that there has been an effort to make a Ranjana/Lantsa unicode 
>> script from Anshuman Pandey since at least 2016.

there was talk of encoding Rañjanā when I was at Berkeley around 2011, between the Mangalam Center and Deborah Anderson and her Script Encoding Initiative, and preliminary suggestions by Everson
(2009) and Manandhar, Karmacharya and Chitrakar (2014). Anshuman then wrote his discussion paper in 2016:

   https://www.unicode.org/L2/L2016/16015-ranjana.pdf

I do not know what the remaining issues are.

> if you look closely at Gujarati (U+0A80-0AFF), Kannada (U+0C80-0CFF), 
> and others you will see that the single and double daṇḍas are mapped 
> to the Devanāgarī block characters
> (U+0964 & U+0965). That being said, if you look at Indic scripts in 
> the SMP (Secondary Multilingual Plane) such as Brahmi (U+11000-1107F), 
> that is not the case

That is also the doing of Andrew and me, in our Brāhmī encoding proposal from 2003:

   https://www.unicode.org/L2/L2003/03249r-brahmi-proposal.pdf

that entered Unicode in 2010. I think for the discrete daṇḍas, we just followed our precedent with Kharoṣṭhī.

Maybe only of historical interest now, but I originally intended the proposal to cover all pre-modern Brāhmī-derived scripts (possibly including Rañjanā), much like all European variants of the Latin script have the same encoding, see the original proposal and this companion article:

   https://stefanbaums.com/publications/baums_2006_3.pdf

There are advantages and disadvantages to such character unification.

> ambiguous glyphs in proto-Bengali script(s) are fraudulently rendered 
> as distinct in Devanāgarī

If you are thinking of things like the va vs. ba issue, then it still seems to me that separate code blocks are not absolutely necessary, just as the editor of a Latin text might decide to only use the letter u (not v) for both vowel and consonant to avoid subjective decisions, without needing to resort to separate Uncial (or whatever) codepoints for that.

All best,
Stefan

--
Stefan Baums, Ph.D.
Institut für Indologie und Tibetologie
Ludwig‐Maximilians‐Universität München

_______________________________________________
INDOLOGY mailing list
INDOLOGY at list.indology.info
https://list.indology.info/mailman/listinfo/indology

