+++
title = "77 Christophe Vielle"
date = "2025-07-30"
upstream_url = "https://list.indology.info/pipermail/indology/2025-July/060886.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2025-July/060886.html)

The disappearance of the numbering of sections and verses for several texts remains the main point to correct in the version now displayed by the  TextGrid interface... as well in the sources which can be gotten through the link you give.
For instance, the "van Nooten & Holland" input of the RV (which becomes here the "R.G." RVS):
https://textgridrep.org/browse/49kng.0
https://textgridlab.org/1.0/aggregator/html/textgrid:49kng.0?mediatype=text/html
https://textgridlab.org/1.0/tgcrud-public/rest/textgrid:49kng.0/data
cannot be used.
Compare
http://gretil.sub.uni-goettingen.de/gretil/corpustei/transformations/html/sa_Rgveda-edAufrecht.htm
(it is true that http://gretil.sub.uni-goettingen.de/gretil/corpustei/sa_Rgveda-edAufrecht.xml is without numbering)
The advantage of GRETIL as it is (was) remains in its clarity not only in the presentation of each text, but also in the general, arborescent, presentation of the whole corpus classified by genres and sub-types, which allows to find a peculiar text easily. The (advanced) search on TextGrid is in this regard less efficient: if for instance one searches for "Veda", then among the 472 results, the access is first given to the "GRETIL Veda Collection" — ok, but  all the (types of) texts are here mixed without any order (even alphabetically): https://textgridrep.org/browse/49knn.0

Note that the GRETIL version of the RVS "converted and revised by Detlef Eichler" displays the "devanagari" accentuation as used by the latter (http://www.detlef108.de/Rigveda.htm), not the original one used by van Nooten & Holland in the HOS volume. See for this one, the University of Texas at Austin duly introduced version here:
https://lrc.la.utexas.edu/books/rigveda/RV00
https://lrc.la.utexas.edu/books/rigveda/RV01
or the one on Titus (https://titus.fkidg1.uni-frankfurt.de/database/titusinx/location.htm s.v. Sanskrit)


Le 30 juil. 2025 à 10:46, Maximilian Mehner <mehnerm at staff.uni-marburg.de<mailto:mehnerm at staff.uni-marburg.de>> a écrit :

Dear Christophe,

how the collection is displayed in TextGrid indeed needs to be worked on. The editors, introductions and references are encoded as before in the TEI source files, "just" not shown in the interface. You can get to the source by following the link on the left of the standard rendering: Download - Object (TEI). Compare for

- Rāmodanta: https://textgridlab.org/1.0/tgcrud-public/rest/textgrid:49m88.0/data

In this case the references you have given were garbled in the conversion,  they of course need to be restored. I will personally see to it.

- Rākṣasakāvya with Ṭīkā: https://textgridlab.org/1.0/tgcrud-public/rest/textgrid:49m8p.0/data

- Mīmāṃsāsūtra: https://textgridlab.org/1.0/tgcrud-public/rest/textgrid:49p2f.0/data

- Kāvyālaṃkāra: https://textgridlab.org/1.0/tgcrud-public/rest/textgrid:49m14.0/data

Best wishes,

Max

On 29.07.25 10:37, Christophe Vielle wrote:
It is very disappointing to see that in this new version all the names of the editors/input makers of each text have disappeared, as well as the introductions to the inputs, especially when the introductions give important explanations (of the abbreviations used in the apparatus etc., since it is sometimes more than a "simple" input). It does not appear to me to be a fair re-use of the work made by the scholars who contributed to the original corpus. Note that the 2020-07-31 "TEI encoding by mass conversion of GRETIL's Sanskrit corpus" had already introduced many slight errors in the text-references (impossible to correct...)

Testing the case of my modest contributions to the corpus,
Compare: http://gretil.sub.uni-goettingen.de/gretil/corpustei/transformations/html/sa_rAmodanta.htm ("structure reference" + "contributor's note")
and https://textgridrep.org/browse/49m89.0 , https://textgridrep.org/browse/49m88.0 : the text appears as something due to Reinhold Grünendahl as collector, and the text, without introduction, appears without any reference or numbering of verses.
or http://gretil.sub.uni-goettingen.de/gretil/corpustei/transformations/html/sa_ravideva-rAkSasakAvyawithTIkA.htm
with https://textgridrep.org/browse/49m8q.0 (again the text appears twice) and https://textgridrep.org/browse/49m8p.0 : same problems, no comment...

I would add the the examples of Pohlus ed. of the MSBh:
http://gretil.sub.uni-goettingen.de/gretil/corpustei/transformations/html/sa_jaimini-mImAMsAsUtra-1-7-comm.htm
searching s.v. Śabara  this input does not appear (it is instead the input of MSBh 1.1.1-5 by Vasudeva) - after some searching, compare: https://textgridrep.org/browse/49p2f.0

or Goodall's ed. of Bhāmaha's Kāvyālaṃkāra: http://gretil.sub.uni-goettingen.de/gretil/corpustei/transformations/html/sa_bhAmaha-kAvyAlaMkAra.htm
compare https://textgridrep.org/browse/49m14.0

Same problems: disappearance of the references etc.
In the state they are displayed for the moment, it is not possible to use these inputs.

I would add that to declare something "distributed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License" (as it is said for each text) when the authors of the inputs/editions are not at all mentioned, or, if it would further happen they are, in making their work corrupt or unreadable, is really problematic.

Even if to move within Github environment is not so easy (to me), at the least the work made by Claudius Teodorescu seems to give in a faithful manner the original files like they are on GRETIL at the moment.

bw,

Christophe

Le 22 juil. 2025 à 17:33, Maximilian Mehner via INDOLOGY <indology at list.indology.info<mailto:indology at list.indology.info>> a écrit :

Dear Claudius,

it’s truly encouraging to see how much effort you’ve invested! However, as merging your versions with the ones on TextGrid would constitute a content update, this is exactly the sort of work that will not happen. Perhaps consider it to be different redactions of the same corpus. And as in both redactions at least the more recent changes are well documented, users should be in a good position to make an informed decision about which version best suits their needs.

Best regards,
Max

Am 25/07/22 11:43, schrieb Claudius Teodorescu:
Dear David, José, and Maximilian,

Congratulations for the initiative of saving *endangered data*, as we may
call it like this, when the funding is lacking.

I would like to mention that, for the GRETIL Search Interface which I
prepared some time ago see [1], I have improved all the files in
the 1_sanskr folder, in order to make them valid XML files firstly, and
valid TEI files, secondly. A change log of the improvements can be found at
[2].

Maybe we can merge the versions of these files, in order to have a single
source of truth.

Best regards,
Claudius Teodorescu

[1] https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fclaudius-teodorescu.gitlab.io%2Fgretil-corpus-site%2F&data=05%7C02%7Cchristophe.vielle%40uclouvain.be%7C8fb13ff877a64296b8ef08ddc9353aa4%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C1%7C0%7C638887952758691069%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=eFkdlH%2FHoTRceyXWSys%2Fy0Yu0p4VZv1GQzSZg%2BSUn7A%3D&reserved=0<https://claudius-teodorescu.gitlab.io/gretil-corpus-site/>
[2]
https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fgithub.com%2Fsanskrit-texts%2Fgretil-corpus%3Ftab%3Dreadme-ov-file%23changes&data=05%7C02%7Cchristophe.vielle%40uclouvain.be%7C8fb13ff877a64296b8ef08ddc9353aa4%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C1%7C0%7C638887952758709711%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=MneoZdD6dIjcCVaXqB5iELx3oK%2BRFFSLYS4yW8kmF44%3D&reserved=0<https://github.com/sanskrit-texts/gretil-corpus?tab=readme-ov-file>

On Mon, 21 Jul 2025 at 17:01, Maximilian Mehner via INDOLOGY <
indology at list.indology.info<mailto:indology at list.indology.info>> wrote:

Dear list members,

in light of last week’s discussion on the sustainability of digital
projects, I would like to share some important updates - or more precisely:
final developments - regarding GRETIL.

The directors of the Göttingen State and University Library (SUB) have
been approached by the German Oriental Society (DMG), Dominik Wujastyk and
myself on multiple occasions. We all emphasised the significance of GRETIL
as a service and appealed for its continued support. Regrettably, it has
become clear that the only form of institutional backing they are willing
to provide is for the long-term preservation of the data.

Fortunately, this responsibility has been entrusted to a colleague with a
background in digital humanities, José Calvo Tello, who has a genuine
interest in enhancing the corpus. He even managed to employ a PhD student
of the Indology department, David Herting, for a couple of weeks.

The announcement we are circulating reads as follows:

Over the course of the last months we at the Göttingen State and
University Library (SUB) have been working on the migration of the the
Göttingen Register of Electronic Texts in Indian Languages (GRETIL) to a
new platform and we are now very happy to announce that GRETIL has found a
new home in the TextGrid repository:

https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Ftextgridrep.org%2Fproject%2FTGPR-2ba9cb1b-9602-202d-71ce-67e63a29de55&data=05%7C02%7Cchristophe.vielle%40uclouvain.be%7C8fb13ff877a64296b8ef08ddc9353aa4%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C1%7C0%7C638887952758724488%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=nLm21DokjR%2BIXcwboo0MtWvVQj4JVUOQ5gdy2WiRMGw%3D&reserved=0<https://textgridrep.org/project/TGPR-2ba9cb1b-9602-202d-71ce-67e63a29de55>

In its current state there are still some irregularities concerning the
rendering of certain elements, but these are being worked on. We would
nevertheless be very glad to kindly invite you to test out GRETIL in this
new environment.

Please note that from a content perspective GRETIL is regarded as a closed
project by the SUB. This means that we, unfortunately, do not have
resources to add new texts or to make philological emendations to the
existing material. Any feedback should therefore be limited to technical
errors only. If, however, you are working on specific collections of Indic
material, the SUB will be able to assist you in integrating your work into
the TextGrid repository as a new project and thus integrating it in the
same repository that contains GRETIL. You can reach out to:

José Calvo Tello, calvotello at sub.uni-goettingen.de<mailto:calvotello at sub.uni-goettingen.de>

for your technical feedback.

The old GRETIL website is still online and will be available at least
until the end of the year. The new GRETIL in TextGrid also offers the old
cumulative ZIP file downloads in its previous form (now integrated into the
DARIAH-DE Repository).The GRETIL e-library will soon be available on the
edocs server of the Göttingen University (
https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fedocs.sub.uni-goettingen.de%2F&data=05%7C02%7Cchristophe.vielle%40uclouvain.be%7C8fb13ff877a64296b8ef08ddc9353aa4%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C1%7C0%7C638887952758741000%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=ZzIcHryEhfBTDkvch%2B9PdtVHBCfkG9x4%2B%2F9ly3ZOm5I%3D&reserved=0<https://edocs.sub.uni-goettingen.de/>).

In the Pali collection, we were not able to migrate the digital facsimiles
of the Pali Text Society editions due to the special layout requirements of
these texts. Please do reach out to us, if you want to work with us on this
issue.

We have presented an in depth explanation of our work and GRETIL in
TextGrid during the poster session of the DARIAH annual event in Göttingen,
on June 19, https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fannualevent.dariah.eu%2Fprogramme%2F&data=05%7C02%7Cchristophe.vielle%40uclouvain.be%7C8fb13ff877a64296b8ef08ddc9353aa4%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C1%7C0%7C638887952758753131%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=Qqj2uDf1IUGDJjTqrOx1wlUgznJHip2I0E%2BYjMGWE%2FQ%3D&reserved=0<https://annualevent.dariah.eu/programme/> . The poster can be
seen at https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fzenodo.org%2Frecords%2F15828259&data=05%7C02%7Cchristophe.vielle%40uclouvain.be%7C8fb13ff877a64296b8ef08ddc9353aa4%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C1%7C0%7C638887952758765016%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=yCu%2FjlZYawdKNX1SNXvCDtcHcIshp%2FVedjpTsfv%2Flzk%3D&reserved=0<https://zenodo.org/records/15828259>

We will also be presenting at the 35th Deutscher Orientalistentag DOT
2025, Erlangen, Septembre 9, 11:30-12:00, in the session on long-term
archiving of DH projects.

With this migration to TextGrid we are sincerely hoping to offer GRETIL a
sustainable and connected future, so it can continue to be useful for the
scholarly community.

Best regards,
David Herting
José Calvo Tello
Maximilian Mehner

_______________________________________________
INDOLOGY mailing list
INDOLOGY at list.indology.info<mailto:INDOLOGY at list.indology.info>
https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Flist.indology.info%2Fmailman%2Flistinfo%2Findology&data=05%7C02%7Cchristophe.vielle%40uclouvain.be%7C8fb13ff877a64296b8ef08ddc9353aa4%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C1%7C0%7C638887952758777034%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=unbk1%2BSX%2FMYOddupD3SjRUNf8Zi050cUz8PaQg1C8UQ%3D&reserved=0<https://list.indology.info/mailman/listinfo/indology>



--
Cu stimă,
Claudius Teodorescu

_______________________________________________
INDOLOGY mailing list
INDOLOGY at list.indology.info<mailto:INDOLOGY at list.indology.info>
https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Flist.indology.info%2Fmailman%2Flistinfo%2Findology&data=05%7C02%7Cchristophe.vielle%40uclouvain.be%7C8fb13ff877a64296b8ef08ddc9353aa4%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C1%7C0%7C638887952758789012%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=GrFZhaCTrAguZqP7XHZns2N3RfRZeK%2FgOCSUQY9M2bY%3D&reserved=0<https://list.indology.info/mailman/listinfo/indology>

–––––––––––––––––––
Christophe Vielle<https://www.uclouvain.be/en/people/christophe.vielle>
Louvain-la-Neuve










–––––––––––––––––––
Christophe Vielle<https://www.uclouvain.be/en/people/christophe.vielle>
Louvain-la-Neuve









-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20250730/1b9792bd/attachment.htm>
