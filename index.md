<h2>Oppimiani asioita TC:n aikana</h2>

<p>
Oivalsin, että hyvin rakennetut Auto Layout -rakenteet tekevät komponenttien
muokkaamisesta huomattavasti joustavampaa ja säästävät aikaa myöhemmässä vaiheessa.
Samalla sain paremman käsityksen siitä, miten käyttöliittymä kannattaa pilkkoa
loogisiin osiin, jotka on mahdollista toteuttaa myös koodipuolella komponentteina.
</p>

<img src="assets/images/autolayout1.png" width="500">
<img src="assets/images/autolayout1structure.png" width="100">

<p><strong>Kuva: Esimerkki Auto Layout -rakenteesta Figma-työkalussa.</strong></p>

<p>
Rakensin komponentin jakamalla sen kahteen pääosaan: Header ja ChatScreen.
Header sisältää hakukentän ja nappien ryhmät, kun taas ChatScreen on jaettu
käyttäjälistaan ja ryhmächat-listaan. Näin rakenteet pysyvät selkeinä ja skaalautuvina.
</p>

<img src="assets/images/DashFrame.png" width="350">

<p><strong>Kuva: Dashboard-näkymä, jossa Auto Layout helpottaa elementtien asemointia.</strong></p>

<hr style="border: 1px solid black; margin: 40px 0;">

<img src="assets/images/wireframeChat.png" width="400">
<p><strong>Kuva: Wireframe-vaiheen suunnitelma</strong></p>

<p>
Lähdin suunnittelemaan chat-näkymää Figma-työkalussa. Hain inspiraatiota
Dribbble-sivustolta ja tavoitteenani oli luoda mahdollisimman selkeä ja
yksinkertainen käyttöliittymä.
</p>

<img src="assets/images/chatscreen.png" width="400">
<p><strong>Kuva: Chat-näkymän jatkokehitetty versio teemaväreillä</strong></p>

<img src="assets/images/MessageFrame.png" width="500">

<p>
Chatscreen on jaettu headeriin ja viestialueeseen. Viestikuplat on rakennettu
Auto Layoutilla erillisistä osista (ikoni, teksti, aikaleima), mikä luo selkeän
hierarkian ja joustavan rakenteen.
</p>

<img src="assets/images/chatWithDashboard.png" width="500">
<p><strong>Kuva: Lopullinen chat näkymä</strong></p>
<p>Chat ruudun toteutti toinen ryhmäläinen, itselle jäi silloin pientä säätöä esim. pitkien nimien kanssa ja tyylittelyt yms.</p>
<img src="assets/images/chatWithPhone.png" width="150">

<p><strong>Kuva: Chat ruutu puhelimella</strong></p>

<img src="assets/images/chatName.png" width="350">
<p><strong>Tässä kuva pitkän nimen muokkaamisesta</strong></p>

<img src="assets/images/nimenlyhennys.png" width="175">

<img src="assets/images/exampleNames.png" width="300">

<hr style="border: 1px solid black; margin: 40px 0;">

<p>
Seuraavassa vaiheessa lähdin kääntämään Figma-mallinnuksia HTML + CSS -toteutuksiksi
Angular-sovelluksen frontendissä.
</p>

<img src="assets/images/figmaCreateprofile1.png" width="400">
<img src="assets/images/figmaCreateprofile2.png" width="300">

<p><strong>Kuva: Figma-suunnitelmat ennen koodivaihetta</strong></p>

<img src="assets/images/chooseusername1.0.png" width="200">
<img src="assets/images/birthday1.0.png" width="200">
<img src="assets/images/choosegames1.0.png" width="180">

<p>
Napit eivät vielä vastaa lopullista ulkoasua, koska ne tulevat myöhemmin
yhteisestä button-komponentista.
</p>

<img src="assets/images/username_component_html.png" width="450">
<p><strong>Kuva: HTML-toteutus “Choose your username” -modaalista</strong></p>

<hr style="border: 1px solid black; margin: 40px 0;">

<p>
Toteutin validointeja signup-, login- ja create-profile-näkymiin.
Harjoittelin erilaisten virhe- ja tilaviestien näyttämistä käyttöliittymässä.
</p>

<img src="assets/images/validoinnit/defaultCreate.png" width="180">
<img src="assets/images/validoinnit/singupp.png" width="350">
<br>
<img src="assets/images/validoinnit/statustextexample.png" width="350">

<p><strong>Kuva: Esimerkki validointien status-teksteistä</strong></p>

<p>
Rakensin funktion, joka tarkistaa sähköpostin virhetilat sekä kenttien vastaavuuden.
Submit-painike aktivoituu vain, kun isFormValid on true.
</p>

<div style="display: flex; flex-direction: column">
<img src="assets/images/validoinnit/code1.png" width="300">
<img src="assets/images/validoinnit/code2.png" width="300">
<img src="assets/images/validoinnit/code3.png" width="300">
</div>

<hr style="border: 1px solid black; margin: 40px 0;">

<h2>Liiketoiminta ja markkinointi</h2>

<p>
Projektin aikana opin soveltamaan liiketoiminnan ja markkinoinnin perusteita käytännössä.
Aloitin laatimalla Business Model Canvasin (BMC) ja Value Proposition Canvasin (VPC),
määrittäen avainresurssit, avainaktiviteetit, jakelukanavat ja asiakassuhteet meidän
palvelumme näkökulmasta.
</p>

<p>
Tärkein oppi oli ymmärtää kohderyhmien merkitys: Overall markets (kaikki pelaajat),
Potential markets (kilpailulliset PC-pelaajat) ja Target markets (pelaajat, jotka
hakivat peliseuraa taitotason, oppimisen tai yhteisön kautta). Konkreettiset
segmentit (nuoret kilpailulliset pelaajat, aloittelijat, tavoitteelliset ja sosiaalisuutta
hakevat) auttoivat hahmottamaan, miten palvelu voisi palvella erilaisia käyttäjiä.
</p>

<p>
Suunnittelin Figmassa ”kutsu kaveri” -sähköpostin simuloidun viraalikampanjan ja uutiskirjemallin,
joilla harjoittelin viestinnän ja brändin rakentamista. Vaikka materiaaleja ei vielä julkaistu,
harjoitus auttoi ymmärtämään, miten käyttäjäkokemusta voidaan tukea markkinoinnin keinoin.
</p>

<p>
Lisäksi pohdin palvelun turvallisuutta ja käyttäytymisen mittaamista sovelluksessa (esim.
toksisuusmittari), sekä tietosuojaa. Opin, että käyttäjien raportoinnit ja moderointi
tulee toteuttaa läpinäkyvästi ja neutraalisti, jotta yksilöitä ei lokeroida, vaan mittari
keskittyy käytökseen. 
</p>

<img src="assets/images/liiketoiminta/Kutsukaveri1.jpg" width="270">
<img src="assets/images/liiketoiminta/Kutsukaveri2.jpg" width="270">
<img src="assets/images/liiketoiminta/uutiskirjeeee.jpg" width="300">

<hr style="border: 1px solid black; margin: 40px 0;">

<h2>Reflektio, ja oppimisen yhteenveto</h2>

<p>
Projektin aikana suurin oppini oli siirtyminen visuaalisesta suunnittelusta
rakenteelliseen ja komponenttipohjaiseen ajatteluun. Alussa lähestyin Figmaa
lähinnä ulkoasun näkökulmasta, mutta opintojakson edetessä ymmärsin Auto Layoutin
merkityksen käyttöliittymän skaalautuvuuden ja jatkokehityksen kannalta.
</p>

<p>
Suunnittelemalla käyttöliittymän loogisina kokonaisuuksina (esim. header, chat,
modaalit) sain paremman käsityksen siitä, miten suunnitelmat siirtyvät
frontend-toteutukseen. Tämä helpotti Angular-työskentelyä ja vähensi
rakenteellisia muutoksia myöhemmässä vaiheessa.
</p>

<p>
Kaikkia suunniteltuja ominaisuuksia ei toteutettu sovelluksessa, mutta niiden
mallintaminen oli silti tärkeä osa oppimisprosessia. Opin priorisoimaan
ominaisuuksia aikataulun ja projektin tavoitteiden mukaan sekä hahmottamaan,
mitkä ideat soveltuvat paremmin jatkokehitykseen.
</p>

<hr style="border: 1px solid black;">

<h3>Toteutumattomat ideat</h3>

<img src="assets/images/eitoteutunut/Errorpage404.png" width="300">
<p><strong>Kuva: 404 error -sivun Figma-mockup</strong></p>
<p>
Suunnittelin 404 error -sivun osana kokonaisvaltaista käyttökokemusta, vaikka
ominaisuutta ei toteutettu lopulliseen sovellukseen. Harjoitus auttoi
ymmärtämään, että myös virhetilanteet ovat osa palvelun brändiä ja
käyttäjäpolkua. Toteutus jätettiin pois aikataulusyistä.
</p>

<img src="assets/images/eitoteutunut/calling.png" width="300">
<img src="assets/images/eitoteutunut/callcard.png" width="200">
<p><strong>Kuva: Voice chat -toiminnallisuuden konseptimockup. Pienempi on mallinnus eräänlaisesta "kortista", joka hoveroituisi sitten dashboardilla, kun voice-chat (puhelu) on käytössä.</strong></p>

<p>
Mallinsin myös voice chat -toiminnallisuuden, jota ei toteutettu projektin
aikana. Keskustelimme ryhmän kanssa sen mahdollisesta roolista palvelun
jatkokehityksessä. Tämä kehitti kykyäni hahmottaa tuotteen tulevaisuuden
laajennusmahdollisuuksia ja miettiä ominaisuuksia tuotantoversiota ajatellen.
</p>
