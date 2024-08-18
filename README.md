
PASOS PARA LA CREACION DEL PROYECTO: 

1. Identificación de Técnicas y Modelos
Para este proyecto, podrías considerar las siguientes técnicas y modelos:

Análisis Exploratorio de Datos (EDA): Para entender la distribución y características de los datos.
Limpieza de Datos: Para manejar valores nulos, duplicados y datos inconsistentes.
Procesamiento de Lenguaje Natural (NLP): Para analizar el texto de las reviews.
Modelos de Machine Learning: Como regresión logística, árboles de decisión, Random Forest, SVM, etc.
Redes Neuronales: Como LSTM o modelos basados en Transformers para análisis de sentimiento.
Ensamblaje de Modelos: Para combinar múltiples modelos y mejorar el rendimiento.
Ajuste de Hiperparámetros: Para optimizar los modelos.

2. Análisis Exploratorio y Limpieza de Datos
a. Cargar y Explorar el Dataset
b. Análisis de Completitud
c. Tokenización y Procesamiento de Texto

3. Entrenamiento del Modelo
a. División del Dataset
b. Entrenamiento de un Modelo de Machine Learning

4. Evaluación del Modelo
a. Métricas de Rendimiento
b. Gráficas de Rendimiento

5. Ensamblaje y Ajuste de Hiperparámetros
a. Ensamblaje de Modelos
b. Ajuste de Hiperparámetros

6. Construcción de la API REST
a. Crear la API con Flask:

from flask import Flask, request, jsonify

app = Flask(__name__)
Se guardara en el puerto por defecto:  Running on http://127.0.0.1:5000 (Press CTRL+C to quit)

7. Despliegue en la Nube
Puedes usar servicios como Heroku, Netlify o Ngrok para desplegar tu API y hacerla accesible desde internet.
