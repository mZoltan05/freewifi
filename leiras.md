#Leírás
A projekt egy OpenWrt az eszközünkre való telepítésével kezdődik.
(Támogatott eszközök listája:http://wiki.openwrt.org/toh/start , 
Telepítéshez tartozó általános leírás: http://wiki.openwrt.org/hu/doc/howto/generic.flashing )
     Az OpenWrt néhány beállítását a WEB felületén keresztül(LuCi) könnyedén elvégezhetjük.
![Alt text](https://github.com/mZoltan05/freewifi/blob/master/OpenWrt.png "LuCi")
SSH-n keresztül elérhetjük az eszközünket, ahová "root" felhasználónévvel és a LuCi-n beállított 
jelszóval léphetünk be.

Egy opkg csomagkezelővel való frissítés után fel is telepíthetjük a nekünk kellő programot, a NoDogSplash-t.

( https://github.com/nodogsplash/nodogsplash , http://wiki.openwrt.org/doc/howto/wireless.hotspot.nodogsplash)

![Alt text](https://github.com/mZoltan05/freewifi/blob/master/sshOpenWrt.png "sshnopenwrt")

A NoDogSplash-t a(z) "/etc/nodogsplash" könyvtárban szabhatjuk személyre.
A Config fájlban bő leírás van. A(z) "/etc/nodogsplash/htdocs/" könyvtárban lévő "splash.html" fog minket belépéskor fogadni.




