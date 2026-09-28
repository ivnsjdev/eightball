# 8 Ballin tietosuojakäytäntö

**Voimaantulopäivä:** 15. syyskuuta 2026

**Viimeksi päivitetty:** 15. syyskuuta 2026

## Lyhyesti

8 Ball ei kerää eikä lähetä mitään. Se on Apple Watch -sovellus, jossa ei ole
lainkaan verkkokoodia: ei palvelinta, ei tiliä, ei analytiikkaa, ei mainontaa,
ei seurantaa eikä kolmannen osapuolen SDK:ta. Kysymystäsi ei koskaan kirjoiteta
mihinkään, joten sovellus ei koskaan saa sitä. Ainoat tallennettavat asiat ovat
valitsemasi ulkoasu, tunnus ja kieli, ja ne tallennetaan kellollesi.

## Keitä me olemme

8 Ballin ("sovellus") on kehittänyt **IVAN CAYABYAB** ("me").

Jos sinulla on kysyttävää tästä käytännöstä tai yksityisyydestäsi, ota meihin
yhteyttä osoitteessa **ivnsjdev@gmail.com**.

## Mitä 8 Ball tallentaa ja missä

8 Ball on ennustava pallo: esität kyllä/ei-kysymyksen, ravistat, ja se näyttää
yhden kahdestakymmenestä vastauksesta. Kolme valintaa, jotka voit tehdä
Asetuksissa, tallennetaan kellollesi watchOS:n vakiomuotoisella
sovellusasetusten tallennustavalla. Emme koskaan saa niitä.

| Mitä 8 Ball tallentaa | Ensisijainen tallennuspaikka | Lähetetäänkö meille automaattisesti? |
| --- | --- | --- |
| Pallolle valitsemasi ulkoasu | Kellollasi | Ei |
| Sen "olkapäälle" valitsemasi tunnus | Kellollasi | Ei |
| Asetuksissa valitsemasi kieli | Kellollasi | Ei |

Tämä on koko luettelo. Muuta ei ole: ei profiilia, ei tunnistetta, ei
käyttölaskuria, ei lokia siitä, mitä kysyit tai mitä sinulle vastattiin.
Sovellus ei lähetä mitään näistä meille tai muille yrityksille, emmekä me
kerää, myy, vuokraa tai jaa niitä. Laitteen varmuuskopioita hallitsee
käyttöjärjestelmä, ei 8 Ball.

## Kysymystäsi ei koskaan kerätä, koska sitä ei koskaan syötetä

8 Ballissa ei ole tekstikenttää, mikrofonin käyttöä eikä sanelua. Kysyt
pallolta ääneen tai mielessäsi, eikä sovellus koskaan saa tietää, mitä
kysyit — ei ole mitään syöttöreittiä, jota pitkin se voisi saapua. Se valitsee
yhden kahdestakymmenestä vastauksesta sattumanvaraisesti tuntematta
kysymystä.

## Vastaustakaan ei säilytetä

Näytöllä näkyvä vastaus elää muistissa vain niin kauan kuin se näytetään.
Sitä ei tarkoituksella koskaan kirjoiteta tallennustilaan, historianäkymää ei
ole, ja se katoaa, kun sovellus suljetaan. Mikään ei kerry käyttökertojen
välillä.

Kun kello on Always-On-tilan himmeässä näkymässä, vastausikkuna on merkitty
yksityisyydelle arkaluontoiseksi, joten watchOS peittää sen, kunnes nostat
ranteesi. Joku, joka vilkaisee laskettua rannettasi, ei näe vastaustasi.

## Ei tiliä, ei kirjautumista, ei pilveä

8 Ballissa ei ole käyttäjätilejä, eikä mihinkään tarvitse rekisteröityä. Se ei
kysy sähköpostiosoitetta, puhelinnumeroa, syntymäaikaa tai muuta tiliin
liittyvää tietoa. Se ei käytä iCloudia, CloudKitiä eikä mitään muuta
synkronointipalvelua, joten ulkoasusi, tunnuksesi ja kielesi eivät siirry
laitteiden välillä. Se on itsenäinen kellosovellus ilman iPhone-lisäsovellusta,
joten se ei jaa mitään puhelimen kanssa. Käyttöjärjestelmäsi laitteen
varmuuskopio voi sisältää 8 Ballin paikallisia sovellustietoja, jos olet
valinnut varmuuskopioida laitteen.

## Liike, ja miksi lupakehotetta ei ole

Havaitakseen ravistuksen 8 Ball lukee kellon laiteliiketietoja — tarkemmin
sanottuna käyttäjän kiihtyvyysvektoria, joka on ranteesi liike ilman
painovoiman vaikutusta. Sitä näytteistetään, kun pallo on näytöllä,
tarkastetaan välittömästi sen päättämiseksi, tapahtuiko juuri tarkoituksellinen
ravistus, ja sitten hylätään. Sitä ei tallenneta, ei säilytetä eikä lähetetä,
eikä sitä käytetä mihinkään muuhun kuin pyörähdyksen käynnistämiseen.

watchOS ei suojaa tätä tietoa lupakehotteella samalla tavalla kuin iOS, minkä
vuoksi kehotetta ei näytetä ja sovellus julkaistaan ilman liikkeen
käyttötarkoituksen kuvausta: käyttötarkoitusmerkkijonon ilmoittaminen, jota
järjestelmä ei koskaan näytä, olisi harhaanjohtavaa eikä informatiivista.
Ranteen tunnistuksen tai Always-On-tilan päälle kytkeminen on kellon asetus,
eikä jotain, mitä 8 Ball pyytää.

## Käyttöoikeudet, joita emme pyydä

8 Ball ei pyydä yhtäkään järjestelmän käyttöoikeutta. Se ei käytä kameraasi,
kuvakirjastoasi, mikrofoniasi, sijaintiasi, yhteystietojasi, kalenteriasi,
terveys- tai treenitietojasi, ilmoituksiasi eikä Siriä, eikä lupakehotetta
näytetä koskaan.

## Ääni, haptiikka ja Digital Crown

8 Ball ei toista ääntä. Palaute on haptista — kolme napautusta pallon
miettiessä, yksi vastauksen kohdalla — Applen kellon vakiohaptiikan kautta.
Digital Crownin kääntäminen vetää palloa käyntiin. Mikään näistä ei lue
mitään kellostasi eikä lähetä siitä mitään.

## Diagnostiikka

Sovellus kirjoittaa yhden merkinnän järjestelmälokiin silloin, kun laiteliike
ei ole käytettävissä laitteistossa, jolla se toimii, jotta ravistukseen
liittyvät virheraportit voidaan ymmärtää. Se ei sisällä henkilötietoja eikä
käyttäjätietoja. Se pysyy laitteella Applen yhtenäisen lokijärjestelmän
alaisuudessa, ei ole kaatumisraportointityökalu, eikä sitä lähetetä meille.

## Ostokset

8 Ball on **kertaostos**. Maksat App Storen hinnan kerran, ja se on ainoa
maksu, joka on olemassa: ei sovelluksen sisäisiä ostoksia, ei tilauksia, ei
kokeilujaksoa, ei maksullista lukituksen avausta eikä mainontaa. Sovellus ei
linkitä StoreKitiä lainkaan, joten sen sisällä ei ole ostokoodia, eikä mikään
sovelluksessa voi koskaan veloittaa sinua — ainoan veloituksen tekee Apple
latauksen yhteydessä, emme me. Ostaminen App Storesta jättää merkinnän
Apple-tilillesi, jonka Apple säilyttää, ja kyseinen osto on sinun ja Applen
välinen asia: emme koskaan saa Apple-tilisi kirjautumistietoja, maksutietojasi,
korttinumeroasi emmekä laskutusosoitettasi, emmekä ylläpidä mitään
ostopalvelinta. Applen käsittely kuuluu sen
[App Store & Privacy](https://www.apple.com/legal/privacy/data/en/appstore/)
-ilmoituksen piiriin. Sovelluksen käyttöä säätelee Applen
[Standard End User License Agreement](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/),
ja App Storesta ladattuja sovelluksia
[Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/)
-ehdot.

## Tukiviestintä

Jos lähetät meille sähköpostia tuen saamiseksi, saamme sähköpostiosoitteesi,
viestisi sekä mahdolliset laite-, sovellusversio-, kuvakaappaus- tai muut
tiedot, jotka päätät liittää mukaan. Käytämme niitä vain vastataksemme,
tutkiaksemme ongelman ja parantaaksemme 8 Ballia. Älä lähetä tietoja, joita
pyyntösi ei vaadi.

Siellä, missä GDPR tai Ison-Britannian GDPR soveltuu, käsittelemme
tukiviestejä oikeutetun etumme perusteella vastata meille kirjoittaviin
ihmisiin ja korjata heidän ilmoittamansa ongelmat. Muuta käsittelyä, jolle
pitäisi etsiä peruste, ei ole, koska 8 Ball ei lähetä meille mitään itsestään.

Tukisähköposti on vapaaehtoista ja tapahtuu 8 Ballin ulkopuolella. Sen
käsittelee sähköpostipalveluntarjoajasi sekä Google, joka isännöi
tukilaatikkoamme,
[Google Privacy Policy](https://policies.google.com/privacy) -käytännön
mukaisesti. Googlen sähköpostipalvelimet sijaitsevat Yhdysvalloissa, joten
meille lähettämäsi tukiviesti käsitellään siellä. Säilytämme tukiviestejä
enintään 24 kuukautta, ja pidempään vain silloin, kun laillinen,
tietoturvaan liittyvä tai kirjanpidollinen velvoite sitä edellyttää. Voit
pyytää meitä poistamaan tukikirjeenvaihtosi lähettämällä sähköpostia alla
olevaan osoitteeseen.

## Ulkoiset linkit

8 Ball voi näyttää tämän tietosuojakäytännön osoitteen Asetuksista, ja sen
avaaminen siirtää linkin pariutetulle iPhonellesi, koska kellossa ei ole omaa
selainta. Tuo kohde — tämä sivu — tarjoillaan GitHub Pagesin kautta, joka
käsittelee vierailun
[GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)
-käytännön mukaisesti. 8 Ball ei lisää kyseiseen linkkiin mitään sinua tai
sovelluksesi kopiota yksilöivää tietoa. Sovellus ei avaa mitään muuta
ulkoista osoitetta.

## Satunnaisuus, ja mitä se ei ole

Jokainen vastaus arvotaan tasajakaumalla kahdestakymmenestä käyttäen
järjestelmän satunnaislukugeneraattoria, ja arvonta tapahtuu ennen kuin pallo
alkaa liikkua — animaatio näyttää jo valitun tuloksen sen sijaan, että se
ohjautuisi kohti jotain. Sovellus ei opi sinusta, ei mukaudu sinuun, ei
profiloi sinua, eikä sillä ole mitään mallia sinusta, jonka mukaan mukautua.
Mikään, mitä teet, ei muuta seuraavaa vastausta.

## Mitä emme tee

Selvyyden vuoksi 8 Ball **ei**:

- lähetä mitään minnekään — se ei sisällä minkäänlaista verkkokoodia
- kerää eikä lähetä kysymystäsi, saamiasi vastauksia tai asetuksiasi
- käytä analytiikkaa, kaatumisraportointia tai telemetriapalveluita
- sisällä mainontaa tai mainostunnisteita
- seuraa sinua sovellusten tai verkkosivustojen välillä eikä jaa tietoja
  datavälittäjien kanssa
- luo käyttäjätilejä eikä vaadi sähköpostiosoitetta, puhelinnumeroa tai
  kirjautumista
- lue kameraasi, kuviasi, mikrofoniasi, yhteystietojasi, sijaintiasi tai
  terveystietojasi
- tallenna eikä säilytä liiketietoja
- käytä tietojasi koneoppimismallien kouluttamiseen
- sisällä mitään kolmannen osapuolen SDK:ta

8 Ballin App Store -tietosuojamerkintä heijastaa tätä:
**Data Not Collected (tietoja ei kerätä)**.

## Tietojen säilyttäminen ja poistaminen

**8 Ballin paikallisten tietojen poistaminen:** poista sovellus kellostasi.
Tämä poistaa valitsemasi ulkoasun, tunnuksen ja kielen. Muuta poistettavaa ei
ole, eikä palvelinkopiota ole olemassa missään. iCloud- tai
tietokonevarmuuskopioita hallitsevat erikseen sinä ja Apple, ja ne voivat yhä
sisältää sovellustietoja; Apple selittää, miten
[hallita iCloud-varmuuskopioita](https://support.apple.com/en-us/108922).

Tukisähköpostit ovat erillään sovellustiedoista. Voit pyytää
tukikirjeenvaihdon poistamista yllä kuvatulla tavalla, ellei meidän tarvitse
säilyttää joitakin tietoja laillisista, tietoturvaan liittyvistä tai
kirjanpidollisista syistä.

## Oikeutesi

Asuinpaikastasi riippuen sinulla voi olla oikeuksia GDPR:n, Ison-Britannian
GDPR:n, CCPA/CPRA:n tai vastaavien lakien nojalla — mukaan lukien oikeus
käyttää, korjata, viedä tai poistaa henkilötietojasi, sekä oikeus olla
joutumatta syrjityksi näiden oikeuksien käyttämisen vuoksi.

Kaiken 8 Ballin sisällä luodun osalta käytät näitä oikeuksia suoraan: kolme
asetusta elävät sovelluksen paikallisessa säilössä kellollasi, eikä meillä
ole niistä kopiota, jonka voisimme tuottaa, muuttaa tai poistaa puolestasi.
Meille lähettämäsi tukikirjeenvaihdon osalta ota meihin yhteyttä pyytääksesi
pääsyä, korjausta tai poistoa. Emme myy emmekä jaa henkilötietoja
mainontatarkoituksiin, emmekä ole koskaan tehneet niin.

Jos uskot, ettemme ole täyttäneet velvoitteitamme, voit ottaa meihin yhteyttä
yllä olevaan osoitteeseen, ja sinulla on oikeus tehdä valitus paikalliselle
tietosuojaviranomaisellesi.

## Lapset

8 Ball on ikäluokiteltu 4+ ja sopii koko perheelle. Se on yleisölle
suunnattu sovellus, ei erityisesti lapsille suunnattu. Sovellus ei tietoisesti
kerää henkilötietoja keneltäkään, mukaan lukien alle 13-vuotiaat lapset (tai
vastaava vähimmäisikä heidän maassaan) — se ei kerää tietoja keneltäkään.
Siinä ei ole chattia, jakamista, sosiaalisia ominaisuuksia, mainontaa tai
ostomahdollisuutta, joiden kautta lapseen voitaisiin ottaa yhteyttä tai häntä
voitaisiin veloittaa. Vanhemman tai huoltajan tulisi lähettää mahdollinen
tukisähköposti lapsen puolesta.

Kaksikymmentä vastausta ovat klassisen lelun vastauksia eivätkä ne ole
neuvoja. 8 Ball on lelu, jolla päätetään esimerkiksi, mitä syödä lounaaksi,
eikä mihinkään siinä tulisi luottaa minkään tärkeän päätöksen tekemisessä.

## Muutokset tähän käytäntöön

Jos tämä käytäntö muuttuu, päivitämme tämän sivun ja tarkistamme yllä olevan
"Viimeksi päivitetty" -päivämäärän. Merkittävistä muutoksista mainitaan myös
sovelluksen julkaisutiedoissa. Suosittelemme tarkistamaan tämän sivun
ajoittain.

## Yhteystiedot

Kysymykset, huolenaiheet tai pyynnöt:

**ivnsjdev@gmail.com**
