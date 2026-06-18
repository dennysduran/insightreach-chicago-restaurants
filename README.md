# 🍽️ InsightReach — Análisis de Restaurantes en Chicago

Proyecto de análisis de datos para InsightReach, empresa de marketing digital.
Integra datos de encuestas con la API de Yelp Fusion para generar recomendaciones
personalizadas de restaurantes por segmento de cliente.

## 📌 Objetivos
- Analizar el comportamiento de 5,384 clientes de Chicago
- Extraer restaurantes reales via Yelp Fusion API
- Generar un sistema de recomendaciones basado en preferencias alimenticias

## 📂 Estructura del proyecto
| Archivo | Descripción |
|---|---|
| `Avance_EDA.ipynb` | Limpieza y análisis exploratorio de datos |
| `Avance_API_Yelp.ipynb` | Extracción de datos via Yelp API + recomendaciones |
| `df_api_yelp_limpio.csv` | Dataset limpio extraído de Yelp |
| `README_pdf.pdf` | Documentación técnica completa |
| `Recomendaciones_pdf.pdf` | Hallazgos y estrategias de negocio |

## 🛠️ Stack técnico
`Python` `pandas` `numpy` `matplotlib` `seaborn` `requests` `Jupyter Notebook`

## 🔍 Hallazgos clave
- Relación directamente proporcional entre estrato socioeconómico y gasto ($5.80 → $54.17)
- 41.14% de clientes cuenta con membresía premium
- Sistema de recomendaciones con rating ponderado (fórmula IMDb)
- Segmentación en 3 perfiles: Premium, Medio y Ocasional
