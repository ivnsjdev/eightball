# Integritetspolicy för 8 Ball

**Datum då policyn träder i kraft:** 15 september 2026

**Senast uppdaterad:** 15 september 2026

## Kortversionen

8 Ball varken samlar in eller överför något. Det är en Apple Watch-app helt
utan nätverkskod: ingen server, inget konto, ingen analys, ingen reklam,
ingen spårning och ingen SDK från tredje part. Din fråga skrivs aldrig in
någonstans, så appen tar aldrig emot den. Det enda som sparas är det utseende, det
emblem och det språk du har valt, och de sparas på din klocka.

## Vilka vi är

8 Ball ("appen") är utvecklad av **IVAN CAYABYAB** ("vi", "oss").

Har du frågor om denna policy eller din integritet, kontakta oss på
**ivnsjdev@gmail.com**.

## Vad 8 Ball sparar, och var

8 Ball är en spådomsboll: du ställer en ja-eller-nej-fråga, skakar, och den
visar ett av tjugo svar. De tre val du kan göra i Inställningar sparas på din
klocka med watchOS standardlagring för appinställningar. Vi tar aldrig emot
dem.

| Vad 8 Ball sparar | Primär lagring | Skickas automatiskt till oss? |
| --- | --- | --- |
| Utseendet du har valt för bollen | På din klocka | Nej |
| Emblemet du har valt för dess axel | På din klocka | Nej |
| Språket du har valt i Inställningar | På din klocka | Nej |

Det är hela listan. Det finns inget annat: ingen profil, ingen identifierare,
ingen användningsräknare, ingen logg över vad du frågade eller vilket svar du
fick. Appen överför inget av detta till oss eller till något annat företag,
och vi samlar inte in, säljer, hyr ut eller delar det. Enhetens säkerhetskopior
styrs av operativsystemet, inte initierade av 8 Ball.

## Din fråga samlas aldrig in, eftersom den aldrig matas in

8 Ball har inget textfält, använder inte mikrofonen och har ingen diktering.
Du frågar bollen högt eller för dig själv, och appen får aldrig veta vad du
frågade — det finns ingen inmatningsväg för den att komma in genom. Den
väljer ett av de tjugo svaren slumpmässigt utan någon kunskap om frågan.

## Svaret sparas inte heller

Svaret på skärmen finns bara i minnet så länge det visas. Det skrivs
medvetet aldrig till lagring, det finns ingen historikskärm, och det
försvinner när appen stängs. Inget ackumuleras mellan sessioner.

Medan klockan är i det nedtonade Always-On-läget markeras svarsfönstret som
integritetskänsligt, så watchOS döljer det tills du lyfter handleden. Någon
som kastar en blick på en sänkt handled läser inte ditt svar.

## Inget konto, ingen inloggning, inget moln

8 Ball har inga användarkonton och det finns inget att registrera sig för.
Appen frågar inte efter en e-postadress, ett telefonnummer, ett födelsedatum
eller någon annan kontoidentitet. Den använder inte iCloud, CloudKit eller
någon annan synkroniseringstjänst, så ditt utseende, ditt emblem och ditt
språk följer inte med mellan enheter. Det är en fristående klockapp utan en
tillhörande iPhone-app, så den delar inget med en telefon. Ditt
operativsystems enhetssäkerhetskopia kan innehålla 8 Balls lokala appdata om
du har valt att säkerhetskopiera enheten.

## Rörelse, och varför det inte finns någon behörighetsförfrågan

För att upptäcka en skakning läser 8 Ball klockans rörelsedata — specifikt
användaraccelerationsvektorn, som är rörelsen av din handled med tyngdkraften
redan borttagen. Den samplas medan bollen visas på skärmen, analyseras
omedelbart för att avgöra om en avsiktlig skakning just har inträffat, och
kastas sedan bort. Den registreras inte, lagras inte och överförs inte, och
den används inte till något annat än att starta en kastning.

watchOS skyddar inte dessa data bakom en behörighetsförfrågan så som iOS gör,
vilket är anledningen till att ingen förfrågan visas och varför appen levereras
utan en användningsbeskrivning för rörelse: att deklarera en syftesbeskrivning
som systemet aldrig visar skulle vara missvisande snarare än informativt. Att
slå på Handledsdetektering eller Always-On är en klockinställning, inte
något 8 Ball begär.

## Behörigheter vi inte begär

8 Ball begär inga systembehörigheter alls. Appen har inte åtkomst till din
kamera, ditt fotobibliotek, din mikrofon, din plats, dina kontakter, din
kalender, dina hälso- eller träningsdata, dina aviseringar eller Siri, och
ingen behörighetsförfrågan kommer någonsin att visas.

## Ljud, haptik och Digital Crown

8 Ball spelar inget ljud. Återkoppling är haptisk: tre knackningar medan
bollen tänker, en när den svarar, via Apples standardhaptik för klockan. Att
vrida på Digital Crown drar upp bollen. Ingen av dessa läser något från din
klocka eller skickar något från den.

## Diagnostik

Appen skriver en anteckning till systemloggen när rörelsedata inte är
tillgänglig på den hårdvara den körs på, så att skakningsrelaterade
felrapporter kan förstås. Den innehåller ingen personlig information och
ingen användardata. Den stannar på enheten under Apples enhetliga loggning,
är inte en kraschrapporteringstjänst, och skickas inte till oss.

## Köp

8 Ball är ett **engångsköp**. Du betalar App Store-priset en gång, och det
är den enda betalningen som finns: inga köp i appen, inga prenumerationer,
ingen provperiod, ingen betald upplåsning och ingen reklam. Appen länkar
inte StoreKit alls, så det finns ingen köpkod i den och inget i appen själv
kan någonsin debitera dig — den enda avgiften tas ut av Apple vid nedladdning,
inte av oss. Att köpa den från App Store lämnar en registrering på ditt Apple
Account som Apple sparar, och det köpet är mellan dig och Apple: vi tar
aldrig emot dina Apple Account-uppgifter, betalningsuppgifter, kortnummer
eller faktureringsadress, och vi driver ingen köpserver. Apples hantering
täcks av deras meddelande
[App Store & Privacy](https://www.apple.com/legal/privacy/data/en/appstore/).
Användningen av själva appen regleras av Apples
[Standard End User License Agreement](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/),
och nedladdningar från App Store av
[Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/).

## Supportkommunikation

Om du mejlar oss för support tar vi emot din e-postadress, ditt meddelande
och eventuell information om enhet, appversion, skärmdumpar eller annan
information du väljer att inkludera. Vi använder den endast för att svara,
utreda problemet och förbättra 8 Ball. Skicka inte information som inte
behövs för din förfrågan.

Där GDPR eller UK GDPR gäller hanterar vi supportmejl med stöd av vårt
berättigade intresse av att svara de personer som skriver till oss och att
åtgärda de problem de rapporterar. Det finns ingen annan behandling att söka
en rättslig grund för, eftersom 8 Ball inte skickar oss något av sig själv.

Support via e-post är valfritt och sker utanför 8 Ball. Det behandlas av din
e-postleverantör och av Google, som hostar vår supportbrevlåda, enligt
[Google Privacy Policy](https://policies.google.com/privacy). Googles
mejlservrar finns i USA, så ett supportmeddelande du skickar till oss
behandlas där. Vi sparar supportmeddelanden i upp till 24 månader, och längre
endast när en rättslig, säkerhetsmässig eller arkiveringsmässig skyldighet
kräver det. Du kan be oss radera din supportkorrespondens genom att mejla
adressen nedan.

## Externa länkar

8 Ball kan visa den här integritetspolicyns adress från Inställningar, och
att öppna den skickar länken vidare till din ihopparade iPhone, eftersom en
klocka inte har någon egen webbläsare. Den destinationen — den här sidan —
hostas av GitHub Pages, som hanterar besöket enligt
[GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
8 Ball lägger inte till någon identifierare av dig eller av ditt exemplar av
appen i den länken. Appen öppnar ingen annan extern adress.

## Slumpmässighet, och vad den inte är

Varje svar dras jämnt fördelat bland de tjugo, med hjälp av systemets
slumptalsgenerator, och dragningen sker innan bollen börjar röra sig —
animationen visar ett resultat som redan är valt, i stället för att styra mot
ett. Appen lär sig inget av dig, anpassar sig inte efter dig, profilerar dig
inte och har ingen modell av dig att anpassa sig med. Inget du gör förändrar
vad nästa svar blir.

## Vad vi INTE gör

För att vara tydliga gör 8 Ball **inte**:

- skickar något någonstans — den innehåller ingen som helst nätverkskod
- samlar in eller överför din fråga, de svar du fick, eller dina
  inställningar
- använder analys-, kraschrapporterings- eller telemetritjänster
- innehåller reklam eller annonsidentifierare
- spårar dig mellan appar eller webbplatser, eller delar data med
  datamäklare
- skapar användarkonton, eller kräver en e-postadress, ett telefonnummer
  eller inloggning
- läser din kamera, dina foton, din mikrofon, dina kontakter, din plats
  eller dina hälsodata
- spelar in eller lagrar rörelsedata
- använder dina data för att träna maskininlärningsmodeller
- innehåller någon SDK från tredje part

8 Balls integritetsetikett på App Store speglar detta: **Data Not Collected
(data samlas inte in)**.

## Datalagring och radering

**För att radera 8 Balls lokala data:** ta bort appen från din klocka. Det
tar bort det utseende, det emblem och det språk du hade valt. Det finns inget
annat att ta bort, och ingen serverkopia finns någonstans. iCloud- eller
datorsäkerhetskopior av enheten styrs separat av dig och Apple och kan
fortfarande innehålla appdata; Apple förklarar hur man
[hanterar iCloud-säkerhetskopior](https://support.apple.com/en-us/108922).

Supportmejl är separata från appdata. Du kan begära radering av din
supportkorrespondens enligt ovan, med förbehåll för information vi måste
behålla av rättsliga, säkerhetsmässiga eller arkiveringsmässiga skäl.

## Dina rättigheter

Beroende på var du bor kan du ha rättigheter enligt GDPR, UK GDPR, CCPA/CPRA
eller liknande lagar — inklusive rätten att få tillgång till, rätta, exportera
eller radera dina personuppgifter, och rätten att inte diskrimineras för att
utöva dem.

För allt som skapas inuti 8 Ball utövar du dessa rättigheter direkt: de tre
inställningarna finns i appens lokala behållare på din klocka, och vi har
ingen kopia som vi kan ta fram, ändra eller radera å dina vägnar. För
supportkorrespondens du har skickat till oss, kontakta oss för att begära
tillgång, rättelse eller radering. Vi säljer eller delar inte personuppgifter
för reklamändamål, och det har vi aldrig gjort.

Om du anser att vi inte har uppfyllt våra skyldigheter kan du kontakta oss på
adressen ovan, och du har rätt att lämna in ett klagomål till din lokala
tillsynsmyndighet för dataskydd.

## Barn

8 Ball är klassad 4+ och är familjevänlig. Det är en app för en allmän
publik snarare än en riktad till barn. Appen samlar inte medvetet in
personlig information från någon, inklusive barn under 13 år (eller
motsvarande minimiålder i deras land) — den samlar inte in något från någon.
Det finns ingen chatt, delningsfunktion, social funktion, reklam eller köp
genom vilket ett barn skulle kunna nås eller debiteras. En förälder eller
vårdnadshavare bör skicka eventuellt supportmejl å ett barns vägnar.

De tjugo svaren är den klassiska leksakens svar och är inte råd. 8 Ball är
en leksak för att avgöra vad man ska äta till lunch, och inget i den bör
läggas till grund för något beslut som spelar roll.

## Ändringar av denna policy

Om denna policy ändras uppdaterar vi den här sidan och reviderar datumet för
"Senast uppdaterad" ovan. Väsentliga ändringar kommer också att noteras i
appens versionsanteckningar. Vi uppmuntrar dig att granska den här sidan
regelbundet.

## Kontakt

Frågor, funderingar eller förfrågningar:

**ivnsjdev@gmail.com**
