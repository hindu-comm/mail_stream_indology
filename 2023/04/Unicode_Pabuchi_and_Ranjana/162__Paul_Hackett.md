+++
title = "162 Paul Hackett"
date = "2023-04-27"
upstream_url = "https://list.indology.info/pipermail/indology/2023-April/057649.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2023-April/057649.html)

Dear Jan (and Charles and Matthew),

First, regarding the handling of “stacked” letters:

> On Apr 27, 2023, at 7:41 AM, Matthew Kapstein via INDOLOGY <indology at list.indology.info> wrote:
> 
> Some strategy for dealing with such graphs - whether to treat them as discrete characters (on analogy to Chinese), of to leave them out and require that users paste them in as graphic elements - will at some point need to be made explicit. 


Both those proposed ideas are a violation of the Unicode standard.  Unicode encodes characters, not glyphs, so it is a non-starter to treat an alphabetic script as a pictographic one (e.g. Chinese).  Second, the rendering of multiple characters as glyphs is what is done at the font-level, *not* the encoding level, and hence the rendering of a stacked group of letters would be something to be encoded in the font and the “pasting” of graphic representations would defeat the entire purpose of encoding the text. 

> On Apr 27, 2023, at 7:53 AM, Charles DiSimone via INDOLOGY <indology at list.indology.info> wrote:
> 
> I know that there has been an effort to make a Ranjana/Lantsa unicode script from Anshuman Pandey since at least 2016.

I would second Charles’s recommendation that you contact Anshu Pandey.  He and I were in contact a few years ago about what to do about missing characters in the Unicode Devanāgarī (U+0900-097F, U+A8E0-A8FF, U+11B00-11B5F) sections, and what it would take to include additional daṇḍas and letter-numerals — something that remains unresolved.  I would definitely seek out his opinion on these matters.

   One issue to be aware of is that at present, Indic punctuation for many scripts is unified in the Devanāgarī block and individual daṇḍa characters are deprecated, and so, for example, if you look closely at Gujarati (U+0A80-0AFF), Kannada (U+0C80-0CFF), and others you will see that the single and double daṇḍas are mapped to the Devanāgarī block characters (U+0964 & U+0965).  That being said, if you look at Indic scripts in the SMP (Secondary Multilingual Plane) such as Brahmi (U+11000-1107F), that is not the case, so there remains some inconsistency in the treatment of these related scripts.  All the more reason to bring Anshu in on your proposal.

> On Apr 27, 2023, at 7:53 AM, Charles DiSimone via INDOLOGY <indology at list.indology.info> wrote:
> 
> Quickly looking over this new effort in comparison to the 2016 document I see that things are similar. Just out of curiosity, how long does it usually take to get a new unicode font approved? I, for one, would be quite glad to see a Ranjana font and I hope it is finally produced. 


As for fonts, there already exist several Rañjana fonts (including one in development by Chris Fynn), but most simply map the characters to the Devanāgarī (or another) block, or even to legacy encodings.


What it would take to get a proper Unicode Rañjana or other Indic script font, however, is always the same answer: money.

For example: based on my work with so-called proto-Bengali manuscripts, I realized the importance of reading pre-14th century Sanskrit in the scripts it was originally written in since ambiguous glyphs in proto-Bengali script(s) are fraudulently rendered as distinct in Devanāgarī, making it nearly impossible to detect mis-readings of a text rendered in that script.  With this in mind, a couple of years ago I put together a proposal for funding to construct such a font to replicate the scripts of such manuscripts.  The first problem that I encountered is that there is no “proto-Bengali” block in Unicode, only closely related blocks such as Newa (U+11400-1147F) and Tirhuta (U+11480-114DF). Second of all, there are roughly three different “flavors” of proto-Bengali, some characters of which bear closer resemblance to Newa, while others bear closer resemblance to Tirhuta.

Even leaving such issues aside, choosing a preferred glyph style, and picking a target encoding, even to construct a font with only the bare minimal number of pre-composed glyphs (such as keeping combining vowels as separate like most Devanāgarī fonts), you are still looking at 5,000 to 8,000 glyphs (comparable to Tibetan). You would need to select representative glyphs from your manuscripts, ideally pass all of these on to a professional calligrapher to render them with stylistic consistency, then hand those off to a font construction team that would convert the calligraphic drawings to vector outlines, and then build the combination rules for mapping character sequences to precomposed glyphs, as well as the rules for rendering combining characters such as vowel markers.

To construct just one font in such a manner, we estimated would require between US$25,000 and US$50,000 in cost, and a year to a year-and-a-half to build. To do the same for Rañjana would be at the top of that spectrum, if not more.

Unfortunately, our proposal was not successful, and my opinion is that the reason for this is that there is a persistent fantasy amongst Indic scholars that these supporting technologies are not part of Indic “research” (and therefore not deserving of funding), are quick and easy to create, and that such supporting technologies should somehow be provided freely to the content-research part of the community, when the truth is quite the opposite, particularly for scripts for which there is no driving commercial use.

Sorry for going on a bit of a rant, but sometimes these things need to be said with a little force. The short take-away is that if you want these sorts of resources (fonts, encodings, keyboard input methods, etc.), you have to support (philosophically and financially) the construction of them, and not simply expect them to be provided to you out of some sense of noblesse oblige on the part of the tech community.

Regards,

Paul Hackett



