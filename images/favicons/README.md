# Subbly — Favicons

Ícone da marca: quadrado arredondado, gradiente verde (#2CE98B -> #14D6C4),
"$" branco (fonte Outfit), fundo transparente.

## Arquivos
- favicon-16.png        16x16   — aba do navegador
- favicon-32.png        32x32   — aba do navegador (retina)
- apple-touch-icon.png  180x180 — iOS / atalho na tela inicial
- icon-192.png          192x192 — PWA / Android
- icon-512.png          512x512 — PWA / splash
- site.webmanifest      manifesto PWA

## Como usar (cole no <head> do site)

```html
<link rel="icon" type="image/png" sizes="32x32" href="/favicons/favicon-32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicons/favicon-16.png">
<link rel="apple-touch-icon" sizes="180x180" href="/favicons/apple-touch-icon.png">
<link rel="manifest" href="/favicons/site.webmanifest">
```

Ajuste o caminho (`/favicons/...`) conforme onde colocar a pasta no seu projeto.
