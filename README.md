# DR Music & Events

Sito vetrina e contatti per Riccardo Zenga e Davide Rizzi.

Sito pubblico: https://dr-music-events-contatti.alessandro-calabro.chatgpt.site/

## Struttura

- `dist/index.html`: pagina statica responsive.
- `dist/assets/`: fotografie, poster e video desktop.
- `dist/assets/hls/`: video mobile in formato HLS, senza audio.
- `.openai/hosting.json`: configurazione di pubblicazione su Sites.

Per vedere il sito in locale:

```sh
python -m http.server 8000 --directory dist
```

Poi aprire `http://localhost:8000`. Su iPhone Safari riproduce il flusso HLS; se il risparmio energetico blocca l'avvio automatico, usare **Riproduci video**.
