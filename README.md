# 📊 Rossmann Store Sales — Predicción de Ventas con Machine Learning

## Objetivo de negocio
Predecir las ventas diarias de 1,115 tiendas Rossmann para optimizar inventario, promociones y personal con semanas de anticipación.

## Stack tecnológico
- Python · Jupyter Notebook
- pandas · numpy · scikit-learn · matplotlib · seaborn
- Kaggle API

## Estructura del proyecto
- notebooks/01_cleaning.ipynb → Carga, unión y limpieza de datos
- notebooks/02_eda.ipynb → Análisis exploratorio con 5 hallazgos de negocio
- notebooks/03_model.ipynb → Modelo predictivo Random Forest + proyección

## Resultados del modelo
| Métrica | Valor |
|---|---|
| R² | 0.71 |
| MAE | €1,183 por tienda por día |
| Error promedio | €29 (sin sesgo sistemático) |

## Hallazgos principales
1. Las promociones aumentan ventas +38.8% y clientes +21.2%
2. Diciembre genera +31% sobre septiembre — dependencia crítica navideña
3. Tiendas con competidor cerca venden €403 más que tiendas aisladas
4. Brecha de 8x entre la tienda #817 (€21,757/día) y la #307 (€2,704/día)

## Dataset
Kaggle — Rossmann Store Sales Competition
844,392 registros · 1,115 tiendas · Período 2013–2015
