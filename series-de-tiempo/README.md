# Análisis de Series de Tiempo en Finanzas

## Resumen
En este proyecto presento un análisis reproducible de series de tiempo aplicado a datos financieros. El trabajo abarca desde la descarga de datos reales hasta el modelado avanzado de volatilidad, demostrando competencias técnicas clave en análisis cuantitativo.

**Puedes ver el reporte completo aquí:** [Reporte HTML](./reporte.html)

## Objetivos
El objetivo principal es aplicar y validar técnicas de modelado, evaluación y visualización de series temporales, incluyendo:
*   Descarga de datos bursátiles (Yahoo Finance).
*   Transformación y limpieza de datos (cálculo de log-retornos).
*   Ajuste y selección de modelos ARMA/ARIMA.
*   Modelado de volatilidad condicional con GARCH.

## Contenido del Análisis

El reporte se estructura en las siguientes secciones:

1.  **Simulación de modelos ARMA:** 
    *   Explicación teórica y práctica de modelos $AR(n)$, $MA(q)$ y $ARMA(p,q)$.
    *   Análisis de estacionariedad y persistencia visual.
2.  **ACF y PACF:**
    *   Uso de funciones de autocorrelación para identificar patrones de dependencia temporal.
3.  **Ajuste de modelos ARIMA:**
    *   Aplicación práctica con datos reales descargados.
    *   Criterios de selección de modelos (AIC, BIC).
4.  **Análisis de residuos:**
    *   Validación de supuestos del modelo.
5.  **Modelo GARCH:**
    *   Justificación del uso de modelos de volatilidad estocástica.
    *   Ajuste de un modelo GARCH(2,1).
6.  **Conclusiones:**
    *   Resumen de hallazgos principales y limitaciones del análisis.

## Tecnologías y Habilidades
*   **Lenguaje:** Python
*   **Librerías:** Pandas, NumPy, Matplotlib/Seaborn, Statsmodels, Arch, Yfinance.
*   **Habilidades:** Data Wrangling, Modelado Estadístico, Series Temporales, Visualización de Datos, Reproducibilidad.

## Archivos
*   `reporte.ipynb`: Jupyter Notebook con todo el código y análisis.
*   `reporte.html`: Versión exportada del reporte para visualización web.
*   `SPY.csv`: Datos descargados (ETF SPDR S&P 500) utilizados en el análisis.

---
*Autor: Fernando J. Terreno*
