# Proyecto de Análisis de Datos - Empresa argentina de Telecomunicaciones

![Foto de portada](img/cover.png)

## Índice
- [Descripción de Archivos](#descripción-de-archivos)
- [Introducción](#introducción)
- [KPIs](#kpis)
- [Conclusiones](#conclusiones)


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

Este proyecto de análisis de datos se centra en la empresa argentina "Enacom", una compania de telecomunicaciones que ofrece varios servicios como la telefonía movil, telefonía fija, servicios de Internet y transmisión de datos. La idea principal es obtener información estratégica a partir de un análisis realizado en Power BI, el cual se centra en tres KPIs clave que proporcionan una vision profunda del rendimiento y la adopción de servicios de Internet de Enacom en las diferentes provincias de la Republica Argentina.

<img src='img/Logo_enacom.png' height=120 width=160>

<br>

La problematica a la cual hice enfasis para este informe es la siguiente: **¿Como aumentar la velocidad de bajada de Internet en las provincias argentinas?** 

Es un tema fundamental para la empresa conocer los beneficios de aumentar las velocidades de bajada de Internet para sus clientes. Uno de los beneficios clave es aumentar el valor de vida de los clientes en la empresa, ya que al contar con mejores velocidades, los clientes estarán más satisfechos con el servicio. Esto, a su vez, desembocará en el aumento de los ingresos de la empresa, al fortalecer la fidelidad de los clientes y generar oportunidades para el crecimiento del negocio.

Dentro de este escenario, la tecnología de fibra óptica se podria considerar como una buena solución a este tema. En la actualidad, la fibra óptica es considerada la tecnología más avanzada y eficiente para la transmisión de datos a alta velocidad. Su funcionamiento se basa en la transmisión de señales a través de hilos delgados de vidrio o plástico. Esto hace que la fibra óptica, hoy en dia, destaque por sobre otras tecnologias de Internet como los cables de cobre (ADSL) o Wireless (por satelite).


## KPIs

La finalidad de los siguientes indicadores clave de rendimiento (KPIs) es poder guiar a la empresa para que pueda lograr los resultados deseados y para que sea capaz de comprender dónde está actualmente posicionada y cómo puede mejorar su negocio.

   - 🔌 **Penetración de fibra óptica por provincia**: Este indicador muestra el porcentaje de conexiones de fibra óptica en relación con el total de conexiones en cada provincia. Gracias a esto, es posible distinguir aquellas provincias que tengan una buena infraestructura de fibra optica en su territorio.
   
   - ⚡**Velocidad promedio de descarga por provincia y trimestre**: Calcula la media de bajada en Mbps (megabits por segundo) para cada provincia y trimestre. Esto permite analizar la calidad de la conexión a Internet en cada provincia a lo largo del tiempo y detectar cambios en la velocidad de descarga.
   
   - 🏘️ **Porcentaje de crecimiento trimestral de la penetración de accesos a Internet por cada 100 hogares por provincia**: Este KPI permitira a la empresa identificar las provincias que están experimentando un mayor crecimiento en términos de adopción de Internet y tomar acciones específicas para impulsar aún más la penetración en esas regiones, o bien mejorar los recursos/servicios en las provincias con un porcentaje bajo de penetracion por cada 100 hogares.


## Conclusiones

El análisis realizado reveló importantes hallazgos sobre las ventas trimestrales de la empresa y su relación con la penetración de fibra óptica en distintas provincias. A través de visualizaciones gráficas, se pudo observar que a medida que las conexiones de fibra óptica aumentaban, las ventas trimestrales también experimentaban un incremento significativo. Esto muestra que la penetración de fibra óptica fue una de las principales causas de los aumentos en los ingresos de la empresa a partir del año 2019.

Al profundizar en las provincias, identifiqué aquellas que presentaban una sólida penetración de fibra óptica en su territorio, así como aquellas que requerían un mayor acceso a esta tecnología. Posteriormente, analice de estas ultimas, la media de bajada de Internet y observe que se encontraban considerablemente por debajo de la media. Este hallazgo resalta la necesidad de mejorar la infraestructura de fibra óptica en dichas provincias para impulsar el desarrollo y la calidad de las conexiones a Internet y asi brindar un mejor servicios a los clientes.

Además, al explorar los datos de accesos por cada 100 hogares por provincia, descubrí interesantes comparativas. Por ejemplo, en la provincia de Buenos Aires, donde se registra una penetración de fibra óptica del 30% y una media de bajada de aproximadamente 24 Mbps, se observó que solo 71 de cada 100 hogares tenían acceso a Internet. En contraste, en Tierra del Fuego, con una penetración de fibra óptica del 1% (un porcentaje demasiado bajo en comparativo con las demas provincias) y una media de bajada de 5,86 Mbps, encontré que un impresionante 85 de cada 100 hogares contaban con acceso a Internet. Con este dato, la empresa podria decidir si priorizar mayor los accesos en las provincias con una media baja de accesos por cada 100 hogares para expandir su clientela, o bien mejorar la calidad de los servicios a los antiguos clientes, como por ejemplo ampliando la infraestructura de fibra óptica para asi aumentar la media de bajada, es decir, la velocidad del internet.

Este informe destaca la relevancia de invertir en infraestructuras de fibra óptica al rededor del pais, sobre todo en las provincias con una media de bajada por debajo de 15 Mbps. Ademas, mejorar la conectividad y garantizar un acceso equitativo a Internet en todo el país. La empresa es capaz de tomar desiciones en base a estos analisis. 