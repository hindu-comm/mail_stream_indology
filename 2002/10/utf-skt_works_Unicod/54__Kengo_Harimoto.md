+++
title = "54 Kengo Harimoto"
date = "2002-10-14"
upstream_url = "https://list.indology.info/pipermail/indology/2002-October/027169.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2002-October/027169.html)

>> I checked Juergen's web site and cannot figure out how in the world I
>> would use those programs in OS X.
>
> It seems to me that if you have not previously used TeX or LaTeX then
> moving to this setup would be `non trivial' but well worth it ;-)

I just checked out the package.  Frst some comments:

- Even for those who have used the above, the package is non-trivial to
install :)  Wouldn't it be nice for someone to include a readme?  It is
not immediately obvious which file goes to where.  If one does not have
experience with teTeX, it seems impossible to install.

- Most files have funny permissions. (444 or 555: read only for even the
owner of the file).

- I'd prefer to have .pl for perl executables, but maybe it's just me.

> I have no experience with OS X but a search on Google gave this
> link. It lists your options if you wish to experiment:
>
>  http://www.masda.vxu.se/~pku/MacOSX_TeX/2002a/msg00382.html

The easiest thing would be just to go to

http://darkwing.uoregon.edu/~koch/texshop/texshop.html

and install TeXShop and teTeX.  Anything else can be safely ignored.
I'd think one'd better not bother with fink.  Perhaps one should get
used to simple LaTeX (not TeX) first.

Emacs comes with OS X by default.

So, in short, in order to use the utf-skt package on a Mac,

1) upgrade to OS X if it's not done yet.

2) install TeXShop along with teTeX.  (TeXShop does not work without
teTeX anyway.)

3) figure out which file from utf-skt package goes to where, and copy
the files to proper location.  (This defnitately requires least
knowledge of file manipulations on a UNIX-like system, as well as
knowledge of root, user, permission, home directory, and $PATH, etc.)

4) Read a lot of documents.

If this is too much,

0) just give up :)  (I might as well choose this path.)

--
kengo



