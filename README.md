# Windows11Long_Alexa
Windows 11 Hun LTSC "Alexa"

Letöltési hely: ...hamarosan itt ...

A *Windows11Long_Alexa* Windows telepítő a gyári Windows 11 Enterprise LTSC 2024 felhasználásával készült, gyorsabb, stabilabb, mint a Windows 11 Pro (teljesen sallang mentes, de minden előnyt élvez, amit egy Windows rendszer tudhat). Minden Windows közül a leghosszabb távon (5 év) támogatott, nem igényel manuális karbantartást, az automatikus rendszer frissítések "atombiztosak", mert felesleges "fícsöröktől" mentesek. (Az "Alexa" ezt csak azzal fejeli meg, hogy a rendszer a gyáritól eltérően nem igényli a SecureBoot /biztonságos rendszerindítás/, TPM2 /biztonsági modul/, és egyéb olyan kritériumok betartását, ami miatt a Windows 11 "régi" gépekre nem telepíthető. (Az elvárás annyi, hogy legyen a gépben 4 GB RAM / kb. 64 GB üres tárhely, és lehetőleg BIOS/EFI rendszerbetöltő. Slussz.😁😁😁)

Telepítési útmutató:

#🛠️⚙️
Töltsd le fenti linken az iso fájlt (< 5GB), majd a Balena Etcher-t közvetlenül ide kattintva. | ⛔ Kivételesen NE használj ehhez a telepítőhöz Rufust! ⛔.

Csatolj egy legalább 8 GB-os USB adattárolót a gépedhez. Ne legyen semmi fontos dolog a 'pendrájvon', mert törölve lesz minden🚩 /telepítés után formázással újra használható/, indítsd el a Balena Etcher-t.

Válaszd ki a [Flash from File]-t, tallózd be a fentről letöltött Win11H_Alexa ISO-t. A [Select Target] gombbal válaszd ki írásra az USB tárolód. [Flash] gombbal indítsd el az ISO kiírását, azaz indítható Windows telepítő készítést az USB-re (5-8 perc az írás).

Csatold az USB tárolót ahhoz a géphez, amelyikre Windowst akarsz telepíteni.

Indítsd el a gépet Boot menü-vel (ez legtöbb gépen a gépgyártó logó megjelenésekor Esc,Del,F2,F8,F9,F10,F12 billentyűvel megy, ha nem vagy biztos benne, keress rá a neten a Tiedre).

Válaszd ki rendszer betöltéshez (boot) az USB tárolót, elindul a Windows 11 telepítő (lehet, hogy a boot menü Mass Storage néven mutatja az USB-t).

Haladj végig a magyar nyelvű telepítő egyszerű lépésein. A telepítés elején: partícionálásnál ügyelj, hogy mit választasz, legjobb minden partíciót törölni (Delete) a tiszta telepítéshez (előtte ments minden fontos dolgot a lemezről, mert teljes törlés lesz). (Ajánlott legalábbis 64 GB üres hely.) Ezen kívül csak felhasználó nevet kell majd választanod, minden más automatikus. KÉSZ. Időigény: kb. 25 perc internet kapcsolat nélkül (igen, ez is lehetséges a gyári telepítőtől eltérően!), átlagos internet sebesség és régebbi proci + SSD esetén + 2-3 perc.

😈 A telepítésből KIMARAD 💩 :

secureboot, és TPM2 ellenőrzés, RAM minimum ellenőrzés (a gyártói telepítő ezek nélkül nem működik részletek);
Windows haszontalanságok: nyomkövető és reklám programok, egyéb "hulladék" ~50 szoftver, lásd a csatolt fájlban; (⛔ emiatt utólag felesleges külső debloating és disable telemetry, meg hasonló parancs programok használata)
online Microsoft fiók (az "élénk online érdeklődés" elhárítására); helyi fióknév (rendszergazda) választás és felhasználó fiók létrehozás történik;
online kapcsolat követelése (de ha akarod, van lehetőség internet kapcsolattal telepíteni [ajánlott]).

😎 Ami BENNE van 👀 :

Hosszú távú automatikus rendszer frissítés a stabilitáshoz, biztonsághoz...

.Alexa mappa: MS aktivátor és nagyszerű/egyszerű programok (pl. Chrome, VLC, Xnview, MS Office, ChrisTitusTech, stb) telepítésének lehetősége (🥳NEM KÖTELEZ TÉGED semmire! Akár törölhető is 1 kattintással).
🥇intel driver telepítő, és AMD driver telepítő, DirectX telepítő... 💥Telepítés után azonnal ajánlott a procidnak megfelelő driver telepítés. (Az .Alexa mappa külön is megtalálható az iso letöltőhelyen, érdemes letölteni és a benne lévő újabb fájlokat a régiek helyére/mellé beemelni, használni az új vagy régebbi Windowson) ✅ Telepítve az alábbi gépen: intel i3 7.gen CPU /elavult/, integrált GPU, 16 GB DDR4 RAM, 64 GB SSD tárhely.✅ Jól funkcionál!
⚠*Bátrabb, tapasztalt felhasználóknak. Külön partícióra másolva az ISO kibontott tartalmát, onnan a setup.exe-vel indítva is működik a telepítés, 2. Windowsként, dual boot módban az 1.-vel.

💻A szerző nem informatikai szakember, de 30 éve foglalkozik Windows-sal, elkötelezett a "személyreszóló" Windows telepítéshez biztonságos, stabil eszközök és módszerek használatára, ez a Windows ilyen. (😎A telepítő ingyenes, és az is marad!💝)
