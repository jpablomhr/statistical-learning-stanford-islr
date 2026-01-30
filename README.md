# 📊 Statistical Learning: From Linear Models to Bias-Variance Tradeoff

![Python](https://img.shields.io/badge/Python-3.9-blue) ![Statsmodels](https://img.shields.io/badge/Library-Statsmodels-orange) ![Status](https://img.shields.io/badge/Status-Active-green)

Este repositorio contiene una implementación práctica y análisis profundo de los conceptos fundamentales de **Statistical Learning** 

El objetivo no es solo ajustar modelos, sino diseccionar la **inferencia estadística** detrás de las predicciones.

## 🧠 Conceptos Clave Implementados

### 1. Inferencia en Regresión Lineal
Exploración de la relación entre presupuestos de marketing y ventas.
- **Hipótesis Testing:** Uso de *t-statistics* y *p-values* para determinar significancia (TV & Radio vs. Newspaper).
- **Intervalos de Confianza:** Interpretación de incertidumbre en los coeficientes $\beta$.

### 2. Regresión Múltiple y Colinealidad
Demostración de cómo la correlación entre variables puede engañar a un modelo simple.
- **Visualización 3D:** El hiperplano de mínimos cuadrados.
- **Análisis de Residuos:** Verificación de supuestos.

### 3. The Bias-Variance Tradeoff
Simulación numérica para visualizar la descomposición del error:
$$E[(y - \hat{f}(x))^2] = Var(\hat{f}(x)) + [Bias(\hat{f}(x))]^2 + Var(\epsilon)$$

## 🛠️ Tecnologías
- **Python**: Numpy, Pandas.
- **Análisis Estadístico**: Statsmodels (para reportes detallados tipo R).
- **Visualización**: Seaborn & Plotly (Gráficos interactivos).

## 🚀 Cómo ejecutar
```bash
git clone [https://github.com/tu-usuario/statistical-learning-islr.git](https://github.com/tu-usuario/statistical-learning-islr.git)
pip install -r requirements.txt
jupyter notebook