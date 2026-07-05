+++
title = "130 Nagaraj Paturi"
date = "2022-07-26"
upstream_url = "https://list.indology.info/pipermail/indology/2022-July/056544.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2022-July/056544.html)

Prof. Amba Kulkarni wrote some time back on BVP list as follows:

I have seen the use of the word शून्य in छन्दशास्त्र of पिङ्गल.
In the shlookas (She corrected Shlookas to Sutras) from 8.28-8.31, he is
describing how to obtain powers
of 2. (2^n in modern notation). The relevant shlokas, their
translation, with an illustration and its equivalent mathematical
expression is given below.
(For more details you may refer to my unpublished paper:
http://arxiv.org/abs/math/0703658v2)


dviḥ arddhe (8.28)
rūpe śūnyam (8.29)
dviḥ śūnye (8.30)
tāvadardhe tadguṇitam (8.31)

If the number is divisible by 2(arddhe), divide by 2 and write 2(dvi).
If not, subtract 1 (rūpe), and write 0 (śūnyam).
If the answer were 0(śūnya), multiply by
2(dvi), and if the answer were 2(arddhe),
multiply (tadguṇitam) by itself (tāvad).

So for example, consider 8.
8
4 2 (if even, divide by 2 and write 2)
2 2 (if even, divide by 2 and write 2)
1 2 (if even, divide by 2 and write 2)
0 0 (if odd, subtract 1 and write 0).

Now start with the 2nd column, from bottom to top.
0 1*2 = 2 (if 0, multiply by 2)
2 2^2 = 4 (if 2, multiply by itself)
2 4^2 = 16 (if 2, multiply by itself)
2 16^16 = 256 (if 2, multiply by itself).

This algorithm may be expressed in modern notation as

power2(n) = [power2(n/2)] ^ 2 if n is even,
= power2(n-1/2) * 2, if n is odd,
= 1, if n = 0.


-- Amba Kulkarni

--------------------------------------------------------------------------------------------------------------------------------------------------------

I cited the following :


Kim Plofker (2009), Mathematics in India, Princeton University Press, ISBN
978-0691120676, page 54–56.



"In the Chandah-sutra of Pingala, dating perhaps the third or second
century BC, there are five questions concerning the possible meters for any
value “n”. [...] The answer is (2)7 = 128, as expected, but instead of
seven doublings, the process (explained by the sutra) required only three
doublings and two squarings – a handy time saver where “n” is large.
Pingala’s use of a zero symbol as a marker seems to be the first known
explicit reference to zero.


 Prof. Amba Kulkarni responded as


This is what the formula I presented at the end shows. From algorithmic
point of view this is a faster algorithm to find 2^n.

If I remember correctly, Prof. Knuth also has mentioned in his book on
Algorithms about this algorithm. Again, since I do not have the book with
me right now, I can not quote.

On Tue, Jul 26, 2022 at 10:19 AM Anurupa Naik <anurupa.n at ifpindia.org>
wrote:

> If I'm not mistaken, you're referring to this part from Prof Gros' French
> translation of *Paripatal* published by the French Institute:
>
> 75 Sans souffrir deux ombres, les trois fois sept mondes
> C'est Toi qui les protèges sous une ombre unique.
> Le néant, le quart, la moitié, un
> Deux, trois, quatre, cinq
> Six, sept, huit, neuf :
> 80 Tu as l'excellence dite par les nombres des âges de quatre sortes :
> Noir aux yeux rouges, Blanc aux yeux noirs [...]
>
> *(Le Paripāṭal. Texte tamoul*. Introduction, traduction et notes par
> François Gros, PIFI n°35, IFP, 1968, p. 16)
> Thank you,
> Anurupa
> IFP
>
> On 26-07-2022 02:52, rajam via INDOLOGY wrote:
>
>
> For whatever its worth … I’m tempted to provide some information from the
> Tamil paripāṭal (பரிபாடல் : 3) where I see a mathematical counting
> starting from ’sūnya’ / ‘zero’.
>
> This poem, paripāṭal (பரிபாடல் : 3), is dedicated to tirumāl (திருமால்,
> Vishnu).
>
> Here, the numbers are counted as: pāḻ (பாழ், meaning ’nothing
> solid/concrete/meaningful…’), kāl (கால், one quarter, 1/4),  pāku (பாகு,
> one half, 1/2), oṉṟu (ஒன்று, one), iraṇṭu (இரண்டு, two), mūṉṟu (மூன்று,
> three), nāṉku (நான்கு, four), aiṉtu (ஐந்து, five), āṟu (ஆறு, six), ēḻu (ஏழு,
> seven), eṭṭu (எட்டு, eight), toṇṭu (தொண்டு, nine).
>
> பாழ் என, கால் என, பாகு என, ஒன்று என,
> இரண்டு என, மூன்று என, நான்கு என, ஐந்து என,
> ஆறு என, ஏழு என, எட்டு என, தொண்டு என,
> நால்வகை ஊழி எண் நவிற்றும் சிறப்பினை …
>
> Now, I request our dear colleague Jean-Luc Chevillard for a translation
> from Gros for this part of the Paripadal poem.
>
> Thanks and regards,
> rajam
>
>
> On Jul 25, 2022, at 9:19 AM, alakendu das via INDOLOGY <
> indology at list.indology.info> wrote:
>
> Dr.Dahejia,
> With due regards, I mention the following points on the issue of "Sunnya"
> 1) "Sunnyata" of Mahayana Buddhism is a purely philosophical concept
> developed by Asanga and his brother BasuBandhu, embodying the principal of
> "ChatushKotiBinirmuktwa"..
> 2) In the world of Mathematics,probably ,an ancient Indian text dating
> back to 5th CE B.C, named as "Lokabibhaga" displayed use of decimal system
> ( including aero) .I would be grateful if any further reference on this
> text can be furnished.
> 3) AryaBhatta's name is  associated with the concept of zero" with
> respect,although there is a view that Maya civilization of Central America
> introduced the concept of zero.
>
> Would like to be enlightened more on this.
> Regards
> Alakendu Das.
>
>
>
> Sent from RediffmailNG on Android
>
>
>
>
> From: Harsha Dehejia via INDOLOGY <indology at list.indology.info>
> Sent: Sun, 24 Jul 2022 16:20:43 GMT+0530
> To: Indology List <indology at list.indology.info>
> Subject: [INDOLOGY] Sunya
>
> Friends:
>
> Is there any evidence that the sunya of mathematics arose out of the
> sunyata of Mahayana Buddhism?
>
> Kind regards,
>
> Hrtsha
> Harsha V. Dehejia
>
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info
> https://list.indology.info/mailman/listinfo/indology
> <https://list.indology.info/mailman/listinfo/indology==>
>
>
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info
> https://list.indology.info/mailman/listinfo/indology
>
>
>
> _______________________________________________
> INDOLOGY mailing listINDOLOGY at list.indology.infohttps://list.indology.info/mailman/listinfo/indology
>
>
> --
> Ms. Anurupa Naik
> Head, Library and Publication Division
> French Institute of Pondicherry (IFP)
> UMIFRE 21 CNRS-MAEE
> P.B. 33
> 11, St. Louis Street
> Pondicherry-605 001, INDIA
>
> Tel: 91-413-2231660
> Fax: 91-413-2231605
> e-mail: anurupa.n at ifpindia.org
> website: www.ifpindia.org
>
>
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info
> https://list.indology.info/mailman/listinfo/indology
>


-- 
Nagaraj Paturi

Hyderabad, Telangana, INDIA.


Senior Director, IndicA
BoS, MIT School of Vedic Sciences, Pune, Maharashtra
BoS Kavikulaguru Kalidasa Sanskrit University, Ramtek, Maharashtra
BoS Veda Vijnana Gurukula, Bengaluru.
Member, Advisory Council, Veda Vijnana Shodha Samsthanam, Bengaluru
BoS Rashtram School of Public Leadership
Editor-in-Chief, International Journal of Studies in Public Leadership
Former Senior Professor of Cultural Studies,
FLAME School of Communication and FLAME School of  Liberal Education,
Hyderabad, Telangana, INDIA.
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20220726/1c3417fe/attachment.htm>
