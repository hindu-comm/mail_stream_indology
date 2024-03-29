+++
title = "09 Birgit Kellner"
date = "2006-04-11"
upstream_url = "https://list.indology.info/pipermail/indology/2006-April/029765.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2006-April/029765.html)

Jonathan Silk schrieb:
> Cross-posted to H-Buddhism and Indology
>
> My friend and colleague Dan Martin (Jerusalem) has asked me to post 
> the following information.
>
> Dan has prepared and posted for free public use a tremendous 
> bibliography/biographical resource, taking account mostly of Indian 
> and Tibetan works primarily of Buddhist interest. Toward this end he 
> has posted his 1769 page (!!) bibliography on a web site in two forms, 
> pdf and rtf. These are available for free download for a limited time 
> (since they take up space on someone else's server).  Go to:
>
>
> http://www.eecs.berkeley.edu/~keutzer/martin/
>
> [...]
> A development that has just taken place in the last few days is this: 
> As I noticed and as anyone else who attempts to use the files will 
> notice, their arrangement in a text document is not the most efficient 
> way to arrange things. For example, cross-references are impossible. 
> The citations are in fact alphabetical by author (with a large section 
> of anonymous = mostly canonical works at the beginning--note that each 
> author is given what biographical information is available, a huge 
> resource in its own right!). However, David Germano at Virginia has 
> already volunteered to arrange and post the work in a Wikipedia kind 
> of way, especially such that users will be able to add citations. This 
> will not, naturally, be implemented immediately, however.
Dear All,

first of all, thanks to Dan Martin for making this immensely useful 
resource available, and thanks to Jonathan for pointing it out.

As with the recent announcement of SARDS2 
(http://www.indologie.uni-halle.de/Sards2/), I have some
suggestions for improving the accessibility of data, or at least 
reflections that might lead to such suggestions ... since David Germano 
already volunteered to participate in efforts towards this end, I'm 
CC-ing this message to him.

[Warning: the following may contain an overdose of technical information 
that could put you to sleep if you're not terribly interested in 
structuring data and conceiving database applications.]

First of all, a Wiki is probably the easiest and fastest way of making 
Dan's data available - this would just involve some fiddling with 
regular expressions to structure the data into general author and work 
headers, some data checking, and finally some cut-and-paste into a 
Mediawiki system -, but it may not necessarily be the best way to build 
a useful resource that's easy to maintain in the long run because a 
large part of the data is structured (bibliographical entries).

As I suggested for SARDS2 a few weeks ago, an automatized way to import 
and export bibliographical citations into standard-compliant formats 
(such as BibTeX or TEI) would not only greatly improve data 
accessibility, but would also serve as a powerful incitement for more 
people to contribute their data into such centralized resources because, 
after all, they can also get data out of these systems and insert it 
into their own bibliographies with (next to) no editorial effort. As for 
SARDS2, Walter Slaje already informed me that such 
export/import-facilities are being envisaged for the future.

A second complex of issues emerges when Dan Martin's massive resource is 
compared with one that's similar in approach, but currently available 
only in German; this is our own little digitization of 
Steinkellner/Much's systematic overview of the literature of the 
logico-epistemological school of Buddhism (published in Göttingen 1995), 
called "SUEBS online" 
(http://www.istb.univie.ac.at/cgi-bin/suebs/suebs.cgi). ("SUEBS" is the 
acronym used for the print edition.)

SUEBS online is not yet finished; there are still formatting and design 
issues, and the data is not yet thoroughly checked. An English 
translation of the German bits that it contains would be desirable, but 
there are no concrete plans to implement it for the time being. (Since 
SUEBS online is currently my own "hobby", all that happens to it or 
doesn't happen to it depends on my own spare time, which is becoming 
increasingly limited.)

More importantly, SUEBS online is intended for collaborative enhancement 
and maintenance of data, allowing scholars and students to contribute 
further data and to edit what they already contributed. This involves 
creation of different permission levels, and will also require some 
editorial control for maintaining consistency of data in the future.

Because SUEBS online was converted from a text document with very little 
effort, its bibliographical entries are unfortunately not structured - 
automatized import/export of data is not possible at the moment. This 
should definitely change in the future.

Dan's resource and SUEBS online are structured in almost the same way: 
data is entered under the headings of authors and their works. There is 
some overlap between the two resources in the field of Buddhist pramana 
in India, where SUEBS, because it is intended as a specialized resource 
in this area, contains more detailed information (until 1994, that is, 
when SUEBS went into print). To me, this raises the issue whether a 
combination of these two resources in some way might not be desirable - 
not as a complete merging of data, but as a technical solution where 
data from one or both collections can be accessed through a meta 
search-engine or something of the kind.

SUEBS online exists as a suite of Perl scripts; data is stored in MySQL 
database tables, and diacritics are all in Unicode (UTF-8). User 
management with different permission levels is implemented in general, 
but needs some tweaking towards real collaborative entry and maintenance 
of data. I'm willing to contribute the code, as well as the database 
structure, to any more comprehensive project that moves into a similar 
direction - it could be a start to build up something more efficient and 
comprehensive. If David Germano is interested in building a more 
structured resource than a Wiki, the SUEBS online code, or at least the 
concrete approach that it embodies, could be used as a starting-point 
for further discussion.

As I've said above, a Wiki is the fastest way to make Dan's data 
available, but perhaps not the most meaningful. When dealing with such 
data, the choice is always between the two extremes of fast availability 
and time-consuming and potentially tedious manipulation of data (and 
creation of program code) for a more structured approach.

My own perspective is pragmatic and therefore somewhere in between: I do 
believe that investing effort into the structuring of data always pays 
off in the end, and that opting for what at first sight seems to be the 
fastest solution often has considerable drawbacks for future use and 
increase of data; for instance, if bibliographical entries in SUEBS 
online remain unstructured, chances are that people won't be terribly 
enthusiastic in contributing data because they can't get it back in a 
reasonable form. Plus, whoever adds data always has to remember the 
conventions used for data entry; this is tedious and consumes creative 
energies that are better directed elsewhere; it also inevitably results 
in mistakes and data inconsistency.

At the same time, I also believe that one does not need to structure 
data "atomistically" down to the smallest conceivable unit, which not 
only consumes infinitely more programming time until resources become 
available, but also makes database resources far too unwieldy and 
complicated not only for future users who are encouraged to contribute, 
but also for future programmers who have to maintain code.

Best regards,

Birgit Kellner
Institute for South Asian, Tibetan and Buddhist Studies
University of Vienna



