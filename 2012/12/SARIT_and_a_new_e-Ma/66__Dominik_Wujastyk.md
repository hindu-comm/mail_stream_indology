+++
title = "66 Dominik Wujastyk"
date = "2012-12-06"
upstream_url = "https://list.indology.info/pipermail/indology/2012-December/037241.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2012-December/037241.html)

Dear INDOLOGYists,

As you may know, the SARIT service, running at http://sarit.indology.info,
is a project that aims to offer freely-downloadable electronic editions of
Indic texts, together with a menu-driven interface to make it easy to
search, index, and do other useful things with the e-texts.  E-texts in
SARIT are editions in the scholarly sense: they have a transparent history
and provenance, they can be cited accurately, and they represent a fixed
point of reference that can be used in footnotes and bibliographies.

SARIT is the beginning of a scholarly language corpus for Sanskrit and
related languages.  As such, it aims to set an example of doing things "the
right way." That is to say, the base e-texts are encoded ("marked-up")
using the Guidelines of the Text Encoding
Initiative<http://www.tei-c.org/index.xml>.
 A big part of that is the addition of structured meta-data to the top of
the files, the "TEI
Header<http://www.tei-c.org/release/doc/tei-p5-doc/en/html/HD.html>,"
that gives a full and structured account of the provenance of the e-text,
who has done what to it, and a history of changes as it evolves and is
corrected or updated.

There's more than this to the design of the SARIT project, but I'll stop
there for the moment.  Files prepared "the SARIT way" are useful for many
purposes in computing and the humanities, far beyond SARIT itself.  TEI
encoding is, in fact, now the accepted standard for all serious textual
work in humanities computing.  There are all sorts of fascinating things
one can do with e-texts, once one has materials in the TEI format.

We have been adding e-texts to SARIT for a few years now, slowly and
carefully, learning all the time.  There is already a sizeable corpus of
materials and SARIT is already more than merely a test system.  However,
this week the SARIT text corpus took a giant step forward, through the
addition of a new text of the complete Mahabharata, the "Southern
recension."

During the last few years, Professor Shrinivasa Varakhedi, Dean and
Director, Karnataka Sanskrit University, has created an e-text of the
seventeen-volume "Kumbakonam" Mahabharata, i.e.,

Krishnacharya, T. R. & Vyasacharya, T. R. (Eds.) Śrīḥ Śrīman Mahābhāratam.
Saṭippaṇam ldots Ṭī. Ār. Kṛṣṇācāryeṇa Ṭī. Ār. Vyāsācāryeṇa ca anekeṣāṃ
viduṣāṃ sāhāyyena dākṣiṇātyabahukośānusāreṇa saṃśodhya = Sriman
Mahabharatam. A New Edition Mainly Based on the South Indian Texts, with
Footnotes and Readings Nirnayasagar Press, Bombay, 1906--1910.

A few weeks ago, Professor Varakhedi contacted me with the wish to give
this e-text freely to the world of scholarship.  I'm delighted to say that
my colleague Patrick Mc Allister, who is webmaster for the SARIT and
INDOLOGY websites, with minor assistance from Dr John Smith and myself, has
now marked up the Mahabharata files donated by Prof. Varakhedi following
the TEI Guidelines, and the e-text was published on the SARIT server
yesterday.

   - http://sarit.indology.info/newphilo/navigate.pl?indologica.11
   - http://sarit.indology.info/newphilo/navigate.pl?indologica.12

The first text above is the Mbh in Roman script (IAST encoding) and the
second is the whole text again in Devanagari.  At the main SARIT search
interface, one can search and index the text in either script.

We still have some tweaking to do on the files, and this may even go on for
a long time.  But we wanted to get the texts to the public as soon as
possible.   I wish to express my great thanks to Patrick Mc Allister for
his hard work and expertise in both humanities computing and Sanskrit.

In a few days, we shall also be adding derived versions of the texts to the
"downloads" section of SARIT, so that people may also take and use the
original XML files or the derived PDF or HTML versions of the Mahabharata
(in both scripts).

This e-Mahabharata, like all the SARIT files, is released under a Creative
Commons license <http://creativecommons.org/licenses/by-sa/3.0/> that
permits free sharing, but insists on authorial attribution and the similar
free distribution of all derivatives under the same terms.  (It's a freedom
that propagates itself.)

May I once again express my enormous gratitude to Prof. Varakhedi for so
generously making these files available to the public, and allowing them to
be mounted on the SARIT server.  I am also full of admiration for the long
task of inputting the data that he has undertaken.  Perhaps only Professor
Tokunaga would fully understand what such a task means.

Enjoy,

Dominik Wujastyk

--
Dr Dominik Wujastyk
INDOLOGY and SARIT


Technical appendix:

The master copies of all SARIT files, including the Mahabharata files, also
live on the Github service, at

   - https://github.com/paddymcall/SARIT

At that location, anyone can use Git to take a copy of the XML files, and
also to submit corrections and updates.  This is for more advanced users,
obviously, people who understand version control systems and are able to
use Git, and who also have a good knowledge of Sanskrit.  But in principle,
it is all open to the public.  If anyone makes a mess, it can easily be
rolled back, since Git keeps a history of all changes.

The purpose of doing this is to be able to track the history of all changes
to the SARIT files in the future, down to the byte level, with
documentation and the ability to fork (and merge) versions in future,
should the need arise.


-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20121206/4185ab3c/attachment.htm>
