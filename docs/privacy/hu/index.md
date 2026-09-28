# A 8 Ball adatvédelmi szabályzata

**Hatálybalépés dátuma:** 2026. szeptember 15.

**Utolsó frissítés:** 2026. szeptember 15.

## Röviden

A 8 Ball semmit sem gyűjt és nem továbbít. Ez egy Apple Watch-alkalmazás, amely
egyáltalán nem tartalmaz hálózati kódot: nincs szerver, nincs fiók, nincs analitika,
nincs hirdetés, nincs nyomkövetés, és nincs harmadik féltől származó SDK sem. A
kérdésedet soha nem gépeled be sehova, így az alkalmazás soha nem kapja meg. Az
egyetlen dolog, amit elment, a kiválasztott kinézet, embléma és nyelv, és ezeket az
órádon tárolja.

## Kik vagyunk

A 8 Ball-t ("az alkalmazás") **IVAN CAYABYAB** fejleszti ("mi", "minket").

Ha bármilyen kérdésed van ezzel a szabályzattal vagy az adataid védelmével
kapcsolatban, írj nekünk a **ivnsjdev@gmail.com** címre.

## Mit tárol a 8 Ball, és hol

A 8 Ball egy jósgömb: feltész egy igen-nem kérdést, megrázod, és megjelenik az egyik
a húsz válasz közül. A Beállításokban választható három dolgot az órád tárolja, a
watchOS szabványos alkalmazásbeállítás-tárolóját használva. Ezeket soha nem kapjuk
meg.

| Mit tárol a 8 Ball | Elsődleges tárhely | Automatikusan elküldve nekünk? |
| --- | --- | --- |
| A gömbhöz választott kinézet | Az órádon | Nem |
| A vállára választott embléma | Az órádon | Nem |
| A Beállításokban kiválasztott nyelv | Az órádon | Nem |

Ez a teljes lista. Semmi más nincs: nincs profil, nincs azonosító, nincs
használatszámláló, és nincs napló arról, hogy mit kérdeztél vagy mit válaszolt neked.
Az alkalmazás ezek közül semmit nem továbbít nekünk vagy más cégnek, és mi sem
gyűjtjük, adjuk el, adjuk bérbe vagy osztjuk meg ezeket. Az eszköz-biztonsági
mentéseket az operációs rendszer vezérli, nem a 8 Ball kezdeményezi.

## A kérdésedet soha nem gyűjtjük, mert sosem adod meg

A 8 Ballnak nincs szövegmezője, nem használja a mikrofont, és nincs diktálás sem.
Hangosan vagy magadban teszed fel a kérdést a gömbnek, és az alkalmazás soha nem
tudja meg, mit kérdeztél — nincs olyan bemenet, amin keresztül ez megérkezhetne
hozzá. A húsz válasz közül véletlenszerűen választ egyet, a kérdés bármiféle
ismerete nélkül.

## A választ sem őrzi meg

A képernyőn megjelenő válasz csak addig létezik a memóriában, amíg látható.
Szándékosan soha nem kerül tárolásra, nincs előzmények képernyő, és eltűnik, amikor
az alkalmazás bezárul. Munkamenetek között semmi nem halmozódik fel.

Amíg az óra az Always-On elhalványított állapotában van, a válaszablak
adatvédelmi szempontból érzékenynek van megjelölve, így a watchOS elrejti azt,
amíg fel nem emeled a csuklódat. Aki csak futólag ránéz egy leengedett csuklóra,
nem olvashatja el a válaszodat.

## Nincs fiók, nincs bejelentkezés, nincs felhő

A 8 Ballnak nincsenek felhasználói fiókjai, és nincs mire regisztrálni. Nem kér
e-mail-címet, telefonszámot, születési dátumot vagy bármilyen más fiókazonosítót.
Nem használ iCloud-ot, CloudKit-et vagy bármilyen más szinkronizálási szolgáltatást,
így a kinézeted, emblémád és nyelved nem utazik az eszközök között. Ez egy önálló
óra-alkalmazás, amelynek nincs kísérő iPhone-alkalmazása, így semmit nem oszt meg
egy telefonnal. Az operációs rendszer eszköz-biztonsági mentése tartalmazhatja a
8 Ball helyi alkalmazásadatait, ha úgy döntöttél, hogy biztonsági mentést készítesz
az eszközről.

## Mozgás, és miért nincs engedélykérő ablak

Ahhoz, hogy észlelje a rázást, a 8 Ball beolvassa az óra mozgásérzékelési adatait —
pontosabban a felhasználói gyorsulás vektorát, amely a csuklód mozgása a gravitáció
már eltávolított hatásával. Ezt akkor mintavételezi, amikor a gömb a képernyőn van,
azonnal megvizsgálja, hogy eldöntse, történt-e szándékos rázás, majd elveti. Nem
rögzíti, nem tárolja és nem továbbítja, és semmi másra nem használja, mint a
pörgetés elindítására.

A watchOS nem zárja el ezt az adatot egy engedélykérő ablak mögé úgy, ahogyan az
iOS teszi, ezért nem jelenik meg semmilyen kérés, és az alkalmazás mozgáshasználati
leírás nélkül kerül kiadásra: egy olyan célszöveg megadása, amit a rendszer soha
nem mutat meg, félrevezető lenne, nem pedig informatív. A Csuklóérzékelés vagy az
Always-On bekapcsolása az óra egyik beállítása, nem valami, amit a 8 Ball kér.

## Engedélyek, amelyeket nem kérünk

A 8 Ball egyáltalán nem kér semmilyen rendszerengedélyt. Nem fér hozzá a
kamerádhoz, fényképtáradhoz, mikrofonodhoz, helyadataidhoz, névjegyeidhez,
naptáradhoz, egészségügyi vagy edzésadataidhoz, értesítéseidhez vagy a Sirihez, és
soha nem jelenik meg semmilyen engedélykérő ablak.

## Hang, haptika és a Digital Crown

A 8 Ball nem játszik le hangot. A visszajelzés haptikus — három koppintás, amíg a
gömb gondolkodik, egy a válasznál —, az Apple szabványos óra-haptikáján keresztül.
A Digital Crown elforgatása felhúzza a gömböt. Ezek közül egyik sem olvas ki semmit
az órádból, és nem küld el semmit róla.

## Diagnosztika

Az alkalmazás egyetlen bejegyzést ír a rendszernaplóba, amikor a mozgásérzékelés
nem érhető el azon a hardveren, amin fut, hogy a rázással kapcsolatos
hibajelentések értelmezhetők legyenek. Nem tartalmaz sem személyes adatot, sem
felhasználói adatot. Az eszközön marad az Apple egységes naplózási rendszerében,
nem egy hibajelentő rendszer, és nem küldjük el nekünk.

## Vásárlások

A 8 Ball egy **egyszeri vásárlás**. Egyszer fizeted ki az App Store árát, és ez az
egyetlen fizetés: nincsenek alkalmazáson belüli vásárlások, nincs előfizetés,
nincs próbaidőszak, nincs fizetős feloldás, és nincs hirdetés. Az alkalmazás
egyáltalán nem kapcsolódik a StoreKithez, így nincs benne vásárlási kód, és semmi
az alkalmazásban nem terhelheti meg téged még egyszer — az egyetlen díjat a
letöltéskor az Apple vonja le, nem mi. Az App Store-ban történő megvásárlás egy
bejegyzést hagy az Apple Accountodban, amelyet az Apple őriz, és ez a vásárlás
közted és az Apple között zajlik: soha nem kapjuk meg az Apple Account
hitelesítő adataidat, a fizetési adataidat, a kártyaszámodat vagy a számlázási
címedet, és nem üzemeltetünk semmilyen vásárlási szervert. Az Apple feldolgozására
az
[App Store & Privacy](https://www.apple.com/legal/privacy/data/en/appstore/) tájékoztatója vonatkozik.
Magának az alkalmazásnak a használatát az Apple
[Standard End User License Agreement](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/)
szabályozza, az App Store-ból történő letöltéseket pedig az
[Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/).

## Támogatási levelezés

Ha támogatásért írsz nekünk e-mailt, megkapjuk az e-mail-címedet, az üzenetedet,
valamint minden olyan eszköz-, alkalmazásverzió-, képernyőkép- vagy egyéb
információt, amelyet úgy döntesz, hogy csatolsz. Ezeket kizárólag a
válaszadásra, a probléma kivizsgálására és a 8 Ball fejlesztésére használjuk. Ne
küldj olyan információt, amely nem szükséges a kéréseddel kapcsolatban.

Ahol a GDPR vagy az UK GDPR alkalmazandó, a támogatási leveleket a jogos érdekünk
alapján kezeljük, amely abban áll, hogy válaszolunk a nekünk írókra, és
megoldjuk a jelentett problémákat. Nincs más adatkezelés, amelyhez jogalapot
kellene keresni, mivel a 8 Ball önmagától semmit nem küld el nekünk.

A támogatási e-mail írása opcionális, és a 8 Ballon kívül történik. Az üzenetet
az e-mail-szolgáltatód és a Google dolgozza fel, amely a támogatási
postafiókunkat üzemelteti, a
[Google Privacy Policy](https://policies.google.com/privacy) szerint. A Google
levelezőszerverei az Egyesült Államokban találhatók, így az általad küldött
támogatási üzenetet ott dolgozzák fel. A támogatási üzeneteket legfeljebb 24
hónapig őrizzük meg, és csak akkor tovább, ha jogi, biztonsági vagy
nyilvántartási kötelezettség ezt megköveteli. Kérheted a támogatási
levelezésed törlését, ha e-mailt küldesz az alábbi címre.

## Külső hivatkozások

A 8 Ball meg tudja mutatni ennek az adatvédelmi szabályzatnak a címét a
Beállításokból, és a megnyitáskor a hivatkozást átadja a párosított
iPhone-odnak, mivel az órának nincs saját böngészője. Ezt a célt — ezt az
oldalt — a GitHub Pages szolgálja ki, amely a látogatást a
[GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)
szerint kezeli. A 8 Ball nem ad hozzá semmilyen, rád vagy az
alkalmazás-példányodra vonatkozó azonosítót ehhez a hivatkozáshoz. Az
alkalmazás semmilyen más külső címet nem nyit meg.

## Véletlenszerűség, és ami nem az

Minden válasz egyenletes eloszlással kerül kiválasztásra a húsz közül, a rendszer
véletlenszám-generátorával, és a sorsolás azelőtt történik, hogy a gömb elkezdene
mozogni — az animáció egy már kiválasztott eredményt mutat be, nem pedig egy felé
halad. Az alkalmazás nem tanul tőled, nem alkalmazkodik hozzád, nem készít rólad
profilt, és nincs rólad semmilyen modellje, amivel alkalmazkodhatna. Semmi, amit
teszel, nem változtatja meg, mi lesz a következő válasz.

## Amit a 8 Ball NEM tesz

Hogy egyértelmű legyen, a 8 Ball **nem**:

- küld semmit sehova — egyáltalán nem tartalmaz hálózati kódot
- gyűjti vagy továbbítja a kérdésedet, a kapott válaszokat vagy a beállításaidat
- használ analitikai, hibajelentési vagy telemetriai szolgáltatásokat
- tartalmaz hirdetést vagy hirdetési azonosítókat
- követ nyomon appok vagy weboldalak között, és nem oszt meg adatot adatbrókerekkel
- hoz létre felhasználói fiókokat, és nem kér e-mail-címet, telefonszámot vagy
  bejelentkezést
- olvassa ki a kamerádat, fotóidat, mikrofonodat, névjegyeidet, helyadataidat
  vagy egészségügyi adataidat
- rögzíti vagy tárolja a mozgásadatokat
- használja az adataidat gépi tanulási modellek betanítására
- tartalmaz semmilyen harmadik féltől származó SDK-t

A 8 Ball App Store-os adatvédelmi címkéje ezt tükrözi:
**Data Not Collected (nem gyűjtött adatok)**.

## Adatmegőrzés és törlés

**A 8 Ball helyi adatainak törléséhez:** töröld az alkalmazást az órádról. Ez
eltávolítja a kiválasztott kinézetet, emblémát és nyelvet. Nincs más
eltávolítanivaló, és sehol nem létezik szerveroldali másolat. Az iCloud vagy
számítógépes eszköz-biztonsági mentéseket te és az Apple külön-külön kezelitek,
és ezek még tartalmazhatnak alkalmazásadatokat; az Apple elmagyarázza, hogyan
lehet
[kezelni az iCloud biztonsági mentéseket](https://support.apple.com/en-us/108922).

A támogatási e-mailek elkülönülnek az alkalmazásadatoktól. Kérheted a
támogatási levelezés törlését a fent leírtak szerint, azon információk
kivételével, amelyeket jogi, biztonsági vagy nyilvántartási okokból meg kell
őriznünk.

## A jogaid

Attól függően, hogy hol élsz, jogaid lehetnek a GDPR, az UK GDPR, a CCPA/CPRA
vagy hasonló jogszabályok alapján — beleértve a személyes adataidhoz való
hozzáférés, azok helyesbítése, exportálása vagy törlése iránti jogot, valamint
azt a jogot, hogy ne érjen hátrányos megkülönböztetés e jogok gyakorlása miatt.

Minden, ami a 8 Ballon belül keletkezik, esetében ezeket a jogokat közvetlenül
te gyakorlod: a három beállítás az alkalmazás helyi tárolójában él az órádon,
és mi nem őrzünk olyan másolatot, amelyet a nevedben elő tudnánk állítani,
módosítani vagy törölni tudnánk. A nekünk küldött támogatási levelezés
esetében vedd fel velünk a kapcsolatot, ha hozzáférést, helyesbítést vagy
törlést szeretnél kérni. Nem adunk el és nem osztunk meg személyes adatot
hirdetési célra, és ezt soha nem is tettük.

Ha úgy gondolod, hogy nem tettünk eleget a kötelezettségeinknek, kapcsolatba
léphetsz velünk a fenti címen, és jogodban áll panaszt tenni a helyi
adatvédelmi hatóságnál.

## Gyermekek

A 8 Ball 4+ korhatár-besorolású és családbarát. Ez egy általános közönségnek
szóló alkalmazás, nem pedig kifejezetten gyerekeknek szánt. Az alkalmazás
tudatosan nem gyűjt személyes adatot senkitől, beleértve a 13 év alatti
gyermekeket is (vagy az adott országban érvényes egyenértékű minimumkort) —
valójában senkitől nem gyűjt semmit. Nincs chat, megosztási vagy közösségi
funkció, hirdetés, sem olyan vásárlási lehetőség, amelyen keresztül egy
gyermeket el lehetne érni vagy meg lehetne terhelni. Bármilyen támogatási
e-mailt egy szülőnek vagy gondviselőnek kell elküldenie a gyermek nevében.

A húsz válasz a klasszikus játék válaszai, és nem tanácsok. A 8 Ball egy
játék arra, hogy eldöntsd, mit egyél ebédre, és semmi benne nem szolgálhat
alapul semmilyen fontos döntéshez.

## A szabályzat módosításai

Ha ez a szabályzat módosul, frissítjük ezt az oldalt, és megváltoztatjuk a
fenti „Utolsó frissítés” dátumot. A lényeges változásokat az alkalmazás
verziómegjegyzéseiben is feltüntetjük. Javasoljuk, hogy időnként nézd át ezt
az oldalt.

## Kapcsolat

Kérdések, aggályok vagy kérések:

**ivnsjdev@gmail.com**
