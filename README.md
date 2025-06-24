# CHALENGE 2 - TELECOM_X

## El objetivo principal de este proyecto fue analizar los factores que influyen en la evasión de clientes en Telecom X, con el fin de entender los patrones de comportamiento que llevan a los usuarios a cancelar el servicio.

A través de la limpieza, tratamiento y análisis exploratorio de los datos proporcionados por la empresa, se buscó:

  * Detectar perfiles de alto riesgo de abandono.

  * Identificar variables clave como tipo de contrato, método de pago, edad, género y gasto total que afectan la retención.

  * Visualizar tendencias y relaciones entre variables para fundamentar la toma de decisiones.

  * Entregar recomendaciones estratégicas basadas en datos para reducir el churn y mejorar la fidelización de clientes.

Este trabajo sirvió como base para que el equipo de ciencia de datos pueda desarrollar modelos predictivos de churn y así anticipar posibles cancelaciones y optimizar las estrategias de retención en la compañía.

============================================================================================

⚙️ Funcionalidad del Proyecto
Este proyecto se estructuró siguiendo el enfoque ETL (Extracción, Transformación, Carga), complementado con análisis exploratorio e informes de resultados. A continuación, se describen las principales funcionalidades desarrolladas en cada etapa:

  1. Extracción de Datos (Extract)
      
      * Se trabajó con un archivo en formato JSON, proporcionado por Telecom X, que contenía información sobre clientes, servicios contratados, pagos, consumo, entre otros.
      * Se utilizó la biblioteca json de Python para leer y cargar los datos, y pandas para estructurarlos en un DataFrame.

  2. Transformación de Datos (Transform)

      * Limpieza de datos: se eliminaron columnas innecesarias, se trataron valores nulos, y se estandarizaron textos.
      * Conversión de tipos: fechas, números y categorías fueron transformados al formato correcto (datetime, float, category, etc.).
      * Desanidamiento y normalización: estructuras complejas del JSON fueron convertidas a columnas planas.
      * Enriquecimiento de datos: se generaron nuevas variables, como clasificación por edad, rangos de gasto, o tipo de contrato simplificado.
    
3. Carga de Datos (Load)

      * Una vez transformados, los datos fueron exportados como un archivo CSV limpio (clientes_limpios.csv), listo para su análisis y para ser usado por el equipo de ciencia de datos en modelos predictivos.

4. Análisis Exploratorio de Datos (EDA)

      * Se aplicó un análisis exploratorio exhaustivo para detectar patrones y relaciones entre variables, utilizando bibliotecas como matplotlib, seaborn y plotly.
      * Se identificaron factores de riesgo de evasión, como:
          * Tipo de contrato (mensual vs. largo plazo).
          * Método de pago (especialmente cheque electrónico).
          * Edad del cliente.
          * Nivel de gasto total.
      * Se generaron visualizaciones para facilitar la interpretación de los hallazgos.

5. Informe y Recomendaciones

      * Se elaboró un informe completo con los principales hallazgos, incluyendo:
          * Comparaciones entre grupos de clientes que abandonaron vs. los que se mantuvieron.
          * Tendencias según edad, género, método de pago y contrato.
          * Recomendaciones estratégicas basadas en datos para reducir el churn.
      * El informe sirve como base para la toma de decisiones y para alimentar futuros modelos predictivos.

============================================================================================

✅ Resumen Funcional del Proyecto

Este proyecto permitió a Telecom X:

  * Comprender mejor el comportamiento de sus clientes.
  * Identificar los principales factores de evasión.
  * Preparar los datos de forma estructurada para análisis avanzados.
  * Obtener recomendaciones prácticas para mejorar la retención y reducir el abandono de servicios.


