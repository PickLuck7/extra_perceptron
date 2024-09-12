# Proyecto de Clasificación de Flores con Perceptrón - Dataset Iris

Este proyecto utiliza un **perceptrón** para clasificar dos tipos de flores (Setosa y Versicolor) del conocido conjunto de datos **Iris**, simplificado a dos clases y dos características. El objetivo es entrenar un modelo que sea capaz de clasificar estas dos clases de flores en función del largo y ancho del sépalo.

## Descripción del Proyecto

El conjunto de datos **Iris** contiene tres clases de flores y cuatro características. Para este proyecto, hemos simplificado el dataset para que solo incluya dos clases de flores (Setosa y Versicolor) y dos características (largo y ancho del sépalo). Utilizamos un **perceptrón**, que es un algoritmo simple pero poderoso de clasificación lineal.

### Dataset

El conjunto de datos **Iris** se encuentra disponible en la librería `scikit-learn`. En este proyecto, utilizamos solo las dos primeras clases y dos características del conjunto de datos para simplificar la tarea de clasificación. 

## Objetivos

- Clasificar dos tipos de flores (Setosa y Versicolor) utilizando un **perceptrón**.
- Evaluar el rendimiento del modelo con métricas como la **exactitud**.
- Visualizar la frontera de decisión para entender cómo el modelo clasifica las dos clases de flores.

## Pasos

### a) Justificación del modelo utilizado

Utilizamos un **perceptrón** porque es un algoritmo simple de clasificación lineal que es fácil de entrenar y funciona bien para problemas linealmente separables. En este caso, con dos clases de flores y dos características, es una solución adecuada para clasificar si una flor es Setosa o Versicolor en función de su largo y ancho de sépalo.

### b) ¿Qué características se utilizaron?

Para simplificar el problema, seleccionamos dos características del conjunto de datos Iris:
- **Largo del sépalo** (en cm)
- **Ancho del sépalo** (en cm)

Estas características son suficientes para clasificar las dos clases de flores seleccionadas.

### c) Métricas utilizadas y su interpretación

- **Exactitud**: Se evaluó el rendimiento del modelo utilizando la métrica de exactitud. En este caso, el modelo logró una exactitud que representa el porcentaje de predicciones correctas para clasificar correctamente entre las dos clases de flores.
