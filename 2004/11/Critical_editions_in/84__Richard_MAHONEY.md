+++
title = "84 Richard MAHONEY"
date = "2004-11-22"
upstream_url = "https://list.indology.info/pipermail/indology/2004-November/028794.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2004-November/028794.html)

On Sun, Nov 21, 2004 at 10:49:06PM +0100, Birgit Kellner wrote:

[snip]

> Ledmac requires encoding critical notes in the following fashion:
> \edtext{This is the text to which the note belongs, and whose
> line-number is placed in the apparatus}{\lemma{Lemma in the critical
> note, optional, otherwise the lemma will be the content of
> "edtext"}{\Afootnote{This is the critical note, belonging to
> apparatus A}}}
>
> Of all this material, only the content of "edtext" really needs to
> be in Devanagari. This is printed as the main text, and also, unless
> a special lemma is given, as a lemma in the apparatus.
>
> The content of "edtext" can be converted to Devanagari through
> enclosure with \Nag{ ... }, but in many cases this proves
> impractical because whatever Devanagari text ends up printed after
> the code for the critical note gets separated - not surprisingly, a
> word-final consonant at the end of \edtext{ } receives a virAma, and
> this is not always how it should be.
>
> I have uploaded .tex and .dvi sample files to show what I mean:
> http://homepage.univie.ac.at/Birgit.Kellner/ledmac_utfskt_test/ledmac_utfskt_test.dvi
> http://homepage.univie.ac.at/Birgit.Kellner/ledmac_utfskt_test/ledmac_utfskt_test.tex
>
> The problem is that a critical note interrupts the Devanagari
> "stream".

Although I'm using TeX, Devanagari for TeX and EDMAC the same issue
can arise. The following code (pre preprocessing) may indicate the
solution:

%%%%%%%%%% base Sanskrit text (Devanaagarii) %%%%%%%%%%

%%%_ + 02:34 base Sanskrit text (Devanaagarii)

% checked:

%%%_ - AB
\VBD
%%%_ : t
\text{$k.rtaak.rtaapariik.so.aya.m$}
%%%_ > l
\lemma{$k.rtaak.rtaa@$}
%%%_ > n
\FD{\MI\ \VP\ \FV\ {\FDN $k.rtaak.rta@$} \LT}/
%%%_ : t
\text{$m.rtyurvi"srambhaghaataka.h$}
%%%_ > l
\lemma{$@vi"srambha@$}
%%%_ > n
\FD{\MI\ \VP\ \FV\ {\FDN $visrambha@$} \LO\ \LT}/
%%%_ : b
$|$

%%%_ - CD
\VMD
%%%_ : b
$svasthaasvasthairavi"svaasya aakasmikamahaa"sani.h || 34$

\VEND

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


N.B. 02:34AB has been broken in two and each half placed within its
own \text{}, in your case \Nag{}. Each lemma only refers to part of
the text in each \text{} construct. The `@' = `abbreviation'.

In your case you may be able to do something such as:

\stanza

\edtext{\Nag{tasmādyato}}{\lemma{ātmabhedāt}{\Bfootnote{PV(S), PV(M),
PVin; ātmabhedo PV(Pr); Tosaki stellt fest, dass ātmabhedo metri causa
nicht möglich ist.}}} \edtext{\Nag{'syātmabhedādasyādhigatirityayam
|}}{\lemma{adhigatir}{\Bfootnote{PV(S), PV(M), PVin; avagatir
PV(Pr)}}} &

\Nag{kriyāyāḥ karmaniyamaḥ siddhā sā tatprasādhanā ||} \&


Another option may be to combine both notes into one, i.e:

\stanza

\edtext{\Nag{tasmādyato'syātmabhedādasyādhigatirityayam
|}}{\lemma{@ātmabhedādasyādhigatir@}{\Bfootnote{ātmabhedāt PV(S),
PV(M), PVin; ātmabhedo PV(Pr); Tosaki stellt fest, dass ātmabhedo
metri causa nicht möglich ist.\ | adhigatir PV(S), PV(M), PVin;
avagatir PV(Pr)}}} &

\Nag{kriyāyāḥ karmaniyamaḥ siddhā sā tatprasādhanā ||} \&

Not sure what you might use for `abbreviation' in LaTeX, perhaps
superscript \circ ?


Best,

 Richard


--
Richard MAHONEY | internet: homepages.comnet.net.nz/~r-mahoney
Littledene      | telephone / telefax (man.): ++64 3 312 1699
Bay Road        | cellular: ++64 25 829 986
OXFORD, NZ      | e-mail: r.mahoney[use"@"]comnet.net.nz



