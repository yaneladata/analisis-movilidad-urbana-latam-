# 🚦 Movilidad Urbana y Productividad Económica en Latinoamérica

## 📌 Resumen Ejecutivo
Este análisis evalúa la relación entre movilidad urbana y productividad económica en ciudades latinoamericanas durante 2024.  
El objetivo fue identificar **ciudades prioritarias para inversión en infraestructura de transporte**, utilizando datos de congestión vehicular (TomTom) e indicadores económicos (OECD).  

El análisis reveló que no existe una correlación lineal clara entre el PIB per cápita y los niveles de congestión vehicular, demostrando que no por ser ciudades más ricas automáticamente tienen mejor movilidad.

---

## 🎯 Objetivo
- Evaluar la relación entre congestión vehicular y productividad económica.  
- Identificar ciudades críticas para inversión en infraestructura de transporte.  
- Proponer recomendaciones basadas en evidencia para mejorar movilidad urbana.  

---

## 📂 Dataset
**Cobertura:** 15 ciudades latinoamericanas en 7 países (Argentina, Brasil, Colombia, México, Perú, Uruguay y Chile).  
**Fuentes:**  
- TomTom (movilidad urbana)  
- OECD (indicadores económicos)  

**Variables de movilidad:**
- `JamsDelay`: Tiempo de retraso por congestión (minutos)  
- `TrafficIndexLive`: Índice de tráfico en tiempo real  
- `TravelTimeLivePer10KmsMins`: Tiempo de viaje por cada 10 km  

**Variables económicas:**
- `city_gdp_capita`: PIB per cápita (USD)  
- `unemployment_pct`: Tasa de desempleo  
- `population`: Población total
  
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

 ## 📊 Hallazgos principales
- **No existe correlación directa** entre PIB per cápita y congestión vehicular.  
- **Ciudad de México**: congestión crítica (2,833 min) con PIB de $21,111 USD.  
- **Bogotá**: alta congestión (1,141 min) con PIB moderado ($11,442 USD).  
- **Brasilia**: caso excepcional — PIB alto ($16,251 USD) y congestión muy baja (101 min), gracias a su diseño urbano planificado.  
- - La **densidad poblacional no determina la congestión**: Buenos Aires (15.4M) maneja mejor el tráfico que Bogotá (11.3M).  

---
## 📊 Visualizaciones

- **Boxplot:** Distribución de congestión por ciudad
- **Histograma:** PIB per cápita en ciudades latinoamericanas
- **Scatter Plot:** Relación PIB vs. Congestión vehicular
- **Análisis Comparativo:** Ranking de ciudades por eficiencia
---

## 💡 Recomendaciones
- **Ciudades prioritarias para inversión:**  
  - Ciudad de México: intervención urgente por congestión crítica.  
  - Bogotá: mejor relación costo-beneficio potencial.  

- **Acciones recomendadas:**  
  - Desarrollar análisis de impacto económico detallado para Ciudad de México y Bogotá.  
  - Replicar el modelo de **Brasilia** como caso de éxito en planificación urbana.  

---

## ⚠️ Limitaciones
- Análisis limitado a datos de 2024.  
- No se incluyen variables socioeconómicas adicionales (ej. costo del transporte, políticas locales).  
- El estudio es exploratorio y no establece causalidad.  

---

## 🔜 Próximos pasos
- Extender el análisis a periodos más largos para detectar tendencias.  
- Incorporar variables socioeconómicas adicionales.  
- Evaluar impacto de políticas de movilidad sostenible en ciudades piloto.

  
---
## 📁 Estructura del repositorio
- `readme.md`
- `data/` → datasets original.
- `notebooks/` → notebooks de análisis.
- `visualizaciones/` → gráficos generados.




