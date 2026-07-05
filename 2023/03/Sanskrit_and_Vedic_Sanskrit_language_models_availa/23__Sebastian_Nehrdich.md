+++
title = "23 Sebastian Nehrdich"
date = "2023-03-13"
upstream_url = "https://list.indology.info/pipermail/indology/2023-March/057368.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2023-March/057368.html)

Dear Dominik, dear list members,

Sure. The models are published on HuggingFace, which is a hub for deep
learning models of various kinds, a lot of them aimed at natural
language processing tasks.
Both models are of the RoBERTa-architecture, which is very similar to
BERT. A description of what BERT is and what it can do can be found
here: https://huggingface.co/blog/bert-101
BERT can be described as a medium size language model in contrast to
large language models such as GPT(3) which have been heavily in the
news over the last couple of months
The models we trained for Sanskrit and Vedic Sanskrit are especially
suited for tasks such as sentence classification, tagging (POS,
morpho-syntax) and dependency parsing.
It needs to be noted however that the models on Hugging Face are not
yet finetuned on any of these tasks, and we didn't yet release
ready-to-use code to do POS tagging etc.
So these models can be used as a basic building block in order to
create a Sanskrit processing pipeline, but they are not yet useful for
downstream applications without finetuning.
I hope this is helpful!
With best wishes,

Sebastian

On Mon, Mar 13, 2023 at 8:13 PM Dominik Wujastyk <wujastyk at gmail.com> wrote:
>
> Dear Sebastian,
>
> I think it would be useful to members of this forum to receive - in addition - a simpler explanation of the remarkable results you and your colleagues have achieved.  Could you do that, including a practical guide to how the ordinary jobbing Indologist can use what you have done for practical purposes in daily work?
>
> With thanks,
> Dominik
