+++
title = "44 Jan Kučera"
date = "2023-07-11"
upstream_url = "https://list.indology.info/pipermail/indology/2023-July/057888.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2023-July/057888.html)

Great work!



I would like to second the immense need for pangrams and/or reference text excerpts in all the Indic scripts this community can cover so that industry has a reliable source to verify their fonts or text rendering implementations.



I would also point out that Arial Unicode MS is no longer maintained or shipped with Office for about 10 years and should not be considered for any practical purposes. 



Best regards,

Jan



From: INDOLOGY <indology-bounces at list.indology.info> On Behalf Of Dominik Wujastyk via INDOLOGY
Sent: Tuesday, July 11, 2023 12:18 PM
To: Peter Scharf <scharfpm7 at gmail.com>
Cc: indology at list.indology.info
Subject: Re: [INDOLOGY] Sanskrit characters: a comparison of 12 fonts and their coverage of conjuncts



This is a most helpful reference, thank you!



My own table of comparisons is more aimed at conveying the look-and-feel of fonts as text, with a few diagnostic conjuncts thrown in.

*	https://cikitsa.blogspot.com/2021/05/expanded-devanagari-font-comparison-33.html

All this makes me think that we should develop some Lorem Ipsum text, and some "Quick brown fox <https://en.wikipedia.org/wiki/The_quick_brown_fox_jumps_over_the_lazy_dog> " text for Devanagari, as a kind of stress test or trip test.



Best,

Dominik





On Tue, 11 Jul 2023 at 04:35, Peter Scharf via INDOLOGY <indology at list.indology.info <mailto:indology at list.indology.info> > wrote:

Dear Indologists,



In 2016 (Friday, 17 June 2:28pm) I shared the results of the ligature formation produced by several Devanagari fonts.  I have just completed a revised comparison and thought it would be useful to share the results of this comparison as well.  A PDF of the comparison is available on The Sanskrit Library's Publications page at https://sanskritlibrary.org/publications.html under the title Sanskrit characters: a comparison of 12 fonts and their coverage of conjuncts.  As previously I compared 1260 ligatures formed by the LaTeX Skt package with seven Unicode fonts.  The ligatures compared were the combined set of all those listed by Ulrich Stiehl in his document, Conjunct Consonants in Sanskrit, Heidelberg, 21 April 2003, pp. 4--34, and those listed in the Skt package documentation Sanskrit for LaTeX2e, pp. 22--35.  The fonts compared this time add Siddhanta, Sanskrit2020, Shobhika-Regular, and Shobhika-Bold.  The full list is as follows:



1. LaTeX Skt package

2. Chandas

3. Uttara

4. Siddhanta

5. Sanskrit2003

6. Sanskrit2020

7. Shobhika-Regular

8. Shobhika-Bold

9. Praja

10. Arial Unicode MS

11. Devanagari MT

12. Mangal



The LaTeX Skt package comes with the TeXLive installation available at https://www.tug.org/texlive/.  The Chandas, Uttara, and Siddhanta fonts were produced by Mihail Bayaryn.  The first two are available at http://www.sanskritweb.net/cakram/; all three are linked to http://svayambhava.blogspot.com/p/siddhanta-devanagariunicode-open-type.html.  The Sanskrit2003 font was produced by Ulrich Stiehl and is available at http://www.omkarananda-ashram.org/Sanskrit/itranslator2003.htm, and the Sanskrit2020 font is an updated version of it that includes the VedicExtensions Unicode block to accommodate Vedic accents available at https://sourceforge.net/projects/advaita-sharada-font/files/Devanagari/.  These fonts are all available free of cost.  Praja was produced by Peter Freund and is available for $35 at https://secure.bmtmicro.com/servlets/Orders.ShoppingCart?CID=5115 <https://secure.bmtmicro.com/servlets/Orders.ShoppingCart?CID=5115&PRODUCTID=51150002> &PRODUCTID=51150002.  Arial Unicode MS is available with Microsoft Office, FrontPage and Publisher, with the installation of international support.  Devanagari MT is available with Mac systems with the Asian languages support.  Mangal is available with Windows systems with supplemental language support.



The comparison showed that the Shobhika fonts (Regular and Bold) are able to produce all conjuncts correctly, without the interruption of an inappropriate virāma, with the exception of two ṭty and ṭṣṭh.  Siddhanta excepts just four: ṅkṣṇv, ṅkhn, ddbr, l̃l.  Chandas and Uttara are able to form all conjuncts correctly with the exception of seven sequences: ṅkṣṇv, ṅrvy, ṭhthy, dḍḍ, ddbr, ddvr, l̃l.  The LaTeX Skt package handles all but 29.  Sanskrit 2003 lacked 82, Sanskrit 2020 lacks 81, Praja 187, Arial Unicode MS 202, Devanagari MT 232, and Mangal 236.



I also checked the behavior of the fonts in handling the accents in the Devanagari extended, and Vedic extensions Unicode pages.  Only Praja font handled them all properly, the LaTeX Skt package handles most Vedic accentuation, Sanskrit 2020 handles all but the Maitrāyaṇī Saṁhitā midstroke.  Shobhika handles all but this and the Samaveda accents.  Most fonts handled only the common accentual system.  A test of Vedic accents with any font can be performed by visiting the Sanskrit Library's interactive Vedic Unicode character phonetic value table at http://sanskritlibrary.org/accents.html.  Simply set your browser to use the font you would like to test.



The first eight fonts listed, i.e. Shobhika, Siddhanta, Chandas, Uttara, LaTeX Skt, Sanskrit 2003 and 2020, and Praja, are therefore commendable; the last three are inadequate for Sanskrit.  Mihail Bayaryn's fonts use private code points to handle accents.  It would be desirable for him to upgrade his fonts, which otherwise handle conjuncts very comprehensively, to handle the Vedic characters in the two Unicode pages mentioned including in particular the combining candrabindu with semivowels l, y, and v.



Other Indic fonts not tested are described on the University of Chicago's South Asia Language Resource Center page at http://salrc.uchicago.edu/resources/fonts/available/hindi/.



Yours,

Peter

******************************

Peter M. Scharf, President

The Sanskrit Library

scharf at sanskritlibrary.org <mailto:scharf at sanskritlibrary.org> 

https://sanskritlibrary.org

******************************

Peter Scharf

scharfpm7 at gmail.com <mailto:scharfpm7 at gmail.com> 




_______________________________________________
INDOLOGY mailing list
INDOLOGY at list.indology.info <mailto:INDOLOGY at list.indology.info> 
https://list.indology.info/mailman/listinfo/indology

-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20230711/004500b9/attachment.htm>
