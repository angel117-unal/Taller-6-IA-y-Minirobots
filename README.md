# Taller 6 Introducción a machine learning

### Presentado por:
- **Ángel Rivera Amortegui**
- **Daniel Echeverry Jimenez**

---
## **Punto 1: Genere un data set con muchos valores y use la herramienta de machine learning **
Archivo: [6_1_modelo_raiz_cuadrada.ipynb](./6_1_modelo_raiz_cuadrada.ipynb)

Descripción:  Este ejercicio consiste en desarrollar un modelo de regresión polinómica para aproximar la función de la raíz cuadrada. El objetivo es capturar la relación no lineal entre la variable independiente x y la variable dependiente y = raiz de x. El proceso incluye la generación de un dataset, la división en conjuntos de entrenamiento y prueba, el entrenamiento del modelo, y la evaluación de su rendimiento. Se generó un dataset creando un conjunto de datos basado en la función de la raíz cuadrada, para después separar los datos en conjuntos de entrenamiento y prueba, con el fin de utilizar un modelo polinómico para capturar la no linealidad de la función. Una vez hecho lo anterior, evaluamos el modelo calculando el error cuadrático medio (MSE) para evaluar el rendimiento del modelo y por último  comparar las predicciones del modelo con los valores reales de la función de la raíz cuadrada. El modelo muestra el error cuadrático medio, y la respectiva comparación de resultados de la variable x, entre el valor real y el valor predicho, llegando a una diferencia de 0.2

## **Punto 2: Programa SVM con todo detalle.**
Archivo: [6_2_Programa_SVM.ipynb](./6_2_Programa_SVM.ipynb)

Descripción:  Este ejercicio consiste en desarrollar un modelo de clasificación utilizando Support Vector Machines (SVM) para predecir el segmento de vehículos basado en datos de ventas mensuales y otras características numéricas. El proceso incluye la carga y preprocesamiento de datos, la preparación de características, la construcción y entrenamiento del modelo, y la evaluación de su rendimiento. Se toma un data set sobre automoviles en India, para luego cargar y preprocesar los datos, en donde se busca leer un archivo de Excel que contiene datos de ventas de vehículos, manejar valores faltantes y limpiar los nombres de las columnas. Luego se selecciona las columnas numéricas relevantes, estandarizarlas y codificar las variables categóricas. Una vez hecho esto buscamos entrenar un modelo SVM para utilizar un clasificador SVM y predecir el segmento de vehículos y por último Evaluamos el modelo calculando la precisión y generando un reporte de clasificación para evaluar el rendimiento del modelo.

## **Punto 3:Algoritmo de K- Nearest, o árboles de decisión. **
Archivo: [6_3_algoritmo_de_K_Nearest,.ipynb](./6_3_algoritmo_de_K_Nearest,.ipynb)

Descripción:Este ejercicio consiste en desarrollar un modelo de clasificación utilizando el algoritmo K-Nearest Neighbors (KNN) para clasificar las especies de flores del dataset Iris. El proceso incluye la carga del dataset, la preparación de los datos, la construcción y entrenamiento del modelo, y la evaluación de su rendimiento. Utilizamos el dataset Iris, que contiene características de flores y sus especies. Luego preparamos los datos dividiendo el dataset en conjuntos de entrenamiento y prueba, esto con el fin de entrenar un modelo KNN y utilizar el algoritmo K-Nearest Neighbors para clasificar las especies de flores. Hecho esto evaluamos el modelo calculando la precisión y generamos un reporte de clasificación para evaluar el rendimiento del modelo y por último representamos gráficamente los resultados de la clasificación.

## **Punto 4:Problema de escogencia. **
Archivo: [6_4_Ejercicio_electivo_máquina_despulpadora_de_café.ipynb](./6_4_Ejercicio_electivo_máquina_despulpadora_de_café.ipynb)

Descripción: Este ejercicio consiste en desarrollar un modelo de clasificación utilizando un Árbol de Decisión para predecir la calidad del procesamiento de café en una máquina despulpadora. El proceso incluye la simulación de datos, la preparación de los datos, la construcción y entrenamiento del modelo, y la evaluación de su rendimiento.Iniciamos simulando los datos y creando un dataset que represente las características de la máquina despulpadora, como el peso de la almendra, la humedad, el tiempo de procesamiento y el estado del tambor. Hecho esto preparamos los datos al convertir la variable categórica de calidad en valores numéricos y dividir el dataset en conjuntos de entrenamiento y prueba. Luego entrenamos un modelo de árbol de Decisión al utilizar un clasificador de árbol de decisión para predecir la calidad del procesamiento. Por último, evaluamos el modelo y visualizamos la importancia de las características:; al calcular la precisión y generar un reporte de clasificación para evaluar el rendimiento del modelo y representar gráficamente la importancia de cada característica en la clasificación respectivamente

### Notas adicionales:
Este repositorio contiene la resolución detallada de los puntos del taller 6 sobre Machine learning. Cada programa ha sido documentado con descripciones claras para facilitar su comprensión y replicación.
