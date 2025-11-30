# BI-Contraloria-DW-Mineria

Proyecto Final de Inteligencia de Negocios (ICC-321) - Pontificia Universidad Católica Madre y Maestra (PUCMM).  

Modelo de minería de datos descriptiva basado en datos públicos de nómina y actividades institucionales de la Contraloría General de la República Dominicana (2018-2025).

## 📋 Descripción del Proyecto
Este repositorio contiene un modelo simplificado de minería de datos descriptiva para segmentar empleados de la Contraloría General. Incluye:
- **Modelo de Minería de Datos**: Clustering (K-means) para identificar grupos naturales de empleados por sueldo, estatus, función y departamento.
- **Objetivos**:
  - Analizar patrones en nómina para detectar ineficiencias o inequidades salariales.
  - Proporcionar insights accionables para la toma de decisiones en la Contraloría.

Datos fuente: Portal de Transparencia de la República Dominicana (nómina-de-empleados-2018-2025). El ETL se realizó previamente; aquí se enfoca en el análisis.

## 📂 Estructura del Repositorio
- **`mining_notebook.ipynb`**: Jupyter Notebook con el modelo de clustering (K-means), preprocessing, visualizaciones y análisis.
- **`merged_empleados.csv`**: Dataset unificado con datos de empleados (sueldo, estatus, función, departamento, etc.) listo para cargar en el notebook.

## ⚙️ Requisitos
- Python 3.8+.
- Librerías: `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`.
- Instala con: `pip install pandas numpy scikit-learn matplotlib seaborn`.
