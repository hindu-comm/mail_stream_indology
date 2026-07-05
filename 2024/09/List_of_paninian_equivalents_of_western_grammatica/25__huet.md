+++
title = "25 huet"
date = "2024-09-07"
upstream_url = "https://list.indology.info/pipermail/indology/2024-September/059631.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2024-September/059631.html)

Dear Harry and colleagues,

I have been running into this hairy grammar terminology problem for my Sanskrit Heritage site’s user interface. 
When you request declension of a nominal stem, with Output font set to Roman, you get e.g.



whereas  with Output font set to Devanagari, you get



and the only problematic case is Vocative, translated as sambodhanam whereas it breaks the Sanskrit numbering of vibhakti from first to seven.
This is consistent with the treatment of vocative forms in Sanskrit, which do not stand for a semantic role in the sentence, but for an address relevant
to the context of enunciation, but not participating to the semantics of the sentence. So even just on nominal declension, this shows that the Western terminology
is awkward, while the Paninian one is more rational.

Similar problem, in worse, for the verbal forms terminology.
For instance, compare:



with:



which shows that prathama should be translated as Third and uttama as First, which is awkward. Somehow the Western terminology puts the speaker first,
whereas the Paninian one corresponds more to the frequency of forms in discourse. 

Concerning the mapping between tense/mode and lakārās, it took our team some time to establish the correspondance between the Western terminology
and the Paninian one. If you want to know the details, please refer to the source code of my (surface) morphology printer given here <https://gitlab.inria.fr/huet/Heritage_Platform/-/blob/development/ML/morpho_string.ml?ref_type=heads>. 
It gives correspondances with abstract (surface) morphological notions and the respective terminologies. 
Some Western terminologies are awkward to translate, like Aorist (borrowed from ancient Greek grammars of the West), of which there are 7 modes of formation of "लुङ् "
Absolutive splits into Absoya -> « ल्यप् » and Absotvaa -> « क्त्वा ». Inversely, लिट् splits into Perfect -> « लिट् (द्वित्व) » and Perpft -> « लिट् (अनुप्रयोग) » for periphrastic perfect.
And many categories are just not relevant outside Sanskrit grammar, and use simply the Paninian terminology, like tasil for Tas -> « तसिल् » 
Benedictive is translated as « आशीर्लिङ् », conceptualized as optative aorist . 
Gati -> « च्वि » romanized as « iiv. » in the spirit of « iic. » for nominal stems, and Namul -> « णमुल् » lumped with Absoya and Absotvaa into « abs. », losing precision. 
Other categories needed to define word formation do not appear in these tables, like « Inftu » for infinitives in -tu, needed to represent compounds like vaktukāma. 
Here there is no straightforward translation into Paninian terminology (tumun+lopa). 

More generally, the software nomenclature follows the Paninian concepts, which are the true structural categories of Sanskrit grammar, not just artifacts of a specific grammar,
and the Western linguistics categories are more or less twisted into those. Thus a serious Sanskrit grammar ought to use the Paninian notions, like Pr Filliozat’s « Grammaire Sanskrite Pâninéenne ». Specially when one wants to discuss kṛt and taddhita formations, and of course compounding, which offer a lot more variations than « exocentric » and « endocentric ». 

Best
Gérard




-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20240907/bd725762/attachment.htm>
-------------- next part --------------
A non-text attachment was scrubbed...
Name: Capture d?e?cran 2024-09-07 a? 21.24.04.png
Type: image/png
Size: 78938 bytes
Desc: not available
URL: <https://list.indology.info/pipermail/indology/attachments/20240907/bd725762/attachment.png>
-------------- next part --------------
A non-text attachment was scrubbed...
Name: Capture d?e?cran 2024-09-07 a? 21.26.41.png
Type: image/png
Size: 74133 bytes
Desc: not available
URL: <https://list.indology.info/pipermail/indology/attachments/20240907/bd725762/attachment-0001.png>
-------------- next part --------------
A non-text attachment was scrubbed...
Name: Capture d?e?cran 2024-09-07 a? 21.41.20.png
Type: image/png
Size: 61743 bytes
Desc: not available
URL: <https://list.indology.info/pipermail/indology/attachments/20240907/bd725762/attachment-0002.png>
-------------- next part --------------
A non-text attachment was scrubbed...
Name: Capture d?e?cran 2024-09-07 a? 21.42.14.png
Type: image/png
Size: 64576 bytes
Desc: not available
URL: <https://list.indology.info/pipermail/indology/attachments/20240907/bd725762/attachment-0003.png>
