# Análisis del mercado de café en Indonesia

- **Autora:** Natalia Sabrina Bernardelli
- **Curso:** Herramientas básicas para el Análisis de Datos
- **Cohorte:** 2026

Este proyecto explora el desempeño de negocios de café en Indonesia mediante análisis con Python y un tablero interactivo en Power BI.

## Pregunta de negocio

¿Cómo se comparan las marcas y los formatos de cafetería en ventas, precios y rentabilidad operativa estimada entre ciudades? También se consideran diferencias por método de pedido y la relación entre descuentos y volumen de ventas.

## Datos

Se utiliza el dataset [Indonesia Coffee Chain Wars Retail Market](https://www.kaggle.com/datasets/luthfimuthathohirin/indonesia-coffee-chain-wars-retail-market), con 13.000 filas y 26 columnas sobre marcas, ciudades, locales, clientes, ventas, precios, descuentos, calificaciones e ingresos y márgenes estimados. La versión depurada es `indonesia_coffee_chain_wars_clean.csv`.

## Métodos y herramientas

Python (pandas, matplotlib y seaborn) se utiliza para validar, limpiar, explorar y visualizar los datos. Las verificaciones documentadas no encontraron datos faltantes, filas duplicadas ni identificadores de transacción repetidos. Se estandarizaron los nombres de columnas y se evitaron transformaciones innecesarias. Seguido de ello se crea un tablero interactivo de una página en Power BI.

El tablero incluiye tarjetas de ventas diarias promedio, ingresos diarios estimados y margen operativo estimado, más comparaciones y filtros por marca, ciudad, formato y método de pedido. Identifica ingresos y márgenes como estimaciones.

## Estructura del repositorio

El repositorio contiene `data/`, `notebooks/` y `dashboard/` para los CSV, el notebook, el informe de Power BI y su vista previa.

## Fuentes y créditos

- Dataset: [Indonesia Coffee Chain Wars Retail Market](https://www.kaggle.com/datasets/luthfimuthathohirin/indonesia-coffee-chain-wars-retail-market), Kaggle.
- Documentación: [pandas](https://pandas.pydata.org/docs/), [Matplotlib](https://matplotlib.org/stable/), [seaborn](https://seaborn.pydata.org/) y [Power BI](https://learn.microsoft.com/power-bi/).
- Imágenes: no se utilizaron imágenes externas. Las visualizaciones y capturas del proyecto son de elaboración propia; los datos se atribuyen a la fuente indicada arriba.
