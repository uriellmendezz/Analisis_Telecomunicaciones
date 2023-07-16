# Proyecto de Análisis de Datos - Empresa argentina de Telecomunicaciones

![Foto de portada](cover.png)

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

El objetivo de este proyecto es extraer y analizar tres KPIs principales a partir de los datos proporcionados por "Enacom", utilizando Power BI. Estos KPIs se centran en aspectos clave de la calidad de la conexión a Internet, los accesos a Internet en los hogares y por habitantes y la distribución de tecnologías de conexión en diferentes provincias.


## KPIs

   - **Velocidad promedio de descarga por provincia y trimestre**: Este KPI calcula la media de Mbps (megabits por segundo) de bajada para cada provincia y trimestre, el cual me permite analizar la calidad de la conexión a Internet en cada provincia a lo largo del tiempo y detectar cambios (aumentos/disminuciones) en la velocidad de descarga del Internet.
   
   - **Crecimiento trimestral de la penetración de acceso a Internet por hogares**: Calcula el porcentaje de crecimiento o disminución de la penetración de acceso a Internet por cada 100 hogares en relación con el trimestre anterior. Este KPI permite evaluar el accesos a Internet en los hogares argentinos y su evolución trimestral.
   
   - **Distribución de tecnologías por provincia**: Sirve para analizar la distribución de tecnologías de conexión (ADSL, Fibra óptica, 4G, Dial up, etc) por provincia. Esto me permite comprender que tecnologías son más utilizadas en las diferentes localidades, partidos y provincias de Argentina y al mismo tiempo puedo saber cuales son los sectores que requieren de mayores servicios

Introducción:

La problematica a la cual hice enfasis para este informe es la siguiente: ¿Como aumentar la velocidad de Internet en las provincias argentinas? 
Es un tema fundamental para la empresa conocer los beneficios de aumentar las velocidades de bajada de Internet para sus clientes. Uno de los beneficios clave es aumentar el valor de vida de los clientes en la empresa, ya que al contar con mejores velocidades, los clientes estarán más satisfechos con el servicio. Esto, a su vez, desembocará en el aumento de los ingresos de la empresa, al fortalecer la fidelidad de los clientes y generar oportunidades para el crecimiento del negocio.

Dentro de este escenario, la tecnología de fibra óptica se podria considerar como una buena solución a esta problematica. En la actualidad, la fibra óptica es considerada la tecnología más avanzada y eficiente para la transmisión de datos a alta velocidad. Su funcionamiento se basa en la transmisión de señales a través de hilos delgados de vidrio o plástico. Esto hace que la fibra óptica, hoy en dia, destaque por sobre otras tecnologias de Internet como los cables de cobre (ADSL) o Wireless (por satelite).

En este informe, me voy a centrar en el análisis de la penetración de fibra óptica en las provincias argentinas y su relación con la velocidad proemdio de bajada de Internet. Tambien pondré foco en los accesos a servicios de Internet por cada 100 hogares por provincia, para poder obtener una visión integral de cada provincia de Argentina.


El análisis realizado reveló importantes hallazgos sobre las ventas trimestrales de la empresa y su relación con la penetración de fibra óptica en distintas provincias. A través de visualizaciones gráficas, se pudo observar que a medida que las conexiones de fibra óptica aumentaban, las ventas trimestrales también experimentaban un incremento significativo. Esto muestra que la penetración de fibra óptica fue una de las principales causas de los aumentos en los ingresos de la empresa.

Al profundizar en las provincias, identifiqué aquellas que presentaban una sólida penetración de fibra óptica en su territorio, así como aquellas que requerían un mayor acceso a esta tecnología. Posteriormente, se analizó la media de bajada de estas provincias y se observó que se encontraban considerablemente por debajo de la media. Este hallazgo resalta la necesidad de mejorar la infraestructura de fibra óptica en dichas provincias para impulsar el desarrollo y la calidad de las conexiones a Internet y asi brindar un mejor servicios a los clientes.

Además, al explorar los datos de accesos por cada 100 hogares por provincia, descubrí interesantes comparativas. Por ejemplo, en la provincia de Buenos Aires, donde se registra una penetración de fibra óptica del 30% y una media de bajada de aproximadamente 24 Mbps, se observó que solo 71 de cada 100 hogares tenían acceso a Internet. En contraste, en Tierra del Fuego, con una penetración de fibra óptica del 1% y una media de bajada de 5,86 Mbps, se encontró que un impresionante 85 de cada 100 hogares contaban con acceso a Internet. Con este dato, la empresa podria decidir si priorizar mayor los accesos en las provincias con una media baja de accesos por cada 100 hogares para expandir su clientela, o bien mejorar la calidad de los servicios a los antiguos clientes, como por ejemplo ampliando la infraestructura de fibra óptica para asi aumentar la media de bajada, es decir, la velocidad del internet.

Estos hallazgos destacan la importancia de seguir impulsando el despliegue de fibra óptica en aquellas provincias con menor penetración y mejorar la calidad de las conexiones a Internet en todo el país. El análisis realizado ofrece una visión clara de la relación entre la penetración de fibra óptica, la media de bajada y los accesos a Internet por provincia, proporcionando así una base sólida para la toma de decisiones y acciones futuras en el ámbito de las telecomunicaciones.

Este informe destaca la relevancia de invertir en infraestructuras de fibra óptica, mejorar la conectividad y garantizar un acceso equitativo a Internet en todo el país, contribuyendo así al crecimiento económico, social y tecnológico de las provincias y de la nación en su conjunto.