# Proyecto de análisis de clientes y restaurantes en Estados Unidos

## Descripción

Este proyecto tiene como objetivo realizar un proceso completo de limpieza, exploración y análisis de una base de datos de clientes de restaurantes en Estados Unidos. El dataset original contenía 30.000 filas y 17columnas, con un alto porcentaje de datos nulos y negativos en varias columnas. Se realizaron diversas etapas de limpieza de datos, análisis estadístico y aplicación de técnicas de machine learning , se desarrollaron visualizaciones y un documento con las recomendaciones principales.

El proyecto fue desarrollado utilizando Python y librerías especializadas para análisis de datos y visualización.

## Objetivos

- Limpiar y preparar los datos para su análisis.
- Identificar patrones de consumo de los clientes.
- Analizar el comportamiento de gasto en restaurantes.
- Estudiar diferencias entre ciudades y segmentos de clientes.
- Integrar información externa proveniente de Yelp.
- Generar recomendaciones de negocio basadas en evidencia.

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Requests
- Jupyter Notebook
- Seaborn

## Proceso de limpieza de datos

Se realizaron las siguientes actividades:

- Corrección de edades negativas o superiores a 120 años.
- Reemplazo de valores faltantes utilizando medianas.
- Eliminación de espacios en blanco en variables de texto.
- Corrección de valores negativos en frecuencia de visita.
- Normalización de números telefónicos.
- Tratamiento de registros sin correo electrónico.
- Validación de tipos de datos.

## Análisis realizados

- Cantidad de personas por ciudad.
- Distribución de clientes por estrato socioeconómico.
- Gasto promedio en restaurantes por ciudad.
- Relación entre frecuencia de visita y gasto promedio.
- Relación entre ingresos mensuales y gasto promedio.
- Preferencias alimenticias de los clientes.
- Perfil de los clientes de mayor gasto.
- Análisis de membresías premium.
- Relación entre consumo de alcohol y edad.
- Integración de información proveniente de Yelp.

## Archivos utilizados

### base_datos_restaurantes_USA_v2.csv

Archivo principal del proyecto que contiene la información de los clientes de restaurantes en Estados Unidos. Incluye variables demográficas, económicas y de comportamiento de consumo, tales como:

- Nombre y apellido.
- Edad y género.
- Ciudad de residencia.
- Estrato socioeconómico.
- Ingresos mensuales.
- Frecuencia de visita a restaurantes.
- Gasto promedio en comida.
- Preferencias alimenticias.
- Consumo de alcohol.
- Tipo de pago más utilizado.
- Estado de membresía premium.
- Información de contacto.

Este archivo fue sometido a un proceso de limpieza, validación y transformación para garantizar la calidad de los análisis realizados.

### yelp_restaurants.csv

Archivo generado a partir de consultas realizadas a la API de Yelp. Contiene información real de restaurantes ubicados en diferentes ciudades de Estados Unidos, utilizada para complementar el análisis interno de clientes.

Las principales variables incluidas son:

- ID del restaurante.
- Nombre del restaurante.
- Categoría gastronómica principal.
- Calificación promedio.
- Número de reseñas.
- Ciudad.
- Nivel de precios.

Este conjunto de datos permitió realizar análisis comparativos del mercado, identificar categorías populares y detectar oportunidades de alianzas con restaurantes altamente valorados.

## Integración con Yelp

Se consultó la API de Yelp para obtener información real de restaurantes.

Los datos extraídos incluyen:

- Nombre del restaurante
- Categoría principal
- Precio
- Calificación
- Número de reseñas
- Ciudad

Esta información permite complementar el análisis interno de clientes con información del mercado real.

## Principales hallazgos

- Existen diferencias significativas en el gasto promedio entre ciudades.
- Las preferencias alimenticias varían según la ubicación geográfica.
- Los clientes con mayores ingresos tienden a presentar mayores niveles de gasto.
- Las membresías premium muestran comportamientos diferentes según la ciudad.
- La información de Yelp permite identificar oportunidades de alianzas estratégicas.

## Propuestas de segmentación

### Segmento 1: Clientes de alto gasto

Características:

- Alto gasto promedio
- Visitas frecuentes
- Ingresos elevados

Estrategia:

- Programas exclusivos
- Beneficios premium
- Recompensas por fidelidad

### Segmento 2: Clientes frecuentes

Características:

- Alta frecuencia de visita
- Gasto medio o alto

Estrategia:

- Descuentos recurrentes
- Acumulación de puntos

### Segmento 3: Clientes según preferencias alimenticias

Características:

- Vegetarianos
- Veganos
- Consumidores de carnes
- Consumidores de mariscos

Estrategia:

- Promociones personalizadas
- Alianzas con restaurantes especializados

### Segmento 4: Clientes premium

Características:

- Membresía activa

Estrategia:

- Beneficios exclusivos
- Eventos especiales
- Promociones diferenciadas

## Conclusión

Este proyecto permitió desarrollar un proceso integral de análisis de datos, abarcando desde la limpieza y preparación de la información hasta la generación de visualizaciones y hallazgos de negocio. A partir del estudio de más de 30.000 registros de clientes, fue posible identificar patrones de consumo, diferencias entre ciudades, comportamientos asociados al gasto y oportunidades de segmentación de clientes.

La integración de datos externos provenientes de Yelp enriqueció el análisis al proporcionar información real del mercado gastronómico, permitiendo contrastar el comportamiento de los clientes con las características de los restaurantes disponibles en cada ciudad.
