# Windows11Long_Alexa🪟🛟
(Windows 11 Long Time Support Chanel - Hu "Alexa") 
<sup>Ez a kiadás a csatornámon levő Windows11H_Alexa tovább fejlesztéseként készült.</sup>

Letöltési hely: <tt><a href="https://mega.nz/file/1IRyhIjb#yxWI9-Kp8kTr20mcY-SOENL4KkLg6_sSioQc-Q5f4e8" target="_blank">Windows11Long_Alexa.iso (MEGA)</a> </tt>

<sup>iso fájl eredetiség ellenőrző összeg / SHA256:  <tt>322E77E35F3A6C3C8CA7FBD20E9424DB53A5DB54D6920E38BC7AC1F8CA4AC965</tt></sup>

A <tt>*Windows11Long_Alexa*</tt> Windows telepítő a gyári Microsoft Windows 11 Enterprise LTSC 2024 felhasználásával készült, gyorsabb, sokkal stabilabb, mint a Windows 11 Pro <sup>*számos, pl. youtube-n terjesztett független teszt bizonyítja</sup> (teljesen sallang mentes, de minden előnyt élvez, amit egy Windows rendszer tudhat, nagy előnye a 11 Pro-val szemben, hogy nem "zaklat" állandó "fícsör" vagy funkció frissítéssel, ami túl sokszor destabilizálja kiadásakor a Windows 11 Pro-t; a javítások végeláthatatlan sorának érkezéséig meg bosszankodik a felhasználó!). 
Minden Windows közül a leghosszabb távon (Long... 10 év!) támogatott, nem igényel manuális karbantartást, a kizárólag szolgáltatási és biztonsági frissítésekkel rendelkező update-k atombiztosak és betonstabilak.

Az "Alexa" ezt azzal fejeli meg, hogy a rendszer a gyáritól eltérően nem igényli a SecureBoot /biztonságos rendszerindítás/, TPM2 /biztonsági modul/, és egyéb olyan kritériumok betartását, ami miatt a Windows 11 "régi" gépekre nem telepíthető. (Az elvárás annyi, hogy legyen a gépben lehetőleg 4 GB RAM / ~64 GB üres tárhely, és lehetőleg BIOS/EFI rendszerbetöltő. Slussz.😁😁😁 Netezés, stream/youtube, netflix, stb., játék, Office szövegszerk., stb... amire egy "mezei" felhasználó vágyik...)

<a href="https://m.youtube.com/watch?v=Z-8IMalnQ2E" target="_blank">
📽️youtube: Long Alexa</a>
<object data="https://m.youtube.com/watch?v=Z-8IMalnQ2E"></object>

Telepítési útmutató:

🛠️
1. Töltsd le fenti linken az iso fájlt (4.68GB), majd a Balena Etcher-t  <a href="https://github.com/balena-io/etcher/releases/download/v2.1.0/balenaEtcher-2.1.0.Setup.exe">ide kattintva.</a>  | ⛔ Kivételesen NE használj ehhez a telepítőhöz Rufust! ⛔.

2. Csatolj egy legalább 8 GB-os USB adattárolót a gépedhez. Ne legyen semmi fontos dolog a 'pendrájvon', mert törölve lesz minden🚩 /telepítés után formázással újra használható/, indítsd el a Balena Etcher-t.

3. Válaszd ki a [Flash from File]-t, tallózd be a fentről letöltött ISO fájlt. A [Select Target] gombbal válaszd ki írásra az USB tárolód. [Flash] gombbal indítsd el az ISO kiírását, azaz indítható Windows telepítő készítést az USB-re (5-8 perc az írás).

4. Csatold az USB tárolót ahhoz a géphez, amelyikre Windowst akarsz telepíteni.

5. Indítsd el a gépet Boot menü-vel (ez legtöbb gépen a gépgyártó logó megjelenésekor <code>Esc, Del, F2, F8, F9, F10, F12</code> billentyűvel megy, ha nem vagy biztos benne, keress rá a neten a Tiedre).

6. Válaszd ki rendszer betöltéshez (boot) az USB tárolót, elindul a Windows 11 telepítő (lehet, hogy a boot menü Mass Storage néven mutatja az USB-t).

7. Haladj végig a magyar nyelvű telepítő egyszerű lépésein. A telepítés elején: partícionálásnál ügyelj, hogy mit választasz, legjobb minden partíciót törölni (Delete) a tiszta telepítéshez (előtte ments minden fontos dolgot a lemezről, mert teljes törlés lesz). (Ajánlott legalábbis 64 GB üres hely.) Ezen kívül csak felhasználó nevet kell majd választanod, minden más automatikus. KÉSZ. Időigény: kb. 20 perc internet kapcsolat nélkül (igen, ez is lehetséges a gyári telepítőtől eltérően!), átlagos internet sebesség és régebbi proci + SSD esetén + 2-3 perc.

😈 A telepítésből KIMARAD 💩 :

SecureBoot és TPM2 ellenőrzés, RAM minimum ellenőrzés (a gyártói telepítő ezek nélkül nem működik részletek);
Windows haszontalanságok: nyomkövető és reklám programok, egyéb "hulladék" ~50 szoftver;
online Microsoft fiók (az "élénk online érdeklődés" elhárítására); helyi fióknév (rendszergazda) választás és felhasználó fiók létrehozás történik;
online kapcsolat követelése (de ha akarod, van lehetőség internet kapcsolattal telepíteni [ajánlott]).

😎 Ami BENNE van 👀 :

Hosszú távú automatikus rendszer frissítés a stabilitáshoz, biztonsághoz...

.Alexa mappa: Microsoft aktivátor és nagyszerű/egyszerű programok (pl. Chrome, VLC, Xnview, MS Office, ChrisTitusTech, stb) telepítésének lehetősége (🥳NEM KÖTELEZ TÉGED semmire! Akár törölhető is 1 kattintással).
🥇intel driver telepítő, és AMD driver telepítő, DirectX telepítő (pl. játékosoknak)... 💥

<sub>Egy rendkívül kellemes használati tapasztalat a Long_Alexával: bár eredetileg a build frissítést letiltottam a telepítőben, de visszakapcsolás esetén végrehajtja a Windows Update /26100.4351 build-re/, és <i>Windows 11 IoT Enterprise</i>-ra vált, ami 5 helyett 10 évig élvezi a MS támogatást👍😁! /A Long_Alexa telepítő azért nem készült IoT-alapon, mert az kizárólag angol nyelven létezik./ A Microsoft heves érdeklődésének korlátozását és a Windows rendszer optimalizálását tovább növeltem telepítés után a github.com-on lévő Crap Fixer (❁´◡`❁) programcsomaggal is.</sub>

<sup>⚠*Bátrabb, tapasztalt felhasználóknak. Külön partícióra másolva az ISO kibontott tartalmát, onnan a setup.exe-vel indítva is működik a telepítés, 2. Windowsként, dual boot módban az 1.-vel. A Long Alexa jelenleg az alábbi gépen/notebook-on szárnyal: 7.gen.intel CPU, integrált GPU, NVME SSD</sup>
<hr>
<tt>💻A szerző nem informatikai szakember, de 30 éve foglalkozik Windows-sal, elkötelezett a "személyreszóló" Windows telepítéshez biztonságos, stabil eszközök és módszerek használatára, ez a Windows ilyen. (😎A telepítő ingyenes, és az is marad!💝)</tt>
