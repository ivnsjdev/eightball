# Zásady ochrany osobních údajů aplikace 8 Ball

**Datum účinnosti:** 15. září 2026

**Poslední aktualizace:** 15. září 2026

## Stručně

8 Ball nic neshromažďuje ani nepřenáší. Je to aplikace pro Apple Watch bez
jakéhokoli síťového kódu: žádný server, žádný účet, žádná analytika, žádná
reklama, žádné sledování a žádné SDK třetích stran. Tvoje otázka se nikam
nezapisuje, takže se k aplikaci nikdy nedostane. Jediné, co se ukládá, je
skin, emblém a jazyk, které sis vybral/a, a ukládají se přímo v tvých
hodinkách.

## Kdo jsme

Aplikaci 8 Ball ("aplikace") vyvíjí **IVAN CAYABYAB** ("my", "nás").

S jakýmkoli dotazem ohledně těchto zásad nebo tvého soukromí nás kontaktuj na
adrese **ivnsjdev@gmail.com**.

## Co 8 Ball ukládá a kde

8 Ball je věštecká koule: položíš otázku, na kterou se dá odpovědět ano/ne,
zatřeseš a koule zobrazí jednu z dvaceti odpovědí. Tři volby, které můžeš
provést v Nastavení, se ukládají v tvých hodinkách pomocí standardního
úložiště předvoleb aplikací systému watchOS. Nikdy je nedostáváme.

| Co 8 Ball ukládá | Hlavní úložiště | Odesíláno nám automaticky? |
| --- | --- | --- |
| Skin, který sis vybral/a pro kouli | V tvých hodinkách | Ne |
| Emblém, který sis vybral/a pro její rameno | V tvých hodinkách | Ne |
| Jazyk, který sis vybral/a v Nastavení | V tvých hodinkách | Ne |

To je kompletní seznam. Nic dalšího neexistuje: žádný profil, žádný
identifikátor, žádné počítadlo využití, žádný záznam toho, na co ses ptal/a
nebo co ti bylo odpovězeno. Aplikace nic z toho nepřenáší ani nám, ani žádné
jiné společnosti, a my to neshromažďujeme, neprodáváme, nepronajímáme ani
nesdílíme. Zálohy zařízení řídí operační systém, nikoli aplikace 8 Ball.

## Tvoje otázka se nikdy neshromažďuje, protože se nikdy nezadává

8 Ball nemá textové pole, nepoužívá mikrofon ani diktování. Koule se ptáš
nahlas nebo v duchu a aplikace se nikdy nedozví, na co ses ptal/a — neexistuje
žádný vstup, kterým by se to k ní mohlo dostat. Vybere jednu z dvaceti
odpovědí náhodně, aniž by o otázce cokoli věděla.

## Ani odpověď se neukládá

Odpověď na obrazovce existuje v paměti jen po dobu, kdy je zobrazena.
Záměrně se nikdy nezapisuje do úložiště, neexistuje obrazovka historie a po
zavření aplikace zmizí. Mezi jednotlivými spuštěními se nic nehromadí.

Když jsou hodinky ve ztlumeném stavu Always-On, je okno s odpovědí označeno
jako citlivé z hlediska soukromí, takže ho watchOS skryje, dokud nezvedneš
zápěstí. Někdo, kdo zahlédne spuštěné zápěstí, tvoji odpověď nepřečte.

## Žádný účet, žádné přihlášení, žádný cloud

8 Ball nemá uživatelské účty a není se k čemu registrovat. Nevyžaduje
e-mailovou adresu, telefonní číslo, datum narození ani žádnou jinou identitu
účtu. Nepoužívá iCloud, CloudKit ani žádnou jinou synchronizační službu,
takže tvůj skin, emblém a jazyk se mezi zařízeními nepřenášejí. Je to
samostatná aplikace pro hodinky bez doprovodné aplikace pro iPhone, takže s
telefonem nesdílí vůbec nic. Záloha zařízení tvého operačního systému může
obsahovat lokální data aplikace 8 Ball, pokud sis zvolil/a zálohovat
zařízení.

## Pohyb a proč se nezobrazuje žádost o oprávnění

Aby 8 Ball zaznamenal zatřesení, čte data o pohybu zařízení hodinek —
konkrétně vektor zrychlení uživatele, což je pohyb tvého zápěstí s již
odečtenou gravitací. Data se snímají, dokud je koule na obrazovce, okamžitě
se vyhodnotí, zda právě došlo k záměrnému zatřesení, a poté se zahodí.
Nezaznamenávají se, neukládají se ani nepřenášejí a nepoužívají se k ničemu
jinému než ke spuštění otočení koule.

watchOS tato data nechrání žádostí o oprávnění tak, jako to dělá iOS, a proto
se žádná žádost nezobrazuje a aplikace se distribuuje bez popisu účelu
použití pohybových dat: uvádět text účelu, který systém nikdy nezobrazí, by
bylo zavádějící, nikoli informativní. Zapnutí Detekce zápěstí nebo Always-On
je nastavení hodinek, nikoli něco, o co by žádal 8 Ball.

## Oprávnění, o která nežádáme

8 Ball nežádá o žádná systémová oprávnění. Nepřistupuje k tvému fotoaparátu,
fototéce, mikrofonu, poloze, kontaktům, kalendáři, zdravotním nebo
tréninkovým údajům, oznámením ani Siri, a žádost o oprávnění se nikdy
nezobrazí.

## Zvuk, haptika a Digital Crown

8 Ball nepřehrává žádný zvuk. Zpětná vazba je haptická — tři poklepání,
zatímco koule přemýšlí, a jedno při odpovědi — prostřednictvím standardní
haptiky Apple pro hodinky. Otáčení Digital Crown kouli roztáčí. Nic z toho
nečte žádná data z tvých hodinek ani z nich nic neodesílá.

## Diagnostika

Aplikace zapíše jeden záznam do systémového protokolu, pokud na hardwaru, na
kterém běží, nejsou dostupná data o pohybu zařízení, aby bylo možné
porozumět hlášením chyb souvisejících se zatřesením. Neobsahuje žádné osobní
údaje ani uživatelská data. Zůstává v zařízení v rámci jednotného
protokolování Apple, není to nástroj pro hlášení pádů a neodesílá se nám.

## Nákupy

8 Ball je **jednorázový nákup**. Zaplatíš cenu App Store jednou, a to je
jediná platba, která existuje: žádné nákupy v aplikaci, žádná předplatná,
žádná zkušební verze, žádné placené odemykání a žádná reklama. Aplikace
vůbec nepropojuje StoreKit, takže v ní není žádný kód pro nákupy a nic v
samotné aplikaci tě nikdy nemůže nijak zpoplatnit — jedinou platbu strhává
Apple při stažení, nikoli my. Koupě přes App Store zanechá záznam na tvém
Apple Account, který uchovává Apple, a tento nákup je záležitostí mezi tebou
a Apple: nikdy nedostáváme přihlašovací údaje k tvému Apple Account,
platební údaje, číslo karty ani fakturační adresu a neprovozujeme žádný
server pro nákupy. Zpracování ze strany Apple se řídí jeho oznámením
[App Store & Privacy](https://www.apple.com/legal/privacy/data/en/appstore/).
Používání samotné aplikace se řídí dokumentem Apple
[Standard End User License Agreement](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/)
a stahování z App Store dokumentem
[Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/).

## Komunikace s podporou

Pokud nám napíšeš e-mail kvůli podpoře, obdržíme tvoji e-mailovou adresu,
tvoji zprávu a jakékoli informace o zařízení, verzi aplikace, snímky
obrazovky nebo jiné informace, které se rozhodneš přiložit. Používáme je
pouze k odpovědi, prošetření problému a vylepšení 8 Ball. Neposílej
informace, které nejsou pro tvůj požadavek potřeba.

Tam, kde se uplatňuje GDPR nebo britské GDPR, zpracováváme podporu e-mailem
na základě našeho oprávněného zájmu odpovídat lidem, kteří nám píšou, a
řešit problémy, které nahlásí. Žádné jiné zpracování, pro které by bylo
třeba hledat právní základ, neexistuje, protože 8 Ball nám sám od sebe nic
neposílá.

Podpora e-mailem je dobrovolná a probíhá mimo 8 Ball. Zpracovává ji tvůj
poskytovatel e-mailu a Google, který hostuje naši schránku podpory, v
souladu s dokumentem
[Google Privacy Policy](https://policies.google.com/privacy). Poštovní
servery Google se nacházejí ve Spojených státech, takže zpráva podpory,
kterou nám pošleš, se zpracovává tam. Zprávy podpory uchováváme až 24
měsíců, déle jen tam, kde to vyžaduje právní, bezpečnostní nebo evidenční
povinnost. O vymazání své korespondence s podporou nás můžeš požádat
e-mailem na adresu níže.

## Externí odkazy

8 Ball může ve svém Nastavení zobrazit adresu těchto zásad ochrany osobních
údajů, a jejich otevření předá odkaz tvému spárovanému iPhonu, protože
hodinky nemají vlastní prohlížeč. Tento cíl — tato stránka — je poskytován
službou GitHub Pages, která návštěvu zpracovává podle dokumentu
[GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
8 Ball k tomuto odkazu nepřidává žádný identifikátor tebe ani tvé kopie
aplikace. Aplikace neotevírá žádnou jinou externí adresu.

## Náhodnost a co náhodností není

Každá odpověď se losuje rovnoměrně ze všech dvaceti pomocí systémového
generátoru náhodných čísel a losování probíhá dříve, než se koule začne
hýbat — animace zobrazuje výsledek, který už byl vybrán, místo aby se k němu
teprve blížila. Aplikace se od tebe neučí, nepřizpůsobuje se ti, nevytváří
tvůj profil a nemá žádný model tebe, podle kterého by se mohla přizpůsobovat.
Nic, co uděláš, neovlivní, jaká bude další odpověď.

## Co **ne**děláme

Pro jasnost, 8 Ball **ne**:

- odesílá nic nikam — neobsahuje žádný síťový kód jakéhokoli druhu
- shromažďuje ani nepřenáší tvoji otázku, odpovědi, které jsi dostal/a, ani
  tvá nastavení
- používá analytiku, hlášení pádů ani telemetrické služby
- obsahuje reklamu ani reklamní identifikátory
- sleduje tě napříč aplikacemi ani weby a nesdílí data s obchodníky s daty
- vytváří uživatelské účty a nevyžaduje e-mailovou adresu, telefonní číslo
  ani přihlášení
- čte tvůj fotoaparát, fotky, mikrofon, kontakty, polohu ani zdravotní údaje
- zaznamenává ani neukládá data o pohybu
- používá tvá data k trénování modelů strojového učení
- obsahuje žádné SDK třetích stran

Štítek soukromí aplikace 8 Ball na App Store to odráží:
**Data Not Collected (údaje nejsou shromažďovány)**.

## Uchovávání a mazání dat

**Chceš-li smazat lokální data aplikace 8 Ball:** odstraň aplikaci z
hodinek. Tím se odstraní skin, emblém a jazyk, které sis vybral/a. Nic
dalšího k odstranění není a na žádném serveru neexistuje žádná kopie.
Zálohy v iCloudu nebo v počítači řídíte samostatně ty a Apple a mohou stále
obsahovat data aplikace; Apple vysvětluje, jak
[spravovat zálohy iCloud](https://support.apple.com/en-us/108922).

E-maily podpoře jsou oddělené od dat aplikace. O vymazání korespondence s
podporou můžeš požádat výše popsaným způsobem, s výhradou jakýchkoli
informací, které musíme uchovat z právních, bezpečnostních nebo evidenčních
důvodů.

## Tvá práva

V závislosti na tom, kde žiješ, můžeš mít práva podle GDPR, britského GDPR,
CCPA/CPRA nebo podobných zákonů — včetně práva na přístup, opravu, export
nebo smazání svých osobních údajů a práva nebýt diskriminován/a za jejich
uplatnění.

U všeho, co vzniká uvnitř 8 Ball, uplatňuješ tato práva přímo sám/sama: tři
předvolby existují v lokálním kontejneru aplikace na tvých hodinkách a my
nemáme žádnou kopii, kterou bychom ti mohli poskytnout, upravit nebo za tebe
smazat. U korespondence s podporou, kterou jsi nám poslal/a, nás kontaktuj s
žádostí o přístup, opravu nebo smazání. Neprodáváme ani nesdílíme osobní
údaje pro reklamní účely a nikdy jsme to nedělali.

Pokud se domníváš, že jsme nesplnili své povinnosti, můžeš nás kontaktovat na
výše uvedené adrese a máš právo podat stížnost u místního úřadu pro ochranu
osobních údajů.

## Děti

8 Ball má hodnocení 4+ a je vhodný pro celou rodinu. Je to aplikace pro
širokou veřejnost, nikoli aplikace cílená na děti. Aplikace vědomě
neshromažďuje osobní údaje od nikoho, včetně dětí mladších 13 let (nebo
odpovídajícího minimálního věku v jejich zemi) — neshromažďuje je od nikoho.
Neexistuje žádný chat, sdílení, sociální funkce, reklama ani nákup, jehož
prostřednictvím by mohlo dojít ke kontaktu s dítětem nebo k jeho
zpoplatnění. Jakýkoli e-mail podpoře by jménem dítěte měl odeslat rodič nebo
zákonný zástupce.

Dvacet odpovědí jsou odpovědi klasické hračky a nejedná se o radu. 8 Ball je
hračka na rozhodnutí, co si dát k obědu, a nic v ní by se nemělo brát jako
podklad pro žádné důležité rozhodnutí.

## Změny těchto zásad

Pokud se tyto zásady změní, aktualizujeme tuto stránku a upravíme datum
„Poslední aktualizace" uvedené výše. Podstatné změny budou také uvedeny v
poznámkách k vydání aplikace. Doporučujeme ti tuto stránku pravidelně
kontrolovat.

## Kontakt

Dotazy, připomínky nebo žádosti:

**ivnsjdev@gmail.com**
