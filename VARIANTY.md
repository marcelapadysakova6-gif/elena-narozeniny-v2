# Dvě varianty webu

| Varianta | Složka | Podklad |
|----------|--------|---------|
| **Světlá (růžová)** | `elena-narozeniny-v2/` | pastelový gradient |
| **Tmavá** | `elena-narozeniny-v2-dark/` | fialovo‑purpurový, jako dřív |

- **Světlá (produkce):** [elena-narozeniny-v2.vercel.app](https://elena-narozeniny-v2.vercel.app)  
- **Tmavá (produkce):** [elena-narozeniny-v2-dark.vercel.app](https://elena-narozeniny-v2-dark.vercel.app)

Další deploy tmavé: ve složce `elena-narozeniny-v2-dark` spusť `npx vercel deploy --prod --yes`.

### iPhone / iPad (Safari)

Obě varianty mají `viewport-fit=cover`, safe area pro výřezy, `100svh`/`100dvh`, Retina canvas (`devicePixelRatio`), `visualViewport` při skrývání lišty a větší tečky navigace na dotyku.
