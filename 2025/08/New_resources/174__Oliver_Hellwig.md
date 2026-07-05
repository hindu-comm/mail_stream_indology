+++
title = "174 Oliver Hellwig"
date = "2025-08-28"
upstream_url = "https://list.indology.info/pipermail/indology/2025-August/061065.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2025-August/061065.html)

Dear all,

a few Sanskrit related resources have been published today:

* The initial version of the Vedic Prose Corpus (VPC), built in 
collaboration with K. Amano and S. Sellmer. Data available for download 
from github; more here:
https://github.com/OliverHellwig/sanskrit/tree/master/corpus/VPC

Note that this resource contains English machine translations for all 
texts (produced with Sebastian Nehrdich's MT model; files named 
qqq-mt.txt in the translation subfolders), and human translations 
aligned at sentence level for selected prose works.

* A slightly reformatted and lemmatized version of almost half of the 
last GRETIL release:
https://github.com/OliverHellwig/sanskrit/tree/master/corpus/GRETIL

General background information about both resources is given in their 
parent git directory ("Sanskrit text repository"):
https://github.com/OliverHellwig/sanskrit/tree/master/corpus

* Those working with Vedic prose might have a look at a new English 
search interface built on top of the VPC:
https://huggingface.co/spaces/OliverHellwig/vpcsearch

This tool lets you enter an English sentence and then searches for 
semantically related statements in Vedic prose - no Sanskrit, no 
questions, nothing generative! See the "How to use this search tool" 
section at the top of the tool.

* Finally, the lexicographic information from VPC and GRETIL has been 
integrated into the DCS, almost doubling the size of its corpus. Right 
now, the accessibility of this new data is somewhat limited. However, 
when searching a word (Query page), results from VPC and GRETIL are 
retrieved simultaneously and displayed under the header "Results for qqq 
from unsupervised lemmatization". Clicking this link gives you access to 
the relevant contexts and additional information about the occurrences.
While integrating this new data, I realized that the VPC search 
interface is almost unusable from smartphones and tablets. I hope this 
has been fixed to some extent, e.g. by introducing a new character 
encoding system (aa for long a etc.; follow the link "Diacritics" on the 
query page).


Best, Oliver

---

Oliver Hellwig
Institute for the Interdisciplinary Study of Language Evolution, 
University of Zurich
