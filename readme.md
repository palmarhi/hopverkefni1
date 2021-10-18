# Sass verkefni á Netlify

`npm install` keyrt til að setja upp öll tól.

Þýddar skrár eru ekki geymdar í git, sjá `.gitignore`.

## Þróun, _development_

Keyrt með `npm run dev`. Þýðir sass yfir í css og fylgist með. Kveikir á browser-sync þjóni sem fylgist með breytingum á _þýddri_ css skrá.

## Raun, _production_

Búið er til _production build_ með `npm run build`. Þær skrár eru settar í `build/` möppu.

Við getum sett upp á t.d. Netlify með því að tengja GitHub repo við. Skilgreind `build` skipun í `package.json` verður keyrð og síðan skilgreinum við að vefur keyri úr `build/` möppu.
