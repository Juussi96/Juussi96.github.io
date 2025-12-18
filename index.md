<p>Suurimman osan viikosta käytin Figmaan perehtymiseen, erityisesti Auto layout -toimintoon. Har-joittelin sen käyttöä rakentamalla chat-sovelluksen näkymää. Opin, miten auto layout helpottaa elementtien asemointia, skaalautumista ja myöhempää siirtoa koodiin, esimerkiksi kun käyttöliit-tymä toteutetaan Angular-sovelluksessa.
Oivalsin, että hyvin rakennetut auto layout -rakenteet tekevät komponenttien muokkaamisesta huomattavasti joustavampaa ja säästävät paljon aikaa myöhemmässä vaiheessa. Samalla sain paremman käsityksen siitä, miten käyttöliittymä ja sen elementit kannattaa pilkkoa loogisiin osiin, jotka on mahdollista toteuttaa myös koodipuolella selkeinä komponentteina.
<p>
<img src="assets/images/autolayout1.png" width="600">
<img src="assets/images/autolayout1structure.png" width="400">

<p>Tässä esimerkkiä. Figma Auto layoutin käyttöä rakenteen hallintaan. Rakensin komponentin ja-kamalla sen ensin kahteen pääosaan: Header ja ChatScreen. Näiden välissä käytin aiemmin tiimi-kaverin tekemää linebreak-elementtiä.
Headerin sisälle rakensin omat ryhmät, esimerkiksi hakukentän ja nappien osiot, jotta ne pysyvät järjestyksessä ja skaalautuvat oikein. ChatScreen puolestaan jaettiin kahteen kokonaisuuteen: käyttäjien listaan ja ryhmächat-listaan. Molempien sisällä on omat otsikot sekä toistuvat elemen-tit, kuten käyttäjäkortit.
<p>
