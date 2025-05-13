# README - Proyecto de Análisis de Evasión de Clientes en Telecom X

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar los factores que influyen en la evasión de clientes (churn) en la empresa de telecomunicaciones Telecom X. Se realiza un proceso completo de ETL (Extracción, Transformación y Carga) y un análisis exploratorio de datos (EDA) para identificar patrones y tendencias que ayuden a comprender y mitigar la evasión de clientes.

## Estructura del Proyecto

El proyecto está organizado en un único notebook de Python con las siguientes secciones:

1. **Importación de Librerías**: Instalación y carga de todas las bibliotecas necesarias.
2. **Carga de Datos desde la API**: Extracción de datos en formato JSON desde la API proporcionada.
3. **Exploración Inicial de los Datos**: Análisis preliminar de la estructura y características de los datos.
4. **Diccionario de Datos**: Descripción detallada de cada variable y su significado.
5. **Verificación de Problemas en los Datos**: Identificación de valores nulos, duplicados y problemas de formato.
6. **Limpieza y Transformación de Datos**: Corrección de inconsistencias y preparación para el análisis.
7. **Creación de la columna "Cuentas_Diarias"**: Cálculo de valores diarios a partir de la facturación mensual.
8. **Estandarización y Transformación (Opcional)**: Conversión de variables categóricas a numéricas y traducción de nombres.
9. **Análisis Descriptivo**: Cálculo de estadísticas para comprender la distribución y comportamiento de los datos.
10. **Visualizaciones**: Gráficos para identificar patrones de evasión por diferentes variables.
11. **Análisis de Correlación (Extra)**: Estudio de la relación entre variables y su impacto en la evasión.
12. **Informe Final**: Resumen de hallazgos, conclusiones y recomendaciones estratégicas.

## Requisitos y Dependencias

Para ejecutar este proyecto, necesitarás las siguientes bibliotecas de Python:

```
pandas
numpy
matplotlib
seaborn
requests
```

Puedes instalar estas dependencias con el siguiente comando:

```bash
pip install pandas numpy matplotlib seaborn requests
```

## Uso del Proyecto

1. **Clonar el repositorio o descargar el notebook**:
   ```bash
   git clone <url-del-repositorio>
   ```

2. **Instalar las dependencias**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Ejecutar el notebook**:
   Abre el notebook en Jupyter, Google Colab o cualquier otro entorno compatible y ejecuta todas las celdas en orden secuencial.

## Datos Utilizados

Los datos se obtienen directamente de la API de Telecom X en formato JSON:
- URL de la API: https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/main/TelecomX_Data.json
 
El conjunto de datos contiene información sobre:
- Características demográficas de los clientes
- Servicios contratados
- Tipo de contrato
- Método de pago
- Cargos mensuales y totales
- Estado de evasión (churn)

## Resultados y Conclusiones

Los principales hallazgos del análisis incluyen:

1. El tipo de contrato es el factor más influyente en el churn, con contratos mensuales mostrando el mayor riesgo.
2. Los clientes con servicio de fibra óptica presentan mayor tendencia a la evasión.
3. El período inicial (primeros 12 meses) es crítico para la retención de clientes.
4. Los clientes con cargos mensuales más altos tienen mayor probabilidad de abandono.
5. La falta de servicios adicionales como seguridad en línea y soporte técnico está correlacionada con mayor churn.

El informe final incluye recomendaciones estratégicas detalladas para abordar estos factores y mejorar la retención de clientes.

## Autor

Mery Vega M. - Estudiante de Ciencia de Datos

