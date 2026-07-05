+++
title = "95 Sebastian Nehrdich"
date = "2023-02-27"
upstream_url = "https://list.indology.info/pipermail/indology/2023-February/057342.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2023-February/057342.html)

Dear list members,

In the context of the BMBF project "ChronBMM - Dating text corpora
using Bayesian Mixture Models" (https://chronbmm.phil.hhu.de/) Oliver
Hellwig, Sven Sellmer and I have developed a number of contextual
language models based on the XLM-RoBERTa architecture that achieve
very strong performance on a host of downstream tasks.
We make two of these models available on our organization on Hugging
Face: https://huggingface.co/chronbmm

One is a multidomain general Sanskrit model trained on more than 2GB
of web-scraped Sanskrit material from various sources (manually typed
etexts as well as OCR input). The second model is a specific model
fine-tuned on a corpus of Vedic Sanskrit which achieves SOTA on POS
tagging,  dependency parsing, and other related tasks. Both models
accept Devanagari as input. No further preprocessing such as Sandhi
splitting is necessary.
With best regards,

Sebastian
