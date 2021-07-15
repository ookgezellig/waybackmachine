# Saving KB-managed websites to the Wayback Machine

## Updated wbm-archiver script - 15-7-2021
On 15-7-2021 I have checked if the [wbm-archiver script from 2 years ago](Literatuurplein/scripts/wbm-archiver/SaveLiteratuurpleinToWaybackMachine.py) was still working. It turned out this was not the case, so I did a small [update of the script](wbm-archiver_15072021/SaveToWaybackMachine.py) to make it work again. However, this script is still not 100% stable or trustworthy and ideally should be checked by a proper developer with knowledge about the WBM and the [Memento protocol](http://mementoweb.org/guide/rfc/) that is used in the WBM. 

It is also noted that the updated script seems to work much slower than 2 years ago, archiving 10 URLs takes approx 1-2 minutes now, while 2 years ago it was approx. 10-20 seconds. This is due to the reduced archiving speed of the WBM itself (this should be verified), not because the updated script itself works slower now. 

So if you plan to archive 10.000s URLs (such as for kb.nl, later in 2021), this will probably take a very long time, and you will probably have to deal with many timeouts, connection failures and errors.

## To be archived sites
* kb.nl: planned for November 2021

## Archived sites 
* [Literatuurplein.nl](https://github.com/ookgezellig/SaveToWaybackMachine/tree/master/Literatuurplein)
* [Leesplein.nl](https://github.com/ookgezellig/SaveToWaybackMachine/tree/master/Leesplein)
* [Lezenvoordelijst.nl](https://github.com/ookgezellig/SaveToWaybackMachine/tree/master/LezenVoorDeLijst)
<!--* [Literaireprijzen.nl](https://github.com/ookgezellig/SaveToWaybackMachine/tree/master/LiterairePrijzennl)-->
* [Gidsvoornederland.nl](https://www.gidsvoornederland.nl/werken-met-gids/meerwaarde-voor-bibliotheken/bibliotheken-in-nederland) (section with information about public libraries in the Netherlands)

## What this repo does
Some websites managed by the KB have been or will be discontinued. To preserve the content of the site (e.g. for sourcing Wikipedia articles) a copy was/will be submitted to The Wayback Machine (web.archive.org).
