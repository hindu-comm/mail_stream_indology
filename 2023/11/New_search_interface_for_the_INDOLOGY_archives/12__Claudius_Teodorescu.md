+++
title = "12 Claudius Teodorescu"
date = "2023-11-02"
upstream_url = "https://list.indology.info/pipermail/indology/2023-November/058378.html"
+++
[Archive link](https://list.indology.info/pipermail/indology/2023-November/058378.html)

Hi,

I have also added to the documentation details about the search for
expressions and proximity search:

Search for expressions

Is it possible to search for expressions by surrounding them with double
quotes.

Is it also possible to make more refined search for expressions, by using
the proximity search, which implies to find search terms separated a
maximum or an exact number of words. For each of these searches, one can
select if the words will be searched for in the same order they are
entered, or not.

The syntax is as follows:

   1. exact number of words, ordered, with two words between the search
   terms: yoga o-exact/2 ayurveda
   2. exact number of words, unordered, with two words between the search
   terms: yoga u-exact/2 ayurveda
   3. maximum number of words, ordered, with maximum two words between the
   search terms: yoga o-max/2 ayurveda
   4. maximum number of words, unordered, with maximum two words between
   the search terms: yoga u-max/2 ayurveda


On Thu, 2 Nov 2023 at 09:30, Claudius Teodorescu <
claudius.teodorescu at gmail.com> wrote:

> Dear all,
>
>
> I received some remarks on the search interface, which I would like to
> answer as follows:
>
> 1. Search by words with capitals: the search string is now lower-cased, so
> it also works for words with capitals.
>
> 2. The "exact search" box is implicit, so it will not pass into not
> selected state when the user selects any of the other options, for the
> reason that, in case when there are not suggestions at all, besides the
> exact term, the user will still get the exact term, if any.
>
> 3. To search for words like "paśupata", it is enough to select the "one
> difference" search type, and the list of three suggestions is displayed
> (pa?upata, pasupata, pazupata); afterwards, one can search by any of these
> suggestions by selecting it and clicking the "Search by suggestions" button.
> By selecting the "two differences" search type, the list of suggestions is
> larger, but still interesting: p??upata, pa?upata, pa?upati, paazupata,
> padapata, parpata, pashupata, pasupata, pasupatas, pasupatha, pazupata,
> pazupatas, pazupati.
> Finally, by selecting the ngram search type, the suggestion list is as
> follows: p??upata, pa?upata, paashupata, paazupata, padarthatattvanirupana,
> pashupata, pasupata, pasupatasutra, pazupata, prakritararupavatara,
> prakrtarupavatara.
> The search types can be combined.
>
> Thanks to Mr. Harry Spier for the remarks!
>
> Best regards,
> Claudius Teodorescu
>
>
> On Thu, 2 Nov 2023 at 00:55, Dominik Wujastyk via INDOLOGY <
> indology at list.indology.info> wrote:
>
>> I'm delighted to announce that our colleague Claudius Teodorescu has been
>> addressing the issue of searching the archive of Indology messages.
>> Applying his formidable computing skills to the problem, he has provided a
>> new interface that successfully searches the whole archive from 1994 to
>> 2020.  The interface is here:
>>
>>    - https://wujastyk.github.io/INDOLOGY-forum-website/
>>
>> and I have also added a link on the main INDOLOGY.info page,
>>
>> [image: indologymenu.png]
>>
>> I believe Claudius will be extending the database to include posts from
>> 2020 to the latest ones.
>>
>> With the most sincere thanks to Claudius for this very helpful feature!
>>
>> Dominik
>>
>> Dominik Wujastyk
>> INDOLOGY list <http://indology.info> committee member
>> *Please do not reply to me personally: re*ply to
>> indology-owner at list.indology.info
>>
>> _______________________________________________
>> INDOLOGY mailing list
>> INDOLOGY at list.indology.info
>> https://list.indology.info/mailman/listinfo/indology
>>
>
>
> --
> Cu stimă,
> Claudius Teodorescu
>


-- 
Cu stimă,
Claudius Teodorescu
-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20231102/f8766be9/attachment.htm>
-------------- next part --------------
A non-text attachment was scrubbed...
Name: indologymenu.png
Type: image/png
Size: 40558 bytes
Desc: not available
URL: <https://list.indology.info/pipermail/indology/attachments/20231102/f8766be9/attachment.png>
