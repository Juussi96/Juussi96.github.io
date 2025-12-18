<h1>Oppimia asioita</h1>
<h2>Autolayout</h2>

<p>Suurimman osan viikosta käytin Figmaan perehtymiseen, erityisesti Auto layout -toimintoon. Harjoittelin sen käyttöä rakentamalla chat-sovelluksen näkymää. Opin, miten auto layout helpottaa elementtien asemointia, skaalautumista ja myöhempää siirtoa koodiin, esimerkiksi kun käyttöliittymä toteutetaan Angular-sovelluksessa.
Oivalsin, että hyvin rakennetut auto layout -rakenteet tekevät komponenttien muokkaamisesta huomattavasti joustavampaa ja säästävät paljon aikaa myöhemmässä vaiheessa. Samalla sain paremman käsityksen siitä, miten käyttöliittymä ja sen elementit kannattaa pilkkoa loogisiin osiin, jotka on mahdollista toteuttaa myös koodipuolella selkeinä komponentteina.
</p>
<img src="assets/images/autolayout1.png" width="600">
<img src="assets/images/autolayout1structure.png" width="200">

<p><strong>Tässä esimerkkiä.</strong></p>
<p>Harjoittelin Figma Auto layoutin käyttöä rakenteen hallintaan. Rakensin komponentin jakamalla sen ensin kahteen pääosaan: Header ja ChatScreen. Näiden välissä käytin aiemmin tiimi-kaverin tekemää linebreak-elementtiä.
Headerin sisälle rakensin omat ryhmät, esimerkiksi hakukentän ja nappien osiot, jotta ne pysyvät järjestyksessä ja skaalautuvat oikein. ChatScreen puolestaan jaettiin kahteen kokonaisuuteen: käyttäjien listaan ja ryhmächat-listaan. Molempien sisällä on omat otsikot sekä toistuvat elemen-tit, kuten käyttäjäkortit.
</p>

<img src="assets/images/dashboardFrame.png" width="400">
<img src="assets/images/dashboardFrameStructure.png.png" width="400">
<p><strong>Tässä dashboardin ”framesta” kuvankaappauksia, jossa käytin autolayouttia asettumaan palaset oikeille paikoille.</strong></p>

<hr>

<h2>Chat ruudun suunnittelu</h2>

<img src="assets/images/wireframeChat.png" width="400">
<p><strong>Wireframe mallinnus</strong></p>
<p>Lähdin toteuttamaan figmassa chat ruutua. Hain tähän ideaa dribbble.com sivuston kautta. Halusin sen olla mahdollisimman yksin kertainen ja selkeästi rakennettu.
</p>

<img src="assets/images/chatscreen.png" width="400">
<p><strong>Chat mallinnus 2.0 (Figma)</strong></p>
<p>Tässä olin tuonut palvelumme teemaan sopivilla väreillä siihen hiukan ilmettä</p>

<img src="assets/images/chatAutolayout.png" width="400">
<img src="assets/images/chatAutolayoutStructure.png" width="400">
<p><strong>Mallinnusta autolayoutin kanssa, saadaakseen selkeän "hierarkian"</strong>

<p>Kokonaisuus on jaettu headeriin ja chatscreeniin. Chatscreen sisältää viestikuplat (incoming ja outgoing), joissa jokainen kupla on rakennettu erillisistä osista, kuten käyttäjä-ikonista, tekstistä ja aikaleimasta. Näin Auto layout pitää rakenteen selkeänä ja joustavana</p>

<hr>
