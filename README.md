# Läraren Sebastians fantastiska ting

Appar, verktyg och övningar för klassrummet.  
Tänkt att hostas via **GitHub Pages** direkt från `main`-branchen.

## Struktur

```
index.html          ← Startsidan med alla länkar
appar/
  dubbelteckning.html
  (fler appar här...)
```

## Lägga till en ny app

1. Lägg HTML-filen i `appar/`-mappen.
2. Öppna `index.html` och hitta `APPS`-arrayen (rad ~20 i scriptet).
3. Lägg till ett objekt:

```js
{
  name: "Min nya app",
  desc: "Kort beskrivning.",
  url: "appar/filnamn.html",
  icon: "🎯",
  category: "matte"   // svenska | matte | engelska | verktyg | lärare
},
```

4. Pusha till GitHub – klart.

## GitHub Pages

Settings → Pages → Source: **Deploy from a branch** → `main` / `/ (root)` → Save.

Sidan blir tillgänglig på `https://dittanvändarnamn.github.io/reponamnet/`
