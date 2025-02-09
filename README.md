# Taller 6 Introducción a machine learning

### Presentado por:
- **Ángel Rivera Amortegui**
- **Daniel Echeverry Jimenez**

---
## **Punto 1: Genere un data set con muchos valores y use la herramienta de machine learning **
Archivo: [reconocLetras.ipynb](./reconocLetras.ipynb)

Descripción:  Este código realiza un análisis exploratorio y un modelo de clasificación utilizando el famoso dataset Iris. Primero, lee las descripciones del archivo iris.names para entender el contexto del conjunto de datos. Luego, analiza las estadísticas descriptivas del dataset y visualiza las distribuciones con un gráfico de pares coloreado por clase. Posteriormente, divide los datos en características y etiquetas, normaliza las clases con LabelEncoder y crea una red neuronal con Keras. La red, diseñada para clasificar las tres especies de iris, se entrena con un conjunto de datos dividido en entrenamiento y prueba, usando sparse_categorical_crossentropy como función de pérdida y el optimizador adam.

## **Punto 2: Programa SVM con todo detalle.**
Archivo: [clasificacionPerrosGatos.ipynb](./clasificacionPerrosGatos.ipynb)
Archivo: [modeloClasificador.keras](./modeloClasificador.keras)

Descripción:  Este ejercicio consiste en desarrollar un modelo de clasificación de imágenes para distinguir entre perros y gatos utilizando redes neuronales convolucionales (CNN). El proceso incluye la creación de un dataset, el preprocesamiento de las imágenes, la construcción y entrenamiento del modelo, y la evaluación de su rendimiento.Se recolectaron  100 imágenes de perros y 100 imágenes de gatos. Luego se normalizaron las imágenes y se dividieron el dataset en conjuntos de entrenamiento, validación y prueba. Después se diseñó una red neuronal convolucional para clasificar las imágenesy se entrenó el modelo con el dataset y evaluar su precisión, y por último se guardó el modelo entrenado para su uso futuro.

## **Punto 3:Algoritmo de K- Nearest, o árboles de decisión. **
Archivo: [Diseño_red_neuronal_Iris.ipynb](./Diseño_red_neuronal_Iris.ipynb)

Descripción: Este código implementa una red neuronal artificial (NNA) desde cero en Python. La red tiene una arquitectura fija con tres capas: dos ocultas y una de salida. Utiliza inicialización Xavier para los pesos y la función sigmoide como activación. El flujo principal incluye:
1. Propagación hacia adelante: Calcula las activaciones de cada capa para una entrada dada.
2. Cálculo de error: Compara la salida de la red con los valores deseados.
3. Retropropagación: Ajusta los pesos y sesgos para minimizar el error mediante el método de descenso de gradiente.
4. Entrenamiento: Itera sobre los datos de entrada y salida hasta que el error cuadrático medio sea aceptable o se alcance un número máximo de iteraciones. También ajusta dinámicamente la tasa de aprendizaje (learning rate).
El código incluye datos de entrenamiento que representan letras (A, E, I, O, U) en forma de matrices binarias y sus salidas deseadas codificadas. Finalmente, se entrena la red para reconocer estas entradas, mostrando la evolución del error durante el proceso y verificando la precisión de la salida entrenada.

## **Punto 4:Problema de escogencia. **
Archivo: [Diseño_red_neuronal_Iris.ipynb](./Diseño_red_neuronal_Iris.ipynb)

Descripción: Este código implementa una red neuronal artificial (NNA)
### Notas adicionales:
Este repositorio contiene la resolución detallada de los puntos del taller 6 sobre Machine learning. Cada programa ha sido documentado con descripciones claras para facilitar su comprensión y replicación.
