---
tags: [ 'Hydrauliikka' ]
header_img: /assets/img/ruorikeskio.jpg
---

## Ruorin kiinnityslaipan muokkaus

Keskeinen komponentti veneen hallintalaitteista on luonnollisestikin ruori, jolla aluksen peräsintä käännetään. Ruori pyörittää hydrauliohjauksen ruoripumppua ohjaten painetta työsylinterin eri päihin. Kun uudistamme koko hydraulijärjestelmän etenkin ohjauksen osalta, myös vanha ruoripumppu sai väistyä uuden orbitrolin tieltä. Orbitroli on traktoreista ja offroad-autoista tuttu komponentti, joka siis ohjaa P-linjan kautta tulevan syöttöpaineen A- tai B-linjaan tasaisesti sen akselia kierrettäessä. Nämä A- ja B-linjat taas yhdistyvät peräsimen työsylinterin kumpaankin päähän, eli kun A-linjaan ohjataan painetta, saa se sylinterissä aikaan työliikkeen ja B-linjasta palautuu poistuva öljy, kun mäntä painaa öljyn takaisin letkuun/putkeen. Lisää hydraulijärjestelmästä on tämän blogin artikkelissa “Hydraulijärjestelmän suunnittelu”.

Uuden orbitrolin myötä myös ruorin ohjausakseli tuli uutena komponenttina asennukseen. Akseli kiinnittyy ruorin keskiöön kiinni 1:20 kartioakselilla, joten tämän aktiviteetin aiheena olikin ruorin keskiölaipan kartioreiän avartaminen, sillä vanha akseli oli selkeästi pienempi. Onneksemme laippa on alumiinia, jota on varsin helppo työstää myös kotikonstein. Ensiksi koitimme viilata ja hioa reikää suuremmaksi, mutta homma vaikutti melko toivottomalta. Toiseksi onneksemme olin joitain vuosia sitten tullut hankkineeksi ex-työkaverin kanssa yhdessä pienen pöytämallisen CNC-koneen, jolle tuli nyt sopivasti käyttöä. Laite on kiinalaiseksi suht tarkka ja liikeradoiltaan toistokykyinen.

![ruorikeskio.jpg](/assets/img/ruorikeskio.jpg)

Tuttuun tapaan aloitin homman mittailulla ja suunnittelulla SketchUpissa, jonka jälkeen siirryin CamBam-nimisen ohjelman pariin. CamBam on CAD/CAM-suunnitteluohjelma, josta työn saa ulostettua G-koodiksi. Kartion mallista reikää varten löytyi onneksi sopiva plugari, joten ihan funktiotasolle ei onneksi suunnittelutyötä tarvinnut jalostaa. G-koodi taas tuodaan LinuxCNC-sovellukseen, joka ohjaa itse laitetta rinnakkaisportin kautta. Ylläoleva kuva on itse asiassa hieman harhaanjohtava, sillä laippa on tarkkaanottaen toisin päin, eli kartio tulee laipan selkäpuolelle. Karaura tehtiin toisella koodilla samoja menetelmiä käyttäen. Mittauksissa päätin jättää koneistettavan reiän hieman tiukaksi, sillä materiaalia on helpompi poistaa kuin lisätä.

Hommassa päästiin vihdoin tiistaina 13.6.2017 eteenpäin ja itse koneistustyöhön. Reikää varten valittiin pallopäinen työkalu, jotta reiän sisäpinnasta tulisi mahdollisimman tasainen. Karauraa varten valitsimme työkaluksi 1-kierteisen terän joka lastuaa alumiinia huomattavasti tehokkaammin kuin tuo pallopäinen terä. Tässä kohtaa olisi hyvä myös mainita disclaimerina, että omat koneistustaitomme ovat täysin Youtube-oppien sekä kokemusten varassa. Pähkäiltyämme hetken terän etenemis- ja pyörimisnopeuksia yms muuttujia, pääsimme vihdoin käynnistämään koneet. Toki pari protoreikää tehtiin ensin puukappaleeseen.

![FullSizeRender_2.jpg](/assets/img/FullSizeRender_2.jpg)

Villen diy-verstas, mancave. Kuvassa oikealla alhaalla näkyykin myös uusi ruoriakseli ja koneen etualalla puuhun tehdyt koeistukset. Työkalu on kohdistettu kappaleen keskipisteeseen ja kone on valmiina työhön.

![IMG_4031.JPG](/assets/img/IMG_4031.JPG)

Terä on siis varsin pieni, halkaisijaltaan 1/8” eli 3,175mm. Kappale on kiinnitetty MDF-pohjalevyyn yksinkertaisesti puuruuveilla.

![IMG_4033.JPG](/assets/img/IMG_4033.JPG)

![IMG_4034.JPG](/assets/img/IMG_4034.JPG)

Lopputulos on melko halutunlainen, joskin reikä on erittäin tyköistuva joten käsityökaluhommia on vielä hiukan. Mikäli reiästä olisi tehnyt liian suuren, ei kartiokiristys toimi lainkaan, joten mittaustarkkuus on valttia tässä tehtävässä. Lopputulosta arvioidessamme totesimme, että reikää varten olisi ollut hyvä ajaa sama reitti toiseen kertaan viimeistelyksi, sillä terä sekä itse kone antoivat tuolla syöttönopeudella sen verran periksi (millin kymmenyksiä), ettei leikkuusta tullut aivan täydellistä. Onneksi homma hoituu varsin helposti Dremelin hiontatyökalulla.
