# Koodin katselmointi vertaisryhmittäin

Ohjelmistoprojekti II -kurssilla hyödynnämme demojen lisäksi koodikatselmointeja vertaispalautteen saamiseksi.

Katselmoitte kurssilla itse vertaisryhmänne koodia ja saatte vastavuoroisesti vertaisryhmältänne palautetta omasta koodistanne. Samalla opimme katselmoimaan koodia ja antamaan rakentavaa palautetta sekä kehitysehdotuksia.

Katselmoinnit suoritetaan siten, että kukin ryhmä lähettää vertaisryhmälleen Teams-kanavalle katselmointipyynnön, johon vertaisryhmä vastaa palautteen kera.

Alkuvaiheessa koodin tai katselmointien laadun ei tarvitse olla häikäisevää, vaan päätavoite on kehittyä kurssin aikana.


**TL;DR: tärkeimmät actionpointit:**

1. Tehkää katselmointipyyntö vertaisryhmällenne luomalla GitHub repositorioonne [issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue), jonka otsikko on "Katselmointipyyntö".
2. Katselmointipyynnössä tulee eritellä noin 100-200 riviä, josta haluatte saada palautetta. Mainitkaa pyynnössä katselmoitavat tiedostostot ja tarpeen tullen niiden osat (esim. tietyt metodit luokasta).
3. Kertokaa katselmointipyynnössänne lyhyesti, miten valitsemanne koodin laatu on varmistettu. Voitte esimerkiksi laittaa linkin automatisoituihin testeihin tai kuvailla muuten millä tavoin olette varmistaneet koodin toimivuuden.
4. Vertaisryhmä lukee katselmointipyynnön avamaalla "Katselmointipyyntö"-issuen repositorion "Issues"-tabilta, katselmoi koodin ja kirjoittaa katselmointipalautteen issueseen kommenttina. Kommentin voi kirjoittaa lomakkeella issuen alaosassa.
5. Kun katselmointipalaute on kirjoitettu, issuen kommenteissa voi käydä palautteesta vapaamuotoista keskustelua.

## Käytännöt

<!-- Koodin katselmointi tehdään versionhallintapalvelussa, joka valtaosalla tiimeistä on GitHub. Mikäli repositorionne ei ole julkinen, toimittakaa katselmoitavaksi haluamanne koodit vertaisryhmälle muulla tavoin, esimerkiksi kopioimalla koodi yksityiseen gistiin ([https://gist.github.com/](https://gist.github.com/)) ja jakamalla sen osoite vertaisryhmälle. Halutessanne voitte myös toimittaa katselmoitavan koodin tiedostona Teamsiin. -->

**Koodin katselmoimiseksi ryhmän ei tarvitse kloonata itselleen toisen ryhmän koodia eikä suorittaa sitä**. Tällä vältetään monimutkaiset ympäristöjen pystyttämiset ja riippuvuuksien asentamiset, jotka vievät aikaa varsinaiselta katselmoinnilta ja kehitysehdotuksilta. Ohjelman testaamisen sijaan keskitytte siis lukemaan koodia ja arvioimaan sen selkeyttä ja luettavuutta.

Selkeän, luettavan ja ylläpidettävän koodin kehittämisestä on julkaistu mm. laajaan suosioon noussut [Clean Code -kirja](https://www.google.com/search?q=robert+c+martin+clean+code). Kirjan lainaaminen ja sen lukeminen kokonaan ei ole välttämätöntä, mutta suosittelemme lukemaan esimerkiksi [kirjan tiivistelmän](https://www.google.com/search?q=robert+c+martin+clean+code+summary) tai samasta kirjasta erityisesti [JavaScriptiä varten sovelletun tyylioppaan](https://github.com/ryanmcdermott/clean-code-javascript) ([https://github.com/ryanmcdermott/clean-code-javascript](https://github.com/ryanmcdermott/clean-code-javascript)

Arvioikaa katselmointipyynnössä saamaanne kuvausta vertaisryhmän laadunvarmistuskäytännöistä. Oletteko luottavaisia tehtyyn laadunvarmistukseen, tai onko teillä kehitysehdotuksia esimerkiksi manuaalisen tai automatisoidun testauksen suhteen?

Antamanne palautteen ei tarvitse välttämättä pohjautua annettuihin lähteisiin, vaan voitte hyvin kirjoittaa omin sanoin kokemuksestanne annetun koodin lukemisessa.


## Projektin valmistelu katselmoitavaksi

Osa projekteista koostuu useista eri osista, kuten front-endistä ja back-endistä. Projekteissa on myös merkittäviä osia valmiista tutoriaaleista tai malliprojekteista lainattuja osia, joiden katselmointi ei ole ryhmän kehittymisen kannalta kovin hyödyllistä. Siksi jokaisen ryhmän on rajattava omasta projektista "kourallinen" koodia, eli suuruusluokkaa 1-2 tiedostoa tai **100-200 riviä**, joista toivotte eniten saavanne palautetta.

Lähettäkää vertaisryhmänne Teams-kanavalle linkki koodeihinne sekä selkeästi eriteltynä ne tiedostot, luokat, funktiot tai muut yksiköt joista toivotte palautetta. Kertokaa katselmointipyynnössänne myös lyhyesti, miten valitsemanne koodin laatu on varmistettu. Voitte esimerkiksi laittaa linkin automatisoituihin testeihin tai kuvailla muuten millä tavoin olette varmistaneet katselmoitavan koodin toimivuuden.

**Voitte koodin ohessa pyytää myös palautetta dokumentaatiostanne tai ohjeistanne**. Tarvittaessa antakaa lisäohjeet, kuten mistä branchista haluatte katselmoinnin tehtävän.


## Projektin katselmointi

Katselmointi suositellaan tehtäväksi koko tiimin voimin joko lähityöskentelynä tai hyödyntäen esimerkiksi Discordia tai Teamsia ruudunjakoa. Katselmoinnin yhteydessä käytävä keskustelu on myös erinomainen tilaisuus oppia itse.

Google on dokumentoinut omia katselmointikäytäntöjään "Best practices" -sivuilleen (https://github.com/google/eng-practices) ja "How to do a code review" -dokumenttiin (https://github.com/google/eng-practices/blob/master/review/reviewer/index.md).

Tässä katselmoinnissa ei ole tarpeen puuttua kaikkiin mahdollisiin koodissa oleviin haasteisiin ja keskeneräisyyksiin, vaan **painottaa sellaisia asioita, joihin pystytte kontribuoimaan positiivisesti**.

Nimeäminen, ymmärrettävyys, kommentointi ja koodin rakenne voivat olla hyviä ehdokkaita palautteelle. Jos jokin kohta koodissa vaikuttaa tarpeettoman monimutkaiselta, yrittäkää pohtia, miten sitä voitaisiin pilkkoa osiin tai yksinkertaistaa ja liittäkää ehdotus mukaan palautteeseenne.


## Muistakaa positiivinen henki

Toisen työn kommentointiin liittyy aina riski kritiikin aiheuttamasta tarpeettomasta mielipahasta. Pyritään siis löytämään kaverin koodista hyviä piirteitä ja antamaan konkreettisia kehitysehdotuksia pelkän kritiikin sijasta. Otetaan myös palaute vastaan hyvillä mielin: kukaan ei odota tiimien työn olevan täydellistä ja tämänkin työvaiheen tarkoitus on kehittyä ohjelmistokehittäjinä.
