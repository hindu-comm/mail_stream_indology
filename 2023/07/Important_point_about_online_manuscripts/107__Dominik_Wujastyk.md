+++
title = "107 Dominik Wujastyk"
date = "2023-07-31"
upstream_url = "https://list.indology.info/pipermail/indology/2023-July/057975.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2023-July/057975.html)

On Fri, 28 Jul 2023 at 17:14, Harry Spier via INDOLOGY <
indology at list.indology.info> wrote:


> Should the title be the exact title in IAST i.e*. *
> *aṃśumatkāśyapāgama.txt*
>
Should the title be the exact title but without diacriticals i.e*. *
> *amsumatkasyapagama.txt*
>

Personally, I'm undecided.  In SARIT, we use the second method,
no-dicriticals in filenames.  But we have tons of accurate metadata inside
the file.


> Does header data within the text file and written at its beginning such as
> exact title or alternate title affect whether it is found in searchs?
>

Yes.  Depending on the search, of course, but Google looks inside files,
for example.


> Should the file have metadata? I.e. should the text file have an html or
> xml wrapper with metadata of its title in HK, Velthuis, devanagari? And in
> this case its alternate title aṃśumadāgama .?
>

YES!  I'm a true believer in accurate, comprehensive metadata.  This is the
file's Title Page or Library Index Card.  It should be as accurate and
comprehensive as possible.  If the data-input people are capable, it should
be structured as a TEI Header
<https://www.tei-c.org/release/doc/tei-p5-doc/en/html/HD.html>, since
that's the only meaningful standard format out there. (JSON would also do,
but isn't so human-readable.  JSON and TEI can be auto-converted in both
directions.)

Declaration of special interest:  I was the author of the first draft of
the TEI Header specification, back in the 90s.

Are there other ways that will help the etext to be found even if the
> search itself is mispelled?
>

This is the job of the search engine, to implement fuzzy matching.  Or, as
Claudio Teodorescu taught me last week, Levenshtein Distance
<https://en.wikipedia.org/wiki/Levenshtein_distance> matching.

So my final opinion is to put effort into a good TEI header.  Second, make
the file name accurate, whether or not there are diacritical marks.

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
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20230731/35f3e2df/attachment.htm>
