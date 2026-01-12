<div>
  <h2>Projektin tausta</h2>
  <p>
    Projektin tavoitteena oli suunnitella ja toteuttaa selainpohjainen palvelu (Synerra), joka helpottaa kilpailullisten videopelien pelaajia löytämään sopivaa peliseuraa. Palvelun ydinidea on tarjota käyttäjille mahdollisuus etsiä pelikavereita erilaisten filttereiden perusteella sekä mahdollistaa syvempi tutustuminen reaaliaikaisen chatin avulla.
  </p>
</div>

<h2>Oppimiani asioita TC:n aikana</h2>

<p>
Ymmärsin, että hyvin rakennetut Auto Layout -rakenteet tekevät komponenttien muokkaamisesta huomattavasti joustavampaa ja säästävät aikaa myöhemmässä vaiheessa. Samalla sain paremman käsityksen siitä, miten käyttöliittymä kannattaa pilkkoa loogisiin osiin.
</p>

<br>

<img src="assets/images/autolayout1.png" width="530">
<img src="assets/images/autolayout1structure.png" width="100">

<p><strong>Kuva: Esimerkki Auto Layout -rakenteesta Figma-työkalussa.</strong></p>

<p>
Rakensin komponentin jakamalla sen kahteen pääosaan: Header ja ChatScreen. Header sisältää hakukentän ja nappien ryhmät, kun taas ChatScreen on jaettu käyttäjälistaan ja ryhmächat-listaan. Näin rakenteet pysyvät selkeinä ja skaalautuvina.
</p>

<img src="assets/images/DashFrame.png" width="480">

<p><strong>Kuva: Dashboard-näkymä, jossa Auto Layout helpottaa elementtien asemointia.</strong></p>

<hr style="border: 1px solid black; margin: 40px 0;">

<img src="assets/images/wireframeChat.png" width="400">
<p><strong>Kuva: Wireframe-vaiheen suunnitelma</strong></p>

<p>
Lähdin suunnittelemaan chat-näkymää Figma-työkalussa. Hain inspiraatiota Dribbble-sivustolta ja tavoitteenani oli luoda mahdollisimman selkeä ja yksinkertainen käyttöliittymä.
</p>

<img src="assets/images/chatscreen.png" width="400">
<p><strong>Kuva: Chat-näkymän jatkokehitetty versio teemaväreillä</strong></p>

<img src="assets/images/MessageFrame.png" width="500">

<p>
Chatscreen on jaettu headeriin ja viestialueeseen. Viestikuplat on rakennettu Auto Layoutilla erillisistä osista (ikoni, teksti, aikaleima), mikä luo selkeän hierarkian ja joustavan rakenteen.
</p>

<img src="assets/images/chatWithDashboard.png" width="500">
<p><strong>Kuva: Lopullinen chat näkymä</strong></p>
<p>Chat ruudun toteutti toinen ryhmäläinen, itselle jäi silloin pientä säätöä esim. pitkien nimien kanssa ja tyylittelyt yms.</p>
<img src="assets/images/chatWithPhone.png" width="180">

<!-- <p><strong>Kuva: Chat ruutu puhelimella</strong></p> -->

<img src="assets/images/chatName.png" width="380">
<p><strong>Tässä kuva pitkän nimen muokkaamisesta</strong></p>

<img src="assets/images/nimenlyhennys.png" width="175">

<img src="assets/images/exampleNames.png" width="370">

<hr style="border: 1px solid black; margin: 40px 0;">

<h4>
Figma-mallinnusten kääntö HTML + CSS
</h4>

<img src="assets/images/figmaCreateprofile1.png" width="400">
<img src="assets/images/figmaCreateprofile2.png" width="300">

<p><strong>Kuva: Figma-suunnitelmat ennen koodivaihetta</strong></p>

<br>

<img src="assets/images/chooseusername1.0.png" width="200">
<img src="assets/images/birthday1.0.png" width="200">
<img src="assets/images/choosegames1.0.png" width="180">

<p>
Napit (buttonit) eivät vielä vastaa lopullista ulkoasua, koska ne tulivat myöhemmin yhteisestä button-komponentista.
</p>

<img src="assets/images/username_component_html.png" width="450">
<p><strong>Kuva: HTML-toteutus “Choose your username” -modaalista</strong></p>

<br>

<img src="assets/images/valmiitModals/readyModals.png" width="700">

<hr style="border: 1px solid black; margin: 40px 0;">

<h4>
Toteutin validointeja signup-, login- ja create-profile-näkymiin. Harjoittelin erilaisten virhe- ja tilaviestien näyttämistä käyttöliittymässä.
</h4>

<div>
  <img src="assets/images/validoinnit/defaultCreate.png" width="160">
  <img src="assets/images/validoinnit/singupp.png" width="370">
</div>

<div style="margin-top: 10px;">
  <img src="assets/images/validoinnit/statustextexample.png" width="370">
</div>

<p><strong>Kuva: Esimerkki validointien status-teksteistä</strong></p>

<p>
Rakensin pienen toiminnallisuuden, joka tarkistaa sähköpostin virhetilat sekä kenttien vastaavuuden. Submit-painike aktivoituu vain, kun isFormValid on true.
</p>

<div style="display: flex; flex-direction: column">
<img src="assets/images/validoinnit/code1.png" width="350">
<img src="assets/images/validoinnit/code2.png" width="450">
<img src="assets/images/validoinnit/code3.png" width="450">
</div>

<hr style="border: 1px solid black; margin: 40px 0;">

<h2>Liiketoiminta ja markkinointi</h2>

<p>
Projektin aikana opin soveltamaan liiketoiminnan ja markkinoinnin perusteita käytännössä. Aloitin tekemällä Business Model Canvasin (BMC) ja Value Proposition Canvasin (VPC), määrittäen avainresurssit, avaintoiminnot, jakelukanavat ja asiakassuhteet palvelumme näkökulmasta.
</p>

<p>
Opin ymmärtämään kohderyhmien merkityksen palvelumme kannalta: Overall markets (kaikki pelaajat), Potential markets (kilpailulliset PC-pelaajat) ja Target markets (pelaajat, jotka hakivat peliseuraa taitotason, oppimisen tai yhteisön kautta). Näitä segmenttejä määritellessä ja miettiessä hahmotin paremmin, miten palvelu voisi palvella erilaisia käyttäjiä ja heidän tarpeitaan.

<p>
Suunnittelin Figmassa ”kutsu kaveri” -sähköpostin simuloidun viraalikampanjan ja uutiskirjemallin, joilla harjoittelin viestinnän ja brändin rakentamista. Vaikka materiaaleja ei vielä julkaistu, harjoitus auttoi ymmärtämään, miten käyttäjäkokemusta voidaan tukea markkinoinnin keinoin.
</p>

<p>
Lisäksi pohdin palvelun turvallisuutta ja käyttäytymisen mittaamista sovelluksessa (esim. toksisuusmittari), sekä tietosuojaa. Opin, että käyttäjien raportoinnit ja moderointi tulee toteuttaa läpinäkyvästi ja neutraalisti, jotta yksilöitä ei lokeroida, vaan mittari keskittyy nimenomaan käytökseen. 
</p>

<img src="assets/images/liiketoiminta/Kutsukaveri1.jpg" width="270">
<img src="assets/images/liiketoiminta/Kutsukaveri2.jpg" width="270">

<hr style="border: 1px solid black; margin: 40px 0;">

<h2>Reflektio, ja oppimisen yhteenveto</h2>

<p>
Opintojakson alussa minulla oli perustaso UI/UX-suunnittelussa, graafisen sisällön tuotanto oli hieman alle perustason ja liiketoiminnan asiat hallinnassa vain alkeet. Projektin aikana suurin oppini oli siirtyminen pelkästä visuaalisesta suunnittelusta rakenteelliseen ja komponenttipohjaiseen ajatteluun.
</p>

<p>
Opintojakson edetessä opin hyödyntämään Auto Layoutia Figma-työkalussa, suunnittelemaan skaalautuvia ja komponenttipohjaisia käyttöliittymiä sekä siirtämään suunnitelmia sujuvasti frontend-toteutukseen Angularissa (vieläkin oppimista). Samalla kehitin tiimityö-, projektinhallinta- ja liiketoimintaosaamistani käytännössä.
</p>

<p>
Projektin aikana huomasin, että käyttöliittymän jakaminen loogisiin komponentteihin ei ainoastaan helpota visuaalista suunnittelua, vaan tukee myös frontend-toteutuksen muokattavuutta ja sovelluksen laatua. Kaikkia suunniteltuja ominaisuuksia ei toteutettu, mutta niiden mallintaminen opetti "priorisoimaan" päätoimintoja ja hahmottamaan mahdollisia lisäpalveluita tulevaa kehitystä tai esim. rahoittajille esitettäväksi.
</p>

<p>
Seuraavana kehitysaskeleena haluaisin panostaa markkinointimateriaaleihin ja niiden visuaaliseen laatuun osana omaa ammatillista kehittymistäni.
</p>

<hr style="border: 1px solid black;">

<h3>Toteutumattomat ideat</h3>

<img src="assets/images/eitoteutunut/Errorpage404.png" width="300">
<p><strong>Kuva: 404 error -sivun Figma-mockup</strong></p>
<p>
Suunnittelin 404 error -sivun osana käyttökokemusta, vaikka sitä ei toteutettu lopulliseen sovellukseen. Virhetilanteet ovat osa käyttäjäpolkua, mutta toteutus jätettiin pois aikataulusyistä.
</p>

<img src="assets/images/eitoteutunut/calling.png" width="300">
<img src="assets/images/eitoteutunut/callcard.png" width="200">
<p><strong>Kuva: Voice chat -toiminnallisuuden konseptimockup. Pienempi kuva näyttää yksittäisen “kortin”, joka hoveroituisi dashboardilla puhelun aikana.</strong></p>

<p>
Mallinsin voice chat -toiminnallisuuden Figmaan. Vaikka sitä toimintoa ei toteutettu, sen mallintaminen auttoi miettimään, miten palvelua voisi laajentaa tulevaisuudessa.
</p>
