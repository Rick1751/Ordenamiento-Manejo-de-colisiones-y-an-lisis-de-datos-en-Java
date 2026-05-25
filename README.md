# EDA: Análisis de Datos en Java (Dev Container)

Este repositorio contiene el entorno de desarrollo y las herramientas necesarias para realizar un Análisis Exploratorio de Datos (EDA) sobre un conjunto de datos cinematográficos (`movies.csv`), [https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies] utilizando Java de forma interactiva mediante Jupyter Notebooks dentro de un contenedor aislado.

## Requisitos Previos

* Docker Desktop instalado y corriendo.
* Visual Studio Code con la extensión **Dev Containers** instalada.

## Estructura del Proyecto

* `.devcontainer/`: Configuración para levantar el entorno automatizado en Docker.
* `ijava/`: Configuración y dependencias del kernel de Java para Jupyter.
* `00_PrimerosPasos.ipynb`: Notebook interactivo para la carga y manipulación de datos.
* `movies.csv`: Dataset principal con los datos de las películas.

## Configuración del Entorno

1. Abrir la carpeta del proyecto en Visual Studio Code.
2. Presionar `Ctrl + Shift + P` (o `Cmd + Shift + P` en macOS) y seleccionar la opción **Dev Containers: Reopen in Container**.
3. Esperar a que Docker construya la imagen e instale el kernel de `IJava`.
4. Abrir el archivo `00_PrimerosPasos.ipynb` y seleccionar el kernel de Java.


### Código Base de Carga

- Se encuentra en el archivo 00 y 02 como formato de cuaderno para pruebas 