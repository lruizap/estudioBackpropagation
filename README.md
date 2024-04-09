# Implementación de Backpropagation en Python

## Introducción

Este proyecto consiste en la implementación del algoritmo de retropropagación (backpropagation) en Python para entrenar una red neuronal simple. El algoritmo de retropropagación es fundamental en el campo del aprendizaje profundo y se utiliza para calcular el gradiente de la función de pérdida con respecto a los pesos de la red, permitiendo así ajustar los pesos de manera que la red pueda aprender a realizar la tarea deseada.

En este proyecto, implementaremos el algoritmo de retropropagación desde cero utilizando Python y NumPy. Además, utilizaremos el conjunto de datos de Iris para demostrar el funcionamiento de la red neuronal en una tarea de clasificación de múltiples clases.

## Contenido del Repositorio

El repositorio contiene los siguientes archivos:

- `backpropagation.py`: Implementación del algoritmo de retropropagación y la clase de red neuronal.
- `README.md`: Documentación del proyecto.
## Requisitos

Para ejecutar el código, se requiere tener instaladas las siguientes bibliotecas de Python:

- NumPy
- scikit-learn
- Keras
- TensorFlow

Se pueden instalar estas bibliotecas utilizando el gestor de paquetes pip de la siguiente manera:

```bash
pip install numpy scikit-learn keras tensorflow
```

## Uso

Para utilizar el código, sigue estos pasos:

1. Clona el repositorio o descarga los archivos en tu máquina local.
2. Asegúrate de tener instaladas las bibliotecas mencionadas en los requisitos.
3. Ejecuta el script `backpropagation.py` para entrenar y probar la red neuronal en el conjunto de datos de Iris.

```bash
python backpropagation.py
```