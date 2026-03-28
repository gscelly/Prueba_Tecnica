# Prueba Técnica Data Engineer

Este repositorio contiene la resolución de la prueba técnica para la posición de **Data Engineer**. La prueba consiste en el procesamiento, análisis y exportación de datos utilizando entornos de **SQL** y **Spark**.

## Contenido del Proyecto

El proyecto está dividido en dos secciones principales:

### 1. Sección SQL (SQLite)
Se trabajó con datos simulados de la Copa Mundial Qatar 2022.
* **Ejercicio 1:** Transformación de datos crudos para calcular la tabla de posiciones (Puntos, Goles a favor/contra y Gol Diferencia).
* **Ejercicio 2:** Determinación de cruces uniendo los resultados con sedes y horarios definidos.
* **Ejercicio 3:** Identificación de Equipos Élite utilizando lógica de quintiles (20% superior).

### 2. Sección PySpark
Procesamiento de de datos y cálculos geométricos.
* **Análisis de Jugadores:** Consolidación de rankings mundiales, creación de indicadores de eficiencia y marcas de mejores jugadores por país.
* **Análisis Geográfico (Centros de Madrid):** * Limpieza de datos.
    * Implementación de una **UDF (User Defined Function)** para calcular la **Distancia Euclidiana** entre centros educativos y el promedio geográfico de su titularidad.
    * Identificación del centro más cercano por cada grupo.

## Estructura de Entregables
* `Ejercicios_DEVSU.ipynb`: Notebook con el código completo y las evidencias de ejecución (outputs).
* `CENTROS_EDUCATIVOS_MADRID.json`: Dataset original utilizado para el análisis geográfico.
* `resultados_devsu.zip`: Archivo comprimido con los outputs generados:
    * `Nuevo_Ranking.json`
    * `centros_centricos.parquet`
    * `centros_centricos.json`
    * `centros_centricos.csv`

---
**Elaborado por:** Galo Celly Alvarado 
**Fecha:** Marzo 2026