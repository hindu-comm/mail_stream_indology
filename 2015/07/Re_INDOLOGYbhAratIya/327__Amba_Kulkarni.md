+++
title = "327 Amba Kulkarni"
date = "2015-07-16"
upstream_url = "https://list.indology.info/pipermail/indology/2015-July/041535.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2015-July/041535.html)

Dear Dhaval Patel,

Thanks for sharing this.

I have a question: Is the test data different from the training?

I assume you have referred to the following two works:

   1. Statistical Constituency parser for Sanskrit compounds
   <http://sanskrit.uohyd.ernet.in/faculty/amba/PUBLICATIONS/samaasa_const_parser_icon2011.pdf>
   Amba Kulkarni and Anil Kumar, ICON 2011, Chennai Dec 18-19
   2. Clues from Astadhyayi for compound identification
   <http://sanskrit.uohyd.ernet.in/faculty/amba/PUBLICATIONS/scti-5scls.pdf>
   Amba Kulkarni and Anil Kumar, 5th international SCLS 2013, Mumbai

The first one reports the performance of the system, using only simple
probabilities.

The performance figures for 56 tags were as follows:

Rank      With 55 tags       With 8 tags
1                   63.0%               72.7%
2                   10.9%               13.2%
3                     7.2%                 9.5%

where Rank indicates the position of the correct solution among all
possible solutions.

The second one uses clues from the A.s.taadhyaayii to detect the compound
type of rare compounds, and the performance was 61%  times we got the first
guess correct, and if we allow 3 guesses, 81% one among the 3 guesses were
correct.

With regards,
Amba Kulkarni


On 16 July 2015 at 00:03, dhaval patel <drdhaval2785 at gmail.com> wrote:

> Respected scholars,
> Recently I have modified one Artificial neural net code for identification
> of samAsas in Sanskrit language.
> https://github.com/drdhaval2785/SamaasaClassification is the code
> location.
>
> The results are very encouraging.
> Without feeding any rule to the computer, the following is the
> classification result
>
> 1. Major 5 samAsa types classification - 70%
> 2. Minor 55 samAsa subtypes classification - 55 %.
> 3. Major 5 samAsa types classification taking the first two entries - 85 %.
>
> Probability of a fluke would be 1 - 20 %, 2 - 0.2 %, 40 %.
>
> So, the machine learning is statistically significant, if not good enough.
>
>
> The database which was used was scraped from
> http://sanskrit.uohyd.ernet.in/Corpus/SHMT/Samaas-Tagging/ and randomly
> shuffled to homogenize the dataset.
>
> The tool was developed for samAsa classification initially, but now
> generalized for any string classification problem.
>
> Hope the scholars would like the tool.
>
> For those interested in Artificial neural networks, the link is
> http://neuralnetworksanddeeplearning.com/
>
>
>
> --
> Dr. Dhaval Patel, I.A.S
> Collector and District Magistrate, Anand
> www.sanskritworld.in
>
> --
> निराशीर्निर्ममो भूत्वा युध्यस्व विगतज्वरः।। (भ.गी.)
> ---
> You received this message because you are subscribed to the Google Groups
> "भारतीयविद्वत्परिषत्" group.
> To unsubscribe from this group and stop receiving emails from it, send an
> email to bvparishat+unsubscribe at googlegroups.com.
> To post to this group, send email to bvparishat at googlegroups.com.
> Visit this group at http://groups.google.com/group/bvparishat.
> For more options, visit https://groups.google.com/d/optout.
>



-- 
आ नो भद्रा: क्रतवो यन्तु विश्वत: ll
Let noble thoughts come to us from every side.
- Rig Veda, I-89-i.
Assoc Prof.
Department of Sanskrit Studies
University of Hyderabad
Prof. C.R. Rao Road
Hyderabad-500 046

(91) 040 23133802(off)

http://sanskrit.uohyd.ernet.in/scl
http://sanskrit.uohyd.ernet.in/faculty/amba


-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20150716/fffdac20/attachment.htm>
