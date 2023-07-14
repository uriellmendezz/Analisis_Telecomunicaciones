# Proyecto de Análisis de Datos - Empresa argentina de Telecomunicaciones

## Índice
- [Descripción de Archivos](#archivos)
- [Introducción](#intro)
- [Objetivo del proyecto](#objetivoproyecto)
- [KPIs](#kpis)
- [Conclusiones](#conlusiones)


## Descripción de Archivos

<summary><strong>🗂️<em>original_datasets</em></strong>: Contiene archivos <em>CSV</em> con los datasets originales de la empresa, es decir, sin procesamiento alguno</summary>

<br>

<summary><strong>🗂️<em>clean_datasets</em></strong>: Contiene archivos <em>CSV</em> con limpieza aplicada, es decir, luego del proceso de transformación de los datos (ETL)</summary>

<br>

<summary><strong>🛠️<em>ETL.ipynb</em></strong>: Archivo <em>.ipynb</em> (notebook) con las transformaciones y limpieza a los datos originales</summary>

<br>

<summary><strong>🕵️‍♂️<em>EDA.ipynb</em></strong>: Archivo <em>.ipynb</em> (notebook) el analisis exploratorio de los datos (EDA) <em>contiene varios graficos de los analisis</em></summary>

<br>

<summary><strong>📊<em>dashboard.pbix</em></strong>: Archivo <em>.pbix</em> que contiene todas las visualizaciones y KPI's del analisis</em></summary>

<br>

<summary><strong>📗<em> README.md</em></strong>: Archivo <em>.md</em> con la documentación del proyecto</summary>

<br>

## Introducción

Este proyecto de análisis de datos se centra en la empresa de telecomunicaciones "Enacom". El objetivo principal es obtener información estratégica a partir de un análisis realizado en Power BI. El análisis se centra en tres KPIs clave que proporcionan una vision profunda del rendimiento y la adopción de servicios de Internet de Enacom en diferentes contextos.

La empresa Enacom es una compania de telecomunicaciones con una solida presencia en el mercado. Ofrece varios servicios de telecomunicaciones, como la telefonía movil, telefonía fija, servicios de Internet y transmisión de datos. 

## Objetivo del Proyecto

El objetivo de este proyecto es extraer y analizar tres KPIs principales a partir de los datos proporcionados por "Enacom", utilizando Power BI. Estos KPIs se centran en aspectos clave de la calidad de la conexión a Internet, los accesos a Internet en los hogares y por habitantes y la distribución de tecnologías de conexión en diferentes provincias y tambien a nivel nacional.


## KPIs

   - **Velocidad promedio de descarga por provincia y trimestre**: Este KPI calcula la media de Mbps (megabits por segundo) de bajada para cada provincia y trimestre, el cual me permite analizar la calidad de la conexión a Internet en cada provincia a lo largo del tiempo y detectar cambios (aumentos/disminuciones) en la velocidad de descarga del Internet.
   
   - **Crecimiento trimestral de la penetración de acceso a Internet por hogares**: Calcula el porcentaje de crecimiento o disminución de la penetración de acceso a Internet por cada 100 hogares en relación con el trimestre anterior. Este KPI permite evaluar el accesos a Internet en los hogares argentinos y su evolución trimestral.
   
   - **Distribución de tecnologías por provincia**: Sirve para analizar la distribución de tecnologías de conexión (ADSL, Fibra óptica, 4G, Dial up, etc) por provincia. Esto me permite comprender que tecnologías son más utilizadas en las diferentes localidades, partidos y provincias de Argentina y al mismo tiempo puedo saber cuales son los sectores que requieren de mayores servicios
