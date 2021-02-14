# Ajoneuvodata
Avoin ajoneuvodata

Näitä autoja Suomi rekisteröi 2019-2021

Mitkä ovat suosituimmat mallit ja merkit ensirekisteröinneissä vuodesta 2019 alkaen helmikuuhun 2021 saakka? Mitkä ovat suosituimmat värit suosituimmilla merkeillä? Mitkä olivat suosituimmat käyttövoimat ja vaihteistot? Minkä merkin mallistossa on eniten sähköhybridejä? Mitkä ovat keskimääräiset päästöt sähköhybrideillä? Ja miten paljon päästöt ovat keskimäärin vähentyneet 1990-luvun puolivälistä alkaen?

Näihin kysymyksiin hain vastauksia, kun kävin läpi ajoneuvojen avointa datan 5.13 aineistoa Traficomin sivuilta. Ajoneuvojen avoin data sisältää kaikkien liikennekäytössä olevien ajoneuvojen rekisteröinti-, hyväksyntä- ja teknisiä tietoja Traficomin ylläpitämästä liikenneasioiden rekisteristä.

Aineisto löytyy osoitteesta: https://www.traficom.fi/fi/ajankohtaista/avoin-data

Aineistossa oli rivejä yhteensä 5 121 148 kpl ja se oli julkaistu 3.2.2021. Aineistosta poimin datan vain henkilöautoista (ajoneuvoluokat M1 ja M1G) ja rajasin sitä vielä vuoden 2019 alusta lähtien ensirekisteröityihin. Aineistoa käsittelin Pythonilla. Artikkelin lopussa on linkki Python-koodiin.

Mitkä ovat suosituimmat merkit? Kärjessä keikkuvat Toyota, Volvo ja Mercedez-Benz.

Mitkä ovat taas suosituimmat mallit? Kärkikolmikon muodostavat Nissanin, Toyotan ja Skodan mallit.

Mitkä ovat suosituimmat värit ensirekisteröinnissä? Suosituimmat värit suosituimmilla merkeillä vaihtelivat. Harmaa oli suosituin väri Skodalla ja Suzukilla. Mustaa suosivat eniten Audi-, BMW-, Mercedes-Benz- ja Volvo-kuskit. Punaisesta tykkäsivät eniten Mazdalla ajavat. Valkoinen oli suosituin usealla merkillä.

Mitkä ovat suosituimmat käyttövoimat? Huhut polttomoottorin kuolemasta näyttävät olevan vahvasti liioiteltuja. Bensiini on vahvasti paalupaikalla ja diesel on kakkosena. Kaksi sadasta ensirekisteröinnistä tehtiin sähköteknologialla.

Mitkä ovat suosituimmat vaihteistot? Kaksi kolmesta valitsi automaatin.

Kiinnostavaa oli tietää myös, minkä merkin mallistossa on eniten sähköhybridejä? Kärjessä ovat Toyota, Mitsubishi ja Volvo. Ensirekisteröityjen sähköhybridien hiilidioksidipäästöt ovat keskimäärin noin 98 grammaa.

Autojen polttomoottoriteknologian kehittyminen näkyy vahvasti hiilidioksidipäästöjen kehityksessä. Päästöt ovat vähentyneet rajusti 1990-luvun puolivälistä alkaen. Vielä 1990-luvun puolivälissä päästöt olivat noin 220, kun nyt ne ovat keskimäärin noin 130.

Kuvaus koodista on nähtävissä github-profiilissani: https://github.com/markok20/Ajoneuvodata
