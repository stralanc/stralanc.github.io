# stralanc.github.io

Questo repository serve **solo** a reindirizzare `https://stralanc.github.io/*` verso `https://stralanc.com/*`.

GitHub Pages è attivo con il dominio personalizzato `stralanc.com` (file `CNAME`): per ogni indirizzo
`stralanc.github.io/...` GitHub risponde con un redirect 301 allo stesso percorso su `stralanc.com`.
Così continuano a funzionare i vecchi link (schede Google Play, app, segnalibri, risultati di ricerca).

Il sito vero e proprio non è qui: sta su https://stralanc.com.

- Non rimuovere `CNAME` e non disattivare GitHub Pages, altrimenti `stralanc.github.io` va in 404.
- Il warning "DNS check unsuccessful" nelle impostazioni di Pages è atteso: il DNS di `stralanc.com` punta a Cloudflare.
