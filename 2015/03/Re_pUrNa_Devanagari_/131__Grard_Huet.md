+++
title = "131 Gérard Huet"
date = "2015-03-13"
upstream_url = "https://list.indology.info/pipermail/indology/2015-March/040838.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2015-March/040838.html)

I think Pr Hock is right, it is a platform problem.

The devanaagarii rendering of the OSX rendering engine is incorrect in the handling of halant in several corner cases.
For instance, the conjunct consonant cCr is incorrectly handled. You may check by this test. When you look at the source of the page, you see the UTF8 encoding of tacCrutvA as:
&#x0924;&#x091A;&#x094D;&#x091B;&#x094D;&#x0930;&#x0941;&#x0924;&#x094D;&#x0935;&#x093E;
corresponding to: tc,C,rut,v
noting "," for virama, and clearly the second virama is incorrectly handled.

I sent an anomaly report on this problem at the official Apple site [http://www.apple.com/fr/macosx/feedback/] on January 28th 2007. It was never acknowledged nor fixed,
through the successive versions of OS X. The rendering of this example is wrong also on my iPhone. So it looks that they fixed Peter's bug but not mine on the iPhone OS…

GH


Le 13 mars 2015 à 23:09, "Hock, Hans Henrich" <hhhock at illinois.edu> a écrit :

> Here is an almost immediate confirmation of my hunch that this is a platform issue. While the message showed the virāma on my iPhone, it does not do so on my MacBook Air. 
> 
> Go figure …
> 
> Hans Henrich
> 
> 
> On 13 Mar 2015, at 13:34, Peter Scharf <scharfpm7 at gmail.com> wrote:
> 
>> Dear indologists,
>> We noticed a quirk in the display of puur.n virAma (i.e. in the Sanskrit Library phonetic ascii encoding pUrR = KH pUrN) in Devanagari and wonder whether anyone has seen this display properly in a webpage with the proper characters.  Here is the Devanagari qwerty input:
>> 
>> पूर्ण This is p U r f N
>> पूर्ण् This is p U r f N f
>> 
>> As you can see they are identical.
>> 
>> पूर्ण्‌् This is p U r f N f f f
>> Finally the virAma displays, but it should not require three virama characters to do so.
>> Thanks for your help.
>> Yours,
>> Peter
>> 
>> *************************
>> Peter M. Scharf
>> scharfpm7 at gmail.com
>> *************************
>> 
>> _______________________________________________
>> INDOLOGY mailing list
>> INDOLOGY at list.indology.info
>> http://listinfo.indology.info
> 
> _______________________________________________
> INDOLOGY mailing list
> INDOLOGY at list.indology.info
> http://listinfo.indology.info



-------------- next part --------------
An HTML attachment was scrubbed...
URL: <https://list.indology.info/pipermail/indology/attachments/20150314/bb063e9d/attachment.htm>
