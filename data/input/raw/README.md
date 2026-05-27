# `data/input/raw/`

Fuentes externas en su forma original. **No están versionadas en el repositorio** porque los términos de licencia de algunos proveedores requieren descarga directa desde el origen.

Ver [`fuentes.qmd`](../../../fuentes.qmd) para enlaces, vintage y licencia de cada archivo.

## Estructura esperada

Una vez descargados todos los archivos, esta carpeta debe verse así:

```
raw/
├── GTED_WB/
│   ├── GTED_FullDatabase_20251010.xlsx
│   ├── c_wb_incomeg.xlsx
│   └── translations.xlsx
├── ENIGH/
│   ├── GASTOS_ENIGH_HN.csv
│   └── status2024.xlsx
└── Recaudacion_Tributaria/
    ├── OECD_revenueHN.xlsx
    ├── UNUWIDERGRD_2025_Full.xlsx
    └── unu_taxRevenueToExpenditure_dic.xlsx
```

El análisis no podrá ejecutarse sin estos archivos.
