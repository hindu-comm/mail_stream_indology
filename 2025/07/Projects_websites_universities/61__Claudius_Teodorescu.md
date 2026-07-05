+++
title = "61 Claudius Teodorescu"
date = "2025-07-18"
upstream_url = "https://list.indology.info/pipermail/indology/2025-July/060842.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2025-July/060842.html)

Dear all,

To add just a small technological note to what Dominik rightfully mentioned
above, I would like to point that, even if it is not so famous, GitLab
offers slightly more features than GitLab. Disclaimer: I am not associated
in any way with GitLab, but I am just sharing the conclusions I got after
publishing 16 digital resources (dictionaries, dictionary corpus, GRETIL
search interface, and a search interface for the Indology mailing list).

Besides the more convenient technical features GitLab has, it features a
community edition which can be installed anywhere, by anyone. And this is
pure gold for the research projects, especially after the funding is over.

At the Academy of Mainz, Germany, where I currently work, ALL the digital
resources we produce are stored in Git-type repository, in a GitLab server
that is made available at the land's level, for academic purposes. When I
worked with the Heidelberg University we had a GitLab instance, too, for
the digital resources we developed. This is also currently the case with
the universities or university libraries, respectively, of Bielefeld,
Dresden, Paderborn, and I am sure for others in Germany. I think this is a
model that can be successfully used.

So, my technical advice would be:
1. Use Git-type repositories for research data of any kind: raw research
data (scans, audio files, etc.), processed research data (transcriptions in
TEI format, etc.), and published research data (transcriptions in HTML
format, static indexes for searching in the browser, audio files in
web-friendly formats, images in web-friendly formats, etc.).
2. Separate the raw and processed data to the published data, by storing
the published data only in Pages storage and regenerating it from the
processed data at any change of the processed data. Do not store data in
the publishing format, which is usually HTML.
3. Keep the research data in a repository that is separated to the
repository with the static website that presents the digital resource In
this way, one can have more views of the data, namely: more publishing
formats (HTML, PDF, ePub), linking of the respective digital resource with
other resources, in a corpora, etc. Also, one will not have to process
again the data for every tiny change of the presentation website.

Key concepts to take away: *Git Storage of data*, *static publishing of
data*.

Examples of static digital resources that I published (the search is done
with an in-browser search engine I made and static indexes):
Search interface for the GRETIL corpus
<https://claudius-teodorescu.gitlab.io/gretil-corpus-site/>
Search interface for the Indology mailing list
<https://wujastyk.github.io/INDOLOGY-forum-website/>

Best regards,
Claudius Teodorescu

On Fri, 18 Jul 2025 at 02:32, Dominik Wujastyk via INDOLOGY <
indology at list.indology.info> wrote:

> The recent scare about the Nepal-German descriptive cataloguing data has
> yet again shown that universities are unreliable hosts for the preservation
> of digital resources.  Long-term members of this forum might remember when
> U. Washington shockingly unplugged Blackbox
> <https://blackbox.hacc.washington.edu/>, a major repository of
> Indological texts, fonts, and software in the 1990s, maintained by Tom
> Ridgeway. The Indology website and archive of etexts used to live on a
> machine at UCL, but it was closed after I left  that university, without
> consulting or warning me.  The University of Cambridge refused to continue
> hosting John Smith's Bombay website when he retired.  The Indology website
> has been able to take over <https://bombay.indology.info/> the hosting of
> that incredibly valuable asset (think: Pabuji, fonts, software,,
> Mahābhārata, Rāmāyana) .  There are many more examples of websites and
> archives being just shut down when faculty members move, or a couple of
> years after project funding ends.
>
> I don't have a great answer to any of this.  But I do think that the
> persistence of digital assets is a vital question for us all and something
> we should all think about carefully if we put valued resources on the
> internet.
>
> For example, the results of my last funded project are accessible through
> http://sushrutaproject.org.  I have tried to push as much important stuff
> as I can tot Github and Zenodo (and http://archive-it.org).  But as soon
> as I stop paying personally for the registration and hosting at
> sushrutaproject.org that gateway website will close down within a few
> weeks.  Do I really want to keep paying, out of my pocket, for the rest of
> my life?
>
> For the new project that I announced yesterday, I've built the website at
> Github.  This costs nothing, so the worry about annual payments is gone.
> And as far as I can tell from reading the Github documentation, they do not
> delete project repositories, even if they become inactive.  If repositories
> are "archived" they simply become read-only (docs
> <https://docs.github.com/en/repositories/archiving-a-github-repository/archiving-repositories>).
> Github seems very enlightened about long-term preservation.  They save
> offline archives at the bottom of a mineshaft in Svalbard - I kid you not.
> There are many good features for project work at Github, and it's all
> free.  Building a simple one-page website is also extremely quick and
> easy.  Building something more complicated, with menus etc., is more
> troublesome.  It's significantly harder than using Wordpress (the Microsoft
> Word of website creation).  But the up-side is that you get a website that
> will persist for years and doesn't require payment.
>
> Within the university world, departments and computing centres are not
> going to look after project data and websites in the long term.  The one
> institution that actually does think long-term is the university library.
> But as far as I can tell, most university libraries are still working out
> what their place is in the digital landscape.
>
>
> Best,
> Dominik
>
>
> --
> Dominik Wujastyk, Professor Emeritus, Classical Indian History
> University of Alberta
>
> "The University of Alberta is committed to the pursuit of truth,
> the advancement of learning, and the dissemination of knowledge
> through teaching, research and other scholarly and creative activities and
> service."
> -- Collective Agreement
> <https://www.ualberta.ca/human-resources-health-safety-environment/media-library/my-employment/agreements/2020-2024-collective-agreement---working-version.pdf>
> 3.01
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
URL: <https://list.indology.info/pipermail/indology/attachments/20250718/d4ea76e4/attachment.htm>
