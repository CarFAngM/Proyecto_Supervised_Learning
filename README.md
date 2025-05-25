# Análisis de Compras y Comportamiento de Clientes

Este proyecto realiza un análisis exploratorio de datos (EDA) sobre los registros de ventas y devoluciones de una tienda en línea. Se estudian los patrones de compra por hora, mes, día de la semana, así como el comportamiento por cliente (última compra, devoluciones, recompras, región, etc.).

Además, se desarrollan modelos predictivos para estimar:
- La probabilidad de devolución
- La probabilidad de recompra
- El monto total gastado por cliente

##  Contenido

- Limpieza y transformación de datos
- Detección y eliminación de duplicados
- Enriquecimiento del dataset con columnas como:
  - Hora, mes y día de la semana
  - Monto total por factura
  - Facturas únicas
- Elaboracion de una nueva tabla para realizar los modelos en base a el Cliente:
- Modelos predictivos:
  - Clasificación para devolución y recompra
  - Regresión para monto total gastado
  - Evaluacion de dichos modelos con recall, accuracy y precision
  - Evaluacion economica del mejor modelo con datos inventados
  - Toma de decisiones en base a el contexto. 
- Visualización de datos con gráficos:
  - Barras
  - Dispersión
  - Histogramas
  - Boxplots

## Estructura del repositorio

├── Proyecto-1--Exploración,-modelos-y-análisis----DM-y-ML.Rmd # Script principal del análisis
├── Proyecto-1--Exploración,-modelos-y-análisis----DM-y-ML.html # Reporte generado (exportación del .Rmd)
├── Presentacion.pdf # Presentación con resultados clave
├── P5_Recompra_Online.xslx # Base de datos

## Requisitos 

- R >= 4.2.0
  
- Paquetes:

Este proyecto fue desarrollado en **R**. Para ejecutarlo correctamente, asegúrate de tener instalados los siguientes paquetes:

```r
install.packages(c(
  "dplyr", "fastDummies", "ggplot2", "psych", "corrplot", "tidyr",
  "broom", "sigr", "WVPlots", "Metrics", "e1071", "weights",
  "tidyverse", "rpart", "rpart.plot", "readxl", "randomForest", "writexl"
))
```

## Cómo ejecutar
Asegurarse de tener el directorio correspondiente y el archivo P5_Recompra_Online.xslx

Abre Proyecto-1--Exploración,-modelos-y-análisis----DM-y-ML.Rmd en RStudio.

Ejecuta todo el documento (Knit) para generar el reporte HTML.

Consulta la presentación Presentacion.pdf para visualizar los resultados clave y recomendaciones.


## Desarrolladores

- Carlos Angel (CarFAngM)
- José Donado 
- Carlos Aldana (C3AC)
- Diego Monroy
- Marco Carbajal (marcocarbajalb)


