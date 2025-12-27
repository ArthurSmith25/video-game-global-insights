# 🎮 Análisis Predictivo de la Industria de Videojuegos: Ice Online Store

**Estrategia de Inteligencia de Datos para el Planeamiento Comercial 2017**

**Proyecto ID:** 06

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scipy](https://img.shields.io/badge/Scipy-Statistical_Inference-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)

## 📌 Contexto de Negocio

Como analista para la tienda online **Ice**, el objetivo central es mitigar el riesgo financiero identificando los drivers de éxito comercial en un mercado de alta volatilidad. Este proyecto procesa datos históricos (1980-2016) para modelar el comportamiento del consumidor y predecir las tendencias de mayor rentabilidad para 2017.

## 🛠️ Pipeline Analítico

El proyecto se estructura en fases de ingeniería y análisis avanzado:

1. **Data Sanitization**: Gestión de valores ausentes e integridad de la muestra.
2. **Análisis de Dinámica de Plataformas**: Modelado de curvas de obsolescencia.
3. **Diagnóstico de Rentabilidad**: Análisis de varianza (Boxplots) y correlación de éxito (Critic Score).
4. **Inteligencia Regional**: Segmentación psicográfica de mercados (NA, EU, JP).
5. **Verificación de Hipótesis**: Aplicación de T-Tests para validación inferencial.

## 📊 Hallazgos Clave (Insights)

- **Dominancia de Octava Generación**: PS4 y Xbox One se identifican como los pilares de inversión para 2017, con la PS4 mostrando la mayor estabilidad comercial.
- **Divergencia Cultural**: Mientras Occidente prioriza Acción y Shooters, el mercado japonés demanda exclusivamente RPGs y hardware portátil (3DS).
- **Calidad vs. Ventas**: Se confirmó una correlación positiva moderada ($r=0.40$) entre las reseñas de expertos y el volumen de ventas, estableciendo un umbral crítico de éxito en los 80 puntos.

## ⚙️ Tecnologías Utilizadas

- **Lenguaje**: Python
- **Librerías**: Pandas, NumPy, Matplotlib, Seaborn, Scipy (stats).
- **Entorno**: Jupyter Notebook / Google Colab.
