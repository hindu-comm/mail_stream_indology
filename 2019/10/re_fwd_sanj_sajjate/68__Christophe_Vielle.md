+++
title = "68 Christophe Vielle"
date = "2019-10-17"
upstream_url = "https://list.indology.info/pipermail/indology/2019-October/051139.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2019-October/051139.html)

Thanks to Harry Spier and Dan Lusthaus for all these additional datas.
So jy > jj can be diachronically explained by the " 'MIA' assimilation of the cluster -jy-" according to Oberlies; nevertheless, other historical explanations are possible (in addition to mine, cf. Whitney G and Renou G below). Note that the epic form of the abs./gerund. āsajja (for °sajya) given by Wackernagel is not found in Oberlies and so cannot be taken into account (even if the form could exist in Pali, see below vissajja, it is there considered as the gerund. of āsādeti, Caus. of āsīdati, ā + sad; Sk. āsādya) .
However, in a synchronic descriptive view, even Oberlies, like Kulikov, does not really present the "secondary" forms sajjate and sajjati as "passive", that, unless I am wrong, they cannot be for the indigenous grammarians. They are middle or active present of the "secondary" root sajj.

It is only because authoritative Western sources like PW or MW qualify the form "sajjate" as a passive, that it is so given in Huet generator, as he explained to me (I quote him):

Just a precision concerning sajjate.
What I indicate in root entries is just indicative, but this is not used by the morphology generation mechanism.
Thus for passive of sañj I generate first the Paninian form sajyate, and only in a supplementary pass I add sajjate. See here<https://eur03.safelinks.protection.outlook.com/?url=https:%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktconjug.cgi%3Flex%3DSH%26q%3Dsa~nj%26t%3DVH%26c%3D1%26font%3Droma&data=02%7C01%7C%7Cb79273c31bb649e0f77708d7523509f4%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068261432797621&sdata=Srr5lOtkcDzudpE84OXsH1FKObw2Mr0go2V3HyCo1Ko%3D&reserved=0>.
https://sanskrit.inria.fr/cgi-bin/SKT/sktconjug.cgi?lex=SH&q=sa~nj&t=VH&c=1&font=roma
This is the general method, I have a general productive scheme that strives to be Paninian, and I have a supplement for generating extra forms found in the literature. For instance, here is the relevant code in the Verbs module:

and compute_extra_sanj () = (* WR Oberlies p LI *)
  let root = "sa~nj"
  and conj = Primary
  and pastem = revcode "sajj" (* "y" replaced by j in passive *) in
  compute_passive_system conj root pastem

This way I can accommodate epic forms in a way that does not pollute the main paradigms.
For epic forms I generally follow Oberlies, who alludes to sajjate on page LI of his Grammar of Epic Sanskrit, a wonderful resource.


Le 17 oct. 2019 à 01:49, Harry Spier <hspier.muktabodha at gmail.com<mailto:hspier.muktabodha at gmail.com>> a écrit :

Here is Oberlies reference:

 saj -> sa(ñ)j


sajj 'to stick, to be caught' (I. [cf. VIA I 210]) --- see p. 244


pr. sajjati, Mbh 1,203.15, 5,55.9 (sam+), 177.20, 13,21.10 (saṁpra+), 39.1, 499* (pra+), 132.7, sajjate, Mbh 3,2.16 ~ 240.3, 5,9.8,67.15, R 2,54.4 (sam+), 100.6, 4,28.20.25, 58.29, 5,37.35, 49, 16

pf. (saṁ)sasajjatuḥ Mbh 6,43.69

sec. caus. sajjayate R 6, 150*.8 (pra+), 7,60.17

rem. A denominative of sajja (<sajya-) is sajjayati /te 'to make s.th<https://eur03.safelinks.protection.outlook.com/?url=http%3A%2F%2Fs.th&data=02%7C01%7C%7Cafc0423e56e64842db0708d7529384e8%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068665856120806&sdata=wJWScjVKkCil%2F11OVtkO3ztxd2bF6dJ3mSw0glJpXGE%3D&reserved=0>. ready' (Mbh 5,150.21 (sajjayanti sma nāgān], R 7,60.17 [sajjaye yāvad āyudham]). Its causative is sajjayate 'to get ready' (Mbh 14,51.2 [sajjayadhvam prayāsyāmaḥ]), its passive sajj(ī)yate 'to be made ready' (Mbh 6,19.39 [... sajjīyamāneṣu sainyeṣu ...], 8,50.36 [āyudhāni ... sajjyantām]) and its verbal adjective sajjita - 'ready' (Mbh 7,53.25).


Harry Spier

I left out an important part of the reference:  i.e. p. 244

 The passive sajyate (sañj) was the base of a secondary root sajj 'to cling' to be caught' (with 'MIA' assimilation of the cluster -jy- [cf. lajjate < *lajyate ~rajyate]).


Harry Spier


Also from Turner- Comparative dictionary of Indo-Aryan

1) sajya<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdsalsrv04.uchicago.edu%2Fcgi-bin%2Fapp%2Fsoas_query.py%3Fqs%3Dsajya%26searchhws%3Dyes&data=02%7C01%7C%7C67fb1419bda04a7fc0c108d752b67fd4%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068816106267985&sdata=PRa7S2zKabLtGxbghyiqygjp8uaQtgM1d7k0KxhRgBo%3D&reserved=0> (p. 758<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdsalsrv04.uchicago.edu%2Fcgi-bin%2Fapp%2Fsoas_query.py%3Fpage%3D758&data=02%7C01%7C%7C67fb1419bda04a7fc0c108d752b67fd4%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068816106277980&sdata=TW1pkUsTHPGzI63ps783%2BwzSTzXKbi6AS%2FF7SgakL7A%3D&reserved=0>) 13095 sajya ʻ strung (of bow) ʼ Kauś., sajja -- ʻ id., put in place on bow (of arrow) ʼ MBh., sajjā -- f. ʻ equipment, dress ʼ lex. [sa -- 2, jyāˊ -- . -- But prob. both in specialized use with bow and arrow and in more general mng. ʻ ready ʼ (MBh.), ʻ equipment, dress, &c. ʼ (NIA.) conn. with √sañj, i.e. sajya -- ʻ *what is put on ʼ > ʻ ready (of equipment) ʼ > ʻ ready ʼ, cf. āsakta -- ʻ donned ʼ R., prasajyā -- f. ʻ application ʼ Pat., K. sanz infl. by sañjayati &c. (J. C. W.) -- In mng. ʻ fresh ʼ see also sadyás, sadyōja -- .]
Pa. sajja -- , ˚aka -- ʻ prepared (of bow with bowstring), ready ʼ; Pk. sajja -- ʻ ready ʼ, NiDoc. sajaka, ǵ Woṭ. sāz, f. syēz ʻ in good order, good ʼ; S. saj̄o ʻ perfect ʼ, sāj̄o ʻ in good state, well, fair (of wind), rich, righthand ʼ; L. sajjā (Ju. -- j̄j̄ -- )ʻ fresh, new, righthand ʼ, khet. sajjā ʻ righthand ʼ, awāṇ. sajjā ʻ decorated, righthand; P. sajjā ʻ righthand ʼ, sajjrā ʻ fresh ʼ; Ku. sāj ʻ necessary furniture ʼ, sajilo ʻ easy ʼ; N. sāsi ʻ fresh, wholesome ʼ (< *sāj after bāsi ʻ stale ʼ < vāsita -- ), sajilo ʻ easy ʼ; A. xāz ʻ suit of clothes, set of ornaments ʼ, xāzu ʻ ready for action ʼ; B. sāj ʻ dress, ornament ʼ; Or. sāja ʻ outfit, armour, harness ʼ; OMth. sāja ʻ dressed up ʼ, Mth. sāj ʻ adornment, garments ʼ; Bhoj. sāj ʻ dress ʼ; OAw. sāja ʻ decoration ʼ; H. sajjā ʻ righthand ʼ, sajīlā ʻ well -- shaped ʼ; OMarw. sāja m. ʻ accoutrements ʼ; G. sājũ ʻ sound, healthy ʼ, sāj m. ʻ dress, equipment ʼ, M. sāj̈ m.; Si. säda ʻ saddle, trappings of horse, armour, pair of panniers ʼ; -- K. sanz m. ʻ equipment ʼ.
sajjana -- 1, sajjayati, sajjita -- , sajjyatē.
sajyátē see sájati.
Addenda: sajya -- : WPah.kṭg. sáj̈ḷɔ ʻ freshly made (of food and drink) ʼ; Garh. sāj ʻ decoration ʼ, sajilu ʻ well -- decorated ʼ.
sajyátē see sájati Add2

Harry Spier


Dear all,

For what it is worth, a few Pali references, and a bit of Sanskrit:

PTS Pali-English Dict
https://dsalsrv04.uchicago.edu/cgi-bin/app/pali_query.py?qs=Sajjati<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdsalsrv04.uchicago.edu%2Fcgi-bin%2Fapp%2Fpali_query.py%3Fqs%3DSajjati&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391121266&sdata=J4XVY61RiiUS0ncBahBPF%2B3a8rbejP9F9wGCntSkthQ%3D&reserved=0>

1) Visajjati<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdsalsrv04.uchicago.edu%2Fcgi-bin%2Fapp%2Fpali_query.py%3Fqs%3DVisajjati%26searchhws%3Dyes&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391131261&sdata=L6Zr%2B%2FZ%2FY%2FvSDbHzDWyYBwBqUf8qFs4y2s8GXTFfOGQ%3D&reserved=0> (p. 639<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdsalsrv04.uchicago.edu%2Fcgi-bin%2Fapp%2Fpali_query.py%3Fpage%3D639&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391131261&sdata=0uIEfMUh3Oskw63Tv85lbx4A1ZYHgbCpeQGAooS%2BFps%3D&reserved=0>) Visajjati Visajjati [vi+sajjati, Pass. of sañj; the regular Act. would be visajati] to hang on, cling to, stick to, adhere (fig.); only in pp. visatta (q. v.). -- The apparent ger. form visajja belongs to vissajjati.

1) Vissajjati<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdsalsrv04.uchicago.edu%2Fcgi-bin%2Fapp%2Fpali_query.py%3Fqs%3DVissajjati%26searchhws%3Dyes&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391141253&sdata=gKA8erGPSoRS%2FQa6TNOSj9DDNupmG1kpNvIaFofFdP0%3D&reserved=0> (p. 641<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdsalsrv04.uchicago.edu%2Fcgi-bin%2Fapp%2Fpali_query.py%3Fpage%3D641&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391141253&sdata=UUICyUGIp%2FvVAQj9jyp2ltfsPFT%2FXQpJ8OcA7O4Dxfg%3D&reserved=0>) Vissajjati Vissajjati [vi+sajjati, of sṛj. The ss after analogy of ussajjati & nissajjati, cp. ossajjati for osajjati]. A. The pres. vissajjati is not in use. The only forms of the simple verb system are the foll.: ger. vissajja, usually written visajja, in meaning "setting free," giving up, leaving behind Sn 522, 794, 912, 1060; Nd1 98; Nd2 596. -- grd. vissajjaniya [perhaps better to vissajjeti1] to be answered, answerable; nt. a reply Nett 161, 175 sq., 191; and vissajjiya to be given away: see under a˚. <-> pp. vissaṭṭha. -- B. Very frequent is the Caus. vissajjeti (also occasionally as visajj˚) in var. meanings, based on the idea of sending forth or away, viz. to emit, discharge J i.164 (uccāra -- passāvaŋ). -- to send Mhvs 8, 3 (lekaŋ visajjayi). -- to dismiss PvA 81 (there). -- to let loose PvA 74 (rathaŋ). -- to spend, give away, bestow, hand over Pug 26 (visajj˚); Nd1 262 (dhanaŋ); Miln 41 (dhaññaŋ); PvA 111, 119. -- to get rid of J i.134 (muddikaŋ). -- to answer (questions), to reply, retort Sn 1005 (˚essati, fut.); VvA 71; PvA 15, 59, 87. -- pp. vissajjita. -- Caus. II. vissajjāpeti (in meanings of vissajjeti) J iv.2 (hatthaŋ=to push away); Miln 143; Mhvs 6, 43.

1) Sanga<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdsalsrv04.uchicago.edu%2Fcgi-bin%2Fapp%2Fpali_query.py%3Fqs%3DSanga%26searchhws%3Dyes&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391151250&sdata=QW9WyRe0lGFHuy7y9Nmrm5Dblez7sITeAWIkuqfXfVk%3D&reserved=0> (p. 666<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdsalsrv04.uchicago.edu%2Fcgi-bin%2Fapp%2Fpali_query.py%3Fpage%3D666&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391151250&sdata=rgpR6gzukXN%2BEvlG8GZwYocO8D3mutzrI1tIM4lasUU%3D&reserved=0>) Sanga Sanga [fr. sañj: see sajjati1] cleaving, clinging, attach- ment, bond S i.25, 117 sq.; A iii.311; iv.289; Dh 170, 342, etc.; Sn 61, 212, 386, 390, 475, etc.; Dhs 1059; DhsA 363; J iii.201; the five sangas are rāga, dosa, moha, māna, and diṭṭhi, Thag. 633=Dhp. 370; DhA iv.187; seven sangas, It. 94; Nd1 91, 432; Nd2 620.
   -- âtiga one who has overcome attachment, free from attachment, an Arahant M i.386; S i.3, 23; iv.158= It 58; Sn 250, 473, 621; DhA iv.159.

1) Sajjati<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdsalsrv04.uchicago.edu%2Fcgi-bin%2Fapp%2Fpali_query.py%3Fqs%3DSajjati%26searchhws%3Dyes&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391161243&sdata=xYaql1D0cufQhgXTVKjfSI6%2B7lrmhCX4E9VRxRiGo5g%3D&reserved=0> (p. 668<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdsalsrv04.uchicago.edu%2Fcgi-bin%2Fapp%2Fpali_query.py%3Fpage%3D668&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391161243&sdata=PgxM9Cg3lECEGUVpNOmsULQ%2FR5lxuqHUY3w%2F%2FttkS68%3D&reserved=0>) Sajjati Sajjati [Pass. of sañj or saj to hang. Cp. sanga] 1. to cling, to, to be attached S i.38, 111 (aor. 2 sg. sajjittho); ii.228; A ii.165; J i.376 (id. asajjittho); Sn 522, 536. ppr. (a)sajjamāna (un) -- attached Sn 28, 466; J iii.352. -- 2. to hesitate J i.376 (asajjitvā without hesitation). -- pp. satta1. -- Cp. abhi˚ & vi˚.

1) Satta<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdsalsrv04.uchicago.edu%2Fcgi-bin%2Fapp%2Fpali_query.py%3Fqs%3DSatta%26searchhws%3Dyes&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391161243&sdata=iTGbsOp%2BC5IO9Q7YkNFQ%2BiNOV4mEqYCYjnC8iCaIITU%3D&reserved=0> (p. 673<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdsalsrv04.uchicago.edu%2Fcgi-bin%2Fapp%2Fpali_query.py%3Fpage%3D673&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391171236&sdata=oHgeEExwHBBSlqf405rG9JE94FJw9sNVV3cbiCr6aUA%3D&reserved=0>) Satta Satta1 [pp. of sañj: sajjati] hanging, clinging or attached to Vin i.185; D ii.246; Nd1 23, 24; Dh 342; J i.376. Cp. āsatta1 & byāsatta.
—

Critical Pali Dictionary
https://cpd.uni-koeln.de/search?article_id=8235<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fcpd.uni-koeln.de%2Fsearch%3Farticle_id%3D8235&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391171236&sdata=mMmXhB8%2BaS1UcfmEP7x2oG3CInFW54VCizQDx4VYWdc%3D&reserved=0>


abhi-sajjati

, pr. 3 sg. (orig. pass, of prec, cf. sa.
sajjate, Buddh.sa. abhi-ṣajyate, Av-ç 1286,1), (a) Utt.
to stick fast on, to linger in (gāme); (b) to take offence
(+ kuppati); AN I 127,1 (~ati + kuppati vyāpajjati
patiṭṭhīyati (or °tthīyati) kopañ ca dosañ ca appac-
cayañ ca pātukaroti) ≠ AN II 203,16 foll. (quoted Sadd
96,27)≠AN III 181,10 foll..≠Pp 30,6 (= laggati, Pp-a)
= 36,26 ≠ MN III 204,19 foll.; 1 sg. n'evâbhisajjāmi
na câpi kuppe, Ja III 120,15* (= laggāmi, Ct.);
pot. 3 sg. ~eyya, Sn 929 (gāme ca nâbhisajjeyya; =
gāme ca gihisaṁsaggâdīhi ~, Pj; cf. Nidd I 387,1
(a)); as to pot. 3 sg. med. ~etha, Ja V 175,24' (see
abhi-sajjati≠ DN III 159,8 (nâ°; = kuṭila-kaṇṭako viya tattha
tattha mammaṁ (so pt, Se; Ee tattha ca cammaώ)
tudanto viya na laggi, Sv); 1 sg. ~sajjiṁ, AN II 204,34
(+ kuppiṁ, etc.); inf. ~itum (imāya appamattāya),
DN I 91,28 (= kodha-vasena laggituṁ, Sv).


—
from Huet’s Sanskrit Grammar Companion: Conjugation
https://sanskrit.inria.fr/cgi-bin/SKT/sktconjug.cgi?lex=MW&q=sa%7Enj&t=VH&c=1&font=roma<https://eur03.safelinks.protection.outlook.com/?url=https:%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktconjug.cgi%3Flex%3DMW%26q%3Dsa~nj%26t%3DVH%26c%3D1%26font%3Droma&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391181230&sdata=vZjL3PbyJ%2FnNeJc9dRMSxyv3ZL7P%2BU1ZBlSoZjsRyy8%3D&reserved=0>

from the conjugation tables of sañj.

Causative conjugation:
Participles

Past Passive Participle
sajjita m.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjita%3Bg%3DMas%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPpp%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391181230&sdata=mkGrBf0nCYq01dVDFAPv%2Brfa8wTtul8FVJQLGSHJqVY%3D&reserved=0> n.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjita%3Bg%3DNeu%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPpp%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391191227&sdata=KKgsZfsa5IEEmnOshiAh8Cr6vdFHZChRQkQ1BHG7lXc%3D&reserved=0> sajjitā f.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjitaa%3Bg%3DFem%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPpp%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391191227&sdata=vHLr8gRD2EmaWaQYIF8V1c6KrInXey6u0rSr%2FgOAI%2Bc%3D&reserved=0>

Past Active Participle
sajjitavat m.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjitavat%3Bg%3DMas%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPppa%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391201223&sdata=y1dmV3%2FdWIC4DeOkvkk0uRUR%2F92H5evgob1w5izfWiI%3D&reserved=0> n.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjitavat%3Bg%3DNeu%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPppa%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391201223&sdata=nam83IkuNnlms1RwQETdcEP2sPoGKB9SVz1pWEDZP%2B4%3D&reserved=0> sajjitavatī f.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjitavatii%3Bg%3DFem%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPppa%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391201223&sdata=ERXzHyvNiCfijnco36hb4rCaOjVeYpUBa%2B6fwiayajg%3D&reserved=0>

Present Active Participle
sajjayat m.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjayat%3Bg%3DMas%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPpra%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391211215&sdata=UfnpNcLnCNSv9Ef3YgvIE9mx3vyQY8VYnFnxmdNzXLI%3D&reserved=0> n.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjayat%3Bg%3DNeu%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPpra%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391211215&sdata=v1DXfJohVQKL98snnZH7Wft8PEyWZoP8tCBtEyjOjec%3D&reserved=0> sajjayantī f.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjayantii%3Bg%3DFem%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPpra%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391221212&sdata=7feQ6cF%2FpYjYMUB6%2B1NRAHETHtOhn2JYu2BD%2BX5Sfzk%3D&reserved=0>

Present Middle Participle
sajjayamāna m.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjayamaana%3Bg%3DMas%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPprm%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391221212&sdata=2UWv8rwhiHl4UAB8U9AocAUWNY9h4HeEyJMEmCsu%2BsA%3D&reserved=0> n.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjayamaana%3Bg%3DNeu%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPprm%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391231205&sdata=9Um8Qf%2BisHybc6po7Tzhx0dsqZdjpbA3BDkdEdFSHsI%3D&reserved=0> sajjayamānā f.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjayamaanaa%3Bg%3DFem%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPprm%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391231205&sdata=p3fkrKIWzYXzFzode0FdjUE67X8sKdNUiv9Uqdja40w%3D&reserved=0>

Present Passive Participle
sajjyamāna m.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjyamaana%3Bg%3DMas%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPprp%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391241196&sdata=vJYHvcevfc4rPacsqLWWhPxLOHanKd%2B%2FHskMItITMBI%3D&reserved=0> n.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjyamaana%3Bg%3DNeu%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPprp%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391241196&sdata=KB4tXWkaqoDh6YXShpHFJGlyA%2FHoYqGb%2FQ%2Fm90NdJTE%3D&reserved=0> sajjyamānā f.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjyamaanaa%3Bg%3DFem%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPprp%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391251195&sdata=243cMuPpY8t7kZV2370%2F7mxYOFw06VZZBoyK7CpBl30%3D&reserved=0>

Future Active Participle
sajjayiṣyat m.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjayi.syat%3Bg%3DMas%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPfuta%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391251195&sdata=PemCnAF4Qt3%2BM0CXmfWJLJK1egNAFHgmr3KOEeAQQRc%3D&reserved=0> n.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjayi.syat%3Bg%3DNeu%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPfuta%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391251195&sdata=7WzaK%2BBz0Yw%2BW7dfpMY%2ByUK94gRqUIuXd5Wp1Y9ZxQs%3D&reserved=0> sajjayiṣyantī f.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjayi.syantii%3Bg%3DFem%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPfuta%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391261185&sdata=mtg51GS%2BPgBmKqbBZsXZi7SjJEUCdnMAW8GH40OD7Ek%3D&reserved=0>

Future Middle Participle
sajjayiṣyamāṇa m.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjayi.syamaa.na%3Bg%3DMas%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPfutm%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391261185&sdata=BicCNX7lbReewWAc6WCGogH7FPHHecs%2BTXRIPNrWeuM%3D&reserved=0> n.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjayi.syamaa.na%3Bg%3DNeu%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPfutm%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391271182&sdata=tp8BoWm%2F5JyFChCGJ23wg15UBsARxNrW9YMT%2BkbEijw%3D&reserved=0> sajjayiṣyamāṇā f.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjayi.syamaa.naa%3Bg%3DFem%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPfutm%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391271182&sdata=ouJeejhPx3ZNj1nKQ4ulQA7NX6VVLgFNCw%2B2EHs%2B10g%3D&reserved=0>

Future Passive Participle
sajjya m.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjya%3Bg%3DMas%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPfutp%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391281172&sdata=Nr7WeQoD9sdyaQQAxuQMUjJ3F158nN1of%2Fu0rjeWkDw%3D&reserved=0> n.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjya%3Bg%3DNeu%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPfutp%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391281172&sdata=zFIFloR8Z%2F5bHzCZWICTMVfMqVk6Ejb8eu65pOImzJw%3D&reserved=0> sajjyā f.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjyaa%3Bg%3DFem%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPfutp%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391291167&sdata=SywkkEfFWEis4w1boAggN4%2BgZKRMpCaOrBS2wERgT1w%3D&reserved=0>

Future Passive Participle
sajjanīya m.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjaniiya%3Bg%3DMas%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPfutp%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391291167&sdata=TY2wk69AsRrREIML3fQ25FJzGcG%2BTarIlDbzvr5c5RE%3D&reserved=0> n.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjaniiya%3Bg%3DNeu%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPfutp%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391301161&sdata=DGH4t%2BtY7u2oVF4DYQw4HRo0izNGYnwOsHOau%2FUieAc%3D&reserved=0> sajjanīyā f.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjaniiyaa%3Bg%3DFem%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPfutp%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391301161&sdata=%2Fn%2BBJuNi6liWLhNrRo%2FvUcpIkLzfPZOoCIq4wORt%2Brw%3D&reserved=0>

Future Passive Participle
sajjayitavya m.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjayitavya%3Bg%3DMas%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPfutp%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391311158&sdata=JZ6OGEzX1%2BGT8FQT3xcXfUJScVY6a5flXDDE6i6VFTk%3D&reserved=0> n.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjayitavya%3Bg%3DNeu%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPfutp%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391311158&sdata=ocB83Rwy1GTxTBjgws0B0pFYJPWdrAOo6IQgJUZLwBg%3D&reserved=0> sajjayitavyā f.<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktdeclin.cgi%3Fq%3Dsajjayitavyaa%3Bg%3DFem%3Bfont%3Droma%3Br%3Dsa%257Enj%3Bp%3DPfutp%3Blex%3DMW&data=02%7C01%7C%7C8722635c5dcc45d83b9608d752b29bf6%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068799391321153&sdata=ph%2B4%2BfWroyvXPdg60xQkISvTUvD4yGntP84xm5jda0c%3D&reserved=0>

Dan

Sorry for having omitted to mention on the subject the authoritative work of Leonid Kulikov, The Vedic -ya- presents: Passives and intransivity in Old Indo-Aryan, Leiden Studies in Indo-European 19, 2012, pp. 273-275; he also explains sajja- forms (already attested in Ved. Br.) as = sajya-, but never explicitely says that sajjate is a passive form (rather a middle class present, and sajjati an active present).



On Wed, Oct 16, 2019 at 4:12 AM Christophe Vielle via INDOLOGY <indology at list.indology.info<mailto:indology at list.indology.info>> wrote:
Dear list,

a student of mine asks me about the form sajjate usually presented (in Western dictionaries and grammars at the least) as a passive alternative/epic form of sajyate (see infra; also, even more surprising, the form sajjati is sometimes also given as a secondary passive form). I am not a specialist of grammar, nevertheless  I have a real difficulty to consider as a passive form something without an apparent -ya suffix (and  without middle ending for sajjati — note that the latter form is also proposed by Whitney G to come from a Cl. IV *sajyati or from *sasjati), and, additionally, why in this case to postulate such an assimilation jj < jy and not a more obvious or natural ñj > jj . It seems indeed to me more easy to consider sajjate (and sajjati) as alternative M (and A) form = *sañjate (and *sañjati, which is given by Kale G), beside more classical sajate/i. The two causative forms sañjayati and sajjayati appears to confirm this explanation (cf. also in MW the double entry sajj = sañj); however, the other has for it the epic abs. °sajja (for °sajya) given by Wackernagel (I have not Oberlies here at hand to check this reference).
Thank you for your comments. Especially, I would be interested to know
1° if it happens that indigenous grammars also consider sajjate as a passive form
2° linguistic historical or comparative arguments for  jj < jy  rather than < ñj

Best wishes,
Christophe

From: Edmond Differding
Sent: Tuesday, October 15, 2019 18:19
To: Christophe Vielle <christophe.vielle at uclouvain.be<mailto:christophe.vielle at uclouvain.be>>
Subject: sañj sajjate

Voici ce que j’ai trouvé sur sajjate :

Grammaire de Whitney §746


<image002.jpg>


Whitney Roots :

<image003.jpg>


Renou §9 [p. 8] :

"Assimilation... par prākritisme... sont ainsi passés dans la langue sajj- 46a)"

[> §46a, p. 50]: "Les rac. en -jj- données gr. comme reposant sur -sj-"

Renou §71.a)1) [p. 77] :

rac. sañj – dépourvue de nasale au présent (en ya), facultativement au causatif, et le maintient ailleurs


Macdonell :

133.A.4.: mentionne juste: perd la nasale : saj-a-


Huet/Heritage :

sañj var. saj v. [1<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2Fcgi-bin%2FSKT%2Fsktconjug.cgi%3Fq%3Dsa%257Enj%3Bc%3D1%3Bfont%3Droma&data=02%7C01%7C%7Cafc0423e56e64842db0708d7529384e8%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068665856120806&sdata=9zn4240CtQRuKR%2BOQNRbd%2FD1%2FoPXeOaNRYDM1Xm%2B1oc%3D&reserved=0>] pr. (sajati) pr. r. (sajate) pft. (sasañja) pp. (sakta) pf. (anu<https://eur03.safelinks.protection.outlook.com/?url=https:%2F%2Fsanskrit.inria.fr%2FDICO%2F3.html%23anu.sa~nj&data=02%7C01%7C%7Cafc0423e56e64842db0708d7529384e8%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068665856130800&sdata=xac8nEpSkuIbd03E2Xjy9diSf%2FukYu78VGyr9Fx619M%3D&reserved=0>, ā<https://eur03.safelinks.protection.outlook.com/?url=https:%2F%2Fsanskrit.inria.fr%2FDICO%2F10.html%23aasa~nj&data=02%7C01%7C%7Cafc0423e56e64842db0708d7529384e8%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068665856130800&sdata=hYH%2B%2FeJsKv2oEnLTZDvohBLT34KmZBrJET%2BKmSGYsTk%3D&reserved=0>, ni<https://eur03.safelinks.protection.outlook.com/?url=https:%2F%2Fsanskrit.inria.fr%2FDICO%2F36.html%23ni.sa~nj&data=02%7C01%7C%7Cafc0423e56e64842db0708d7529384e8%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068665856140793&sdata=jqvxW4iRqwGCkIcQ6FIoGZ9kOmxsZB1YaNCl4zf5igk%3D&reserved=0>, pra<https://eur03.safelinks.protection.outlook.com/?url=https:%2F%2Fsanskrit.inria.fr%2FDICO%2F44.html%23prasa~nj&data=02%7C01%7C%7Cafc0423e56e64842db0708d7529384e8%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068665856140793&sdata=sbQ7Ur%2FMgmOdHLlkwKAoc8SWJYplhD0YD%2B%2BHfoZie08%3D&reserved=0>, sam<https://eur03.safelinks.protection.outlook.com/?url=https:%2F%2Fsanskrit.inria.fr%2FDICO%2F66.html%23sa.msa~nj&data=02%7C01%7C%7Cafc0423e56e64842db0708d7529384e8%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068665856150787&sdata=LcVW3jljbawdv1vVbDdBEGggFaPQVqtvOmde12Pz9dU%3D&reserved=0>) adhérer — ps. (sajjate) être attaché à, être suspendu à


Monier Williams :

[ sajj ]2 ( = √ [ sañj<https://eur03.safelinks.protection.outlook.com/?url=https:%2F%2Fsanskrit.inria.fr%2FMW%2F276.html%23sa~nj&data=02%7C01%7C%7Cafc0423e56e64842db0708d7529384e8%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068665856150787&sdata=RlJgHnnom6Mv1qZCe7zs6D31GNOkJRVTM0oh6gQLOI8%3D&reserved=0> ] ; cf. [ sajjaya<https://eur03.safelinks.protection.outlook.com/?url=https%3A%2F%2Fsanskrit.inria.fr%2FMW%2F276.html%23sajjaya&data=02%7C01%7C%7Cafc0423e56e64842db0708d7529384e8%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068665856160783&sdata=KTJgit8JSKxAXztpgLoUi8PdihFNCatEfsq26Zc5EUQ%3D&reserved=0> ] ) , Caus. [ sajjayati ] , to cling , adhere , fasten or fix or attach to (loc.) Lit. Kathās. ; to fix (the mind) upon Lit. BhP. ; to cause one's self to be embraced (by other men) Lit. Mn. viii , 362.

[ sañj ]2 Root ( or [ saj ] ) cl. [1] P. ( Lit. Dhātup. xxiii , 18) [ sájati ] ( rarely Ā. [ °te ] ; pf. [ sasañja ] Lit. Br. ( in some rare and doubtful cases in Lit. MBh. and Lit. Ragh. [ sasajja ] ) ; 3. pl. [ sejuḥ ] Lit. ŚBr. ; aor. [ asāṅkṣīt ] , [ sāṅkṣīt ] , UP. ; [ asañji ] Lit. Br. ; [ ásakthās ] , [ °ta ] Lit. RV. Lit. Br. ; Prec. [ sajyāt ] Gr. ; fut. [ saṅktā ] , [ saṅkṣyati ] Lit. ib. ; inf. [ saktum ] Lit. MBh. ; [ saṅktos ] Lit. Br. ; ind.p. [ -sajya ] , [ -sáṅgam ] Lit. ib. ) , to cling or stick or adhere to , be attached to or engaged in or occupied with (loc.) Lit. Br. Lit. Ragh. Lit. Naish. : Pass. [ sajyáte ] ( generally [ sajjate ] , ep. also [ °ti ] ) , to be attached or fastened , adhere , cling , stick (with [ na ] , " to fly through without sticking " , as an arrow) Lit. ŚBr. ; to linger , hesitate Lit. MBh. Lit. R. ; to be devoted to or intent on or occupied with (loc.) Lit. MBh. Lit. Kāv. : Caus. [ sañjayati ] (aor. [ asasañjat ] ; for [ sajjayati ] see √ [ sajj ] ) , to cause to stick or cling to , unite or connect with (loc.) Lit. Bhag. Lit. Śaṃk. : Desid. [ sisaṅkṣati ] see [ ā-√ sañj ] : Intens. [ sāsajyate ] , [ sāsaṅkti ] Gr. ( ( cf. accord. to some , Lat. (segnis) ; Lith. (segu4) , " I attach. " )


Böthlingk & Roth:

sañj , sajati Dhātup. 23, 18  (saṅge, pariṣvaṅge). P. 6, 4, 25.  Vop. 8, 102.  asāṅkṣīt (s. u. pra), sasañja, sasañjatus und sasajatus Vop.  asaktaḥ saṅkṣyāmi (vgl. unter ā und Kār. 2 aus Siddh.  zu P. 7, 2, 10 ); partic. sakta .
1) anhängen, zusammenhängen Śāṅkh. Br. 24, 1.  yad adya dugdhaṃ pṛthivīm asakta sich hängen an Tbr. 1, 4, 3, 3.
— 2) act. hängen bleiben, sich anheften: sasañjuḥ (sasajjuḥ ed. Calc.) — mattebhakaṭeṣu phalareṇavaḥ Ragh. 4, 47.
— 3) pass. sajyate hängen (intrans.) an Śat. Br. 10, 2, 6, 8. 14, 6, 9, 28. 11, 6.  gewöhnlich mit Assimilation sajjate (episch auch sajjati, welches Dhātup. 7, 22  als bes. Wurzel in der Bed. gatau angefuhrt wird; etc……

— anu
1) act.
a) behängen: ātmānaṃ rasena Śat. Br. 7, 3, 1, 3.
— b) hinzufügen Pār. Gṛhy. 1, 5. 8.
— 2) pass.
a) °sajyate
α) hängen bleiben —, haften an (loc.): dharmapūte ca manasi nabhasīva na jātu rajo 'nuṣajyate Daśak. 64, 18.  sich anschliessen Comm. zu Vs. Prāt. 4, 173.
— β) sich wieder anschliessen so v. a. aus dem Vorangehenden nachgelten, - zu ergänzen sein: saṃnidhānād evety anuṣajyate Comm. zu Kap. 1, 98.  Sāh. D. 238, 4.
— b) °ṣajjate
α) sich Jmd (acc.) anschliessen so v. a. auf dem Fusse folgen: gopās tam anvasajjanta śakaṭaiḥ Bhāg. P. 10, 39, 33. 83, 34.
— β) hängen an so v. a. sich hingeben, sich beschäftigen mit, mit den Gedanken, mit dem Herzen bei Etwas (loc.) sein: indriyārtheṣu, karmasu Bhag. 6, 4.  kuśale karmaṇi  18, 10.  kāye Bhāg. P. 4, 20, 5.  draviṇe  11, 23, 23.


Puis encore dans :

Wackernagel, Vol 1, p163 : jj < jy

[X]



Kale : Higher Sanskrit Grammar App II p 138:

[X]



Bref, je n’ai rien trouvé de règle solide qui explique le jj ! Renou parle de géminations en général, mais j’avoue ne pas avoir compris….

J’attends vos commentaires !

Bonne soirée,
Edmond



–––––––––––––––––––
Christophe Vielle<https://uclouvain.be/en/directories/christophe.vielle>
Louvain-la-Neuve



_______________________________________________
INDOLOGY mailing list
INDOLOGY at list.indology.info<mailto:INDOLOGY at list.indology.info>
indology-owner at list.indology.info<mailto:indology-owner at list.indology.info> (messages to the list's managing committee)
http://listinfo.indology.info<https://eur03.safelinks.protection.outlook.com/?url=http%3A%2F%2Flistinfo.indology.info&data=02%7C01%7C%7Cafc0423e56e64842db0708d7529384e8%7C7ab090d4fa2e4ecfbc7c4127b4d582ec%7C0%7C0%7C637068665856160783&sdata=GdEUUd%2BEzvZq2xx6XDwtXT56BMnQH3Q6bHwvX2ZXoCE%3D&reserved=0> (where you can change your list options or unsubscribe)

–––––––––––––––––––
Christophe Vielle<https://uclouvain.be/en/directories/christophe.vielle>
Louvain-la-Neuve





-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20191017/48db9b16/attachment.htm>
