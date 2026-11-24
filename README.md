# Harmonia · Treinamento Musical

Site estático para estudo de harmonia no **teclado** e no **violão**.

- Piano de 3 oitavas (Dó3–Dó6) e braço de violão com 15 casas
- Identificação automática de acordes (cifra, nome em português, inversão, intervalos e escalas)
- Posições de violão geradas automaticamente para qualquer acorde
- Transposição (½ tom, oitava ou para um tom escolhido)
- Tocar junto, rasgueado ou arpejado, com samples reais de piano e violão
- Banco de acordes salvos, sequência com BPM, andamento, compasso, ritmos, metrônomo e loop

Feito com [Tonal.js](https://github.com/tonaljs/tonal) (teoria musical) e [Tone.js](https://tonejs.github.io/) (áudio).

## Rodar localmente

```bash
npx http-server -p 5173
```

## Publicar

É um único `index.html`, sem build: na Vercel, importe o repositório e use o preset **Other** (sem comando de build).
