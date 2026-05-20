# Optimización de Fuerza Laboral: Predicción de Rotación de Personal (HR Workforce Optimization)

## Descripción del Proyecto
Este proyecto de Ciencia de Datos tiene como objetivo identificar patrones de desgaste laboral y predecir el riesgo de rotación de personal en una planta industrial. Mediante técnicas de análisis estadístico y Machine Learning, buscamos proporcionar al área de Recursos Humanos una herramienta de **Alerta Temprana** que permita intervenciones preventivas y focalizadas.

## Metodología
El proyecto sigue un ciclo de vida estándar de Data Science:
1. **Análisis Exploratorio (EDA):** Identificación de correlaciones entre variables sociodemográficas/laborales y la rotación.
2. **Estadística Inferencial:** Validación de hipótesis mediante pruebas $Chi^2$ y $t$-Student.
3. **Machine Learning:** Desarrollo de un modelo de *Random Forest Classifier*.
   - **Calibración:** Optimización del umbral de decisión (*threshold tuning*) al 30% para maximizar la capacidad de detección (Recall) de colaboradores en riesgo.
   - **Interpretabilidad:** Análisis de importancia de variables (*Feature Importance*) para comprender los detonantes del burnout.

## Herramientas Utilizadas
- **Lenguaje:** Python 3.13
- **Análisis y Manipulación:** Pandas, NumPy
- **Visualización:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Entorno:** Jupyter Notebooks / VS Code

## Nota sobre los Datos
**Aviso importante:** Todos los conjuntos de datos (`dim_empleados.csv`, `fact_evaluaciones.csv`, `reporte_origen_rh.xlsx`) utilizados en este repositorio **fueron creados sintéticamente para fines didácticos y de demostración técnica**. Toda la información contenida en ellos es **totalmente ficticia** y no corresponde a personas o empresas reales.

## Estado del Proyecto
🚧 **En desarrollo:** Continuamente trabajando en la mejora del modelo predictivo y en la documentación de estrategias de retención de talento.
