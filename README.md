# **Face_Emotion**
En este repositorio trabajaremos el entrenamiento de una red neuronal convolucional para la clasificación de emociones y la detección en tiempo real usando una cámara web. 

## Entrenamiento en google colab

El entrenamiento lo realizaremos en google colab. Vamos a configurar un entorno para trabajar con las siguientes versiones de librerías:
    
*     Tensorflow = 2.4.1
      Keras = 2.4.3 

### Preparación del entorno

    $ conda create -n FaceEmotion
    $ conda activate FaceEmotion
    $ conda install python=3.7
    $ pip install tensorflow==2.4.1
    $ pip install keras==2.4.3
    $ pip install imutils opencv-python h5py
    $ pip install matplotlib == 3.2.2
    
### Usando WebCam

Ejecutar el archivo FaceEmotionVideo.py

    $ python FaceEmotionVideo.py
