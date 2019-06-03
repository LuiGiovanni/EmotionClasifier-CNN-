# EmotionClassifier -CNN-

## Introduccion
Un sistema de reconocimiento de emociones se comprime en dos procesos:
    - La deteccion de la cara
    - La deteccion de emociones en dicha cara
En este proyecto ponemos en practica ambos procesos basandose en el proyecto *Demonstration of Facial Emotion Recognition on Real Time Video Using CNN : Python & Keras*
de donde pueden ver una explicacion mas a fondo.

## Data-set
Puedes descargar los datos llamados *facial expression recognition*, es un set de datos de [**Kaggle**](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data) Se necesita hacer una cuenta y aceptar el reto para descargar los datos, estos datos consisten de imagenes de caras en escala de grises de 48x48 pixeles.

## Instalacion
Se necesitan instalar unas cosillas:
- Keras
- opencv
- Tensorflow

## Implementacion
Para correr un version de prueba ejecuta:
```
python video_emotion_color_demo.py
```

## Resultados
Muchas veces tus caras deben ser un poco exageradas para conseguir resultados, pero en general describe bien las emociones mostradas. Nota rapida: a veces los lentes afectan por eso en las imagenes aparezco sin lentes.

![alt tag](images/neutral.png)
![alt tag](images/happy.png)
![alt tag](images/angry.png)
![alt tag](images/suprise.png)


