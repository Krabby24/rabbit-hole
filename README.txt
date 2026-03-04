# 🕳️ Rabbit Hole

> *Un sito web che non è quello che sembra.*

---

## Cos'è

**Rabbit Hole** è un esperimento di design interattivo costruito come un singolo file HTML.

Si apre come una pagina qualunque — testo nero, sfondo bianco, font da sito anni '90. Una riga sola. Niente di speciale.

Ma c'è qualcosa di nascosto.

Cliccandolo, si apre una voragine: un wormhole animato che risucchia lo schermo e conduce a un secondo layer — più oscuro, più dinamico, più vivo. E poi un terzo. E un quarto. Ogni strato è esteticamente distinto dal precedente: dal cyberpunk al glitch, dal cosmo psichedelico all'horror digitale.

In tutto ci sono **8 layer**, ognuno con un hotspot invisibile da scovare. Nessun indizio ovvio. Solo la curiosità come guida.

---

## Struttura
```
rabbit-hole/
└── index.html
```

Zero dipendenze. Zero librerie esterne. Zero cartelle esposte.  
Tutto il codice — HTML, CSS, JavaScript, animazioni canvas — vive in un unico file.

---

## I Layer

| # | Atmosfera | Tecnica |
|---|-----------|---------|
| 1 | Anni '90 — semplicissimo, quasi vuoto | HTML puro |
| 2 | Cyberpunk — griglia animata, testo al neon | Canvas 2D |
| 3 | Glitch — distorsione visiva, rumore rosso | CSS animation |
| 4 | Cosmico — stelle pulsanti, viola profondo | Canvas 2D |
| 5 | Psichedelico — anelli di colore in rotazione | Canvas 2D |
| 6 | Matrix — pioggia di codice, terminale | Canvas 2D |
| 7 | Horror — flickering, rosso sangue | CSS animation |
| 8 | Silenzio — ritorno al bianco | HTML puro |

---

## La transizione

Ogni hotspot trovato attiva un **wormhole**: un'animazione canvas generativa con anelli concentrici in rotazione, raggi radiali e un flash centrale. Dura ~2 secondi, poi il layer successivo appare.

---

## Come funziona

Gli hotspot sono `div` assolutamente posizionati, invisibili, senza bordi né highlight visivi.  
L'unico segnale è un cambio del cursore in `crosshair` al passaggio — sottile, intenzionale.

Non c'è mappa. Non c'è timer. Non c'è punteggio.  
C'è solo il prossimo buco.

---

## Deploy

Hostato su **GitHub Pages** — nessun server, nessun backend, nessuna configurazione.
```
https://[username].github.io/rabbit-hole/
```

---

## Tecnologie

- HTML5
- CSS3 (animazioni, gradienti, keyframes)
- JavaScript vanilla
- Canvas API (animazioni generative)

---

*Buona fortuna.*
```

Salvalo come `README.md` nella stessa cartella di `index.html`. La struttura finale su GitHub sarà:
```
rabbit-hole/
├── index.html
└── README.md