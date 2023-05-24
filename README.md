# PROYECTO INDIVIDUAL N° 2

## Accidentes aéreos

![](https://fondosmil.com/fondo/31188.jpg)

![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/pandao/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)


# Introducción  
La historia de la aviación en cuanto a seguridad ha experimentado importantes cambios a lo largo de los últimos 120 años. A continuación, se presenta un resumen por etapas destacando hitos importantes:

Inicios hasta los años 1920:

1903: Los hermanos Wright realizan el primer vuelo controlado y motorizado en Kitty Hawk, Carolina del Norte, marcando el inicio de la aviación.
1912: El naufragio del Titanic lleva a la implementación de leyes de seguridad marítima, lo que a su vez impulsa mejoras en la seguridad de la aviación.
Hasta los años 1950:

1931: Se establece la International Civil Aviation Organization (ICAO), una agencia de la ONU encargada de promover la seguridad y la cooperación en la aviación civil internacional.
1944: Se crea la Convención sobre Aviación Civil Internacional (Convenio de Chicago), que establece estándares y regulaciones para la aviación civil a nivel mundial.
Hasta 1992:

1953: Se funda la International Air Transport Association (IATA), una organización que promueve la seguridad y la eficiencia en la industria de la aviación comercial.
1960: Se establece el Flight Data Recorder (FDR) o "caja negra", que registra datos de vuelo para su posterior análisis en caso de accidentes.
1970: Se implementa el concepto de Crew Resource Management (CRM), que enfatiza la comunicación y la toma de decisiones en equipo para mejorar la seguridad operacional.
1981: Se crea el Sistema de Información y Análisis de la Seguridad Operacional (SAFO) de la ICAO para recopilar y analizar datos sobre incidentes y accidentes aéreos.
Hasta la actualidad:

1992: Se establece la Organización de Aviación Civil Internacional (OACI), una agencia de la ONU que promueve la seguridad y la cooperación en la aviación civil a nivel mundial. Se adopta el Programa Universal de Auditoría de la Seguridad Operacional (USOAP) para evaluar y mejorar el cumplimiento de las normas de seguridad por parte de los Estados miembros.
2001: Los ataques del 11 de septiembre en Estados Unidos conducen a importantes mejoras en la seguridad de la aviación, incluyendo el refuerzo de las medidas de control de acceso y la implementación del programa de seguridad de la cabina reforzada.
Actualmente: Se continúan implementando mejoras en la seguridad operacional, como el uso de tecnologías avanzadas en sistemas de navegación y comunicación, mejoras en la capacitación del personal, inspecciones y mantenimiento rigurosos de aeronaves, y mayor enfoque en la gestión de riesgos.
A lo largo de la historia, la aviación ha experimentado avances significativos en materia de seguridad operacional. La implementación de regulaciones, la adopción de estándares internacionales, el desarrollo de tecnologías y la mejora en la gestión de riesgos han contribuido a reducir la incidencia de accidentes y garantizar la seguridad de los pasajeros y la tripulación. Sin embargo, es importante destacar que la seguridad operacional sigue siendo una prioridad constante en la industria de la

## **Informe de Análisis de Datos Aéreos**

Introducción: 
En este informe, se realiza un análisis exhaustivo de los datos aéreos recopilados, con el objetivo de obtener información relevante, identificar patrones, outliers y anomalías, y explorar las relaciones entre las variables. Se emplea Python como herramienta principal para el análisis de datos.

### 1.  Análisis Descriptivo:

####  1.1. Resumen Estadístico: 
El uso de un resumen estadístico en el análisis de datos de accidentes aéreos brinda una visión cuantitativa y objetiva de los eventos, lo que ayuda a los investigadores y profesionales de la aviación a comprender mejor la magnitud de los accidentes, identificar patrones relevantes y tomar decisiones informadas para mejorar la seguridad operacional.

#### 1.2. Distribución de Variables Numéricas:
La generación de histogramas y gráficos de densidad en el análisis de datos de accidentes aéreos es una herramienta efectiva para visualizar y comprender la distribución de variables numéricas clave. Estas representaciones gráficas ayudan a identificar asimetrías, determinar la forma de la distribución y proporcionar información valiosa para la toma de decisiones relacionadas con la seguridad operacional.

#### 1.3. Conteo de Variables Categóricas:
El conteo de variables categóricas y su visualización en gráficos de barras nos ayuda a identificar las categorías más frecuentes en los datos de accidentes aéreos. Esto nos proporciona información importante para comprender la prevalencia de ciertas compañías aéreas y tipos de aeronaves en los accidentes, lo que a su vez puede influir en las estrategias de mejora y prevención de la seguridad operacional.

### 2.  Análisis Bivariado:

#### 2.1. Correlación entre Variables Numéricas: 
 El cálculo de la matriz de correlación y su visualización mediante un heatmap nos permite identificar relaciones lineales entre variables numéricas y determinar si existe una correlación positiva o negativa. Esto nos ayuda a comprender mejor las interacciones entre las variables y a identificar posibles factores de riesgo o causas relacionadas en los accidentes aéreos.

#### 2.2. Relación entre Variables Categóricas y Numéricas:
 Al analizar la relación entre variables categóricas y numéricas, como el 'Operator' y 'Fatalities', a través de gráficos de barra o boxplot, podemos identificar posibles diferencias significativas en los resultados numéricos según las categorías categóricas. Esto nos ayuda a comprender mejor cómo ciertas variables categóricas pueden influir en los resultados y contribuir a la toma de decisiones relacionadas con la seguridad operacional y la mitigación de riesgos en la aviación.

### 3.  Identificación de Patrones:

#### 3.1. Análisis Temporal:
El análisis temporal utilizando gráficos de líneas o barras para variables como 'Year', 'Month', 'Day of Week', etc., nos permite identificar patrones estacionales, cambios a lo largo de los años y días de la semana con mayor incidencia de accidentes. Esto nos proporciona información valiosa para comprender las tendencias y tomar decisiones informadas en términos de seguridad operacional y prevención de accidentes en la aviación.



#### 3.2. Análisis Geográfico:
El análisis geográfico utilizando gráficos de dispersión o mapas nos permite visualizar la distribución geográfica de los accidentes aéreos y identificar áreas con mayor frecuencia de ocurrencia. Esto nos brinda información valiosa para analizar posibles factores relacionados con la ubicación y tomar medidas proactivas para mejorar la seguridad operacional en esas áreas o investigar las causas subyacentes de los accidentes.

## 4.  Detección de Outliers y Anomalías:

4.1. Boxplots y Diagramas de Dispersión: 
el uso de boxplots y diagramas de dispersión en el análisis de datos de accidentes aéreos nos permite identificar outliers y visualizar valores atípicos en variables numéricas. Esto nos ayuda a identificar posibles registros con datos incorrectos o inusuales, así como comprender mejor la distribución de los datos y detectar patrones o características inusuales que requieran una atención especial.

4.2. Z-Score y Análisis de Anomalías: 
El uso del z-score y el análisis de anomalías nos permite identificar valores numéricos que se desvían significativamente de la media de la distribución. Establecer un umbral nos ayuda a identificar posibles anomalías que requieren una revisión adicional para determinar su validez y tomar las acciones adecuadas. Esto contribuye a mejorar la calidad de los datos y la confiabilidad de los resultados del análisis.


## Comentario y conclusiones de las métricas:

País con la mayor cantidad de fatalidades: Esta métrica nos permite identificar el país con la mayor cantidad de víctimas fatales en accidentes aéreos. Es importante destacar que este dato puede variar dependiendo del período de tiempo y la base de datos utilizada. Al identificar el país con más fatalidades, se puede poner énfasis en mejorar la seguridad operacional y la prevención de accidentes en esa región.

![](C:/Users/JHONED/OneDrive/Escritorio/PI-2/Sin%20t%C3%ADtulo.png)

Número total de muertes y accidentes: Esta métrica proporciona una visión general de la magnitud de los accidentes aéreos en términos de fatalidades y la cantidad de eventos ocurridos. Permite evaluar el impacto global de los accidentes y comprender la escala de los desafíos de seguridad en la aviación.



Fechas con mayor cantidad de accidentes dentro del año: Esta métrica ayuda a identificar los períodos de tiempo específicos dentro de un año en los que se registran más accidentes aéreos. Puede revelar patrones estacionales o factores específicos que contribuyen a una mayor incidencia de accidentes en ciertas fechas. Esto es valioso para la planificación de medidas de seguridad y la asignación de recursos durante períodos críticos.



Ubicación de los accidentes: Esta métrica nos brinda información sobre la distribución geográfica de los accidentes aéreos. Al visualizar la ubicación de los accidentes en un mapa, podemos identificar áreas con mayor concentración de eventos y analizar posibles factores relacionados con la ubicación, como condiciones geográficas, infraestructura aeroportuaria, entre otros. Esto puede ayudar en la implementación de medidas específicas de seguridad en áreas de mayor riesgo.



Promedio de accidentes por país: Esta métrica nos permite calcular el promedio de accidentes aéreos por país. Es útil para comparar la frecuencia de los accidentes entre diferentes países y evaluar el desempeño en términos de seguridad operacional. Los países con un promedio más alto pueden requerir una atención especial en términos de mejoras en la seguridad y la implementación de regulaciones más estrictas.



Tasa de supervivencia de los accidentes de avión: Esta métrica indica el porcentaje de personas que sobreviven a los accidentes de avión. Permite evaluar la eficacia de los procedimientos de evacuación, la calidad del entrenamiento del personal de cabina y la efectividad de las medidas de seguridad implementadas en las aeronaves. Una alta tasa de supervivencia es un indicador de la eficiencia de las prácticas de seguridad y puede sugerir áreas donde se pueden realizar mejoras.


## Recomendaciones:

-   Con base en el análisis realizado, se recomienda continuar mejorando las medidas de seguridad en la aviación, especialmente en operaciones militares y de carga, donde se registran altas fatalidades.
-   Es importante realizar un seguimiento continuo de los patrones temporales y geográficos de los accidentes aéreos para identificar áreas de mayor riesgo y tomar medidas preventivas adecuadas.
-   Se sugiere realizar un análisis más detallado de las causas de los accidentes aéreos, investigando factores como el mantenimiento de las aeronaves, la capacitación de los pilotos y el cumplimiento de los protocolos de seguridad.

## Limitaciones:

-   Es importante tener en cuenta que este análisis se basa en los datos disponibles y en las suposiciones realizadas. Puede haber limitaciones en la calidad y la integridad de los datos recopilados, lo cual puede afectar los resultados obtenidos.
-   Algunas variables importantes pueden no estar presentes en el conjunto de datos o pueden tener valores faltantes, lo que puede limitar la capacidad de análisis en ciertos aspectos.
-   Este informe se centra principalmente en el análisis descriptivo y exploratorio de los datos. Para realizar análisis más profundos y obtener conclusiones más sólidas, pueden ser necesarios enfoques y técnicas adicionales.

En resumen, este informe ha proporcionado un análisis detallado de los datos aéreos, identificando patrones, outliers y anomalías, y explorando las relaciones entre variables. Los hallazgos y recomendaciones pueden ser utilizados para mejorar la seguridad en la aviación y prevenir accidentes aéreos en el futuro. Es importante tener en cuenta las limitaciones y considerar análisis adicionales para obtener una comprensión más completa de los datos.

