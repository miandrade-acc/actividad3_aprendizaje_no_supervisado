# 🧠 Segmentación de Usuarios - Actividad Semana 3

Este proyecto implementa modelos de aprendizaje no supervisado para segmentar usuarios de una plataforma digital con base en su comportamiento y transacciones.

## ⚙️ Entorno de trabajo

- **Lenguaje:** Python 3.10+
- **Entorno:** JupyterLab / Jupyter Notebook
- **Base:** Anaconda (opcional)

## 📦 Librerías utilizadas

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- plotly *(para visualizaciones interactivas, opcional)*
- umap-learn *(si se desea comparar con t-SNE)*

## 🗂️ Estructura del proyecto

actividad1_semana3/  
├── data/          # Dataset original y procesado  
├── notebooks/     # Cuadernos .ipynb con el desarrollo  
├── results/  
│   ├── graficos/  # Visualizaciones de clusters  
│   └── tablas/    # Tabla resumen de perfiles  
├── docs/          # Informe y presentación final  
└── README.md      # Descripción técnica del proyecto  

## 🧾 Dataset utilizado

- **Nombre:** Online Retail Dataset  
- **Fuente:** https://archive.ics.uci.edu/ml/datasets/online+retail  
- **Formato:** CSV (originalmente XLSX, convertido para optimización)  
- **Descripción:** Datos de transacciones de clientes en una tienda de retail online del Reino Unido entre 2010 y 2011.

## 🧪 Técnicas aplicadas

1. **Análisis Exploratorio (EDA):**
   - Estadísticas básicas, limpieza, normalización
   - Distribución de productos, países, y precios

2. **Modelado No Supervisado:**
   - K-means: con método del codo y silueta
   - DBSCAN: con ajuste de eps y min_samples
   - PCA: reducción de dimensiones
   - Visualización 2D: proyecciones de clusters

## 📈 Resultados Generados

### 🔹 Gráficos (en `/results/graficos/`)

- pca_kmeans_clusters.png: Segmentos según K-means  
- pca_dbscan_clusters.png: Segmentos según DBSCAN  

### 🔸 Tabla resumen (en `/results/tablas/`)

- tabla_perfiles_kmeans.csv: Promedios por cluster identificado

## 📌 Conclusiones

- K-means permitió identificar 3 perfiles distintos de usuarios con claridad.  
- DBSCAN fue útil para detectar posibles valores atípicos (outliers).  
- La combinación de reducción con PCA mejoró la visualización e interpretación de los resultados.  
- Los perfiles detectados pueden ser usados para campañas de marketing personalizadas.

## 👥 Autores

- MARÍA AUGUSTA FLORES  
- MARCELO ISMAEL ANDRADE  
- JORGE ANDRÉS ORELLANA  
- GALO VLADIMIR GONZÁLEZ  

**Curso:** Aprendizaje Automático - UEES  
**Fecha:** Mayo 2025


