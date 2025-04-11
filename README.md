# MongoDB-Redis
Nereliacinių duomenų bazių užduotis – „Maisto užsakymų platforma“, realizuota naudojant Python Flask, MongoDB ir Redis. <br />
Platforma skirta restoranų, klientų ir jų užsakymų valdymui. <br />
MongoDB naudojama duomenų saugojimui, o Redis – spartesnei rekomendacijų paieškai ir laikinam kešavimui.

### Funkcionalumas:
- Restoranų registravimas: pavadinimas, darbo laikas, adresas, meniu.
- Meniu valdymas: galima pridėti patiekalus su jų pavadinimu, aprašymu, kaina ir paveikslėliu.
- Klientu registracija: vardas, pavardė, telefono numeris.
- Užsakymų pateikimas: klientas pasirenka patiekalus iš meniu, nurodo kiekius, atsiėmimo būdą (pickup/delivery), jei pasirenkama 'delivery', nurodomas pristatymo adresas.
- Užsakymų peržiūra: rodomas pateikalų sąrašas, bendra kaina, pristatymo būdas bei pristatymo adresas (jei yra).
- Rekomendacijos: <br />
&nbsp;&nbsp;&nbsp;&nbsp; - Pasiūlomi trys populiariausi kliento patiekalai. <br />
&nbsp;&nbsp;&nbsp;&nbsp; - Galimybė greitai užsisakyti paskutinį užsakymą dar kartą.
