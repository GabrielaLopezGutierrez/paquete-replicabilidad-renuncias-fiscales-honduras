# Renuncias fiscales sin seguimiento

**Paquete de replicabilidad** · Análisis del gasto tributario en Honduras, 2017–2023

> ⚠️ **Propuesta interna en revisión.** Este repositorio se publica bajo el usuario personal de la autora mientras se evalúa con Sendas Think Tank el formato definitivo del paquete de replicabilidad. La versión oficial migrará al espacio institucional de la organización una vez aprobada.

[![Sitio](https://img.shields.io/badge/sitio-GitHub%20Pages-1a3a52)](https://gabrielalopezgutierrez.github.io/paquete-replicabilidad-renuncias-fiscales-honduras)
[![Licencia análisis](https://img.shields.io/badge/análisis-CC%20BY%204.0-b8341d)](https://creativecommons.org/licenses/by/4.0/)
[![Licencia código](https://img.shields.io/badge/código-MIT-1a3a52)](LICENSE)

Este repositorio contiene el código, datos y documentación que acompañan la publicación [*Renuncias fiscales sin seguimiento*](https://www.sendas.org/en/publications/renuncias-fiscales-sin-seguimiento) de Sendas Think Tank.

## 🌐 Cómo usar este paquete

**👉 La forma recomendada es visitar el sitio:** [gabrielalopezgutierrez.github.io/paquete-replicabilidad-renuncias-fiscales-honduras](https://gabrielalopezgutierrez.github.io/paquete-replicabilidad-renuncias-fiscales-honduras)

El sitio presenta cada figura con su visualización interactiva, el código que la genera y la tabla de datos que la alimenta. Desde ahí también podés descargar el notebook como `.ipynb`.

## 📦 Contenido

| Archivo | Descripción |
|---|---|
| `analisis.qmd` | Análisis completo (fuente) |
| `index.qmd` | Portada del sitio |
| `replicar.qmd` | Guía para correr el código |
| `fuentes.qmd` | Procedencia y licencias de cada fuente |
| `data/input/raw/` | Fuentes externas (descargar manualmente) |
| `data/input/auxiliary/` | Tablas puente de Sendas |
| `data/output/` | Resultados generados |
| `docs/documentacion.pdf` | Documentación metodológica |

## ⚡ Setup rápido (replicación local)

```bash
git clone https://github.com/GabrielaLopezGutierrez/paquete-replicabilidad-renuncias-fiscales-honduras.git
cd paquete-replicabilidad-renuncias-fiscales-honduras
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
# Descargar archivos raw manualmente (ver fuentes.qmd) y colocar en data/input/raw/
quarto preview
```

Requiere [Quarto](https://quarto.org/docs/get-started/) y Python 3.11+.

## 📖 Citar este paquete

> López Gutiérrez, G. (2026). *Renuncias fiscales sin seguimiento: gasto tributario en Honduras, 2017–2023* [Paquete de replicabilidad]. Sendas Think Tank.
> https://github.com/GabrielaLopezGutierrez/paquete-replicabilidad-renuncias-fiscales-honduras

## 🐛 Reportar problemas

Abrir un [issue](https://github.com/GabrielaLopezGutierrez/paquete-replicabilidad-renuncias-fiscales-honduras/issues) para errores en código, datos o documentación. Para preguntas metodológicas: [economic-team@sendas.org](mailto:economic-team@sendas.org).

## 📄 Licencias

- **Análisis y documentación** · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- **Código** · [MIT](LICENSE)
- **Fuentes externas** · ver [Fuentes y licencias](fuentes.qmd)

---

**Autora.** Gabriela López Gutiérrez · [gabriela@sendas.org](mailto:gabriela@sendas.org)
**Institución.** [Sendas Think Tank](https://www.sendas.org)
