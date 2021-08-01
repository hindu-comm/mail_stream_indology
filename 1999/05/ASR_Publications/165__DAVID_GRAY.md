+++
title = "165 DAVID GRAY"
date = "1999-05-06"
upstream_url = "https://list.indology.info/pipermail/indology/1999-May/016820.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/1999-May/016820.html)

Indeed, do not open it!  Evidently it only infects windows computers,
not MACs.  The following is what Symantec's AVCenter has to say about
the virus:

Happy99.Worm
                                  VirusName:
                                              Happy99.Worm
                                     Aliases:
                                              Trojan.Happy99, I-Worm.Happy
                                  Likelihood:
                                              Common
                            Region Reported:
                                              World Wide
                              Characteristics:
                                              Trojan Horse, Worm



                            Description:

                            This is a worm program, NOT a virus. This
program has reportedly been received through email
                            spamming and USENET newsgroup posting. The
file is usually named HAPPY99.EXE in the
                            email or article attachment.

                            When being executed, the program also opens
a window entitled "Happy New Year 1999 !!"
                            showing a firework display to disguise its
other actions. The program copies itself as SKA.EXE
                            and extracts a DLL that it carries as
SKA.DLL into WINDOWS\SYSTEM directory. It also
                            modifies WSOCK32.DLL in WINDOWS\SYSTEM
directory and copies the original
                            WSOCK32.DLL into WSOCK32.SKA.

                            WSOCK32.DLL handles internet-connectivity in
Windows 95 and 98. The modification to
                            WSOCK32.DLL allows the worm routine to be
triggered when a connect or send activity is
                            detected. When such online activity occurs,
the modified code loads the worm's SKA.DLL. This
                            SKA.DLL creates a new email or a new article
with UUENCODED HAPPY99.EXE inserted into
                            the email or article. It then sends this
email or posts this article.

                            If WSOCK32.DLL is in use when the worm tries
to modify it (i.e. a user is online), the worm adds
                            a registry entry:
                               HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\RunOnce=SKA.EXE

                            The registry entry loads the worm the next
time Windows start.


                            Removing the worm manually:

                                1.delete WINDOWS\SYSTEM\SKA.EXE
                                2.delete WINDOWS\SYSTEM\SKA.DLL
                                3.in WINDOWS\SYSTEM\ directory, rename
WSOCK32.DLL to WSOCK32.BAK
                                4.in WINDOWS\SYSTEM\ directory, rename
WSOCK32.SKA to WSOCK32.DLL
                                5.delete the downloaded file, usually
named HAPPY99.EXE

                            Windows prevents you to do step #3 and #4
above if the machine is still connected to the Internet.
                            The file "windows\system\wsock32.dll" is
used whenever the machine is connected to Internet (i.e.
                            through dial-up or LAN connection).


                            If you are using dial-up connection (i.e.
America Online), you need to do the
                            following:

                                1.terminate internet connection
                                2.delete WINDOWS\SYSTEM\SKA.EXE
                                3.delete WINDOWS\SYSTEM\SKA.DLL
                                4.in WINDOWS\SYSTEM\ directory, rename
WSOCK32.DLL to WSOCK32.BAK
                                5.in WINDOWS\SYSTEM\ directory, rename
WSOCK32.SKA to WSOCK32.DLL
                                6.delete the downloaded file, usually
named HAPPY99.EXE


                            If you are connected to Internet through LAN
(i.e. in the office or cable modem),
                            you need to do the following:

                                1.From the Start menu, select
shutdown-restart in MS DOS mode
                                2.type CD \windows\system when DOS
prompt (C:\)appears
                                3.type RENAME WSOCK32.DLL WSOCK32.BAK
                                4.type RENAME WSOCK32.SKA WSOCK32.DLL
                                5.type DEL SKA.EXE
                                6.type DEL SKA.DLL



                            Safe Computing:

                                   This worm and other trojan-horse type
programs demonstrate the need to practice safe
                                   computing. One should not execute any
executable-file attachment (EXE, SHS, MS Word
                                   or MS Excel file) that comes from an
email or a newsgroup article from an untrusted
                                   source.

                            Norton AntiVirus users can protect
themselves from this virus by downloading the current virus
                            definitions either through LiveUpdate or
from the following webpage:

                            http://www.symantec.com/avcenter/download.html

                            Write-up by: Raul K. Elnitiarta
                            March 2, 1999



Ralph Bunker wrote:
>
> Make that I would NOT run it if I were you.
> At 06:39 AM 5/6/99 -0700, you wrote:
> >I received two messages with subject ASR Publications. The second one had
> >an attachment called HAPPY99.EXE. This is what my virus checker had to say
> >about it. I would run it if I were you.
> >
> >   Infected object c:\Eudora\Attach\HAPPY99.EXE.
> >   Happy99 trojan
> >   Cannot verify this virus.
> >



