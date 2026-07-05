+++
title = "106 Claudius Teodorescu"
date = "2023-07-29"
upstream_url = "https://list.indology.info/pipermail/indology/2023-July/057958.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2023-July/057958.html)

An *ngram index* would also help.

For instance, by using such an index for a corpus with misspelled words,
which are transliterations from Sanskrit and other languages, for searching
for *tattva*, among other results one can see: *tattva?, tattvaj, tattvam*,
*tattvas*, *?tmatattvam*, *?tmatattvam?*, *?tadbh?vatattvam*,
*?r?tattvanidhi*, *?ivatattvaratn?kara*.

The ngram index uses a similarity threshold, which can be used to filter
out the results that are too different.

For the case you mentioned, I think that, by using an ngram index,
searching for *buddha* would surely return *budha, bauddha*, and even
*buddhist*, depending of the similarity threshold.

Claudius

On Sat, 29 Jul 2023 at 12:56, Jan Kučera <jan.kucera at ujca.cz> wrote:

> There is a lot of catalogues and search interfaces produced by different
> people with different levels of training in different disciplines, over a
> long time of development of software capabilities. Some will be better,
> some will be worse. And different libraries will choose different
> transliteration rules.
>
>
>
> MARC models: https://www.loc.gov/marc/bibliographic/ecbdmulti.html
>
> BIBFRAME notes: https://guides.loc.gov/bibframe-manual/non-latin-scripts
>
>
>
> The same way search can be made case insensitive, it can be made accent
> insensitive, making your two propositions discoverable either way:
>
>
>
>
>
> Both Google and Bing seem to be happy to ignore some diacritics but not
> others (in the example above, they do not have any results for the ASCII
> version). This evolves and changes with time.
>
>
>
> As for being able to find misspelled entries, it again depends on the
> catalogue and its search engine. Putting aside recent models you can train
> with data of your choice, there is an old deterministic algorithm called
> SOUNDEX <https://en.wikipedia.org/wiki/Soundex>, which would match
> “budha” with “bauddha” (however not “buddhist”). Both SQL and MySQL have
> SOUNDEX function built in. These databases can also perform accent
> insensitive search (and you do not need to change the database schema in
> order to do so).
>
>
>
> People who put manuscripts on-line are therefore limited by the
> capabilities of the interfaces they will be indexed and accessed through,
> and which often conflict with each other. I would suggest the best practice
> is to include the text in the original script if possible and specify the
> script (ISO 15924 <https://www.unicode.org/iso15924/iso15924-codes.html>)
> and the language (ISO 639 <https://iso639-3.sil.org/code_tables/639/data>)
> separately in the metadata. This records all the necessary information that
> future search engines can utilize. If providing
> transliteration/transcription, be consistent with the rules and note which
> schema you are using. (And obviously use Unicode.)
>
>
>
> Best regards,
>
> Jan Kučera
>
> *ल* Institute of South and Central Asia Students, Prague
>
>
>
>
>
> *From:* INDOLOGY <indology-bounces at list.indology.info> *On Behalf Of *Harry
> Spier via INDOLOGY
> *Sent:* Saturday, July 29, 2023 12:27 AM
> *To:* indology at list.indology.info
> *Subject:* [INDOLOGY] CORRECTION: Important point about online manuscripts
>
>
>
> Jonathan Silk brought up an important point about on-line manuscripts when
> he showed how spelling affects whether an online manuscript is found or
> not. Of course his example "Bauddha Gamartha Samgraha" showed how a title
> prevented finding a manuscript.  But those of us who work in putting
> manuscripts on-line do so, not just so they'll be found by members of lists
> we make announcements to, but hopefully that they may be found many years
> in the future, so to me the question is how do we title on-line manuscripts
> and what metadata do we associate with them so they will be found in
> searchs (perhaps decades in the future)..
>
>
>
> For example picking a manuscript title at random *aṃśumatkāśyapāgama* .
>
> Should the file name be the exact title in IAST i.e*. *
> *aṃśumatkāśyapāgama.txt*
>
> Should the file name be the exact title but without diacriticals i.e*. *
> *amsumatkasyapagama.txt*
> Does header data within the text file and written at its beginning such as
> exact title or alternate title affect whether it is found in searchs?
>
> Should the file have metadata? I.e. should the text file have an html or
> xml wrapper with metadata of its title in HK, Velthuis, devanagari? And in
> this case its alternate title aṃśumadāgama .?
>
> Are there other ways that will help the etext to be found even if the
> search itself is mispelled?
>
>
>
> Note: I'm asking these questions not in the context of "best manuscript
> transcription practices" but just in what will help an etext be found in
> google searchs. Does Google even say anything about how to maximize this?
>
> Thanks,
>
> Harry Spier
>
>
>
> On Wed, Jul 26, 2023 at 3:34 PM Jonathan Silk via INDOLOGY <
> indology at list.indology.info> wrote:
>
> Ron is not kidding. I searched for "Buddhist," nothing, then "bauddha" and
> got --I'm not making this up:
> Bauddha Gamartha Samgraha.
>
>
>
> bauddhāgama... okaaay
>
>
>
> On Wed, Jul 26, 2023 at 9:20 PM Davidson, Ronald M. <
> RDavidson at fairfield.edu> wrote:
>
> I appreciate everyone’s input on manuscript collections.
>
> Perhaps I overlooked it’s notice by others, but this rather idiosyncratic
> collection came to my attention some time ago:
> http://indianmanuscripts.com/
>
> It bills itself as the largest collection of Indian manuscripts and
> antique books. There are some valuable items, but the romanization is via
> the North Indian/Hindi pronunciation one sometimes finds in Archive.org as
> well. Consequently, items are a bit challenging to spot from time to time.
>
> Best wishes,
> Ron
>
> ________________________________
> Ronald M. Davidson, Ph.D.
> Professor of Religious Studies
> 345 Donnarumma Hall
> Fairfield University, 1073 North Benson Road
> Fairfield CT 06824-5195, U.S.A.
> 203-254-4000 x 2489
>
>
>
> From: INDOLOGY <indology-bounces at list.indology.info> on behalf of Dominik
> Wujastyk via INDOLOGY <indology at list.indology.info>
> Reply-To: Dominik Wujastyk <wujastyk at gmail.com>
> Date: Wednesday, July 26, 2023 at 1:19 PM
> To: Timothy Cahill <tccahill at loyno.edu>
> Cc: "Indology (indology at list.indology.info)" <indology at list.indology.info>
> Subject: Re: [INDOLOGY] Manuscript collections on archive.org
>
> Thanks for this Tim. Links to the resources you mention are already there
> in the listing at http: //indology. info/external-resources, afaik. The way
> information is presented is far from clear: I'm trying to get an upgrade to
> the Wordpress
>
> Thanks for this Tim.  Links to the resources you mention are already there
> in the listing at http://indology.info/external-resources<
> https://urldefense.com/v3/__http:/indology.info/external-resources__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSllw06S9$>,
> afaik.  The way information is presented is far from clear: I'm trying to
> get an upgrade to the Wordpress plugin, in the hope of improving
> presentation.
>
> About the Asiatic Society of Mumbai, some of their MSS could be found at
> archive.org<
> https://urldefense.com/v3/__http:/archive.org__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSuTMMfsO$>
> by searching in Devanagari, but I think they have been taken down.
>
> Best,
> Dominik
>
> On Tue, 25 Jul 2023 at 17:37, Timothy Cahill <tccahill at loyno.edu<mailto:
> tccahill at loyno.edu>> wrote:
> Greetings,
>    The  Lalcand Research Library (originally in Lāhore) of D.A.V. College,
> Chandigarh has a large collection, some of which was previously available
> on archive.org<
> https://urldefense.com/v3/__http:/archive.org__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSuTMMfsO$>.
> The manuscripts that I downloaded a few years back came with a full roman
> transcription as well as translations. Current web site:
> https://www.davchd.ac.in/lcrl<
> https://urldefense.com/v3/__https:/www.davchd.ac.in/lcrl__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSpaa1g5t$
> >
>     A MS from the Asiatic Society of Mumbai was also available on
> archive.org<
> https://urldefense.com/v3/__http:/archive.org__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSuTMMfsO$>
> some years back, but it too has disappeared from there and (likely) been
> integrated into their new site at:
> https://www.asiaticsociety.org.in/index.php/holdings/manuscripts<
> https://urldefense.com/v3/__https:/www.asiaticsociety.org.in/index.php/holdings/manuscripts__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSvyP8Ipm$
> >
> This site requires registration and the payment of a fee as an annual
> subscription.
>    One note about the Penn collection: it is integrated into the worldcat
> site, so a search for a book will also bring up notices of the Penn
> collection, plus links that bring you directly to the digitized images.
> Best wishes,
> Tim Cahill
>
>
> On Tue, Jul 25, 2023 at 3:25 PM Dominik Wujastyk via INDOLOGY <
> indology at list.indology.info<mailto:indology at list.indology.info>> wrote:
> Deepest thanks to everyone who has sent me further links for the list of
> "Online Libraries of Scanned Manuscripts" at INDOLOGY.info.  I'm using a
> cheap-and-cheerful plugin for Wordpress that doesn't allow manual
> rearrangement of the list items.  So it's a bit of a grab-bag.
>
> Best,
> Dominik
>
>
> Dominik Wujastyk
> INDOLOGY list<
> https://urldefense.com/v3/__http:/indology.info__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSq1FwWDK$>
> committee member
> Please do not reply to me personally: reply to
> indology-owner at list.indology.info<mailto:indology-owner at list.indology.info
> >
>
> On Tue, 25 Jul 2023 at 13:23, Dominik Wujastyk <wujastyk at gmail.com<mailto:
> wujastyk at gmail.com>> wrote:
> already there, via Colenda.  What is the relationship between UPenn's
> Colenda and OPenn?
>
> On Tue, 25 Jul 2023 at 08:50, Eric Moses Gurevitch via INDOLOGY <
> indology at list.indology.info<mailto:indology at list.indology.info>> wrote:
> In addition to the already-mentioned repositories, Penn Libraries has
> digitized almost 3000 South Asian manuscripts:
> https://openn.library.upenn.edu/html/indic_contents.html<
> https://urldefense.com/v3/__https:/openn.library.upenn.edu/html/indic_contents.html__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSmm83kw7$
> >
>
> Take care,
> Eric
>
> On Tue, Jul 25, 2023 at 9:13 AM Matthew Kapstein via INDOLOGY <
> indology at list.indology.info<mailto:indology at list.indology.info>> wrote:
> There's also a nice collection of Sanskrit mss. from Cambridge U. :
> https://cudl.lib.cam.ac.uk/collections/sanskrit/1<
> https://urldefense.com/v3/__https:/cudl.lib.cam.ac.uk/collections/sanskrit/1__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CShcl01D3$
> >
>
> The Gallica database of the Bibliotheque nationale de France also includes
> scans of many Skt. and other Indic mss., but I haven't found an easy way to
> globally search Skt. alone. Here's the general site:
> https://gallica.bnf.fr/accueil/en/content/accueil-en?mode=desktop<
> https://urldefense.com/v3/__https:/gallica.bnf.fr/accueil/en/content/accueil-en?mode=desktop__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSoB8mRef$
> >
>
> And, if anyone cares to look up the details and post them, the Endangered
> Archives programme of the British Library (https://eap.bl.uk/<
> https://urldefense.com/v3/__https:/eap.bl.uk/__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSl4EoJt9$>)
> has scanned quite a lot of Pali and probably some Sanskrit as well (not to
> mention Tibetan, Mongolian, etc.).
>
> The Buddhist Digital Archives (https://library.bdrc.io/<
> https://urldefense.com/v3/__https:/library.bdrc.io/__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSnNHHHR3$>),
> though specializing in Tibetan, has recently branched out to include Pali,
> Sanskrit, and SE Asian languages, though I am not yet clear about what part
> of these additions are redirects to other databases.
>
> Matthew T. Kapstein
> Professor emeritus
> Ecole Pratique des Hautes Etudes, PSL Research University, Paris
>
> Associate
> The University of Chicago Divinity School
>
> https://ephe.academia.edu/MatthewKapstein<
> https://urldefense.com/v3/__https:/ephe.academia.edu/MatthewKapstein__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSrNbNEQz$
> >
>
> Sent with Proton Mail<
> https://urldefense.com/v3/__https:/proton.me/__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CStXUS1wn$>
> secure email.
>
> ------- Original Message -------
> On Tuesday, July 25th, 2023 at 3:48 PM, Giovanni Ciotti via INDOLOGY <
> indology at list.indology.info<mailto:indology at list.indology.info>> wrote:
>
>
> Dear all,
>
> I've recently become aware of this one (registration required):
> https://lucknowdigitallibrary.com/publication-category/manuscripts<
> https://urldefense.com/v3/__https:/lucknowdigitallibrary.com/publication-category/manuscripts__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSjduIswz$
> >
>
> All best,
> Giovanni
>
> - - -
> Dr. Giovanni Ciotti
> Spokesperson
> The Palm-Leaf Manuscript Profiling Initiative (PLMPI)
> (
> https://www.csmc.uni-hamburg.de/written-artefacts/working-groups/plmpi.html
> <
> https://urldefense.com/v3/__https:/www.csmc.uni-hamburg.de/written-artefacts/working-groups/plmpi.html__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSkdIhime$
> >)
> Cluster of Excellence - Understanding Written Artefacts
> Warburgstraße 26
> 20354 Hamburg
> Germany
>
>
> On Tue, 25 Jul 2023 at 10:56, Royce Wiles via INDOLOGY <
> indology at list.indology.info<mailto:indology at list.indology.info>> wrote:
> Admittedly NOT on archive.org<
> https://urldefense.com/v3/__http:/archive.org__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSuTMMfsO$>,
> however, the Jain elibrary
>
> https://jainelibrary.org/<
> https://urldefense.com/v3/__https:/jainelibrary.org/__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSjDvUeyZ$
> >
>
> (free registration required for full access)
>
> has scanned and uploaded around 800 manuscripts (seemingly exclusively
> Jain texts) (findable in the category on the left of the site) as well as
> the 16,899 ‘books’ on the site and 6,000+ ‘articles’
>
>
>
> On 25 Jul 2023, at 20:25, Christophe Vielle via INDOLOGY <
> indology at list.indology.info<mailto:indology at list.indology.info>> wrote:
>
> There is also
> Chunilal Gandhi Vidyabhavan, Surat, Pandit Shivadatta Shukla collection
>
> https://archive.org/search?query=creator%3A%22Chunilal+Gandhi+Vidyabhavan+Surat%22
> <
> https://urldefense.com/v3/__https:/archive.org/search?query=creator*3A*22Chunilal*Gandhi*Vidyabhavan*Surat*22__;JSUrKysl!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSvg4hoGj$
> >
>
>
> Le 24 juil. 2023 à 22:38, Harry Spier via INDOLOGY <
> indology at list.indology.info<mailto:indology at list.indology.info>> a écrit :
>
> Dear list members,
> Has anyone compiled a list of manuscript collections on archive.org<
> https://urldefense.com/v3/__http:/archive.org/__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSvkhyxNi$>.
> I'm of course aware of egangotri, but I would appreciate it if members
> could give me references to other collections of original manuscripts.
> Thanks,
> Harry Spier
>
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info<mailto:INDOLOGY at list.indology.info>
> https://list.indology.info/mailman/listinfo/indology<
> https://urldefense.com/v3/__https:/list.indology.info/mailman/listinfo/indology__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSpDM7ZWw$
> >
>
> –––––––––––––––––––
> Christophe Vielle<
> https://urldefense.com/v3/__https:/uclouvain.be/en/directories/christophe.vielle__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSvTIz19-$
> >
> Louvain-la-Neuve
>
>
>
>
>
>
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info<mailto:INDOLOGY at list.indology.info>
> https://list.indology.info/mailman/listinfo/indology<
> https://urldefense.com/v3/__https:/list.indology.info/mailman/listinfo/indology__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSpDM7ZWw$
> >
>
>
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info<mailto:INDOLOGY at list.indology.info>
> https://list.indology.info/mailman/listinfo/indology<
> https://urldefense.com/v3/__https:/list.indology.info/mailman/listinfo/indology__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSpDM7ZWw$
> >
>
>
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info<mailto:INDOLOGY at list.indology.info>
> https://list.indology.info/mailman/listinfo/indology<
> https://urldefense.com/v3/__https:/list.indology.info/mailman/listinfo/indology__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSpDM7ZWw$
> >
>
>
> --
>
> Eric Moses Gurevitch
>
> National Endowment for the Humanities Postdoctoral Fellow
>
> Vanderbilt University
>
> eric.m.gurevitch at vanderbilt.edu<mailto:eric.m.gurevitch at vanderbilt.edu>
>
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info<mailto:INDOLOGY at list.indology.info>
> https://list.indology.info/mailman/listinfo/indology<
> https://urldefense.com/v3/__https:/list.indology.info/mailman/listinfo/indology__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSpDM7ZWw$
> >
>
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info<mailto:INDOLOGY at list.indology.info>
> https://list.indology.info/mailman/listinfo/indology<
> https://urldefense.com/v3/__https:/list.indology.info/mailman/listinfo/indology__;!!KIFmrYtlezdzESbnm_I!G8N2kAYTlbp44IXQeE_dWSczSMHlu4_dQk7xroKmRRFSNT8rZx8uf2raVorV_Sk8cyA49ulYrhFwovqCowh-Ze5CSpDM7ZWw$
> >
>
>
> --
> Timothy C. Cahill, PhD
> स:, तम्, तेन, तस्मै, तस्मात्, तस्य, तस्मिन्
> Associate Professor
> Department of Religious Studies
> Loyola University New Orleans
> 6363 St. Charles Ave.
> New Orleans, Louisiana  70118
> USA
>
>
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info
> https://list.indology.info/mailman/listinfo/indology
>
>
>
> --
>
> Prof. dr. J.A. Silk
> Leiden University
>
> Leiden University Institute for Area Studies, LIAS
>
> Matthias de Vrieshof 3, Room 0.05b
>
> 2311 BZ Leiden
>
>
>
> website: www.OpenPhilology.eu
>
> copies of my publications may be found at
>
> https://leidenuniv.academia.edu/JASilk
>
>
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info
> https://list.indology.info/mailman/listinfo/indology
>
>
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info
> https://list.indology.info/mailman/listinfo/indology
>


-- 
Cu stimă,
Claudius Teodorescu
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20230729/2fcf168e/attachment.htm>
-------------- next part --------------
A non-text attachment was scrubbed...
Name: image002.png
Type: image/png
Size: 27460 bytes
Desc: not available
URL: <https://list.indology.info/pipermail/indology/attachments/20230729/2fcf168e/attachment.png>
-------------- next part --------------
A non-text attachment was scrubbed...
Name: image003.png
Type: image/png
Size: 27970 bytes
Desc: not available
URL: <https://list.indology.info/pipermail/indology/attachments/20230729/2fcf168e/attachment-0001.png>
