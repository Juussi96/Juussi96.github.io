<h1>Oppimia asioita</h1>
<h2>Autolayout</h2>

<p>
Oivalsin, että hyvin rakennetut auto layout -rakenteet tekevät komponenttien muokkaamisesta huomattavasti joustavampaa ja säästävät paljon aikaa myöhemmässä vaiheessa. Samalla sain paremman käsityksen siitä, miten käyttöliittymä ja sen elementit kannattaa pilkkoa loogisiin osiin, jotka on mahdollista toteuttaa myös koodipuolella selkeinä komponentteina.
</p>
<img src="assets/images/autolayout1.png" width="600">
<img src="assets/images/autolayout1structure.png" width="200">

<p><strong>Kuva: Tässä esimerkkiä autolayout.</strong></p>
<p>Harjoittelin Figma Auto layoutin käyttöä rakenteen hallintaan. Rakensin komponentin jakamalla sen ensin kahteen pääosaan: Header ja ChatScreen. Näiden välissä käytin aiemmin tiimi-kaverin tekemää linebreak-elementtiä.
Headerin sisälle rakensin omat ryhmät, esimerkiksi hakukentän ja nappien osiot, jotta ne pysyvät järjestyksessä ja skaalautuvat oikein. ChatScreen puolestaan jaettiin kahteen kokonaisuuteen: käyttäjien listaan ja ryhmächat-listaan. Molempien sisällä on omat otsikot sekä toistuvat elemen-tit, kuten käyttäjäkortit.
</p>

<img src="assets/images/dashboardFrame.png" width="300">
<img src="assets/images/dashboardFrameStructure.png" width="100">
<p><strong>Kuva: Tässä dashboardframe, jossa käytin autolayouttia. Näin sain aseteltua palasia oikealle paikoilleen.</strong></p>

<hr>

<h2>Chat ruudun suunnittelu</h2>

<img src="assets/images/wireframeChat.png" width="400">
<p><strong>Kuva: Wireframe mallinnus</strong></p>
<p>Lähdin toteuttamaan figmassa chat ruutua. Hain tähän ideaa dribbble.com sivuston kautta. Halusin sen olla mahdollisimman yksin kertainen ja selkeästi rakennettu.
</p>

<img src="assets/images/chatscreen.png" width="400">
<p><strong>Kuva: Chat mallinnus 2.0 (Figma)</strong></p>
<p>Tässä olin tuonut mallinnukseen ilmettä palvelumme teemaan sopivilla väreillä, jotta saadaan siihen ilmettä</p>

<img src="assets/images/chatAutolayout.png" width="400">
<img src="assets/images/chatAutolayoutStructure.png" width="400">
<p><strong>Kuva: Mallinnusta autolayoutin kanssa, saadaakseen selkeän "hierarkian"</strong></p>

<p>Kokonaisuus on jaettu headeriin ja chatscreeniin. Chatscreen sisältää viestikuplat (incoming ja outgoing), joissa jokainen kupla on rakennettu erillisistä osista, kuten käyttäjä-ikonista, tekstistä ja aikaleimasta. Näin Auto layout pitää rakenteen selkeänä ja joustavana</p>

<hr>

<h2>Mallinnuksien kääntäminen angularin puolelle (frontend)</h2>

<img src="assets/images/figmaCreateprofile1.png" width="300">
<img src="assets/images/figmaCreateprofile2.png" width="300">

<p><strong>Ylempänä kuvat figma suunnitelmista, joita lähdin kääntämään sitten HTML + CSS.</strong></p>

<img src="assets/images/chooseusername1.0.png" width="200">
<img src="assets/images/birthday1.0.png" width="200">
<img src="assets/images/choosegames1.0.png" width="200">

<p><strong>Kuvat ”valmiista” koodista. Napit ei vielä olen oikean mallisia, kun ne tulevat sitten "yhteisestä” button-komponentista.</strong></p>

<img src="assets/images/username_component_html.png" width="200">

<p><strong>Kuva lopullisesta html koodista</strong></p>

<img src="assets/images/profilecreation1.png" width="200">
<img src="assets/images/profilecreation2.png" width="200">
<img src="assets/images/profilecreation3.png" width="200">

<p><strong>Kuvat: Lopullisesta näkymästä</strong></p>

<p>Modali-ikkunoiden jälkeen lähdin rakentamaan "Create profile" pääsivustoa. Lähdin toteuttamaan tätä toisen ryhmäläiseni aiemmin luomansa "Login" sivuston mukaan.</p>

<img src="assets/images/loginScreen.png" width="350">

<p><strong>Kuva: Login näkymä</strong></p>

<img src="assets/images/profilecreationMain.png" width="350">
<img src="assets/images/profilecreationMain2.png" width="350">

<p>Pienemmällä näyttökoolla vaihtuu järjestys!
Alla css säädöt!</p>

<img src="assets/images/cssprofilecreation1.png" width="350">
<img src="assets/images/cssprofilecreation2.png" width="350">

<hr>

<h2>Validointeja: sing up sivustolle ja profiilin luonnissa</h2>

<p>Tein signup-, login-email-sivustoille ja create-profile modaaleihin validointeja. Harjoittelin erilaisia validointimalleja ( https://dribbble.com/shots/20340740-Sign-up-Forms-Users-need-to-know-password-requirements ) ja niiden näyttämistä käyttöliittymässä (esim. virheilmoitukset ja varoitukset). </p>

<img src="assets/images/validoinnit/singup1.png" width="350">
<img src="assets/images/validoinnit/singup2.png" width="350">
<img src="assets/images/validoinnit/exampleStatustext.png" width="350">
<p><strong>Kuva: Esimerkki yhdestä status tekstistä</strong></p>

<p>Rakensin lisäksi funktion, joka tarkistaa sähköpostin virhetilat (esim. sisältääkö ison kirjaimen, numeron ja vähintään kuusi merkkiä) sekä sen, että sähköpostikentät vastaavat toisiaan, jolloin Submit-painike aktivoituu vain validissa tilassa. (eli formValid on true tilassa, jolloin voidaan jatkaa)</p>

<img src="assets/images/validoinnit/code1.png" width="250">
<img src="assets/images/validoinnit/code2.png" width="250">
<img src="assets/images/validoinnit/code3.png" width="250">
