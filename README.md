# Análisis Econométrico de la Dispersión Salarial

Análisis empírico sobre microdatos del mercado de trabajo para evaluar la influencia de variables académicas e institucionales en los retornos salariales, desarrollado en Python.

---

## 🎯 Objetivo y Pregunta de Investigación
Evaluar los determinantes del salario y la dispersión salarial inicial analizando el impacto del tipo de estudios y variables sociodemográficas mediante especificaciones de regresión lineal múltiple con términos de interacción.

## 📊 Metodología y Técnicas Econométricas
- **Especificación del modelo:** Regresión lineal multivariante (MCO / OLS) incorporando efectos de interacción.
- **Diagnóstico econométrico:**
  - Contraste de heterocedasticidad (Breusch-Pagan / White).
  - Corrección de varianza con errores estándar robustos **HC3**.
  - Evaluación de multicolinealidad (VIF) y normalidad de residuos.
- **Procesamiento de datos:** Limpieza, recodificación de variables categóricas e imputación con `pandas`.

## 🛠️ Stack Tecnológico
- **Lenguaje:** Python 3.x
- **Librerías principales:** `pandas`, `numpy`, `statsmodels`, `scipy`, `seaborn`, `matplotlib`

## 📈 Resultados y Hallazgos Principales
<!-- Puedes arrastrar aquí una captura o gráfico exportado de tu análisis -->
- **Hallazgo 1:** Breve resumen del coeficiente más relevante y su significatividad estadística.
- **Hallazgo 2:** Interpretación económica del efecto de interacción detectado.
- **Conclusión de negocio / política:** Implicación práctica del resultado empírico.

## 🚀 Cómo reproducir el análisis
1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/Alexggarcia7/tu-nombre-de-repo.git](https://github.com/Alexggarcia7/tu-nombre-de-repo.git)
