# PLN - Procesamiento del Lenguaje Natural

En este repositorio se encuentran los desafios realizados durante el cursado de la materia Procesamiento del lenguaje natural (PLN), de la carrera especializacion en inteligencia artificial de la Universidad de Buenos Aires. 

# Desafío 1: Vectorizacion

Este desafío tiene como finalidad presentar algunos conceptos y herramientas de PLN. Se realizó la vectorizacion de documentos utilizando OneHotEncoding y TF-IDF.
Con estas técnicas representamos documentos como una secuencia de vectores numéricos y luego utilizamos la similitud del coseno para calcular su similitud semantica.

[Ver el cuaderno de Jupyter](https://github.com/paulacentioni/NLP-CEIA/blob/main/1a%20-%20vectorizacion.ipynb)

# Desafío 2: Chatbot

En este desafío, se abordó la tarea de desarrollar un chatbot mediante el uso de redes neuronales densas (DNN) y la librería spaCy. La implementación se centró en la clasificación de mensajes del usuario en categorías específicas, como saludos, problemas o solicitudes de información. El modelo de DNN categoriza el texto de entrada, permitiendo respuestas predefinidas acordes a cada categoría identificada. 

[Ver el cuaderno de Jupyter](https://github.com/paulacentioni/NLP-CEIA/blob/main/2b%20-%20bot_dnn_spacy_esp.ipynb)

# Desafío 3: Embeddings con Gesim

En este desafío, nos enfocamos en generar embeddings de palabras con Gensim, una técnica utilizada para transformar palabras y frases en vectores numéricos reales. Utilizamos como dataset el libro [Los juegos del hambre](https://github.com/paulacentioni/NLP-CEIA/blob/main/hungergames.txt) aplicando Gensim para crear representaciones numéricas que capturan el significado y el contexto profundo de la narrativa. 

[Ver el cuaderno de Jupyter](https://github.com/paulacentioni/NLP-CEIA/blob/main/3b_Custom_embedding_con_Gensim.ipynb)

# Desafío 4: Prediccion próxima palabra

El propósito de este desafío es emplear documentos para crear embeddings de palabras mediante la capa Embedding de Keras. Estos embeddings, combinados con capas LSTM, se utilizan para predecir la próxima palabra en un texto ingresado por el usuario. En este caso, se utilizó el mismo conjunto de datos que el desafío anterior (Libro Los juegos del hambre).

[Ver el cuaderno de Jupyter](https://github.com/paulacentioni/NLP-CEIA/blob/main/4d_predicci%C3%B3n_palabra.ipynb)

# Desafío 5: Sentiment analysis con Embeddings + LSTM

En este desafío, el objetivo es utilizar un dataset de comentarios de clientes de un eCommerce, para entrenar un modelo que sea capaz de predecir la evaluación en cantidad de estrellas del comprador utilizando como input el texto de crítica. 

[Ver el cuaderno de Jupyter](https://github.com/paulacentioni/NLP-CEIA/blob/main/5_clothing_ecommerce_reviews.ipynb)

# Desafío 6: Bot QA

En este desafío, nos centramos en entrenar un mini Q&A chatbot para responder preguntas. Utilizamos datos disponibles del challenge ConvAI2 de conversaciones en ingles. Para mejorar el rendimiento del modelo, realizamos dos pruebas: una utilizando el conjunto de datos balanceados y otra implementando oversampling para abordar desequilibrios y mejorar la calidad de las respuestas generadas. 

[Ver el cuaderno de Jupyter](https://github.com/paulacentioni/NLP-CEIA/blob/main/6_bot_qa.ipynb)




















