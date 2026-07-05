+++
title = "33 Dhaval Patel"
date = "2023-01-06"
upstream_url = "https://list.indology.info/pipermail/indology/2023-January/057173.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2023-January/057173.html)

Dear friends,

Kindly find attached the announcement of launch of a Sanskrit verb form
generator (vidyut-prakriya) from Mr. Arun Prasad, which may be of interest
to some of you.

QUOTE

नमो विद्वद्भ्यः --

*vidyut-prakriya* generates Sanskrit words by applying Paninian rules
step-by-step. Our long-term goal is for the program to generate all valid
Paninian words.

*Summary*
vidyut-prakriya is heavily indebted to the SanskritVerb
<https://groups.google.com/g/bvparishat/c/sm-lW9qj0A8> generator from Dr.
Dhaval Patel, I.A.S and Dr. Shivakumari Katuri, and we are grateful to the
authors for their encouragement in this project.

If you are familiar with SanskritVerb, vidyut-prakriya offers the following
improvements:

- It adds many more forms (जुगुप्सते etc, अतत etc, -आम्बभूव etc.)
- It fixes various small bugs.
- Its prakriyas generally have more detail, especially for it-Agama rules.
- It can run in a web browser without an internet connection.
- It is much faster. On my laptop, vidyut-prakriya can generate all
kartari-tinantas in about 4 seconds. This speed is especially useful for
testing and for natural language processing tools.
- It has partial support for sanAdi forms. These have not been tested very
much, so please use with caution.

*Code: *https://github.com/ambuda-org/vidyut/tree/main/vidyut-prakriya
*Demo*: https://ambuda-org.github.io/vidyullekha/-- click on a dhatu to see
its tinanta padas, and click on a pada to see its prakriya.

*Notes*:
We are sharing our system publicly so that we can collect feedback and
better discover bugs. Please share it widely so that we can collect more
feedback.

- For bug reports, please use https://github.com/ambuda-org/vidyut/issues .
- We are eager to partner with scholars and experts to better test our
system. If you are interested in working with us more closely, please
contact us at https://ambuda.org/contact.
- We have partial support for subantas and krdantas, but these are not
available in the demo yet.
- Testing was done by comparing our program to the output of SanskritVerb.
Most differences have been accounted for and are (we believe) in
vidyut-prakriya's favor, but a few small errors likely remain.

Regards,

Arun Prasad

UNQUOTE

-- 
Dr. Dhaval Patel
www.sanskritworld.in
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20230106/7b953d79/attachment.htm>
