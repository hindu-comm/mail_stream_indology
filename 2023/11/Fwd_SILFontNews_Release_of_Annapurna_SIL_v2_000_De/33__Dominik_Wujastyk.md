+++
title = "33 Dominik Wujastyk"
date = "2023-11-09"
upstream_url = "https://list.indology.info/pipermail/indology/2023-November/058400.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2023-November/058400.html)

---------- Forwarded message ---------
From: SIL Font News <sil-font-news at groups.sil.org>
Date: Thu, 9 Nov 2023 at 15:10
Subject: [SILFontNews] Release of Annapurna SIL v2.000 (Devanagari script)
To: SIL Font News <sil-font-news at groups.sil.org>


We are happy to announce the release of Annapurna SIL version 2.000. This
release has additional characters, new features and bug fixes.


*Note that this is a major upgrade that may cause document reflow assome
glyphs widths have changed and line spacing has been adjusted.*

First release that uses a UFO-based design and production workflow

   - All sources are in open formats
   - Build toolkit and workflow is completely open-source
   - See https://silnrsi.github.io/silfontdev/en-US/Introduction.html

Web fonts are provided in both WOFF and WOFF2 formats

Added Devanagari characters:

   - U+A8FC DEVANAGARI SIGN SIDDHAM
   - U+A8FD DEVANAGARI JAIN OM
   - U+A8FE DEVANAGARI LETTER AY
   - U+A8FF DEVANAGARI VOWEL SIGN AY

Added recommended characters (Latin, punctuation, other) for non-Latin
fonts:

   - U+02C7 caron
   - U+02D8 breve
   - U+02D9 dotaccent
   - U+02DA ring
   - U+02DB ogonek
   - U+02DD hungarumlaut
   - U+0306 brevecomb
   - U+034F graphemejoinercomb
   - U+03C0 pi
   - U+2000 enquad
   - U+2001 emquad
   - U+2002 enspace
   - U+2003 emspace
   - U+2004 threeperemspace
   - U+2005 fourperemspace
   - U+2006 sixperemspace
   - U+2007 figurespace
   - U+2008 punctuationspace
   - U+200A hairspace
   - U+2010 hyphentwo
   - U+2011 nonbreakinghyphen
   - U+2012 figuredash
   - U+2015 horizontalbar
   - U+2027 hyphenationpoint
   - U+2028 lineseparator
   - U+2029 paragraphseparator
   - U+2060 wordjoiner
   - U+2126 Omega, Ohm
   - U+2202 partialdiff
   - U+2206 Delta
   - U+220F product
   - U+2211 summation
   - U+2215 divisionslash
   - U+2219 bulletoperator
   - U+221A radical
   - U+221E infinity
   - U+222B integral
   - U+2248 approxequal
   - U+2260 notequal
   - U+2264 lessequal
   - U+2265 greaterequal
   - U+2423 blank
   - U+25CA lozenge
   - U+FB01 fi
   - U+FB02 fl
   - U+FE00 VS1
   - U+FE01 VS2
   - U+FE02 VS3
   - U+FE03 VS4
   - U+FE04 VS5
   - U+FE05 VS6
   - U+FE06 VS7
   - U+FE07 VS8
   - U+FE08 VS9
   - U+FE09 VS10
   - U+FE0A VS11
   - U+FE0B VS12
   - U+FE0C VS13
   - U+FE0D VS14
   - U+FE0E VS15
   - U+FE0F VS16
   - U+FEFF zeroWidthNoBreakSpace
   - U+FFFC objectReplacementCharacter
   - U+FFFD replacementCharacter

Added variant glyphs:
  DEVANAGARI CHA variants

   - Full Cha with tail
   - Half Cha with no stem or halant

  DEVANAGARI HEADSTROKE variants

   -   Discrete (to show the number of missing characters)
   -   Narrow (for use in typography)
   -   Filler (zero advance width for use in typography)

  DEVANAGARI JAIN OM variant (extended headstroke)

Added Stylistic Set features:

   - ss16 uses ligature forms for ra + ukar (or uukar) with nukta
   - ss17 for full Cha with tail, half Cha with no stem or halant

Added Character Variant features:

   - cv21 for headstroke variants discrete, narrow and filler
   - cv22 for Jain Om variants with extended headstroke
   - Graphite only: added features cv01-cv17 to correspond to OpenType
   ss01-ss17

Width of typographic spaces have been made more consistent to reflect
common publishing industry usage. Note that this may affect line and page
lengths. Affected spaces:

   - U+2003 EN SPACE
   - U+2004 THREE-PER-EM SPACE
   - U+2005 FOUR-PER-EM SPACE
   - U+2006 SIX-PER-EM SPACE
   - U+2009 THIN SPACE
   - U+200A HAIR SPACE
   - U+202F NARROW NO-BREAK SPACE

Fixed OpenType rendering of double Nga stack with open-Ya to match Graphite
Fixed OpenType rendering of nukta forms of stemless characters with open-Ya
to match Graphite
Added Graphite rules to reorder ikar before full vowel and possible cons or
half-cons
Fixed Ra+ukar collision with preceding ukar
Fixed ikar-anusvara collision on conjuncts
Fixed misoriented contours and duplicated knots
Added UFO key and value data to set head table flag bits 0 and 1
Revised content and format of the documentation

The home page is http://software.sil.org/annapurna/.

-- 
Thank you for your interest in SIL fonts. This is not a discussion list, it
is purely a place for SIL to give news and announcements related to all SIL
font releases. If you need assistance with SIL fonts, please go to
https://community.software.sil.org/c/silfonts
---
You received this message because you are subscribed to the Google Groups
"SIL Font News" group.
To unsubscribe from this group and stop receiving emails from it, send an
email to sil-font-news+unsubscribe at groups.sil.org.
To view this discussion on the web visit
https://groups.google.com/a/groups.sil.org/d/msgid/sil-font-news/3038aed6-e5e6-4dd0-a297-51da7684751en%40groups.sil.org
<https://groups.google.com/a/groups.sil.org/d/msgid/sil-font-news/3038aed6-e5e6-4dd0-a297-51da7684751en%40groups.sil.org?utm_medium=email&utm_source=footer>
.
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20231109/bf41136a/attachment.htm>
