# Vaatimusmäärittely ja Scrum-backlogit

---

# Vaatimusmäärittely

- _Vaatimusmäärittely_ on ohjelmistotuontoprosessin vaihe, jossa määritellään _asiakkaan vaatimukset_ toteutettavalle ohjelmistolle
- Vaatimusmäärittelyn aikana vaatimukset selvitetään ja _dokumentoidaan_, jotta kehitystiimi voi aloittaa teknisen suunnittelun ja toteutuksen
- Ketterässä ohjelmistokehityksessä vaatimusmäärittelyä tehdään iteratiivisesti vähän kerrassaan
- Asiakas (Scrumissa tuoteomistaja) _priorisoi_ vaatimukset
- Kuhunkin iteraatioon valitaan toteutettavaksi ne vaatimukset, jotka tuovat asiakkaalle _mahdollisimman paljon liiketoiminnallista arvoa_

---

# User story

- Ketterän vaatimusmäärittelyn tärkein työväline on _user story_
- User storyt kuvaat loppukäyttäjän kannalta _arvoa tuottavia toiminnallisuuksia_
- User storyt kirjoitetaan _asiakkaan ymmärtävällä kielellä_, eli ne eivät saa sisältää turhan teknistä kieltä

> ❌ Käyttäjänä voin lähettää HTTP-kutsun rekisteröitymisestä vastaavaan API-endpointtiin, joka lisää käyttäjätunnuksen ja salasanan tietokantatauluun "users"

> ✅ Käyttäjänä voin rekisteröityä järjestelmään käyttäjätunnuksella ja salasanalla

---

# Hyvän user storyn kriteerit

- Erään suositun määritelmään mukaan hyvä user story toteuttaa _INVEST_-kriteerit:
  - **I**ndependent: user story on riippumaton muista user storyista
  - **N**egotiable: user storyn kuvauksessa on joustoa toteutuksen suhteen
  - **V**aluable: user story tuottaa arvoa
  - **E**stimable: user storyn toteutukseen kuluva aika on määriteltävissä
  - **S**mall: user story on riittävän pieni, toteutus vie enintään yhden sprintin
  - **T**estable: user storyn toteutuksen toimivuus on todennettavissa

---

# Hyvän user storyn kriteerit

Yleisin rike INVEST-kriteereitä kohtaan on se, että _user story on liian suuri_:

> ❌ Käyttäjänä voin rekisteröityä järjestelmään käyttäjätunnuksella, salasanalla, profiilikuvalla ja profiilikuvauksella

Tässä tilanteessa user story kannattaa _pilkkoa useaksi user storyksi_:

> ✅ Käyttäjänä voin rekisteröityä järjestelmään käyttäjätunnuksella ja salasanalla

> ✅ Käyttäjänä voin rekisteröitymisen yhteydessä antaa profiilikuvan

> ✅ Käyttäjänä voin rekisteröitymisen yhteydessä antaa profiilikuvauksen

---

# Product backlog

- Scrumissa _product backlog_ on tuoteomistajan priorisoima lista user storyja
- Product backlogin kärjessä eli korkeimmilla prioriteetilla olevat user storyt valitaan toteutettavaksi seuraavan sprintin aikana
- Product backlogin user storyja lisätään, muokataan ja priorisoidaan jatkuvasti sprinttien edetessä

---

# Sprint backlog

![bg fit right:25%](product-backlog-sprint-backlog.png)

- Product backlogilta valitaan sprintin aikana toteutettavat user storyt sprintin tehtävälistana toimivaan _sprint backlogiin_
- Kehitystiimi valitsee product backlogin kärjestä user storyt, jotka kokevat pystyvänsä toteuttaa sprintin aikana
- Kehitystiimi pilkkoo user storyt teknisen tason _taskeiksi_
- Taskit lisätään sprint backlogille

---

# User storyn pilkkominen taskeiksi

Esimerkiksi tämän user storyn:

> Käyttäjänä voin rekisteröityä järjestelmään käyttäjätunnuksella ja salasanalla

Voisi jakaa esimerkiksi näihin teknisiin taskeihin:

- Kirjautumislomake, jossa on tekstikentät käyttäjätunnukselle ja salasanalle
- Tietokantaulu "users", jossa sarakkeet "username" ja "password"
- HTTP API-endpoint /api/register rekisteröitymislomakkeen lähettämiselle

---

# Sprint backlog

![bg fit right:50%](./sprint-backlog.png)

- Sprint backlog organisoidaan usein taulukkomaiseksi _taskboardiksi_, jossa on yksi rivi kutakin sprinttiin valittua user storya kohti
- User storyyn liittyvät taskit kulkevat vasemmalta oikealle niiden tilaa kuvaavien sarakkeiden, kuten "not started", "in progress", "done" kautta

---

# Backlogien käyttö sprintin suunnittelussa

- Sprintin suunnittelun aikana Scrum-tiimi päivittää product backlogia tulevaa sprinttiä varten:
  - Lisää tarvittaessa uusia user storyja, tai muokkaa olemassaolevia
  - Priorisoi user storyja
- Kun product backlogin on ajantasalla, valitsee kehittäjätiimi sopivan määrän user storyja seuraava sprinttiä varten
- Valitut user storyt pilkotaan kehittäjätiimin toimesta teknisiksi taskeiksi ja taskit lisätään sprint backlogille
- Kehittäjätiimi sopii sprintin työnjaosta: kuka ottaa minkäkin taskin vastuulleen

---

# Backlogien käyttö sprintin aikana

- Sprintin aikana kehitystiimi päivittää jatkuvasti sprint backlogilla olevien taskien tilaa
  - Esimerkiksi kun jokin taski valmistuu, tulee se siirtää "done"-tilaan
- Sprint backlogin tarkoitus on siis peilataa reaaliajassa sprintin edistymistä ja edistää prosessin _läpinäkyvyyttä_
- Sprint backlogia tarkkaillaan jatkuvasti ja siitä keskustellaan kehitystiimin tapaamisissa

---

# Backlogien hallintaan soveltuvia alustoja

- Lähitöissä backlogit ovat tyypillisesti valkotaululle muodostettuja taskboardeja, joissa taskit ja user storyt ovat post-it -lappuja
- Backlogien hallintaan verkossa löytyy useita palveluita, kuten _GitHub projects_, _Jira_ ja _Trello_
- Näistä etenkin GitHub projects on saavuttanut suurta suosiota, koska se linkittyy luontevasti GitHubin versionhallintapalveluihin
- Päättäkää tiimin kesken omaan työskentelyynne parhaiten sopiva alusta. Voitte myös halutessanne kokeilla useampaa alustaa kurssin aikana