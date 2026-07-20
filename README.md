# CriaPixel

Site institucional da **CriaPixel** — estúdio independente brasileiro de desenvolvimento de games, tradução e adaptação, e ROM hacking.

Site estático, sem build step. Publicado via GitHub Pages a partir da branch `main`.

## Estrutura

```
index.html              página única
assets/logo-paisagem.svg   logo (pixel art, SVG)
assets/favicon.svg         ícone da aba
```

## Rodando localmente

```sh
python3 -m http.server 8000
# abra http://localhost:8000
```

## Imagens

Todos os assets estão no repositório, exceto as telas do Emocre exibidas na TV de tubo,
que são carregadas direto de `emocre.com`.

- `shot-*.png` — capturas de emulador dos jogos traduzidos. São PNG (lossless) porque
  são pixel art; a página aplica `image-rendering: pixelated` para escalar sem borrar.
- Fotos de pessoas — JPEG 360×360, recorte quadrado centralizado.
