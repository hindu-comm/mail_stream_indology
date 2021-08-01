+++
title = "07 Dominik Wujastyk"
date = "2010-07-06"
upstream_url = "https://list.indology.info/pipermail/indology/2010-July/034567.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2010-July/034567.html)

Dear Timothy,

Yes (I presume you don't mean my typo, "vīrsena"), e.g., 4 is where the
Somdev Vasudev's RomDev mapping is used.  Here's the procedure.


   1. The actual mapping file is published by Somdev in his blog, here:
   http://sarasvatam.blogspot.com/2010/03/updated-teckit-romdev.html
   2. Cut and paste this text, and save it in a Unicode file called
   RomDev.map.  Save that file in a place which XeTeX can "see," e.g.,
   something like local/texmf/fonts/misc/xetex/fontmapping/
   3. You now need to compile the human-readable *.map file into a binary
   *.tec file, so that XeTeX can read it directly.  This is done by the program
   Teckit<http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&cat_id=TECkit>,
   which you can get here:

   http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&item_id=TECkitDownloads
   4. I'm working with Ubuntu GNU/Linux.  For me, the command is,
   *teckit_compile RomDev.map -o RomDev.tec
   *
   I'm afraid I don't know the Windows or Mac command invocation.
   5. Now you have a file in a place like
   local/texmf/fonts/misc/xetex/fontmapping/RomDev.tec
   6. Run the command that rebuilds the database of files that TeX knows
   about.  In Linux it's
   *sudo mktexlsr*
   7. That's it!  XeTeX can now see, and make use of the RomDev mapping,
   that converts Unicode transliteration into Devanāgarī.

Best,
Dominik

PS I've copied this posting to my blog, for reference:

   -
   http://cikitsa.blogspot.com/2010/07/how-do-i-install-romdev-mapping-for.html

On 6 July 2010 18:13, TIMOTHY P. LIGHTHISER <tlighthiser at gmail.com> wrote:

> Hi!
>
> Thanks for the sample file.
>
> Everything appeared correctly in the pdf, except the text in the fourth
> sample.
>
> If I may, how does one put to use Somadeva's mapping?
>
> t
>
>
>
>
>
>
>
>
>
>
>
> On Tue, Jul 6, 2010 at 7:31 AM, Dominik Wujastyk <wujastyk at gmail.com>
> wrote:
> > Dear colleagues,
> >
> > A number of you have been kind in your responses to my blog post about
> using
> > XeLaTeX to do Devanagari, so I've gone further and posted a mini-edition
> > that exemplifies the use of the previous stuff (Unicode romanisation
> input,
> > with Nagari output), as well as the Ledmac system for formatting a
> critical
> > edition.  The materials are here:
> >
> >   -
> >
> http://cikitsa.blogspot.com/2010/07/minimal-edition-of-sanskrit-verse-using.html
> >
> > Best,
> > Dominik
> >
> > Dr Dominik Wujastyk
> > Institut für Südasien-, Tibet- und Buddhismuskunde
> > Universität Wien
> > Spitalgasse 2-4, Hof 2, Eingang 2.1
> > A-1090 Vienna
> > Austria
> >
>
>
>
> --
> Timothy P. Lighthiser
> 1263 33rd Avenue
> San Francisco, CA 94122-1302
> USA
>



