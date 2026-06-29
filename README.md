# Trabajo-Practico-Integrador-de-Programaci-n-1
# Gestión de Datos de Países en Python

## Trabajo Práctico Integrador - Programación 1

### Integrantes

* Bautista Mariani
* Bruno Gatti

## Descripción del Proyecto

Este proyecto consiste en el desarrollo de una aplicación en Python que permite gestionar información de países almacenada en un archivo CSV.

El sistema fue desarrollado como Trabajo Práctico Integrador de la materia Programación 1, aplicando los conceptos estudiados durante la cursada, tales como listas, diccionarios, funciones, estructuras condicionales y repetitivas, lectura y escritura de archivos CSV, ordenamientos y estadísticas.

La aplicación permite agregar, actualizar, buscar, filtrar y ordenar información sobre distintos países, además de generar estadísticas generales a partir de los datos almacenados.

## Estructura de Datos Utilizada

Cada país se almacena como un diccionario con los siguientes atributos:
{
    "nombre": "Argentina",
    "poblacion": 45376763,
    "superficie": 2780400,
    "continente": "America"
}
Todos los países se almacenan dentro de una lista.


## Requisitos

* Python 3.x
* Módulo csv (incluido en Python)
* Archivo CSV ubicado en: datos/paises.csv

## Ejecución del Programa

1. Descargar o clonar el repositorio.
2. Abrir una terminal en la carpeta del proyecto.
3. Ejecutar: python main.py
4. Utilizar el menú mostrado en consola.

## Funcionalidades Implementadas

### Gestión de Países

* Agregar un país.
* Actualizar población y superficie.
* Buscar un país por nombre.

### Filtros

* Filtrar por continente.
* Filtrar por rango de población.
* Filtrar por rango de superficie.

### Ordenamientos

* Ordenar por nombre.
* Ordenar por población.
* Ordenar por superficie.
* Orden ascendente y descendente.

### Estadísticas

* País con mayor población.
* País con menor población.
* Promedio de población.
* Promedio de superficie.
* Cantidad de países por continente.

### Persistencia de Datos

* Lectura de información desde CSV.
* Escritura de información en CSV.


## Ejemplo de Archivo CSV

nombre,poblacion,superficie,continente
Argentina,45376763,2780400,America
Brasil,213993437,8515767,America
Alemania,83149300,357022,Europa
Japon,125800000,377975,Asia

## Ejemplo de Uso

### Entrada

Seleccione una opción: 3
Buscar: arg

### Salida

Nombre: Argentina
Población: 45376763
Superficie: 2780400 km²
Continente: America

## Tecnologías Utilizadas

* Python 3
* CSV
* Listas
* Diccionarios
* Funciones

## Repositorio

Link del repositorio: Falta

## Video Demostrativo

Link del video: Falta

## Documentación

La documentación completa del proyecto se encuentra incluida en el archivo PDF entregado junto al repositorio.

## Conclusión

Este proyecto permitió aplicar de manera práctica los conceptos fundamentales de Programación 1, incluyendo estructuras de datos, modularización mediante funciones, manejo de archivos, validaciones y algoritmos de ordenamiento y búsqueda.
