+++
title = "107 Dominik Wujastyk"
date = "2024-07-29"
upstream_url = "https://list.indology.info/pipermail/indology/2024-July/059486.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2024-July/059486.html)

When PanditProject <http://panditproject.org> was being planned, Yigal and
his team developed a data model that corresponds quite closely to the more
recent BIBFRAME.  In particular, the clean distinction between *work*,
*person*, and *manuscript* (PP Data Model
<https://www.panditproject.org/info/model>).  In BIBFRAME, this is *work*,
*agent* and *instance+item*.

MARC had two serious failings in relation to manuscript work.

First, MARC databases are flat-file databases (like spreadsheets).  That is
a disaster for data integrity.  If you have to enter, say, a bibliography
for the Bhagavadgītā separately for every single BG manuscript, first it's
laborious, and second it becomes error-prone over many records.

Second, the structure and content of MARC records don't fit the information
we want to record about manuscripts, especially Indian MSS.  MARC can be
bent for MS cataloguing, but it's always non-standard and weird.  MARC just
wasn't designed for that.

   - Pass, Gregory. 2003. Descriptive Cataloging of Ancient, Medieval,
   Renaissance, and Early Modern Manuscripts (Chicago: American Library
   Association) <
   http://www.ala.org/acrl/sites/ala.org.acrl/files/content/publications/booksanddigitalresources/digital/AMREMM_full.pdf
   >

was a brave attempt to bridge the MARC-MS gap, but it was never widely
adopted and it was written as if Asia didn't exist.

BIBFRAME (which is new to me) provides a framework for creating a "triple
store", but that doesn't get one all the way to a relational database.
Although nowadays the relational database model is considered a bit old, as
far as I know it is still the only way to solve the issue of "atomic
values" (Codd), i.e., only enter information about an entity (author,
title, manuscript) *once**.  *All other references to that information are
hot links (relational links) to that one atomic instance.  I am not au fait
with the whole triplestore concept, but I believe you can build a
relational database system on top of triplestore/RDF data.  But prima facie
I can't see how RDF triples enforce atomic data values.

That's why PanditProject is so important.  (Well, one of the reasons.)  As
it grows, it has data-integrity built into the very heart of how it works.
So when there are tens of thousands or millions of entries, there will
still be only a single entry each for Bhagavadgītā or Kālidāsa or MS
Kathmandu KL 699 or any other entity.  If future scholarship decides
definitively that it's Kauṭalya not Kauṭilya, the *one* entry for that name
can be updated and every other instance in all the millions of records will
be automatically correct too.

Best,
Dominik


--
Professor Dominik Wujastyk
<https://apps.ualberta.ca/directory/person/wujastyk>
,

Singhmar Chair in Classical Indian Society and Polity
,

Department of History, Classics, and Religion
<http://historyandclassics.ualberta.ca/>
,
University of Alberta, Canada
.


South Asia at the UofA:

sas.ualberta.ca

SSHRC research: The Suśruta Project <http://sushrutaproject.org>

Journal: History of Science in South Asia <http://hssa-journal.org>


On Mon, 29 Jul 2024 at 05:44, Jan Kučera <jan.kucera at ujca.cz> wrote:

> For cataloguing records there is the MARC replacement, BIBFRAME, and its
> work-instance-item model:
> https://www.loc.gov/bibframe/docs/bibframe2-model.html
>
>
>
> Whoever is interested in BIBRAME there is a free workshop in Helsinki in
> September: http://www.bfwe.eu/helsinki_2024
>
>
>
> Thanks,
>
> Jan
>
> *ल* Institute of South and Central Asia Students, Prague
>
> Chair, Script Encoding Working Group, Unicode
>
>
>
>
>
> *From:* INDOLOGY <indology-bounces at list.indology.info> *On Behalf Of *Dominik
> Wujastyk via INDOLOGY
> *Sent:* Sunday, July 28, 2024 5:05 AM
> *To:* Harry Spier <vasishtha.spier at gmail.com>
> *Cc:* indology at list.indology.info
> *Subject:* Re: [INDOLOGY] Descriptive sanskrit manuscript catalogues best
> practices
>
>
>
> Chapter 2 of the Text Encoding Guidelines
> <https://tei-c.org/release/doc/tei-p5-doc/en/html/HD.html> addresses this
> very issue.  When the TEI Guidelines were first being thought through, the
> concept we worked with was that the "document header" should function like
> a library catalogue card.  Of course it got more detailed and diverse as
> more types of document were considered.
>
>
>
> In any case, TEI chapter 2 is a major, deeply-considered standard for this
> task.  It's the elephant in the room.  In planning a future policy for an
> etext repository, TEI 2 should either be adopted, adapted, or -- god forbid
> -- consciously rejected.  Whatever position is taken, it has to be
> vis-a-vis TEI 2.
>
>
>
> As a footnote, I was chair
> <https://www.tei-c.org/release/doc/tei-p5-doc/en/html/PREFS.html> of the
> first TEI document header committee from 1991, and I wrote the first draft
> of this part of the TEI standard.  If you don't like it, blame me  :-)   Of
> course, it evolved unrecognizably after my time.
>
>
>
> Best,
>
> Dominik
>
>
>
>
>
> Prof. Dominik Wujastyk
>
> Singhmar Chair in Classical Indian Polity and Society
>
> University of Alberta
>
> --
>
> "The University of Alberta is committed to the pursuit of truth, the
> advancement of learning, and the dissemination of knowledge through
> teaching, research and other scholarly and creative activities and service"
>
>
>
>
>
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20240729/d5af7b66/attachment.htm>
