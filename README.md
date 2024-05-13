# Deep-Learning
Pronóstico Precio Vivienda

## Contenido del Notebook

### Cargar Datos
Carga de los archivos train_v2.csv y test_v2.csv.

### Análisis Exploratorio

- Identificación de valores desconocidos.
- Detección y eliminación de filas duplicadas.
- Estadísticas descriptivas de las variables del conjunto de datos.

### Ingeniería de Variables
- Creación de una variable adicional.

### Preprocesamiento de Datos
- Eliminación de variables no numéricas.
- Eliminación de variables que no tienen sentido lógico para la predicción.
- Normalización de variables de entrada mediante min-max.

### División de Datos
- División de los datos de entrenamiento en Train (80%) y Validation (20%).

### Modelado de Red Neuronal
- Creación de una red neuronal con 2 capas ocultas, 200 neuronas en cada capa y función de activación ReLU.

### Entrenamiento del Modelo
- Utilización de la métrica RMSE como función de coste.

### Evaluación del Modelo
- Evaluación de la predicción en el conjunto de prueba.

### Creación de una Arquitectura que Produce Overfit
Implementación de una arquitectura que cause overfitting.

### Regularización
- Pruebas con 3 ejemplos de distintas técnicas de regularización para identificar la que mejor funciona.


## Archivos Incluidos

- train_v2.csv: Conjunto de datos de entrenamiento.
- test_v2.csv: Conjunto de datos de prueba.

## Requerimientos de Ejecución
- Python 3
- Jupyter Notebook
- Librerías: Pandas, NumPy, Scikit-learn, TensorFlow (o Keras)

