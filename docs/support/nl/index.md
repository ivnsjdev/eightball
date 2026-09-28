# Ondersteuning voor 8 Ball

**Laatst bijgewerkt:** 15 september 2026

8 Ball is een waarzegbal voor Apple Watch: stel een ja-of-nee-vraag, schud je
pols, en lees een van de twintig klassieke antwoorden. Hij draait alleen op
het horloge, zonder dat er een iPhone-app nodig is. Het is een eenmalige
aankoop zonder verder iets te kopen, en er is geen account, geen server, geen
advertenties, geen analyse en geen tracking — de app bevat helemaal geen
netwerkcode, dus hij werkt precies hetzelfde als het horloge offline is.

<a id="contact"></a>
## Contact

De snelste manier om ons te bereiken is per e-mail:

**ivnsjdev@gmail.com**

We streven ernaar binnen 2-3 werkdagen te reageren. Om ons te helpen je
sneller te helpen, voeg je het volgende toe:

- je Apple Watch-model en watchOS-versie (**Watch-app op iPhone → Algemeen →
  Info**, of **Instellingen → Algemeen → Info** op het horloge)
- de versie van 8 Ball, te zien op de App Store-vermelding
- wat je aan het doen was — schudden, aan de Digital Crown draaien, tikken,
  of in Instellingen
- wat je verwachtte dat er zou gebeuren, en wat er in plaats daarvan gebeurde

## Veelgestelde vragen

### Hoe stel ik de bal een vraag?

Drie manieren, wat het beste bij het moment past:

- **Schud je pols** — een bewuste flik.
- **Draai aan de Digital Crown** — ongeveer een derde omwenteling, in beide
  richtingen.
- **Tik op de bal.**

De bal windt zich op, tuimelt, en het antwoordvenster draait in beeld. Je
voelt drie tikjes terwijl hij nadenkt en één als hij antwoordt, zodat het ook
zonder te kijken werkt.

### Welke apparaten heeft het nodig?

Een Apple Watch met **watchOS 11 of nieuwer**. 8 Ball is een op zichzelf
staande horloge-app: er is geen iPhone-app om te installeren, en de app heeft
je telefoon niet in de buurt of een internetverbinding nodig.

### Hoe kom ik bij Instellingen?

**Houd de bal ongeveer een halve seconde ingedrukt.** Instellingen heeft drie
rijen — **Skin**, **Embleem** en **Taal** — en elke rij toont wat er op dat
moment gekozen is.

De lange druk wordt gebruikt in plaats van de Digital Crown, omdat de kroon
juist een van de manieren is om de bal een vraag te stellen, en een lijst op
het hoofdscherm die mogelijkheid zou wegnemen.

### Wat kost 8 Ball?

Eén betaling op de App Store, tegen de prijs die op de vermelding voor jouw
land wordt getoond. Daarna is er niets anders te kopen: geen in-app-aankopen,
geen abonnement, geen betaalde laag en geen advertenties. Elke skin, elk
embleem en alle 32 talen zijn vanaf het begin inbegrepen — niets wordt
achtergehouden of later ontgrendeld. De app bevat helemaal geen aankoopcode,
dus niets erin kan je opnieuw iets in rekening brengen.

Apple regelt alle facturering via de App Store, dus we zien je betaalgegevens
nooit. Om de kosten na te vragen of een terugbetaling aan te vragen, gebruik
je
[reportaproblem.apple.com](https://reportaproblem.apple.com).

### Is 8 Ball privé?

Ja. Er is geen server, geen analyse, geen advertenties en geen SDK's van
derden, en de app bevat geen enkele vorm van netwerkcode. Hij ontvangt je
vraag nooit, omdat er nergens is om er een te typen. Het enige wat wordt
opgeslagen, is de skin, het embleem en de taal die je hebt gekozen, en die
blijven op je horloge. Zie het
[privacybeleid](../../privacy/nl/) voor volledige details.

### Is het geschikt voor kinderen?

Ja. 8 Ball heeft een 4+-classificatie en is geschikt voor het hele gezin:
geen chat, geen deelfunctie, geen sociale functies, geen advertenties en
niets te kopen. De twintig antwoorden zijn die van het klassieke speeltje.
Het is een speeltje om te bepalen wat je gaat eten, geen bron van advies.

## De bal en zijn antwoorden

### Zijn de antwoorden echt willekeurig?

Ja. Elk antwoord wordt uniform getrokken uit de twintig, met de
willekeurige-getallengenerator van het systeem, en de trekking gebeurt
**voordat** de bal begint te bewegen. De tuimeling toont vervolgens een
resultaat dat al is bepaald — het stuurt niet naar een resultaat toe.

### Waarom kreeg ik twee keer achter elkaar hetzelfde antwoord?

Omdat dat is wat een eerlijke trekking doet. Elke vraag is een onafhankelijke
kans van 1 op 20, en het vorige antwoord wordt bewust **niet** uit de
volgende trekking gefilterd. Een echte 8-ball herhaalt zich, en het
verwijderen van het laatste antwoord uit de pool zou de trekking meetbaar
niet-uniform maken. Over twintig vragen gerekend, is een herhaling ergens de
waarschijnlijke uitkomst, geen bug.

### Weet de app wat ik vroeg?

Nee, en dat kan ook niet. Er is geen tekstveld, geen dictee en geen
microfoongebruik. Je stelt je vraag hardop of in gedachten; de app ziet
alleen een schudbeweging, een draai aan de kroon of een tik.

### Hebben de gekleurde antwoorden verschillende kansen?

Nee. De drie tonen — **Affirmative**, **Non-committal** en **Negative** —
kleuren alleen het antwoordvenster, zodat je het oordeel kunt aflezen voordat
je de woorden leest. Er zijn tien bevestigende, vijf vrijblijvende en vijf
ontkennende antwoorden, en elk van de twintig is even waarschijnlijk, dus de
tonen zijn onderling niet even waarschijnlijk.

### Waar is mijn antwoordgeschiedenis?

Die is er niet, met opzet. Het antwoord wordt in het geheugen bewaard zolang
het op het scherm staat en wordt nooit naar opslag geschreven, dus het is
verdwenen zodra de app sluit. Er stapelt zich niets op.

## Schudden

### Schudden doet niets

De schuddetector is afgestemd op een **bewuste polsflik** — hij wil een piek
van ongeveer 2 g, aangehouden gedurende ongeveer een halve seconde, wat je
arm optillen, lopen, een klap of een tik tegen een tafel niet zal opleveren.
Flik je pols alsof je een thermometer naar beneden schudt.

Als er dan nog steeds niets gebeurt:

- Controleer of de bal al aan het rollen is. Schudbewegingen worden ongeveer
  een seconde na het starten van een worp genegeerd, zodat de schudbeweging
  waarmee de worp begon niet meteen een tweede kan starten.
- Laat je pols zakken en til hem weer op. Met de pols naar beneden is het
  horloge gedimd en zal de bal bewust niet rollen.
- Gebruik in plaats daarvan de Digital Crown of een tik. Beide werken overal,
  ook op een oplaadstation, waar schudden niet mogelijk is.

### Hij rolt terwijl ik dat niet wilde

De trigger vereist een aangehouden schudbeweging in plaats van één enkele
piek, dus onbedoelde worpen zijn zeldzaam. Als je dagelijkse beweging hem
toch activeert, gebruik dan de kroon of een tik en laat ons weten wat je aan
het doen was — de drempelwaarden zijn instelbaar, en echte meldingen zijn
hoe ze worden afgesteld.

### VoiceOver staat aan en schudden doet niets

VoiceOver claimt de schudbeweging voor zijn eigen navigatie. Op de bal tikken
werkt nog steeds om een vraag te stellen, net als de kroon; de bal is ook
beschikbaar als knop, dus een dubbele tik met VoiceOver werkt ook. Het
antwoord wordt aangekondigd zodra het binnenkomt, samen met zijn toon.

## Skins en emblemen

### Hoe verander ik het uiterlijk van de bal?

Houd de bal ingedrukt om Instellingen te openen, en kies dan **Skin** voor de
bal zelf of **Embleem** voor het teken op de schouder. Elke kiezer toont de
keuze op een echte bal voordat je hem bevestigt.

Er zijn twaalf skins — **Classic, Ivory, Slate, Ruby, Emerald, Sapphire,
Amethyst, Rose, Gold, Ember, Aurora, Neon** — en twaalf emblemen — **Eight,
Question, Star, Moon, Sparkles, Bolt, Flame, Heart, Spade, Pool Ball, Crystal
Ball, Dice**. Dat zijn 144 combinaties, en ze zijn allemaal vanaf het begin
ontgrendeld.

### Zijn er skins of emblemen vergrendeld, of betaald?

Nee. Elke skin en elk embleem is meteen beschikbaar. Er is niets te
ontgrendelen, te verdienen of te kopen.

### Ik heb opnieuw geïnstalleerd en mijn skin staat weer op Classic

Je keuzes bevinden zich in de lokale gegevens van de app op het horloge,
zonder account of iCloud-synchronisatie erachter, dus het verwijderen van de
app wist ze. Kies ze opnieuw in Instellingen — het kost niets en alles is nog
steeds ontgrendeld.

## Instellingen en toegankelijkheid

### Hoe verander ik de taal?

Houd de bal ingedrukt → **Instellingen** → **Taal**. 8 Ball ondersteunt
**32 talen** en de taalkiezer staat los van de taal van je horloge, zodat je
de bal in één taal kunt lezen terwijl je horloge op een andere taal staat.
Rechts-naar-links-talen geven de app een rechts-naar-links-indeling.

### De animatie is te veel

Zet **Beweging verminderen** aan (Watch-app op iPhone → Toegankelijkheid, of
Instellingen → Toegankelijkheid op het horloge). 8 Ball respecteert dit met
een veel kortere, rustigere worp in plaats van de volle tuimeling. Het
antwoord blijft ongewijzigd — het werd in beide gevallen bepaald voordat de
animatie begon.

### Werkt 8 Ball met VoiceOver?

Ja. De bal is een knop met een label, en elk antwoord wordt aangekondigd
samen met zijn toon zodra het binnenkomt, zodat een vraag gesteld en
beantwoord kan worden zonder naar het scherm te kijken. Terugvegen naar de
bal herhaalt het huidige antwoord.

### Ondersteunt het Always-On, en hoe zit het met de batterij?

Ja. Zodra je je pols laat zakken, stopt de animatie meteen in plaats van
ongezien door te lopen, en de versnellingsmeter wordt uitgeschakeld zodra de
app niet op de voorgrond staat — een actieve bewegingssensor is de echte
batterijkost op een horloge, niet het tekenen.

Het antwoordvenster wordt ook als privacygevoelig gemarkeerd, zodat watchOS
het onleesbaar maakt in de gedimde stand. Iemand die een steelse blik werpt
op je neerhangende pols leest je antwoord niet.

### Is er een complicatie of een wijzerplaatwidget?

Niet in deze versie. 8 Ball is de app alleen.

### Is er een iPhone-versie?

8 Ball is alleen voor het horloge. Dezelfde 8-ball, met de rest van een
randomizer eromheen, maakt deel uit van **Pickify** op iPhone en iPad.

## Bugs en functieverzoeken

Mail ons op **ivnsjdev@gmail.com**. Bugmeldingen met de details die worden
genoemd onder [Contact](#contact) hierboven zijn het nuttigst, en
functieverzoeken worden serieus gelezen.

## Gebruiksvoorwaarden

8 Ball wordt gelicentieerd onder Apple's standaardlicentieovereenkomst voor
apps, de
[Apple Standard End User License Agreement](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/).
Downloads via de App Store vallen daarnaast onder de
[Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/).

## Privacybeleid

[Lees het privacybeleid](../../privacy/nl/)
