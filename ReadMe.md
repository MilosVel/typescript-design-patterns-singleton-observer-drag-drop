 <script type="module" src="dist/app.js"></script> // nema defer?

u tsconfig.json:

1. outfile se mora zakomentarisati (outfile se mora koristikoristiti kada se upotrebljava namespace -> "outfile":"./dist/bundle.js")
2. "target": "es6"
3. "module": "es2015"

u tsconfig.json:

1. "experimentalDecorators": true -> da bi se koristili dekoratori,
2. "noUnusedParameters": true /_ Report errors on unused parameters. _/,
3. Da li ce se u browseru u consoli prikazivati js ili ts ispisivanje zavisi od: "sourceMap": true
