# psicologiatech.github.io

Site principal da conta PsicologiaTech no GitHub Pages.

- `index.html` leva para o [Giro a Giro](https://psicologiatech.github.io/giro-a-giro/).
- `.well-known/assetlinks.json` prova à Google que o app Android do Giro a Giro e este site são da mesma dona. Recebe a impressão digital (SHA-256) da chave de assinatura do app quando ele for enviado ao Google Play.
- `.nojekyll` faz o GitHub Pages publicar a pasta `.well-known` (sem ele, pastas que começam com ponto ficam de fora).
