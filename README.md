# 🇨🇱 Chile — Consumer Food Price Analysis (ODEPA)

Analysis of consumer food prices from [ODEPA](https://www.odepa.gob.cl/) (Oficina de Estudios y Políticas Agrarias), Chile's agricultural policy office.

## What's Inside

The notebook `analisis_precios_chile.ipynb` covers:

1. **Data overview** — records by product group and region
2. **Weekly price trends** — 10 key fruits & vegetables tracked week by week
3. **Regional comparison** — price differences across Chile's regions
4. **Price volatility** — min/max spread analysis per product
5. **Heatmap** — region × product average price matrix
6. **Summary statistics** — consolidated table

## Data

Source file: `precio_consumidor_publico_2026.csv` from ODEPA's public portal.

- **Period:** January – March 2026
- **Scope:** 9 regions, ~230 products (fruits, vegetables, dairy, meats, staples)
- **Granularity:** weekly prices by monitoring point

## Setup

```bash
pip install -r requirements.txt
```

Open `analisis_precios_chile.ipynb` in VSCode (or Jupyter) and run all cells.

> The CSV must be in the same folder as the notebook.

## Products Analyzed

| Spanish | English |
|---|---|
| Palta | Avocado |
| Tomate | Tomato |
| Limón | Lemon |
| Plátano | Banana |
| Manzana | Apple |
| Lechuga | Lettuce |
| Cebolla | Onion |
| Papa | Potato |
| Zanahoria | Carrot |
| Naranja | Orange |
