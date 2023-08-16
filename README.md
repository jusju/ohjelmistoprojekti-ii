# Ohjelmistoprojekti 2, SOF007AS3A <!--SWD4TN024-->

Tämä Git-repositorio sisältää Ohjelmistoprojekti II -kurssin dokumentaation ja tiedostot.

## Kurssin sisältö

Opintojaksolla opiskelijat suunnittelevat ohjelmiston oikeaan tarpeeseen. Opiskelijat:

1. Organisoivat oman ryhmänsä toiminnan.
1. Tutustuvat tarpeeseen, joka voidaan ratkaista ohjelmistolla.
1. Määrittelevät ja suunnittelevat ratkaisun tuotantoiteraatio kerrallaan.
1. Toteuttavat ja esittelevät tuotantokelpoisia ratkaisuversioita.
1. Julkaisevat ohjelmistoratkaisun.

Kurssin suoritettuaan opiskelija ymmärtää ongelman ratkaisemiseen tarvittavia ohjelmistokehittäjän taitoja. Hän kykenee ymmärtämään ja kuvaamaan tarpeita ja ehdottamaan niihin soveltuvia ohjelmistoratkaisuja. Hän osaa itsenäisesti lisätä osaamistaan aiemmin tuntemattomista teknologioista. Hän oppii arvioimaan ja valitsemaan avoimen maailman ongelmanratkaisuun soveltuvia teknologioita ja menetelmiä. Hän osaa ottaa vastuun jostakin toteutettavan ratkaisun osa-alueesta. Hän osaa jakaa hankkimaansa osaamista muille tiiminsä jäsenille. Opiskelija osaa tiimin jäsenenä toteuttaa tuotantokelpoisen ohjelmistoratkaisun ongelmaan.

Kurssin arviointi perustuu ryhmätyöskentelyyn, ryhmän lopullisen tuloksen tarkoituksenmukaiseen toimivuuteen sekä kurssin lopuksi yksilötyönä tehtävään esseeseen, jossa arvioidaan omaa ja ryhmän toimintaa.

Ohjelmistokehityksen teknologioita -kurssi toimii osin tämän kurssin teknisenä tukikurssina. Suosittelemme hyödyntämään kyseisellä kurssilla käsiteltyjä aiheita, kuten testausta ja jatkuvaa integraatiota, tämän kurssin projektissa.

Kurssin lopputulokset julkaistaan lähtökohtaisesti avoimella lisenssillä.

Katso myös:

- [opintojaksokuvaus](https://opinto-opas.haaga-helia.fi/course_unit/SOF007AS3A)
- [Scrum guides](https://scrumguides.org/)
- [Readme Driven Development](https://tom.preston-werner.com/2010/08/23/readme-driven-development.html)

## Kurssin opettajat

Kalle Ilves (kalle.ilves@haaga-helia.fi) ja Jukka Juslin (jukka.juslin@haaga-helia.fi)

## 📑 Aiemmin hankitun osaamisen tunnistaminen (AHOT)

Jos olet hankkinut tämän opintojakson mukaisen osaamisen työsi kautta, voit osoittaa osaamisesi tavanomaisen osallistumisen sijasta AHOT-menettelyllä. Osaamisen tunnistamiseksi ilmoittaudu tälle kurssille normaalisti, ja ole yhteydessä kurssin opettajiin AHOT-järjestelyjen osalta **viimeistään kurssin ensimmäisen viikon aikana**.

Tarkemmat ohjeet AHOT-käytäntöjen suhteen löydät [erilliseltä sivulta](./ahot.md).

# 📅 Kurssin aikataulu _(syksy 2023)_

Kurssin yhteiset tapaamiset järjestetään _tiistaisin klo 11-13:45 luokassa 5006 22.8. alkaen_.

Kurssille varattuina ajankohtina työskennellään projektin parissa scrum-kehyksen mukaisesti. Tavoitteenamme on työskennellä kolmen viikon sprinteissä, joita mahtuu kurssille 4 kappaletta. Intensiivi- ja lomaviikkoja ei huomioida osana sprinttien kestoa.

Kunkin tiimin sprintin aloitukset ja katselmoinnit pyritään järjestämään toistuvasti samoina viikonpäivinä ja kellonaikoina, jolloin sprinttien pituudet pysyvät tasaisina.

Kurssin laajuus on 10 opintopistettä, [eli noin 270 tuntia](https://www.haaga-helia.fi/fi/ects-jarjestelma-ja-tutkintotodistuksen-liite-eli-diploma-supplement). Syksyn aikana viikoittaiseksi työmääräksi tulee noin 17 tuntia. Tulet siis työskentelemään merkittävässä määrin myös yhteisten tapaamisten ulkopuolella.

## Sprint 0: Projektien käynnistys _(21.8.-3.9.)_

### 📅 22.8. tiimien muodostaminen

- Kurssin käytäntöjen ja tavoitteiden käsittely
- Ketterä ohjelmistokehitys ja Scrum
- Jakautuminen tiimeihin. Tiimin tavoitekoko on 5 henkilöä
- [Palvelujen kehittämisen menetelmät (haaga-helia.fi)](https://www.haaga-helia.fi/fi/tool-factory-menetelmat-palvelujen-kehittamiseen)
- [Esimerkkejä avoimen rajapinnan tarjoavista palveluista](avoimet-rajapinnat.md)

#### ✏️ Tehtävä

- Projektiaiheiden pohtiminen tiimin kesken. Hyviksi aiheiksi on todettu scopeltaan eli laajuudeltaa siinä määrin pienet, että ei jouduta tekemään esimerkiksi 15 tietokantataulua. Ohjelmistoa kannattaisi tehdä siinä toivossa, että se tulisi oikeasti käyttöön, vaikkakin tavoite on usein osoittautunut erittäin haastavaksi.
- Yksi kaikille tarjottu aihe on Haaga-Helian helpdeskin vetäjän ehdottama lentohintojen seuraaminen: https://www.youtube.com/watch?v=16A4tTeLq4g
- Jos ideoita ei meinaa spontaanisti syntyä, niin opettajille on ehdottaa seuraavia aiheita: 1) sovellus verenpaineiden noin päivittäiseen mittaamiseen mahdollisesti pienellä graafisella kuvaajalla 2) Työtuntien nauhoitussovellus sitä varten, että kun tekee tuntityötä jollekin, niin on oltava tarkka kirjanpito siitä, että mitä on tehty, milloin ja kuinka pitkään. Tuntityössähän usein on jokin palkka, esimerkiksi 40 euroa. 3) Opiskelijan omaan käyttöön voisi tehdä juna/bussi/raitiovaunu/metro sovelluksen joka hakisi avoimista rajapinnoista tarkkaa tietoa yksittäisen opiskelijan tarpeisiin kustomoituna ja sivu olisi niin yksinkertainen, että se on helppo avata puhelimellakin.
- Avoimen datan lähteisiin ja avoimen lähdekoodin projekteihin tutustuminen.
- Projektiaiheiden pohtiminen tiimin kesken. [Aikaisempien lukukausien projekteja](./aiempia-projekteja.md) vilkaisemalla saa hyvän kuvan kurssin projektien laajuudesta.

### 📅 29.8. "define sprint"

- Vaatimusmäärittely ketterässä ohjelmistokehityksessä
- Käyttäjätarinat
  - Esimerkki määrittelydokumentista ja käyttäjätarinoista: [Form Autofill for Firefox Desktop](https://docs.google.com/document/d/1j31lNkc_OFNNoxKmOJX5LWrbLn5zD19ngwsQtq_edVc/edit)
- Scrum backlogit
- GitHub project -palvelun nopea intro
  - YouTube: [Plan and track projects closer to your code #DemoDays](https://youtu.be/SI1ra-XHWHM)
  - GitHub blog: [How we’re using projects to build projects](https://github.blog/2022-05-16-how-were-using-projects-to-build-projects/)

#### ✏️ Tehtävä

- [Projektin GitHub-repositorion luominen](https://docs.github.com/en/get-started/quickstart/create-a-repo) ja jakaminen opettajalle.
- Projektin kuvaus GitHub-repositorion [README-tiedostoon](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes). Kuvauksesta tulee tässä vaiheessa tulla ilmi ainakin seuraavat asiat:
  - Alustava kuvaus projektista, jossa vastataan ainakin seuraaviin kysymyksiin:
    - Projektin nimi.
    - Mikä on toteuttavan sovelluksen tarkoitus?
    - Mitkä ovat sovelluksen tärkeimmät ominaisuudet, eli mitä sovelluksen käyttäjä voi sillä tehdä?
    - Mitä toteutusteknologioita (esim. ohjelmointikieltä, tai sovelluskehystä kuten Spring Boot, tai Django) projektin toteutuksessa tullaan käyttämään.
  - Ryhmän jäsenten nimet.
- User storyjen tai taskien valinta ensimmäiselle sprintille ja niiden lisääminen Github projects -taululle.

**Jokaisen tiimiläisen tulee palauttaa tiimin projektin GitHub-repositorion linkki [Moodlen-kautta](https://hhmoodle.haaga-helia.fi/mod/assign/view.php?id=2522804) sunnuntaihin 3.9. mennessä.**

## Sprint 1 _(4.9.-24.9.)_

Sprint 1:llä tiimit aloittavat itsenäisen työskentelyn projektin toteuttamisen parissa ja hyödyntävät ohjausta opetustilaisuuksissa ja Teams-kanavalla. Sprintti päättyy tiimikohtaisiin katselmointeihin.

### 📅 5.9. Sprint 1:n käynnistys

- Harjoitellaan Git:in käyttöä tiimityöskentelyssä
- Jos Git-taidot ovat päässeet ruostumaan, kannattaa käydä läpi [Versionhallinta: Git ja GitHub](https://tkt-lapio.github.io/git/)-materiaali läpi ennen opetuskertaa
- Tiimit aloittavat itsenäisen työskentelyn projektien parissa. Opettajat tutustuvat tiimien backlogeihin ja keskustelevat/antavat palautetta suunnitelmista.

### 📅 12.9.

Sprint 1 jatkuu. Tiimit työskentelevät itsenäisesti projektien parissa ja hyödyntävät opettajien ohjausta kutsumalla opettajat mukaan tiimin tapaamisiin.

### 📅 19.9. Sprint 1 katselmoinnit

Kukin tiimi esittelee **sprintin tulokset** ja **ensimmäisen version dokumentaatiostaan** (readme). Tiimit pitävät itsenäisesti retrospektiivit, joiden perusteella työtapoja kehitetään seuraavaa sprinttiä varten.

Tällä sprintillä esiteltävä versio voi hyvin olla paikallisesti ajossa kehittäjällä.

#### Sprint 2 planning

Katselmointien jälkeen tiimit valitsevat käyttäjätarinat sprintille 2 ja tekevät niihin tarvittavat tarkennukset ja määrittelyt.

## Sprint 2 _(25.9.-15.10.)_

### 📅 26.9. Sprint 2:n käynnistys

Tiimit työskentelevät itsenäisesti projektien parissa ja hyödyntävät ohjausta kutsumalla opettajat mukaan tiimin tapaamisiin.

### 📅 3.10.

Sprint 2 työskentely jatkuu. Opettajat nimeävät jokaiselle tiimille **vertaisryhmän**, jotka **katselmoivat toistensa lähdekoodit** ja antavat palautetta demoissa.

Vertaisryhmät toimittavat toisilleen katselmointipyynnöt, jossa ovat rajanneet omasta projektistaan katselmoitavan osan.

[Koodin katselmoinnin ohjeistus](scrum/koodin-katselmointi.md).

### 📅 10.10. Sprint 2 katselmoinnit

Kukin tiimi esittelee sprintin tulokset opettajille ja vertaisryhmille. **Mahdollisuuksien mukaan sovelluksen tulisi olla ajossa tuotantoympäristöä vastaavassa ympäristössä**, tai tuotantoympäristön tulisi olla vähintään valittu perustellusti.

**Vertaisryhmät** toimittavat toisilleen katselmointiraportit lähdekoodin katselmointien tuloksista.

Tiimit pitävät itsenäisesti retrospektiivit, joiden perusteella työtapoja kehitetään seuraavaa sprinttiä varten.

#### Sprint 3 planning

Katselmointien jälkeen tiimit valitsevat käyttäjätarinat sprintille 3 ja tekevät niihin tarvittavat tarkennukset ja määrittelyt.

## Kurssin puolivälin itsearvioinnit

Kurssin ensimmäisen itsearvioinnin kirjoittaminen ja oman oppimisen pohdinta. Tarkemmat ohjeet ja aikataulun löydät kurssin Teams-kanavalta projektien loppuvaiheessa.

## 16.-22.10. Intensiiviviikko

Ei kurssin yhteisiä tapaamisia.

## Sprint 3 _(23.10.-12.11.)_

### 📅 24.10. Sprint 3:n käynnistys

Tiimit työskentelevät itsenäisesti projektien parissa ja hyödyntävät ohjausta kutsumalla opettajat mukaan tiimin tapaamisiin.

### 📅 31.10.

Tiimit työskentelevät itsenäisesti projektien parissa ja hyödyntävät ohjausta kutsumalla opettajat mukaan tiimin tapaamisiin.

Vertaisryhmät toimittavat toisilleen katselmointipyynnöt, jossa ovat rajanneet omasta projektistaan katselmoitavan osan.

### 📅 7.11. Sprint 3 katselmoinnit

Kukin tiimi esittelee sprintin tulokset opettajille ja vertaisryhmille.

**Vertaisryhmät** toimittavat toisilleen katselmointiraportit lähdekoodin katselmointien tuloksista.

Tiimit pitävät itsenäisesti retrospektiivit, joiden perusteella työtapoja kehitetään seuraavaa sprinttiä varten.

## Sprint 4 _(13.11.-3.12.)_

Tiimit pyrkivät viimeisessä sprintissä stabiloimaan projektinsa, eli he keskittyvät erityisesti toimintavarmuuden takaamiseen uusien ominaisuuksien jäädessä pienemmälle painoarvolle.

Sprintin tavoitteena on projektien lähdekoodien julkaisu, sekä sovellusten mahdollinen julkaisu sovelluskaupassa, npm:ssä tai web-palvelimella.

### 📅 14.11. Sprint 4:n käynnistys

Tiimit työskentelevät itsenäisesti projektien parissa ja hyödyntävät ohjausta kutsumalla opettajat mukaan tiimin tapaamisiin.

### 📅 21.11.

Tiimit työskentelevät itsenäisesti projektien parissa ja hyödyntävät ohjausta kutsumalla opettajat mukaan tiimin tapaamisiin.

Vertaisryhmät toimittavat toisilleen katselmointipyynnöt, jossa ovat rajanneet omasta projektistaan katselmoitavan osan. Viimeisessä sprintissä ei vertaiskatselmoida koodia, vaan projektin "yleisilmettä" painottuen erityisesti Git-repostitorioon ja dokumentaatioon.

[Ohjeita projektin viimeistelyyn (dokumentointi, stabilointi ja tietoturva).](scrum/projektin-viimeistely.md)

### 📅 28.11. Projektien loppudemot

Sprint 4 päättyy kurssin loppudemoihin, joissa kukin tiimi esittelee tuloksiaan muille.

Muistakaa myös dokumentoida projektinne mahdolliset tunnettut puutteet ja bugit ([GitHub issueina](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue)).

## Itse- ja vertaisarvioinnit

Kurssin itse- ja vertaisarviointien kirjoittaminen ja oman oppimisen pohdinta. Tarkemmat ohjeet ja aikataulun löydät kurssin Teams-kanavalta projektien loppuvaiheessa.

---

Tämän sivuston ovat kehittäneet Teemu Havulinna ja Ismo Harjunmaa. Materiaali pohjautuu suuresti Ohto Rainion kurssimateriaaleihin.
