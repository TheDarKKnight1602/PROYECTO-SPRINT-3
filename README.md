# PROYECTO-SPRINT-3

# Análisis del Comportamiento de Usuarios por Ciudad y Día de la Semana

Este proyecto tiene como objetivo probar la hipótesis de que la actividad de los usuarios de una plataforma de música en línea varía según el día de la semana y la ciudad en la que se encuentren (Springfield y Shelbyville).

## 🎯 Objetivo

Probar la siguiente hipótesis:

> La actividad de los usuarios y las usuarias difiere según el día de la semana y dependiendo de la ciudad.

## 📁 Estructura del Proyecto

El análisis se divide en tres etapas:

1. **Descripción de los datos:** Exploración inicial del conjunto de datos, incluyendo revisión de columnas, tipos de datos y valores nulos.
2. **Preprocesamiento:** Limpieza de encabezados, tratamiento de valores ausentes y duplicados, y normalización de categorías (por ejemplo, géneros musicales).
3. **Prueba de hipótesis:** Agrupación de datos por ciudad y día para comparar la cantidad de canciones reproducidas y evaluar diferencias en el comportamiento del usuario.

## 🧪 Dataset

- Nombre: `music_project_en.csv`
- Ubicación esperada: `/datasets/music_project_en.csv`
- Columnas:
  - `user_id`: identificador del usuario
  - `track`: título de la canción
  - `artist`: nombre del artista
  - `genre`: género musical
  - `city`: ciudad del usuario
  - `time`: hora exacta de reproducción
  - `day`: día de la semana

## 🛠️ Tecnologías y Librerías

- Python 3.x
- Pandas

