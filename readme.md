# Hópverkefni 1


|   | Mikael Andri Ingason |Pálmar Sæmundsson |Sigurður Örn Gunnarsson |
| ------------- |:-------------:|:-------------:|:-------------:|
| HÍ     | mai24    |pas4     |sog6     |
| GitHub     |  MikaelAndriIngason    |palmarhi    |sog6    |



## Sass verkefni á Netlify

Verkefnið felst í því að smíða vef eftir forskrift.

## Keyrsla

Til að keyra verkefni þarf Node.js og npm að vera uppsett á tölvunni. 

Verkefnið er keyrt með `npm run dev`. Skipunin setur í af stað fersli sem þýðir sass yfir í css og fylgist með. Kveikir á browser-sync þjóni sem fylgist með breytingum á _þýddri_ css skrá.

Með `npm run lint` er stylelint keyra á Sass

## Raun

Búið er til _production build_ Með `npm run build` er búið til _production build_. Við það keyrist skilgreind `build` skipun í `package.json` Þær skrár eru settar í `build/` möppu sem vefur keyrir úr.

Það er búið að tengja GtHub við Netlify og Netlify með því að tengja GitHub repo við. Skilgreind `build` skipun í `package.json` verður keyrð og síðan skilgreinum við að vefur keyri úr `build/` möppu.

## Skipulag

Verkefninu er skipt þannig upp í möppur að allar html skrár eru í rót. CSS/Sass skrár eru í `styles` möppu nema styles.scss sem er í rót. Í styles möppunni eru scss skrár fyrir hverja síðu en þar eru einnig scss skrár fyrir sameiginlega hluti eins og _header, footer, navigation og products_.

Myndir eru geymdar í `images` möppu og öll icon sem notuð eru á vefsíðum eru í `icons` möppu.
