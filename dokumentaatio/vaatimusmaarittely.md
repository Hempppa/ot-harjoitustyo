# Vaatimusmäärittely

## Sovelluksen tarkoitus

 Klassinen miinaharava peli. Pelissä on yksi vakio vaikeustaso (esim. 16x16 ruudukko ja 40 miinaa).

## Perusversion tarjoama toiminnallisuus

### Alkunäkymä

 - Tämä näkymä avautuu pelin käynnistyttyä
 - Perustoteutuksessa täältä voi vain siirtyä pelaamaan peliä

### Pelin aloitus/valikko

 - Alussa on vain yksi vaikeustaso, joten peli alkaa suoraan 
 - Peliä pelataan tavallisen miinaharavan tyyliin:
   - Pelin tavoite on avata kaikki miinattomat ruudut
   - Jos avataan miinan sisältävä ruutu, peli päättyy
   - Kukin avattu miinaton ruutu kertoo numerolla montako miinaa sen viereisistä ruuduista (1-8kpl) löytyy
   - Epäiltyjä miinoja voi liputtaa, joka helpottaa miinojen seuraamista
     - Liputettua ruutua ei voida avata, lipun voi myös poistaa

## Jatkokehitysideoita

 Tässä vaiheessa nämä ovat ominaisuuksia, jotka on tarkoitus lisätä perustoiminnallisuuden jälkeen. 

### Tulostaulu

 - Tietokanta, johon tallennettaisiin peliin kestänyt aika
   - Vain voitettujen pelien ajat tallennetaan
 - Vanhojen arcade pelikoneiden tyyliin, pelin jälkeen käyttäjä antaa nimen joka ilmestyy ajan vierelle
 - Tulostaulua pääsee tarkastelemaan jokaisen pelin jälkeen ja alkunäkymästä
   - Pelin jälkeen kerrotaan myös käyttäjän sija listalla

### Muita vaikeustasoja

 - Muita "Pre-settejä" eli valmiiksi valittuja vaikeuksia
   - Eli vaihtelua miinojen määrään ja kentän kokoon
   - Nämä voi myös tallentaa tulostauluun, joista jokainen vaikeustaso tallennetaan erikseen

 - Oma "Custom" pelimuoto
   - Käyttäjä saa itse syöttää sekä kentän koon, että miinojen määrän
   - "Pelattavuus" käyttäjän omalla vastuulla, eli mahdollisuus esim. täyttää koko kenttä miinoilla
   - Kuitenkin jokin yläraja vaikka 1000x1000 ja alaraja 1x1
   - Eri vaihtoehtojen lukumäärän takia tulostaulun käyttö ei ole järkevää