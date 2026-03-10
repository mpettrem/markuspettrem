# markuspettrem.no

Personlig designportefølje for Markus Rosenvinge Pettrém.

## Struktur

```
markuspettrem/
├── index.html       # Hele siden (én fil)
└── images/          # Legg bilder her
    ├── ngir.jpg
    ├── adv-rtm.jpg
    ├── styringsportal.jpg
    ├── isfit.jpg
    └── portrett.jpg
```

## Legge til bilder

1. Legg bildefilen i `images/`-mappen
2. Åpne `index.html` i en teksteditor
3. Finn f.eks.:
   ```html
   <div class="card-img-ph">Legg til bilde</div>
   ```
4. Bytt ut med:
   ```html
   <img class="card-img" src="images/ngir.jpg" alt="NGIR prosjekt">
   ```

## Publisering

Siden er koblet til Netlify og publiseres automatisk når du pusher endringer til `main`-branchen.

## Lokal forhåndsvisning

Åpne `index.html` direkte i nettleseren, eller bruk en enkel server:

```bash
npx serve .
```
