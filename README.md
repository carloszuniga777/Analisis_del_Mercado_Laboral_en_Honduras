# Estudio del Mercado Laboral en Honduras (2012 - 2025)

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white) ![RStudio](https://img.shields.io/badge/RStudio-75AADB?style=for-the-badge&logo=rstudio&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![Versión](https://img.shields.io/badge/Versión-1.0.0-brightgreen?style=for-the-badge) ![Licencia](https://img.shields.io/badge/Licencia-MIT-blue?style=for-the-badge)

## 1. 📘 Introducción

El mercado laboral constituye uno de los principales termómetros del desarrollo económico y social de un país. En el caso de Honduras, su comportamiento ha estado marcado por transformaciones demográficas, choques económicos recurrentes y brechas estructurales persistentes que afectan de manera desigual a distintos grupos de la población.

Este proyecto desarrolla un análisis integral del mercado laboral hondureño a partir de datos oficiales, con el objetivo de comprender su evolución en el período 2012–2025 y evaluar la relación entre el crecimiento del potencial humano y la capacidad real del mercado para absorberlo. El estudio se apoya en dos conceptos centrales —la Población en Edad de Trabajar (PET) y la Población Económicamente Activa (PEA)— como ejes analíticos para examinar la dinámica del empleo, el desempleo y la participación laboral.

El análisis incorpora una perspectiva demográfica desagregada por género y grupos etarios, lo que permite identificar patrones diferenciados, brechas persistentes y rupturas estructurales asociadas tanto a cambios metodológicos como a eventos económicos recientes, como la pandemia de COVID-19 y los desastres naturales ETA e IOTA. A lo largo del proyecto, los datos son transformados en indicadores comparables y visualizaciones analíticas que facilitan la interpretación de tendencias de largo plazo y la generación de insights accionables.

En conjunto, este estudio busca ofrecer una base analítica sólida para la comprensión del mercado laboral hondureño, sirviendo como insumo para la toma de decisiones, el diseño de políticas públicas y el desarrollo de análisis más profundos sobre la calidad y sostenibilidad del empleo en el país.

------------------------------------------------------------------------

## 2. 🔗 Enlaces del proyecto

-   ¡Echa un vistazo al proyecto en Kaggle! [Ver proyecto en Kaggle](https://www.kaggle.com/code/carloszuniga7/estudio-del-mercado-laboral-en-honduras#An%C3%A1lisis-de-la-din%C3%A1mica-laboral:-participaci%C3%B3n,-ocupaci%C3%B3n-y-desempleo).

-   ¡Echa un vistazo al proyecto en Power Bi! [Ver proyecto en Power Bi](https://app.powerbi.com/view?r=eyJrIjoiNGRlMWY3YjAtOWFjYS00MmEzLThkZDAtMzZhOGY3NWZkMzcyIiwidCI6ImUxMTlmY2ZmLTRmMzUtNDMzOC04MzQzLTc2ZDQ1OTg5NGI2YiIsImMiOjR9).

------------------------------------------------------------------------

## 3. 🧭 Metodología

Este proyecto adopta un enfoque de análisis de datos estructurado y sistemático, fundamentado en la toma de decisiones basadas en datos. Por ello, se seguirá un proceso metodológico compuesto por seis etapas claves:

1.  **Formular** preguntas y definición del problema.

2.  **Preparar** los datos recopilados mediante su recopilación y almacenamiento.

3.  **Procesamiento** de la información a través de la limpieza y validación de datos.

4.  **Análisis** orientado a identificar patrones, relaciones y tendencias .

5.  **Compartir** y comunicar los hallazgos a públicos relevantes.

6.  **Actuar** sobre los datos y utilice los resultados del análisis para apoyar la toma de decisiones

------------------------------------------------------------------------

## 4. ❓ Definición del Proyecto (Preguntar)

### 4.1. Objetivo del análisis

#### 4.1.1. General

-   El objetivo del presente caso de estudio es analizar la evolución del desempleo en Honduras entre 2012 y 2025, identificando patrones por grupo etario y género, así como rupturas estructurales asociadas a choques económicos recientes.

#### 4.1.2. Específicos

-   Identificar tendencias por género y edad.

-   Detectar grupos vulnerables con mayor tasa de desempleo.

-   Proponer KPIs para seguimiento en el dashboard.

-   dentificar brechas de género persistentes

-   Analizar el impacto que tuvieron el COVID-19 y los desastres naturales ETA y IOTA en Honduras sobre el empleo.

## 5. 🗂️ Datos Utilizados (Preparar)

La información es suministrada directamente del Instituto Nacional de Estadística (INE) en Honduras de los períodos de 2012 hasta 2023 y la Encuesta Permanente de Hogares de Propósitos Múltiples (EPHPM) en el periodo de 2024 hasta 2025

Se construyo dos dataset en formato dimensional con el objetivo de poder hacer el análisis estadístico en R. Para ello, fue necesario consolidad la información proveniente de distintas tablas oficiales, lo que permitió estructurar el análisis en dos niveles:

-   Edad

-   Género

## 6. 🧹 Limpieza y Procesamiento (Procesar)

La etapa de limpieza y procesamiento de datos inició con un análisis exploratorio de datos (EDA), cuyo objetivo fue examinar la distribución de las variables y validar la consistencia del conjunto de datos. En esta fase se identificaron posibles problemas de calidad, como valores faltantes, registros duplicados e inconsistencias en la información.

Posteriormente, se llevó a cabo el proceso de depuración de los datos utilizando el lenguaje R. Este procedimiento incluyó la eliminación de espacios en blanco innecesarios en las cadenas de texto, así como el redondeo de valores numéricos, con el fin de garantizar uniformidad y precisión en las variables cuantitativas.

Finalmente, los registros fueron reorganizados mediante la reclasificación de los grupos de edad en categorías definidas, lo que permitió estructurar la información de manera más analítica y facilitar su interpretación en las etapas posteriores del análisis.

## 7. 📊 Análisis orientado a la identificación de patrones, relaciones y tendencias (Analizar)

La etapa de análisis se enfocó en transformar los datos procesados en información interpretable, con el objetivo de identificar patrones persistentes, relaciones relevantes y tendencias temporales que permitan comprender la dinámica del mercado laboral en Honduras.

Para ello, los datos fueron organizados de manera estructurada por año, grupo etario y sexo, priorizando un enfoque longitudinal que facilitara la comparación interanual y la detección de rupturas estructurales. El uso de indicadores relativos —como la tasa de actividad, ocupación y desempleo— permitió analizar la evolución del mercado laboral más allá del crecimiento poblacional, asegurando comparabilidad entre períodos y grupos con distintos tamaños demográficos.

Durante el análisis emergieron hallazgos relevantes que desafiaron supuestos iniciales. Uno de los más significativos se observa a partir de 2017, año en el que se registra un aumento abrupto de la población en edad de trabajar. Este cambio no responde a un crecimiento demográfico real, sino a una ampliación sustancial de la cobertura estadística del Instituto Nacional de Estadística. Al incorporar poblaciones previamente no captadas —principalmente inactivas—, se evidenció una caída en la tasa de actividad que no representa una contracción económica, sino una corrección en la medición del mercado laboral.

El análisis temporal permitió identificar tendencias estructurales claras. A pesar del crecimiento sostenido de la población en edad de trabajar, la población económicamente activa muestra un estancamiento relativo, revelando una brecha persistente entre el potencial laboral del país y su capacidad de absorción efectiva. Esta divergencia sugiere limitaciones estructurales del mercado para integrar a nuevos participantes, particularmente jóvenes, mujeres y adultos mayores.

Asimismo, el análisis reveló relaciones asimétricas entre los distintos indicadores durante períodos de crisis. En 2020, la pandemia de COVID-19 y los desastres naturales ETA e IOTA alteraron el comportamiento habitual del mercado laboral: mientras el desempleo se incrementó de forma abrupta, la tasa de actividad también aumentó, reflejando un fenómeno de “trabajador adicional”, donde personas previamente inactivas ingresaron al mercado ante la pérdida de ingresos en los hogares. Este comportamiento evidencia la vulnerabilidad de amplios segmentos de la población y la fragilidad de los mecanismos de protección económica.

La desagregación por edad y género permitió identificar brechas estructurales persistentes. Los adultos entre 30 y 44 años concentran los indicadores más estables y favorables del mercado laboral, funcionando como el núcleo productivo del país. En contraste, los jóvenes enfrentan mayores barreras de inserción, con tasas de desempleo sistemáticamente superiores, mientras que la participación femenina se mantiene significativamente por debajo de la masculina, incluso en períodos de recuperación económica.

En conjunto, estos hallazgos permiten concluir que el mercado laboral hondureño presenta un crecimiento desigual, con una capacidad limitada para integrar de manera equitativa a su población en edad productiva. El análisis aporta evidencia clave para responder a la pregunta central del estudio: si bien el potencial humano del país continúa expandiéndose, las oportunidades laborales no crecen al mismo ritmo ni se distribuyen de forma homogénea, lo que plantea desafíos relevantes para la sostenibilidad del empleo y el diseño de políticas públicas orientadas a la inclusión laboral.

### 7.1. PEA y PET

Para entender el mercado laboral en Honduras, es fundamental diferencias entre dos conceptos: • PET (Población en Edad de Trabajar): Es el universo total de personas que, por su edad, el Estado considera aptas para trabajar (en Honduras, generalmente a partir de los 10 o 15 años, dependiendo de la medición). Es el potencial humano máximo del país. • PEA (Población Económicamente Activa): Es un subconjunto de la PET. Son las personas que están dentro del mercado laboral, ya sea porque tienen un empleo (Ocupados) o porque no lo tienen pero lo están buscando activamente (Desocupados). En resumen: La PET es "quiénes podrían trabajar" y la PEA es "quiénes quieren o están trabajando". La diferencia entre ambas son los Inactivos (estudiantes, amas de casa, jubilados o personas que no buscan empleo).

### 7.2. Variables clave

| Variable      | Descripción                     |
|---------------|---------------------------------|
| Año           | Año de la encuesta              |
| Grupo de edad | Rangos etarios                  |
| Sexo          | Hombre / Mujer                  |
| PET           | Población en Edad de Trabajar   |
| PEA           | Población Económicamente Activa |
| Ocupados      | Personas con empleo             |
| Desocupados   | Personas sin empleo             |

### 7.3. Métricas Claves:

| Métrica | Fórmula | Interpretación |
|----|----|----|
| Tasa de desempleo | Desocupados / PEA | \% de personas activas sin empleo |
| Tasa de ocupación | Ocupados / PET | \% de población en edad de trabajar con empleo |
| Tasa de actividad | PEA / PET | \% de población en edad de trabajar que participa en el mercado laboral |

## 8. 📣 Compartir

La etapa de Compartir se centra en la comunicación efectiva de los hallazgos obtenidos durante el análisis de datos. En esta fase, los resultados son transformados en visualizaciones claras, coherentes y visualmente pulidas, con el propósito de facilitar su comprensión y apoyar la toma de decisiones informadas.

Para guiar este proceso, se evaluó si el análisis permitió responder de manera directa a la pregunta empresarial planteada, así como la historia que los datos revelan y su relación con el objetivo original del estudio. Asimismo, se tuvo en cuenta el perfil de la audiencia, asegurando que el nivel de detalle, el lenguaje visual y la narrativa fueran adecuados para los usuarios finales del análisis.

Las visualizaciones fueron diseñadas para comunicar los hallazgos de forma intuitiva, destacando patrones, tendencias y comparaciones relevantes del mercado laboral. Se priorizó la selección del formato más adecuado para cada tipo de información, con el fin de maximizar la claridad y el impacto del mensaje.

Finalmente, se consideraron criterios de accesibilidad en la presentación, como el uso de colores legibles, etiquetas claras y estructuras visuales comprensibles, garantizando que la información pueda ser interpretada correctamente por una audiencia diversa. El entregable de esta etapa consiste en un conjunto de visualizaciones de apoyo que sintetizan los hallazgos clave del análisis, sirviendo como puente entre los resultados técnicos y su aplicación práctica en el contexto del proyecto.

## 9. 🎯 Actuar

La etapa de Actuar consolida los resultados del análisis y los traduce en conclusiones accionables, alineadas con el alcance real del estudio y con las oportunidades de profundización futura. A partir de los hallazgos obtenidos, se confirma que el análisis permitió comprender el comportamiento del mercado laboral hondureño desde una perspectiva general, así como su dinámica desagregada por género y por grupos etarios, identificando patrones relevantes, brechas persistentes y tendencias estructurales a lo largo del tiempo.

**Conclusión**.

El estudio evidencia que el mercado laboral en Honduras presenta dinámicas diferenciadas según el género y la edad, lo que refleja desigualdades estructurales en la participación, el acceso al empleo y la estabilidad laboral. Si bien el análisis ofrece una visión clara y consistente de estas dimensiones, sus conclusiones deben interpretarse dentro del marco de un enfoque demográfico agregado, el cual resulta adecuado para diagnósticos generales, pero insuficiente para evaluar la calidad del empleo o las condiciones laborales en profundidad.

Los insights generados pueden ser utilizados por tomadores de decisión para evaluar la evolución del empleo, la participación laboral y las brechas existentes entre distintos segmentos de la población. Estos resultados constituyen una base analítica sólida para estudios exploratorios, formulación de hipótesis y diseño preliminar de políticas públicas o investigaciones sectoriales.

No obstante, el estudio presenta delimitaciones claras que condicionan el alcance de sus aplicaciones. El análisis se limita a variables demográficas básicas y no incorpora factores estructurales clave, como el nivel educativo, la profesión u ocupación, ni el tipo de empleo —formal, informal o precario—, lo que restringe la capacidad de analizar la calidad del empleo, la adecuación entre formación y ocupación, y los niveles de vulnerabilidad laboral.

En consecuencia, los próximos pasos del proyecto apuntan a ampliar el marco analítico mediante la integración de nuevas variables y fuentes de información. La incorporación de dimensiones educativas, ocupacionales y contractuales permitiría profundizar en la segmentación del mercado laboral, identificar brechas más complejas y generar insights de mayor valor estratégico.

Como parte de esta etapa, los resultados han sido integrados en un portafolio profesional que incluye el estudio de caso completo y sus visualizaciones principales, acompañado de una narrativa clara orientada a la comunicación efectiva de los hallazgos. Asimismo, se contempla la preparación y práctica de la presentación de resultados, con el objetivo de adaptar el mensaje a distintas audiencias y contextos de uso.

El entregable final de esta fase comprende un conjunto de insights de alto nivel, junto con una lista estructurada de análisis adicionales que orientan futuras líneas de exploración y fortalecen la proyección analítica del proyecto.

------------------------------------------------------------------------

## 10. 🚀 Posibles mejoras futuras

-   Incorporar variables de nivel educativo.
-   Analizar la profesión u ocupación.
-   Diferenciar tipos de empleo (formal, informal y precario).
-   Evaluar la calidad y estabilidad del empleo.
-   Integrar nuevas fuentes de datos complementarias.

------------------------------------------------------------------------

## 11. 🛠️Tecnologías utilizadas

-   **R:** Lenguaje de programación.
-   **RStudio:** Entorno de desarrollo para R.
-   **Power BI:** Entorno de desarrollo de dashboards.

------------------------------------------------------------------------

## 📂 Uso del repositorio

Repositorio:\
<https://github.com/carloszuniga777/Analisis_del_Mercado_Laboral_en_Honduras/tree/main>

1.  Clonar el repostorio:

    ``` bash
    git clone https://github.com/carloszuniga777/Analisis_del_Mercado_Laboral_en_Honduras.git
    ```

2.  **Abrir los scripts en RStudio.**

3.  Ejecutar el análisis siguiendo el flujo definido en el archivo `.R`.

4.  Explorar el dashboard interactivo desarrollado en Power BI para la visualización de los resultados

------------------------------------------------------------------------

## 📜 Licencia

Este proyecto utiliza la [Licencia MIT](https://opensource.org/licenses/MIT), la cual permite su uso, modificación y distribución con fines académicos y profesionales, siempre que se otorgue el debido crédito al autor.
