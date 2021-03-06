Advanced Tremulous Combat Simulator
-----------------------------------

This is a map ported from the [Tremulous](http://tremulous.net/) game to the [Unvanquished](https://www.unvanquished.net/) game. It features a symetrical combat simulation to train new recruits in fighting the alien menace.

Ported from Tremulous gpp package from [http://ingar.satgnu.net/files/tremulous/base/](http://ingar.satgnu.net/files/tremulous/base/).

This port is an Interstellar Oasis initiative: [https://github.com/InterstellarOasis/InterstellarOasis](https://github.com/InterstellarOasis/InterstellarOasis).

Levelshot
---------

![Levelshot](meta/atcshd/atcshd_web.jpg)

How-to
------

* Get the source

```
git clone https://github.com/InterstellarOasis/map-atcshd_src.dpkdir.git
cd map-atcshd_src.dpkdir/
```

* Build

You need the [Urcheon](https://github.com/illwieckz/Urcheon) tool.  
You will find the dpkdir in `build/test`.

```
urcheon build
```

* Package

You will find the dpk in `build/pkg`.

```
urcheon package
```

Run the map:

```
daemon -pakpath build/pkg +devmap atcshd
```

Credits
-------

Unvanquished port:

* Thomas “illwieckz” Debesse <dev@illwieckz.net> (http://gg.illwieckz.net)

Mapping:

* Nicolas “Jex“ Jansens <jex@orodu.net>
* Stijn “Ingar“ Buys <ingar@osirion.org>
* Superpie

Textures:

* Georges "TRaK" Grondin
* Stijn “Ingar“ Buys
* Superpie

Sound effects:

* Stijn “Ingar“ Buys

Special thanks:

* Tim “Timbo” Angus <tim@ngus.net>
* Asa “Norfenstein” Kravets
* Dan “kharnov” Floda
* lakitu7
* ravyn
* Who-[Soup]

Legal
-----

Changes by Thomas Debesse fall under the Internet Systems Consortium License:  
http://directory.fsf.org/wiki/License:ISC

Assets by Tremulous contributors fall under the Creative Commons Attribution-ShareAlike 2.5 Generic License:  
http://creativecommons.org/licenses/by-sa/2.5/

Textures by Georges Grondin fall under the Creative Commons Attribution-ShareAlike 2.0 Generic License:
http://creativecommons.org/licenses/by-sa/2.0/

History
-------

* 2015-08-16:	Advanced Tremulous Combat Simulator 1.2 (Unvanquished community map)
* 2011-05-24:	Advanced Tremulous Combat Simulator 1.2 gpp2
* 2010-12-16:	Advanced Tremulous Combat Simulator 1.2 gpp1
* 2009-12-04:	Tremulous 1.2 Beta (Gameplay preview)
* 2006-03-31:	Tremulous 1.1.0 (Standalone)
* 2005-08-11:	Advanced Tactical Combat Simulator
