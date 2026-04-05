# Brecha de Género y Salarial en Chile
## Análisis de la Brecha Salarial de Género en Chile (2016-2026)

## Descripción del Proyecto
Este repositorio contiene un análisis estadístico y técnico sobre las disparidades de ingresos entre hombres y mujeres en el mercado laboral chileno. Utilizando microdatos oficiales de la Encuesta Suplementaria de Ingresos (ESI) del INE, el proyecto identifica brechas críticas segmentadas por sector económico y nivel educativo.

##Stack Tecnológico
Lenguaje: Python 3.10
Librerías de Análisis: Pandas, NumPy
Visualización: Matplotlib, Seaborn, Tableau
Entorno Cloud: Google Cloud Platform (BigQuery para procesamiento masivo)

## Metodología (Pipeline ETL)
Extracción: Obtención de microdatos desde el portal de datos abiertos del INE Chile.
Transformación (Limpieza):
Tratamiento de valores nulos y registros atípicos (outliers).
Normalización de variables de ingresos y categorías de ocupación.
Análisis: Cálculo de la brecha salarial bruta y ajustada por horas trabajadas y nivel de instrucción.
Carga/Visualización: Exportación de resultados a un Dashboard interactivo en Tableau.

## Hallazgos Clave
Brecha Promedio: Se identificó una brecha salarial del XX% a nivel nacional.
Sectores Críticos: El sector de Minería presenta la brecha más alta, mientras que Tecnología muestra una tendencia a la reducción.
Efecto Educación: A mayor nivel educativo, la brecha tiende a [aumentar/disminuir] según los datos procesados.

## Estructura del Repositorio
/data: Diccionarios de datos y fuentes.
/notebooks: Jupyter Notebooks con el Análisis Exploratorio (EDA).
/scripts: Scripts de Python para la automatización del proceso.

## Dashboard y gráficos estadísticos.

## Cómo Ejecutar el Proyecto
bash
git clone https://github.com
cd brecha-salarial-chile
pip install -r requirements.txt
python main.py
Use code with caution.

💡 Consejo para tu GitHub:
Una vez que crees el archivo README.md, asegúrate de incluir una imagen o captura de pantalla de tu gráfico de barras o tu dashboard de Tableau. Los reclutadores suelen mirar primero lo visual antes de leer el código.
¿Te gustaría que te ayude a redactar la conclusión técnica de este análisis para incluirla en el párrafo de "Hallazgos Clave"?
