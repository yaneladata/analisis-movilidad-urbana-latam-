# 📊 Análisis de Movilidad Urbana y Economía en Latinoamérica

🎯 Descripción del Proyecto
Análisis de la relación entre movilidad urbana y productividad económica en 15 ciudades latinoamericanas durante 2024. El proyecto evalúa cómo la congestión vehicular se relaciona con indicadores económicos para identificar ciudades prioritarias para inversión en infraestructura de transporte.

📈 Hallazgos Clave
### 🚦 Congestión Vehicular
- Ciudad más congestionada: Ciudad de México (2,833 minutos de retraso)
- Mejor movilidad: Brasilia (101 minutos de retraso)
- Caso crítico: Bogotá (1,141 minutos con PIB moderado)

### 💰 Relación PIB-Congestión
- No existe correlación lineal entre PIB per cápita y congestión
- Brasilia: Modelo exitoso (PIB alto + baja congestión)
- Planificación urbana más determinante que riqueza económica

🛠️ Metodología
### Fuentes de Datos
- TomTom Traffic Index: Métricas de congestión vehicular
- OECD Cities: Indicadores económicos urbanos

### Procesamiento
1. Limpieza: Estandarización de formatos y columnas
2. Agregación: Promedios anuales por ciudad
3. Integración: Unión INNER de datasets
4. Análisis: Visualizaciones y correlaciones

### Variables Clave
Movilidad:
- JamsDelay: Tiempo de retraso por congestión
- TrafficIndexLive: Índice de tráfico en tiempo real
- TravelTimeLivePer10KmsMins: Tiempo de viaje por 10km

Economía:
- city_gdp_capita: PIB per cápita (USD)
- unemployment_pct: Tasa de desempleo
- population: Población total

## 📊 Visualizaciones

- **Boxplot:** Distribución de congestión por ciudad
- **Histograma:** PIB per cápita en ciudades latinoamericanas
- **Scatter Plot:** Relación PIB vs. Congestión vehicular
- **Análisis Comparativo:** Ranking de ciudades por eficiencia

## 🚀 Recomendaciones Estratégicas

### 🎯 Ciudades Prioritarias para Inversión
1. **Bogotá:** Alta congestión + PIB moderado → ROI potencial alto
2. **Ciudad de México:** Congestión extrema → Impacto económico crítico
3. **Lima:** Oportunidad de mejora significativa

### 📋 Estrategias Recomendadas
- **Replicar modelo Brasilia:** Planificación urbana eficiente
- **Transporte público masivo** en ciudades con >1,000 min retraso
- **Políticas de movilidad sostenible** priorizando ciudades con PIB >$15,000
