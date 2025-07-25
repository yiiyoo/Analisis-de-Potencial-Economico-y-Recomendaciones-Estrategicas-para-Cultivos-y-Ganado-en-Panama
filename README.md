# Análisis de Potencial Económico y Recomendaciones Estratégicas para Cultivos y Ganado en Panamá

**Autor:** Gabriel I. Ortega  
**Asesor:** Julio A. Aguirre  
**Fecha:** 24 de julio de 2025  
**Evento:** Feria del Ingenio Juvenil - SENACYT

---

## Descripción del Proyecto

Este proyecto realiza un análisis exhaustivo del sector agropecuario de Panamá utilizando datos públicos de la base FAOSTAT (2018–2023). El objetivo es identificar:

- Los cultivos y productos ganaderos más rentables en términos de valor económico por hectárea.
- Los productos con mayor crecimiento en producción.
- Recomendaciones estratégicas para la inversión agrícola y el diseño de políticas públicas.

Este análisis contribuye a la toma de decisiones fundamentadas para agricultores, inversionistas y organismos como SENACYT y el MIDA.

---

## Estructura del Repositorio

```bash
├── data/
│   ├── produccion_faostat.csv
│   └── comercio_faostat.csv
├── notebooks/
│   └── analisis_agro_panama.ipynb
├── visualizations/
│   ├── top10_rentabilidad.png
│   ├── crecimiento_productos.png
│   └── correlaciones_valor_area.png
├── README.md
└── requirements.txt```

---

## **Metodología**

Fuente de Datos:

FAOSTAT - Producción (área, rendimiento, volumen)
FAOSTAT - Comercio (volumen y valor de exportación)

Herramientas Usadas:

- Python (pandas, numpy, matplotlib, seaborn)
- Colab Notebook

Métricas Clave:

Valor por Hectárea (USD/ha) = Rendimiento × Precio de Exportación

Crecimiento de Producción (%) = ((Prod_2023 - Prod_2018) / Prod_2018) × 100

## **Referencias**
FAO. (2025). FAOSTAT: Producción y Comercio Agropecuario.
https://www.fao.org/faostat/en/#data/QCL
https://www.fao.org/faostat/en/#data/TCL
