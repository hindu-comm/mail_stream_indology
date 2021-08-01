+++
title = "38 Peter Schreiner"
date = "2019-11-15"
upstream_url = "https://list.indology.info/pipermail/indology/2019-November/051324.html"

+++
[Archive link](https://list.indology.info/pipermail/indology/2019-November/051324.html)

Kann mir jemand, bitte, die folgende Fehlermeldung (voller mir nicht 
vertrauter Termini und jedenfalls kein TUSTEP-Format) erklären, die von 
der darunter reproduzierten Prozedur (welche früher funktioniert hatte; 
sie stammt letztlich aus der Feder von Herrn Ott und dient dazu, die 
Devanagari-Schrift in die zu druckende Datei, in der sie vorkommt, 
einzubinden) ausgelöst wird. Wenn diese Meldung erscheint, ist der 
Computer blockiert und es bleibt nur Neustart...

"TUSTEP API function failed

Error in Resize from function sw2:

Kein Prozess ist am anderen Ende der Pipe"

= = = = =

#an,,?1.ps
#an,daten*xdvng.pfa
#da,?1_i.ps,sdf-ap

#makro
$$ set actps = FULL_NAME (TUSTEP, "?1.ps", -STD-)
$$ set fullps = FULL_NAME (TUSTEP, "?1_i.ps", -STD-)
$$ set fntlib = "c:\daten"
$$ execute *
copy "<fntlib>\xdvng.pfa" + <actps> <fullps>"
*eof

#- zum Anschauen in GhostView
#*zeps,?1_i.ps

#- zum Ausdrucken
#*psdr,?1_i.ps,ger=-std-,anz=1,op=-std-

= = = = =

Vielen Dank im voraus!

Peter Schreiner

-- 
Peter Schreiner
Chemin de Boracles 94
1008 Jouxtens-Mézery
Switzerland

Tel. +41-21-635 0365
mobile: +41-76-422 0365
email: peter.schreiner at aoi.uzh.ch





