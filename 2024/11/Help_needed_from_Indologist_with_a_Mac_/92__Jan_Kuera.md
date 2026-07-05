+++
title = "92 Jan Kučera"
date = "2024-11-27"
upstream_url = "https://list.indology.info/pipermail/indology/2024-November/059882.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2024-November/059882.html)

And the reason for that is because the files contain invalid UTF-8 characters. You might be good without BOM if you fix the broken files.

As an example, in advayatArakopaniSat-M00102-IAST.txt, line 31 has “pūrṇamadaḥ � iti śāntiḥ” where the middle character is supposed to be dash I assume, but it is not UTF-8 encoded. I attach list of all the files with invalid characters.

Also note that the following links are broken on the individual files page:

kedārakalpa<https://muktalib7.com/DL_CATALOG_ROOT/MUKTABODHA-LIBRARY-IAST/kedArakalpa-M00671-IAST.txt>
tatvaśodhanam<https://muktalib7.com/DL_CATALOG_ROOT/MUKTABODHA-LIBRARY-IAST/tatvazodhanam-M00655-IAST.txt>
bṛhattantrasāra<https://muktalib7.com/DL_CATALOG_ROOT/MUKTABODHA-LIBRARY-IAST/bRhattantrasAra-M00013-IAST.txt>
śrīcakrasādhanam<https://muktalib7.com/DL_CATALOG_ROOT/MUKTABODHA-LIBRARY-IAST/zrIcakrasAdhanam-M00652-IAST.txt>
śrīvidyānityapaddhati<https://muktalib7.com/DL_CATALOG_ROOT/MUKTABODHA-LIBRARY-IAST/zrIvidyAnityapaddhati-M00654-IAST.txt>

Hope this helps.

Best regards,
Jan Kučera
ल Institute of South and Central Asia Students, Prague



From: INDOLOGY <indology-bounces at list.indology.info> On Behalf Of Jan Kucera
Sent: středa 27. listopadu 2024 9:51
To: Harry Spier <vasishtha.spier at gmail.com>; indology at list.indology.info
Subject: Re: [INDOLOGY] Help needed from Indologist with a Mac.

Dear Harry,

I confirm that some of the files are opened with wrong encoding in TextEdit. Unfortunately, TextEdit refuses to open it with UTF-8 when you pick it manually.

You could fix this by including a BOM mark at the beginning of the file. Let me know if you need any assistance.

Thanks,
Jan

From: INDOLOGY <indology-bounces at list.indology.info<mailto:indology-bounces at list.indology.info>> On Behalf Of Harry Spier via INDOLOGY
Sent: středa 27. listopadu 2024 2:39
To: indology at list.indology.info<mailto:indology at list.indology.info>
Subject: [INDOLOGY] Help needed from Indologist with a Mac.

Dear list members,
I've just added a feature to the Muktabodha digital library where you can download individual files.  These are plain text files encoded in utf-8, but I'm getting some feedback that when some users download and open these text files, then some files display correctly but in other files the characters with diacriticals are not being displayed correctly.

 I think this is just a Mac problem and (I don't have a Mac and my windows computer displays correctly) and I've seen some postings about UTF-8 not working in TEXTEDIT.

Could a Mac user download a few of the etexts from the individual file download
https://muktalib7.com/DL_CATALOG_ROOT/MUKTABODHA-LIBRARY-IAST/UTF8-TITLE-LINK-LIST.html

see if some display incorrectly and if they do then in TextEdit change the encoding from automatic to UTF-8 and re-open the file.
The instructions I've seen for doing this in  TextEdit are:
In the TextEdit app  on your Mac, choose File > Open, then select the file (don’t open it).
Click Options in the lower-left corner of the window.
Click the Plain Text Encoding pop-up menu and choose an encoding.

Thanks,
Harry Spier
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20241127/4edf09fd/attachment.htm>
-------------- next part --------------
advayatArakopaniSat-M00102-IAST.txt
AgamaprAmANya-M00001-IAST.txt
ahirbudhnya saMhita Volume 1-M00002a-IAST.txt
ahirbudhnya saMhita Volume 2-M00002b-IAST.txt
amRtezvaradikSAvidhi-M00539-IAST.txt
aMzumatkAzyapAgama-M00198-IAST.txt
anAdivIrazaivasaGgraha-M00615-IAST.txt
Anandatantra-M00066-IAST.txt
anuttaraprakAzapaJcAzikA-M0511-IAST.txt
ASTaprakaraNa bhogakArikA-M00005-IAST.txt
ASTaprakaraNa mokSakArikA-M00006-IAST.txt
ASTaprakaraNa nAdakArikA-M00007-IAST.txt
ASTaprakaraNa paramokSanirAsakArikA-M00008-IAST.txt
bhagavadgItA-M00167-IAST.txt
bRhannIlatantra-M00116-IAST.txt
brhattantrasAra-M00013-IAST.txt
devInAmavilAsa-M00166-IAST.txt
devIrahasya-M00310-IAST.txt
dhvajArohaNavarSavarddhanavidhi-M00542-IAST.txt
dhyAnaratnAvali-E0008-IAST.txt
dIkSAprakAza-M00015-IAST.txt
dIkSAvidhi-M00543-IAST.txt
dvizatikAlottara-M00200-IAST.txt
gorakSazataka-M00522-IAST.txt
hAhArAvatantra-M00283-IAST.txt
IzAnazivagurudevapaddhati Volume 1-M00016-IAST.txt
IzAnazivagurudevapaddhati Volume 2-M00017-IAST.txt
IzAnazivagurudevapaddhati Volume 3-M00018-IAST.txt
IzAnazivagurudevapaddhati Volume 4-M00233-IAST.txt
IzvarapratyabhijJAkaumudI-M00053-IAST.txt
IzvarapratyabhijJAvimarzinI-M00019-IAST.txt
IzvarapratyabhijJAvimarzinIvyAkhyA-M00197-IAST.txt
jayAkhyasaMhitA-M00123-IAST.txt
jJAnArNavatantra-M00069-IAST.txt
kaivalyasAra-M00602-IAST.txt
kAlAnalatantra-M00193-IAST.txt
kalpavRkSa-M00051-IAST.txt
kAmaratnatantra-M00239-IAST.txt
kAmezvarIpUjA-M00546-IAST.txt
kaulajJAnanirNaya-M00027-IAST.txt
krIyakramAdyotikA-M00126-IAST.txt
kriyAsAra volume 2-M00050-IAST.txt
kubjikAguhyezvarIpUjApaddhati-M00547-IAST.txt
kubjikAgurumaNDalapUjA-M00548-IAST.txt
kubjikApUjA-M00549-IAST.txt
kubjikAtantra-M00030-IAST.txt
kulamuktikallolinI-M00318-IAST.txt
kulapradIpa-M00068-IAST.txt
lakSmItantra-M00206-IAST.txt
lalitaasahasranaama-M00057-IAST.txt
lallezvarIvAkyAni-M00032-IAST.txt
mahAnayaprakAza-M00033-IAST.txt
mahAnayaprakAza-M00034-IAST.txt
mahAnirvAnatantra-M00049-IAST.txt
mahApratyaGgIrA-M00552-IAST.txt
mahAvAkyopaniSat-M00109-IAST.txt
mahotsavavidhikrama-M00131-IAST.txt
makuTAgama-M00036-IAST.txt
mAlinIvijayavArtika-M00158-IAST.txt
matatrayaikyaprakAzikA-E0009-IAST.txt
merutantra-M00195-IAST.txt
mokSasopAna-M00315-IAST.txt
mRgendrAgama-M00037-IAST.txt
mRtyuNjayapUjApaddhati-M00554-IAST.txt
mukuTAgama-M00424-IAST.txt
narezvaraparIkSA-M00039-IAST.txt
nATyazAstram Vol. 3-M00362-IAST.txt
netratantra-M00038-IAST.txt
nirvANaguhyakAlIpUjA-M00557-IAST.txt
nityASoDazikArNavatantra with the commentary called setubandha-M00052-IAST.txt
paJcaratnavyAkhyA-M00603-IAST.txt
parAkramapUjA-M0311-IAST.txt
parAtriMzikAvivaraNa-M0409-IAST.txt
parAtrIzikAlaghuvRtti-M00042-IAST.txt
parAtrizikAtAtparyadIpikA and zAktavijJAna-M00043-IAST.txt
parAtrizikAvivRti-M00044-IAST.txt
parazurAmakalpasUtra-M00214-IAST.txt
pauSkara saMhitA-M00259-IAST.txt
pauSkaravRtti-M00196-IAST.txt
pazcimajyeSThAmnAyakarmArcanapaddhati-M00566-IAST.txt
prANatoSiNI arthakANDa-M00072-IAST.txt
prANatoSiNI dharmakANDa-M00071-IAST.txt
prANatoSiNI kamyakANDa-M00073-IAST.txt
prANatoSiNI part 6-M00061-IAST.txt
prANatoSiNI sargakANDa-M00070-IAST.txt
purazcaryArNava volume 1-M00045-IAST.txt
purazcaryArNava volume 2-M00046-IAST.txt
purazcaryArNava volume 3-M00047-IAST.txt
revantapUjA-M00563-IAST.txt
rudrayamalatantra uttarakANDa-M00074-IAST.txt
sakalAgamasArasaGgraha-M00063-IAST.txt
samayadIkSAdhivAsanavidhi-M00564-IAST.txt
sarvajJAnottaravRttiH-M00227-IAST.txt
sarvollasatantra-M00120-IAST.txt
SaTtriMzAttattvasandoha-M00151-IAST.txt
saubhAgyataraGgiNI-M00312-IAST.txt
sUkSmAgama-M00329-IAST.txt
svacchandapaddhati-M00194-IAST.txt
svacchandatantra-M00091-IAST.txt
tantrAloka chapters 1 thru 14-M00092-IAST.txt
tantrAloka chapters 15 thru 38-M00093-IAST.txt
tantrarAjatantra-M00122-IAST.txt
tantrasAra-M00153-IAST.txt
tArAbhaktisudhArNava-M00055-IAST.txt
tArArahasya-M00095-IAST.txt
tArArahasyavRttikA-M00096-IAST.txt
tattvacintAmaNi chapters 01 thru 05-M00085-IAST.txt
tattvacintAmaNi chapters 06 thru 10-M00086-IAST.txt
tattvacintAmaNi chapters 11 thru 15-M00087-IAST.txt
tattvacintAmaNi chapters 16 thru end-M00088-IAST.txt
uDDAmezvaratantra-M00169-IAST.txt
vAmakezvarImata-M00097-IAST.txt
vArAhItantra-M00317-IAST.txt
varivasyArahasya-M00098-IAST.txt
vAruNapaddhati-M00223-IAST.txt
vijayottaratantra-E0010-IAST.txt
vIrAgama-M00253-IAST.txt
viraktotpattikriyAlakSaNa-M00619-IAST.txt
vIrazaivAcArapradIpikA-M00609-IAST.txt
vIrazaivAnandacandrikA-M00611-IAST.txt
vIrazaivasiddhAntottarakaumudI-M00604-IAST.txt
vIrazaivasiddhAntottarakaumudI-M00605-IAST.txt
vIrazaivotkarSapradIpikA-M00612-IAST.txt
vyomavyApistava-M00059-IAST.txt
yoginIhRdaya-M00115-IAST.txt
yoginiitantra-M00064-IAST.txt
zaivakalAviveka-M00181-IAST.txt
zaivasiddhAntaparibhASA-M00075-IAST.txt
zaivasiddhAntaparibhASAmaJjarI-M00254-IAST.txt
zAktAnandataraGgiNI-M00134-IAST.txt
zAktapramoda-M00054-IAST.txt
zAradAtilaka-M00077-IAST.txt
zataratnasaMgraha-M00078-IAST.txt
zivAdvaitadarpaNa-M00606-IAST.txt
zivAdvaitimaJjarI-M00607-IAST.txt
zivAgamAdimAhAtmya-M00058-IAST.txt
zivArcanacandrikA-M00079-IAST.txt
zrIkarabhAsya-M00346-IAST.txt
