## :mortar_board: I used this as an assignment for students learning about Open Data. This is an example of completed exercise.
![Kuvakaappaus](https://www.tavastiasoft.fi/wp-content/uploads/2020/12/junat-kartalla.png)
# Junien sijainnin näyttäminen kartalla
Tässä harjoituksessa opit miten avoimesti saatavalla olevaa sijaintidataa voidaan suhteellisen yksinkertaisesti esittää graafisessa muodossa kartalle sijoitettuna.

Käytämme harjoituksessa rautatieliikenteen avointa dataa, jota saamme liikenne- ja viestintäviraston [Digitraffic](https://www.digitraffic.fi/) APIsta. Datan esittämiseen käytämme [Leaflet.js](https://leafletjs.com/) -kirjastoa ja [OpenStreetMap](https://www.openstreetmap.org)-karttapalvelua.

Oheisessa kartta.html -tiedostossa on valmiina jo kartan luova osa koodia. Siihen tarvitsee siis vielä toteuttaa ohjelmakoodi, joka hakee junien tiedot rajapinnasta ja sijoittaa ne kartalle näkyviin.
