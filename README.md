# 🚦 Movilidad Urbana y Productividad Económica en Latinoamérica

## 📌 Resumen Ejecutivo
Este análisis evalúa la relación entre movilidad urbana y productividad económica en ciudades latinoamericanas durante 2024.  
El objetivo fue identificar **ciudades prioritarias para inversión en infraestructura de transporte**, utilizando datos de congestión vehicular (TomTom) e indicadores económicos (OECD).  

Hallazgo clave: **no existe correlación lineal clara entre PIB per cápita y niveles de congestión vehicular**, demostrando que no por ser ciudades más ricas automáticamente tienen mejor movilidad.

---
## 🎯 Objetivo
- Evaluar la relación entre congestión vehicular y productividad económica.  
- Identificar ciudades críticas para inversión en infraestructura de transporte.  
- Proponer recomendaciones basadas en evidencia para mejorar movilidad urbana.  

---

## 📂 Dataset
**Cobertura:** 15 ciudades en 7 países (Argentina, Brasil, Colombia, México, Perú, Uruguay, Chile).  
**Fuentes:** TomTom (movilidad) + OECD (economía).  

**Variables de movilidad:**
- `JamsDelay`: Tiempo de retraso por congestión (minutos)  
- `TrafficIndexLive`: Índice de tráfico en tiempo real  
- `TravelTimeLivePer10KmsMins`: Tiempo de viaje por cada 10 km  

**Variables económicas:**
- `city_gdp_capita`: PIB per cápita (USD)  
- `unemployment_pct`: Tasa de desempleo  
- `population`: Población total  

**Procesamiento:**
- Unión INNER de datasets TomTom + OECD.  
- Limpieza de formatos numéricos y porcentajes.  
- Conversión de variables económicas a `float64`.  
- Agregación ciudad-año para métricas anuales.  


---
## 🛠️ Herramientas y librerías
- Python (pandas, numpy)  
- Matplotlib / Seaborn — visualizaciones (boxplot, histogramas, gráficos de barras)  
---

## 🔬 Metodología
1. Integración de datasets TomTom y OECD.  
2. Limpieza y estandarización de variables.  
3. Agregación de métricas anuales por ciudad.  
4. Visualizaciones exploratorias (boxplot, histogramas, gráficos comparativos).  
5. Interpretación de hallazgos y recomendaciones de inversión.

---

## 📊 Visualizaciones

- **Boxplot:** Distribución de congestión por ciudad
- **Histograma:** PIB per cápita en ciudades latinoamericanas
- **Scatter Plot:** Relación PIB vs. Congestión vehicular
- **Análisis Comparativo:** Ranking de ciudades por eficiencia
---


## 📊 Hallazgos principales
| Ciudad           | PIB per cápita (USD) | Congestión (min) | Observación        |
|------------------|----------------------|------------------|--------------------|
| Ciudad de México | $21,111               | 2,833            | Congestión crítica |
| Bogotá           | $11,442               | 1,141            | Alta congestión, PIB moderado |
| Brasilia         | $16,251               | 101              | Caso excepcional: PIB alto y baja congestión |

- **No existe correlación directa** entre PIB per cápita y congestión vehicular.  
- **La infraestructura de transporte es más determinante que la densidad poblacional**: Buenos Aires (15.4 millones de habitantes) maneja mejor el tráfico que Bogotá (11.3 millones).  
- **Brasilia demuestra que la planificación urbana puede lograr simultáneamente alta productividad y baja congestión.**

---

## 💡 Recomendaciones
- **Ciudades prioritarias:**  
  - Ciudad de México: intervención urgente.  
  - Bogotá: mejor relación costo-beneficio.  
- **Acciones:**  
  - Desarrollar análisis de impacto económico detallado para ambas ciudades.  
  - Replicar modelo de Brasilia como caso de éxito.  

---

## 📁 Estructura del repositorio
- `readme.md`
- `data/` → datasets original.
- `notebooks/` → notebooks de análisis.
- `visualizaciones/` → gráficos generados.




