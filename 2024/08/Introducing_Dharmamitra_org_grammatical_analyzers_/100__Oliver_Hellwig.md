+++
title = "100 Oliver Hellwig"
date = "2024-08-30"
upstream_url = "https://list.indology.info/pipermail/indology/2024-August/059597.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2024-August/059597.html)

Dear all,

just a brief follow up to Sebastian's mail: the analysis system (i.e.
the algorithm called by the inference script) has roughly the same error
rate as a single human annotator. Very practically, this means that you
can now analyze your own Sanskrit text collection(s) offline at the
levels of lexicon and morpho-syntax, store the results, and create, for
example, your own thesaurus or whatever you have in mind.

Best, Oliver

---

Oliver Hellwig, IVS Zurich

On 29/08/2024 00:15, Sebastian Nehrdich via INDOLOGY wrote:
> Dear List members,
>
> This is to briefly introduce dharmamitra.org <http://dharmamitra.org/>,
> a project lead by Kurt Keutzer and myself at BAIR, UC Berkeley,
> focussing on providing various GenAI-driven applications for classical
> Asian languages.
>
> We recently finished work on a set of neural Sanskrit grammatical
> analyzer tools together with Oliver Hellwig based on the annotations of
> the DCS. This annotation system is now part of the interactive interface
> at dharmamitra.org <http://dharmamitra.org/>: When typing Sanskrit input
> into the translation box, a button with the label 'grammar' appears
> below the translation box and when clicking on this, the analyzed
> Sanskrit sentences become visible. This tools currently provides word
> segmentation, lemmatization and morphosyntactic tagging.
>
> We also have inference scripts for this system on this github repository
> for those of you who want to run the tools independently on theirown
> machine (a GPU is advisable as it might otherwise be very slow):
> https://github.com/sebastian-nehrdich/sanskrit-analyzers <https://
> github.com/sebastian-nehrdich/sanskrit-analyzers>
> Among these applications you will also find dependency parsing for Vedic
> Sanskrit, a function we do not yet support interactively on the website,
>
> A publication on the architecture, data etc. used for these tools is
> currently on the way.
>
> We also are open to providing API access for individuals and projects
> that would like to use these tools in their workflow. Feel free to
> contact us if you are interested!
>
> Dharmamitra.org also works on providing machine translation capabilities
> for Sanskrit into English and other languages. In case you are
> interested in this topic and would like to learn more, perhaps even
> collaborate or contribute in some way, feel free to reach out to us. We
> are more than happy to work together with people that want to explore
> the possibilities of this technology.
>
> With best wishes,
>
> Sebastian Nehrdich
>
>
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info
> https://list.indology.info/mailman/listinfo/indology

