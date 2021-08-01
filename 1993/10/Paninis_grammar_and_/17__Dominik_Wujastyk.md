+++
title = "17 Dominik Wujastyk"
date = "1993-10-08"
upstream_url = "https://list.indology.info/pipermail/indology/1993-October/000719.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/1993-October/000719.html)

 In message Thu, 07 Oct 93 17:17:38 BST,
 Devaraya Prabhu <prabhu at rex.cs.tulane.edu>  writes:

> 	Backus-Naur Form (BNF) is the most commonly adopted notation for
>   describing the grammars of computer languages (such as Pascal, C..)
>    According  Ingerman(*), this notation is similar to the one employed
>  by  Panini in  describing the rules of Sanskrit grammar.  No, I have
>  not read  the source. I am just quoting from the foot-note of a text
> book..
>    (*) Ingerman, P.Z. [1967] "Panini-Backus form suggested",
> Communications  			   of the ACM, 10:3, 137.
>

I have studied Panini's grammar and I am familiar with BNF notation.
Panini's notational scheme is not similar to BNF in any meaningful way.
Indeed it is not known for sure that Panini even had a notational scheme in
the written sense:  i.e., I believe that the current thinking in the debate
about the date at which writing began to be used for scholarly purposes in
India would exclude Panini.  So we should talk rather of Panini's
"encoding" or some such term, free of reference to writing.  This doesn't
alter the argument about whether features of the Asthadhyayi are similar to
BNF or not.

The main point is that Panini's system of codes, abbreviations, and
redefined case endings is vastly more subtle and sophisticated than BNF,
and is aimed at doing a different job.  BNF is really just a very simple
way of writing down the logical relationships between items in a program; a
linear version of Venn diagrams, almost.  It is purely descriptive, where
as Panini's rules are operative.  To put it differently, BNF notation is
useful for *describing* grammars; the Astadhyayi *is* a grammar.  The
characterization of Ingerman's article you cite above makes it sound as
though Ingerman thought Panini was describing a grammar of Sanskrit.
That's not the case: Panini was describing Sanskrit.  BNF rules are more
like meta-rules wrt grammar.

Really, all this talk of BNF and Boolean logic amounts to no more than
saying Panini was logical, systematic, and had a metalanguage.  This is
very impressive, of course, but it isn't news, and wasn't even news in 1967.

I append Ingerman's 1967 article.  [I don't know if you read CACM. It's fun
going back this far in a major computing journal:  these 1960s issues of
CACM still think that a good way of promoting a new piece of computer
equipment is to have a photograph with a pretty girl touching it, or
leaning over it, or appearing to work it.  And in the following year (1968:
147f.) there is Dijkstra's famous letter to the editor: "Go To Statement
Considered Harmful".  The echos of the heated debate started by this letter
are still heard today, especially with Knuth cocking a snook at Dijkstra by
including goto mechanisms in his Literate Programming project, WEB.]

Dominik

-----------------------------------------------------------------------
Communications of the ACM, vol 10/ No. 3/ March 1967, pp. 137-8.
I have typed this fast, without checking.  Also, the original had
correct diacritics in all Sanskrit words, which I have omitted.
-----------------------------------------------------------------------
"Panini-Backus From" Suggested
Editor:
Knuth, in a recent Letter to the Eeiyor of CACM [1], makes the point that
the metasyntactic notation used in, e.g., the ALGOL 60 report [2] should be
renamed.  In particular, he observes the well-acceded fact that the
so-called Backus Normal Form is, indeed, not a normal form in any sense.
The purpose of this letter is to observe that Backus was not the first to
use the form with which his name has become associated, although he did,
indeed, discover it independently.

Dr. Alexander Wilhelmy has called to my attention [3] a work by Panini [4].
Panini was a scholar who flourished between 400 B.C. and 200 B.C.; perhaps
his most significant work was the compilation of a grammar of Sanskrit.  In
order to describe the (rather complicated) rules of gra1mar, he invented a
notation which is equivalent in its power to that of Backus, and has many
similar properties: given the use to which the notation was put, it is
possible to identify structures equivalent to the Backus "|" and to the sue
of the meta-brackets "<" and ">" enclosing suggestive names.  Panini avoided
the necessity for the character "::=" by writing the meta-result on the
right rather than the left (see, e.g., [5] and [6] for a similar notation).

Since it is traditional in professional circles to give credit where credit
is due, and since there is clear evidence that Panini was the earlier
independent inventor of the notation, may I suggest the name "Panini-Backus
From" as being a more desirable one?  Not only does it give due credit, but
it also avoids the misues of the word "Normal."

REFERENCES
1.  Knuth, Donald E.  Backus normal form vs.  Backus Naur form. Comm. ACM 7,
    12 (Dec. 1964), 735-736.
2.  Naur, P. [Ed.].  Revised report on the algorithmic language ALGOL 60.
    Comm. ACM 6, 1 (Jan. 1963), 1-17.
3.  Wilhelmy, A.  Private communication dated 5 November 1966.
4.  Kavyatirtha, Narayana Rama Acarya (Ed.) Paninimunipranitah
    astadhyayisutrapathah vartikapathasamalankrtah.  Bombay, India, 1954
    (See also [7], supplied by Dr. Donald Knuth.) [Kavya, N. R. A. (Ed.)
    Panini--Reading of Rules in Eight Chapters, Embellished by His Pupils].
5.  Irons, E. T.  Maintenance manual for PSYCO--part one.  Institute for
    Defense Analysiss, Princeton, N. J.
6.  Ingerman, P. Z.  A Syntax-Oriented Translator.  Academic Press, New
    York, 1966.
7.  Panini.  The Ashtadhyayi.  Edited and translated into English by Srisa
    Chandra Vasu, Delhi, India, 1962.

Peter Zilahy Ingerman
Manager, LAnguage Systems Standards & Research
Radio Corporation of America
Cherry Hill, N. J.  08034
-----------------------------------------------------------------------
--
Dominik Wujastyk           Phone (and voice messages): +44 71 611 8467



> From mehta at kc235-2.mgmt.purdue.edu 8 1993 Oct U 08:25:00
Date: 8 Oct 1993 08:25:00 U
From: "Mehta, Shailendra" <mehta at kc235-2.mgmt.purdue.edu>
Subject: RE: Panini's grammar and Boolean logic (+Ingerman's article)


I am grateful to Dominik for posting a copy of Ingerman's letter. I was going
to go down and copy it myself but he saved me (and many others I am sure) a bit
of trouble. I have seen this article (letter really) referred to in many
scholarly publications, and it was a surprise to note how modest its scope
really is. Surely Panini deserves a better formal analysis. 

I am neither a grammarian nor a logician by training, though I have dabbled a
little, here and there, so I am not sure that I am competent enough to make the
subsequent statements. But I hope I am provocative with being offensive.


I am sure there is a great need to create mirror of Panini in the modern
terminology of logic, in order that his contributions be properly appreciated
outside the small band of grammarians. Surely his appeal to logicians and
computer scientists would be greatly enhanced if he could be fully explained in
their own language. Once this is done, he ought to take his place in the
history of world thought as one of the Titans. Panini was without doubt, as
Saussure among others pointed out, without peer as a linguist in the long
history of the subject. To those who do not mind such categorical statements,
he was the greaterst linguist of all time. But to merely say that is to damn
him with faint praise. Surely he was much more. 

In any case, it seems to me that Panini's grammar must be the most concentrated
form of thought in existence. How much he manages to say in the compass of
40-50 pages must be without parallel. In many ways, if not most, he surpasses
Euclid. Further, the shorthand that he uses with the Siva sutras right in the
beginning, ought *not* to be possible by the simple laws of combinatorics. I
mean, what is the probability that a naturally evolved language can have such a
regular coding scheme ? (Has anyone figured the relevant probabilities out ?)

One way or another, these issues are rather important, and surely deserve
greater attention than that which Ingerman was able to provide, but the best
that I, in my limited exposure, have seen so far, is a four volume rendering BY
a logician. What Panini needs is a good four volume rendering IN logic.

Shailendra Raj Mehta
mehta at mgmt.purdue.edu










