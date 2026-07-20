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

## Imagens pendentes

Alguns assets ainda não estão no repositório e aparecem como placeholders na página.
Basta soltar os arquivos em `assets/` com estes nomes exatos e trocar o `<div class="shot-ph">` /
`<div class="av-ph">` correspondente por uma tag `<img>`:

| Arquivo esperado            | Onde aparece                        |
| --------------------------- | ----------------------------------- |
| `assets/afonso.jpg`         | equipe                              |

As telas do Emocre no CRT são carregadas direto de `emocre.com` e já funcionam.
