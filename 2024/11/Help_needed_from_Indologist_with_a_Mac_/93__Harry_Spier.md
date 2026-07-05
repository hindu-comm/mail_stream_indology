+++
title = "93 Harry Spier"
date = "2024-11-27"
upstream_url = "https://list.indology.info/pipermail/indology/2024-November/059883.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2024-November/059883.html)

Thank you Jan for identifying the problem.
Harry Spier

On Wed, Nov 27, 2024, 4:36 AM Jan Kučera <jan.kucera at ujca.cz> wrote:

> And the reason for that is because the files contain invalid UTF-8
> characters. You might be good without BOM if you fix the broken files.
>
>
>
> As an example, in advayatArakopaniSat-M00102-IAST.txt, line 31 has “pūrṇ
> amadaḥ *�* iti śāntiḥ” where the middle character is supposed to be dash
> I assume, but it is not UTF-8 encoded. I attach list of all the files with
> invalid characters.
>
>
>
> Also note that the following links are broken on the individual files page:
>
>
>
> kedārakalpa
> <https://muktalib7.com/DL_CATALOG_ROOT/MUKTABODHA-LIBRARY-IAST/kedArakalpa-M00671-IAST.txt>
>
> tatvaśodhanam
> <https://muktalib7.com/DL_CATALOG_ROOT/MUKTABODHA-LIBRARY-IAST/tatvazodhanam-M00655-IAST.txt>
>
> bṛhattantrasāra
> <https://muktalib7.com/DL_CATALOG_ROOT/MUKTABODHA-LIBRARY-IAST/bRhattantrasAra-M00013-IAST.txt>
>
> śrīcakrasādhanam
> <https://muktalib7.com/DL_CATALOG_ROOT/MUKTABODHA-LIBRARY-IAST/zrIcakrasAdhanam-M00652-IAST.txt>
>
> śrīvidyānityapaddhati
> <https://muktalib7.com/DL_CATALOG_ROOT/MUKTABODHA-LIBRARY-IAST/zrIvidyAnityapaddhati-M00654-IAST.txt>
>
>
>
> Hope this helps.
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
>
>
> *From:* INDOLOGY <indology-bounces at list.indology.info> *On Behalf Of *Jan
> Kucera
> *Sent:* středa 27. listopadu 2024 9:51
> *To:* Harry Spier <vasishtha.spier at gmail.com>; indology at list.indology.info
> *Subject:* Re: [INDOLOGY] Help needed from Indologist with a Mac.
>
>
>
> Dear Harry,
>
>
>
> I confirm that some of the files are opened with wrong encoding in
> TextEdit. Unfortunately, TextEdit refuses to open it with UTF-8 when you
> pick it manually.
>
>
>
> You could fix this by including a BOM mark at the beginning of the file.
> Let me know if you need any assistance.
>
>
>
> Thanks,
>
> Jan
>
>
>
> *From:* INDOLOGY <indology-bounces at list.indology.info> *On Behalf Of *Harry
> Spier via INDOLOGY
> *Sent:* středa 27. listopadu 2024 2:39
> *To:* indology at list.indology.info
> *Subject:* [INDOLOGY] Help needed from Indologist with a Mac.
>
>
>
> Dear list members,
>
> I've just added a feature to the Muktabodha digital library where you can
> download individual files.  These are plain text files encoded in utf-8,
> but I'm getting some feedback that when some users download and open these
> text files, then some files display correctly but in other files the
> characters with diacriticals are not being displayed correctly.
>
>
>
>  I think this is just a Mac problem and (I don't have a Mac and my windows
> computer displays correctly) and I've seen some postings about UTF-8 not
> working in TEXTEDIT.
>
>
>
> Could a Mac user download a few of the etexts from the individual file
> download
>
>
> https://muktalib7.com/DL_CATALOG_ROOT/MUKTABODHA-LIBRARY-IAST/UTF8-TITLE-LINK-LIST.html
>
>
>
> see if some display incorrectly and if they do then in TextEdit change the
> encoding from automatic to UTF-8 and re-open the file.
>
> The instructions I've seen for doing this in  TextEdit are:
>
> In the TextEdit app  on your Mac, choose File > Open, then select the file
> (don’t open it).
>
> Click Options in the lower-left corner of the window.
> Click the Plain Text Encoding pop-up menu and choose an encoding.
>
>
>
> Thanks,
>
> Harry Spier
>
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20241127/53d1c935/attachment.htm>
