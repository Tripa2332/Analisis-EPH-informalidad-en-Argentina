# Análisis de la informalidad laboral en Argentina

Trabajo integrador de **Python para Ciencia de Datos** sobre la informalidad entre trabajadores asalariados, a partir de microdatos de la Encuesta Permanente de Hogares (EPH).

## Objetivo

Explorar los datos y entrenar un clasificador k-NN para estimar si una persona asalariada tiene o no descuento jubilatorio. El análisis se enfoca en describir patrones y evaluar el modelo; sus resultados no identifican causas ni deben interpretarse como una evaluación individual.

## Archivos

- [`TP_EPH_informalidad.ipynb`](./TP_EPH_informalidad.ipynb): notebook con la carga, limpieza, exploración y modelado.
- [`consignas/TP Integrador · Segundo parcial.docx`](./consignas/TP%20Integrador%20%C2%B7%20Segundo%20parcial.docx): consigna del trabajo.
- [`data/eph_2024_2026.csv`](./data/eph_2024_2026.csv): microdatos de entrada, con variables individuales y del hogar.
- [`data/eph_asalariados_limpio.csv`](./data/eph_asalariados_limpio.csv): datos preparados que genera el notebook.

## Cómo ejecutar

1. Cloná el repositorio y abrí `TP_EPH_informalidad.ipynb` en Jupyter o Visual Studio Code.
2. Instalá, si hace falta, las bibliotecas usadas en el notebook: `numpy`, `pandas`, `seaborn`, `matplotlib` y `scikit-learn`.
3. Ejecutá las celdas en orden, desde el comienzo y con la carpeta del repositorio como directorio de trabajo.

El notebook toma de `data/` los trimestres 2, 3 y 4 de 2025 y el trimestre 1 de 2026. La carpeta `consignas/` contiene el documento de referencia.
