# Proyecto Análisis de Medallas Olímpicas

## Descripción

Este proyecto realiza un análisis exploratorio de datos (EDA) sobre un conjunto de datos de medallas olímpicas utilizando Pandas. El objetivo es analizar las medallas de oro, plata, bronce y el total obtenido por cada país en los Juegos Olímpicos.

## Objetivos

1. **Cargar los datos**: Importar los datos desde el archivo CSV a un DataFrame de Pandas
2. **Exploración inicial**: Utilizar métodos básicos para explorar el tamaño, las columnas y los tipos de datos del DataFrame
3. **Limpieza de datos**: Identificar y manejar valores faltantes o incorrectos, especialmente en las columnas de medallas donde los valores faltantes indican 0 medallas
4. **Análisis de Medallas de Oro por País**: Identificar los 3 países con más medallas de Oro en total
5. **Análisis de Medallas Totales por País**: Obtener un dataframe que contenga solo los países que ganaron más de 10 medallas en total

## Estructura del Proyecto

```
Proyecto medallas/
├── Proyecto.ipynb      # Notebook principal con el análisis
├── medallas.csv        # Dataset con información de medallas olímpicas
```

## Requisitos

- Python 3.7 o superior
- Jupyter Notebook o JupyterLab
- Pandas

## Uso

1. Abre el notebook `Proyecto.ipynb` en Jupyter Notebook o JupyterLab
2. Ejecuta las celdas en orden para realizar el análisis completo
3. Asegúrate de que el archivo `medallas.csv` esté en el mismo directorio que el notebook

## Estructura de Datos

El archivo `medallas.csv` contiene las siguientes columnas:

- **Oro**: Número de medallas de oro obtenidas
- **Plata**: Número de medallas de plata obtenidas
- **Bronce**: Número de medallas de bronce obtenidas
- **Total**: Total de medallas obtenidas
- **Pais**: Nombre del país

## Análisis Realizado

El notebook incluye:

- Carga y visualización inicial de los datos
- Exploración de la estructura del dataset (shape, info, columnas)
- Identificación de valores faltantes
- Limpieza de datos (reemplazo de valores nulos por 0)
- Conversión de tipos de datos
- Identificación de los top 3 países por medallas de oro
- Filtrado de países con más de 10 medallas totales

## Resultados Principales

El análisis identifica:
- Los 3 países con más medallas de oro
- Los países que obtuvieron más de 10 medallas en total

## Autor

Proyecto de análisis de datos olímpicos.

