# Proyecto Data Analytics

## Introducción

En la actualidad, las telecomunicaciones han evolucionado para convertirse en uno de los pilares fundamentales de la sociedad moderna. Desde la transmisión de información a través de medios electrónicos como la telefonía y la televisión hasta el intercambio de datos en tiempo real a través del internet, estos servicios son esenciales para la vida diaria. Particularmente, el internet ha permitido que personas y organizaciones de todo el mundo se mantengan conectadas, impulsando cambios significativos en la forma en que trabajamos, nos comunicamos y consumimos información.

En Argentina, el sector de las telecomunicaciones ha experimentado un crecimiento notable, colocándose a la vanguardia en América Latina con más de 62 millones de conexiones para 2020. Este crecimiento ha sido crucial para mantener a la sociedad argentina conectada, especialmente durante situaciones críticas como la pandemia global, que incrementó la dependencia en servicios de comunicación continua.

Mi rol en este proyecto es el de Analista de Datos para una empresa ficticia del sector telecomunicaciones, con el objetivo de realizar un análisis detallado del comportamiento del mercado nacional. La principal área de interés es el acceso a internet, pero también se abordarán otros servicios de comunicación para proporcionar una visión integral que permita identificar oportunidades de mejora y crecimiento, optimizando la calidad del servicio y ajustando las estrategias comerciales de la empresa.

## Descripción

En este proyecto, asumí el rol de Analista de Datos para colaborar con la empresa ENACOM en un contexto ficticio. Mi tarea consistió en llevar a cabo un análisis exhaustivo para identificar tendencias en la evolución del acceso a internet en Argentina durante la última década. Adicionalmente, se realizaron análisis para descubrir patrones ocultos en los datos y se crearon visualizaciones que faciliten la comprensión de los mismos. Este trabajo busca ayudar a ENACOM a tomar decisiones estratégicas bien fundamentadas, aprovechando las oportunidades del mercado y mejorando la promoción de sus servicios.

## Tabla de Contenido

1. [Introducción](#Introducción)
2. [Descripción](#Descripción)
3. [KPI](#KPI)
4. [Análisis de Datos](#Análisis-de-Datos)
5. [Autores](#Autores)

## KPI

Durante el desarrollo del dashboard en Power BI, se definieron dos KPI principales para medir el rendimiento y establecer objetivos de crecimiento:

- **Incremento del 2% en el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia.**

  La fórmula empleada para calcular este KPI es:
  \[
  KPI = \frac{(\text{Nuevo acceso} - \text{Acceso actual})}{\text{Acceso actual}} \times 100
  \]
  Aquí, "Nuevo_acceso" representa el número de hogares con acceso a Internet previsto para el próximo trimestre, y "Accesos_Totales_Porcentaje_2023" corresponde al acceso actual.

- **Incremento del 4.2% en el acceso al servicio de internet para el próximo trimestre, cada 100 individuos, por provincia.**

  En este caso:
  - "Nuevos_ingresos" se refiere al número de individuos con acceso a Internet tras el próximo trimestre.
  - "Acceso_cada_100_hab_2023" representa el acceso actual por cada 100 habitantes.

## Análisis de Datos

### Acceso por la Tecnología de Conexión ADSL
![Acceso a la tecnología](Imagenes/Accesos_tecnologia.png)

**Conclusiones:**

1. **Distribución de ADSL_LOG:** 
   La distribución presenta una alta concentración en valores bajos (cerca de 11), con algunos valores atípicos en el extremo superior, lo que indica posibles outliers que pueden influir en el análisis estadístico.

2. **Visualización con Gráfico de Violín:** 
   Confirma la distribución asimétrica, mostrando una densidad significativa en los valores bajos y una dispersión notable hacia valores más altos.

3. **Rango de Valores:** 
   La mayoría de los valores se encuentran entre 0 y 6, con un pequeño grupo alcanzando hasta 12, lo que sugiere una distribución sesgada hacia valores más bajos.

**Resumen:** La variable ADSL_LOG muestra una distribución asimétrica con una concentración de valores bajos y algunos outliers en el extremo superior.

### Acceso por Cada 100 Individuos
![Accesos por cada 100 hogares](Imagenes/Evolucion_Acceso_cada_100_Habitantes.png)

**Conclusiones del Análisis de los Gráficos de Accesos por Trimestre:**

1. **Crecimiento Continuo:** 
   A lo largo de los trimestres, se observa un aumento constante en el porcentaje de accesos por cada 100 habitantes, reflejando un crecimiento sostenido en la conectividad.

2. **Consistencia entre Trimestres:** 
   La tendencia ascendente es consistente en todos los trimestres, lo que sugiere que no hay diferencias significativas en el crecimiento del acceso a internet entre los distintos periodos del año.

3. **Impacto de la Pandemia:** 
   Entre 2020 y 2021, se observa un incremento notable, probablemente impulsado por la pandemia de COVID-19 y la necesidad de teletrabajo y educación a distancia.

4. **Punto Máximo en 2023:** 
   El año 2023 muestra el valor más alto en cada trimestre, alcanzando un 0.24% de accesos por cada 100 habitantes.

**Resumen:** El análisis evidencia un crecimiento uniforme y sostenido en el acceso a internet, con un pico notable durante la pandemia y un crecimiento continuo hasta 2023.

### Porcentaje de Acceso por Cada 100 Hogares
![Boxplot](Imagenes/Porcen_Accesos_cda_100_hogares.png)

**Conclusiones:**

1. **Disparidades entre Provincias:** 
   Existen diferencias significativas en el acceso a internet entre las distintas provincias, con algunas mostrando una conectividad mucho mayor que otras.

2. **Provincias Destacadas:** 
   Buenos Aires y Córdoba tienen las medianas más altas, indicando un mejor acceso, mientras que Formosa y Santiago del Estero presentan menores niveles de conectividad.

3. **Outliers:** 
   Se observan valores atípicos en algunas provincias, lo que puede indicar áreas con conectividad excepcionalmente alta o baja en comparación con la tendencia general.

**Resumen:** El análisis de la distribución del acceso a internet por provincia revela una significativa variabilidad, destacando tanto disparidades regionales como la presencia de outliers que pueden necesitar atención especial.

## Autores

Este proyecto fue realizado por **Tomas Feiertag**.