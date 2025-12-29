<p>
Oivalsin, että hyvin rakennetut Auto Layout -rakenteet tekevät komponenttien
muokkaamisesta huomattavasti joustavampaa ja säästävät aikaa myöhemmässä vaiheessa.
Samalla sain paremman käsityksen siitä, miten käyttöliittymä kannattaa pilkkoa
loogisiin osiin, jotka on mahdollista toteuttaa myös koodipuolella komponentteina.
</p>

<img src="assets/images/autolayout1.png" width="600">
<img src="assets/images/autolayout1structure.png" width="200">

<p><strong>Kuva: Esimerkki Auto Layout -rakenteesta Figma-työkalussa.</strong></p>

<p>
Rakensin komponentin jakamalla sen kahteen pääosaan: Header ja ChatScreen.
Header sisältää hakukentän ja nappien ryhmät, kun taas ChatScreen on jaettu
käyttäjälistaan ja ryhmächat-listaan. Näin rakenteet pysyvät selkeinä ja skaalautuvina.
</p>

<img src="assets/images/dashboardframe.png" width="350">

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
<img src="assets/images/choosegames1.0.png" width="200">

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

<img src="assets/images/validoinnit/defaultCreate.png" width="200">
<img src="assets/images/validoinnit/singupp.png" width="350">
<img src="assets/images/validoinnit/statustextexample.png" width="350">

<p><strong>Kuva: Esimerkki validointien status-teksteistä</strong></p>

<p>
Rakensin funktion, joka tarkistaa sähköpostin virhetilat sekä kenttien vastaavuuden.
Submit-painike aktivoituu vain, kun isFormValid on true.
</p>

<img src="assets/images/validoinnit/code1.png" width="300">
<img src="assets/images/validoinnit/code2.png" width="300">
<img src="assets/images/validoinnit/code3.png" width="300">
