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

Jukka Juslin (jukka.juslin@haaga-helia.fi) ja Jukka Remes (jukka.remes@haaga-helia.fi)

## 📑 Aiemmin hankitun osaamisen tunnistaminen (AHOT)

Jos olet hankkinut tämän opintojakson mukaisen osaamisen työsi kautta, voit osoittaa osaamisesi tavanomaisen osallistumisen sijasta AHOT-menettelyllä. Osaamisen tunnistamiseksi ilmoittaudu tälle kurssille normaalisti, ja ole yhteydessä kurssin opettajiin AHOT-järjestelyjen osalta **viimeistään kurssin ensimmäisen viikon aikana**.

Tarkemmat ohjeet AHOT-käytäntöjen suhteen löydät [erilliseltä sivulta](./ahot.md).

# 📅 Kurssin aikataulu _(kevät 2024)_

Kurssin yhteiset tapaamiset järjestetään _tiistaisin klo 8:00-10:30 luokassa 5006 16.1. alkaen_.

Kurssille varattuina ajankohtina työskennellään projektin parissa scrum-kehyksen mukaisesti. Tavoitteenamme on työskennellä kolmen viikon sprinteissä, joita mahtuu kurssille 4 kappaletta. Intensiivi- ja lomaviikkoja ei huomioida osana sprinttien kestoa.

Kunkin tiimin sprintin aloitukset ja katselmoinnit pyritään järjestämään toistuvasti samoina viikonpäivinä ja kellonaikoina, jolloin sprinttien pituudet pysyvät tasaisina.

Kurssin laajuus on 10 opintopistettä, [eli noin 270 tuntia](https://www.haaga-helia.fi/fi/ects-jarjestelma-ja-tutkintotodistuksen-liite-eli-diploma-supplement). Kurssin aikana viikoittaiseksi työmääräksi tulee noin 17 tuntia. Tulet siis työskentelemään merkittävässä määrin myös yhteisten tapaamisten ulkopuolella.

## Sprint 0: Projektien käynnistys _(16.1.-30.1.)_

### 📅 16.1. tiimien muodostaminen

- [Opetustilaisuuden kalvot](./kalvot/johdanto/johdanto.pdf)
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

### 📅 23.1. "define sprint"

- [Opetustilaisuuden kalvot](./kalvot/vaatimusmaarittely/vaatimusmaarittely.pdf)
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
    - Mitä toteutusteknologioita (esim. ohjelmointikieltä, tai sovelluskehystä kuten Spring Boot, tai Django) projektin toteutuksessa tullaan käyttämään. Tässä on tärkeää, että jos esimerkiksi Palvelinohjelmointi eli nykyiseltä nimeltään Back end-ohjelmointi ei ole arvosanaa 5, niin tilanne ei parane vaihtamalla tekniikkastäkkiä. 
  - Ryhmän jäsenten nimet.
- User storyjen valinta ensimmäiselle sprintille ja niiden jakaminen teknisiin taskeihin
- User storyjen lisääminen product backlogille ja taskien lisääminen sprint backlogille
- Linkki backlogeihin GitHub-reposiorion README-tiedostoon
- Varmistakaa, että _GitHub-repositorio ja backlog on julkinen_, jotta opettaja voi tarkastella sitä 

**Jokaisen tiimiläisen tulee palauttaa tiimin projektin GitHub-repositorion linkki [Moodlen-kautta](https://hhmoodle.haaga-helia.fi/mod/assign/view.php?id=2522804) sunnuntaihin 28.1. mennessä.**

## Sprint 1 _(30.1.-13.2.)_

Sprint 1:llä tiimit aloittavat itsenäisen työskentelyn projektin toteuttamisen parissa ja hyödyntävät ohjausta opetustilaisuuksissa ja Teams-kanavalla. Sprintti päättyy tiimikohtaisiin katselmointeihin.

### 🏃 30.1. Sprint 1:n käynnistys

- Harjoitellaan Git:in käyttöä tiimityöskentelyssä
- Gitin ja githubin toiminta on kuvattu hyvin seuraavassa materiaalissa: [Versionhallinta: Git ja GitHub](https://tkt-lapio.github.io/git/)-materiaali läpi ennen opetuskertaa
- Parityönä on suoritettava hyväksytysti Git harjoitus, jonka Jukka Juslin on tehnyt: https://jtjuslin.kapsi.fi/git-opetus/git-exercises-version11.pdf Git-harjoituksen suorittaneiden opiskelijanumerot tullaan listaamaan tähän kohtaan tällä sivulla ja vain heillä on mahdollista saada hyväksytty arvosana kurssista. 
- Tiimit aloittavat itsenäisen työskentelyn projektien parissa. Opettajat tutustuvat tiimien backlogeihin ja keskustelevat/antavat palautetta suunnitelmista.

### 📅 6.2. ja 13.2.

Sprint 1 jatkuu. Tiimit työskentelevät itsenäisesti projektien parissa ja hyödyntävät opettajien ohjausta kutsumalla opettajat mukaan tiimin tapaamisiin.

### 🔎 13.2. Sprint 1 katselmoinnit

Kukin tiimi esittelee **sprintin tulokset** ja **ensimmäisen version dokumentaatiostaan** (README). Tiimit pitävät itsenäisesti retrospektiivit, joiden perusteella työtapoja kehitetään seuraavaa sprinttiä varten.

Tällä sprintillä esiteltävä versio voi hyvin olla paikallisesti ajossa kehittäjällä.

#### Sprint 2 planning

Katselmointien jälkeen tiimit valitsevat käyttäjätarinat sprintille 2 ja tekevät niihin tarvittavat tarkennukset ja määrittelyt.

## Sprint 2 _(27.2.-12.3.)_ (2 viikon sprint)

### 🏃 27.2. Sprint 2:n käynnistys

Tiimit työskentelevät itsenäisesti projektien parissa ja hyödyntävät ohjausta kutsumalla opettajat mukaan tiimin tapaamisiin.

### 📅 5.3.

Sprint 2 työskentely jatkuu. Opettajat nimeävät jokaiselle tiimille **vertaisryhmän**, jotka **katselmoivat toistensa lähdekoodit** ja antavat palautetta demoissa.

Vertaisryhmät tekevät toisilleen katselmointipyynnöt **ennen seuraavaa opetuskertaa**, jossa ovat rajanneet omasta projektistaan katselmoitavan osan.

[Koodin katselmoinnin ohjeistus](scrum/koodin-katselmointi.md).

### 📅 12.3.

Sprint 2 jatkuu. Tiimit työskentelevät itsenäisesti projektien parissa ja hyödyntävät opettajien ohjausta kutsumalla opettajat mukaan tiimin tapaamisiin.

Vertaisryhmät tekevät toisilleen viikon aikana koodikatselmoinnin ja toimittavat sen **ennen seuraavaa opetuskertaa**.

[Koodin katselmoinnin ohjeistus](scrum/koodin-katselmointi.md).

### 🔎 12.3. Sprint 2 katselmoinnit

Kukin tiimi esittelee sprintin tulokset opettajille ja vertaisryhmille. **Mahdollisuuksien mukaan sovelluksen tulisi olla ajossa tuotantoympäristöä vastaavassa ympäristössä**, tai tuotantoympäristön tulisi olla vähintään valittu perustellusti.

Tiimit käy yhdessä läpi koodikatselmoinnin ja sopii sen perusteella tehtävistä parannuksista.

Tiimit pitävät itsenäisesti retrospektiivit, joiden perusteella työtapoja kehitetään seuraavaa sprinttiä varten.

#### Sprint 3 planning

Katselmointien jälkeen tiimit valitsevat käyttäjätarinat sprintille 3 ja tekevät niihin tarvittavat tarkennukset ja määrittelyt.

### 18.-24.3. Intensiiviviikko

Ei kurssin yhteisiä tapaamisia.

## Sprint 3 _(26.3.-16.4.)_

### 🏃 26.3. Sprint 3:n käynnistys

Tiimit työskentelevät itsenäisesti projektien parissa ja hyödyntävät ohjausta kutsumalla opettajat mukaan tiimin tapaamisiin.

### 📅 2.4. ja 9.4.

Tiimit työskentelevät itsenäisesti projektien parissa ja hyödyntävät ohjausta kutsumalla opettajat mukaan tiimin tapaamisiin.

Vertaisryhmät tekevät toisilleen katselmointipyynnöt **ennen seuraavaa opetuskertaa**, jossa ovat rajanneet omasta projektistaan katselmoitavan osan.

[Koodin katselmoinnin ohjeistus](scrum/koodin-katselmointi.md).

### 🔎 16.4 Sprint 3 katselmoinnit

Kukin tiimi esittelee sprintin tulokset opettajille ja vertaisryhmille.

Vertaisryhmät tekevät toisilleen viikon aikana koodikatselmoinnin ja toimittavat sen **ennen seuraavaa opetuskertaa**.

Tiimit pitävät itsenäisesti retrospektiivit, joiden perusteella työtapoja kehitetään seuraavaa sprinttiä varten.

#### Sprint 4 planning

Katselmointien jälkeen tiimit valitsevat käyttäjätarinat sprintille 4 ja tekevät niihin tarvittavat tarkennukset ja määrittelyt.

## Sprint 4 _(16.4.-7.5.)_

Tiimit pyrkivät viimeisessä sprintissä stabiloimaan projektinsa, eli he keskittyvät erityisesti toimintavarmuuden takaamiseen uusien ominaisuuksien jäädessä pienemmälle painoarvolle.

Sprintin tavoitteena on projektien lähdekoodien julkaisu, sekä sovellusten mahdollinen julkaisu sovelluskaupassa, npm:ssä tai web-palvelimella.

### 🏃 16.4. Sprint 4:n käynnistys

Tiimit työskentelevät itsenäisesti projektien parissa ja hyödyntävät ohjausta kutsumalla opettajat mukaan tiimin tapaamisiin.

### 📅 23.4.

Tiimit työskentelevät itsenäisesti projektien parissa ja hyödyntävät ohjausta kutsumalla opettajat mukaan tiimin tapaamisiin.

[Ohjeita projektin viimeistelyyn (dokumentointi, stabilointi ja tietoturva).](scrum/projektin-viimeistely.md)

### 📅 30.4.

Tiimit työskentelevät itsenäisesti projektien parissa ja hyödyntävät ohjausta kutsumalla opettajat mukaan tiimin tapaamisiin.

Tiimit reflektoivat omaa ja tiimin työskentelyä projektin aikana tekemällä **itse- ja vertaisarvioinnin**. Jokaisen tiimiläisen täytyy tehdä vertaisarviointi **ennen seuraavaa opetuskertaa**. Vertaisarvioinnin tekeminen on pakollista kurssinmerkinnän saamiseksi. Myöhässä palautettu vertaisarviointi vaikuttaa arvosteluun heikentävästi.

Lisätkää repositoryn README.md tiedostoon jokaisen ryhmäläisen kokonimi ja linkki github-profiiliin.

Tiimit reflektoivat työskentelyään myös tekemällä projektistaan lyhyen [loppuraportin](loppuraportti.md).

### 🔎 7.5. Projektien loppudemot

Sprint 4 päättyy kurssin loppudemoihin, joissa kukin tiimi esittelee tuloksiaan muille.

Muistakaa myös dokumentoida projektinne mahdolliset tunnettut puutteet ja bugit ([GitHub issueina](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue)).

### 📅 14.5.

Varapäivämäärä mahdollisten sairastumisten varalta. 

## Itse- ja vertaisarvioinnit

Kurssin itse- ja vertaisarviointien kirjoittaminen ja oman oppimisen pohdinta. Tarkemmat ohjeet ja aikataulun julkaistaan projektien loppuvaiheessa.

---

Tämän sivuston ovat kehittäneet Teemu Havulinna, Ismo Harjunmaa, Kalle Ilves ja Jukka Juslin. Materiaali pohjautuu suuresti Ohto Rainion kurssimateriaaleihin.
