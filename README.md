# HablaImaginada-DeepLearning

Se propone disenar una arquitectura de redes neuronales profundas mezclando redes neuronales convolucionales (CNN) para la extracción de características de alto nivel, redes neuronales de memoria a corto y largo plazo (LSTM) para conservar la secuencia temporal del EEG y redes neuronales completamente conectadas para la clasifícación de las senales de EEG.

### CNN-1Capa-TrainTest.ipynb
* CNN-2D (8@3x7)
* MaxPool (2x2)
* Dense (64)
* Dropout (0.5)
* Dense (n)

### CNN-2Capas-TrainTest.ipynb
* CNN-2D (8@1x7)
* MaxPool (2x2)
* CNN-2D (16@1x7)
* MaxPool (2x2)
* Dense (64)
* Dropout (0.5)
* Dense (n)

### CNN1D-LSTM-CV5.ipynb
* CNN-1D (4@1x3)
* CNN-1D (4@1x3)
* Dropout (0.5)
* MaxPool (2)
* LSTM (16)
* Dropout (0.5)
* Dense (64)
* Dense (n)

Validacion cruzada de 5

### CNN1D-LSTM-TrainTest-Yo.ipynb
* CNN-1D (4@1x7)
* CNN-1D (8@1x7)
* LSTM (8)
* Dropout (0.5)
* Dense (32)
* Dropout (0.5)
* Dense (n)

### CNN1D-LSTM-TrainTest.ipynb
* CNN-1D (4@1x3)
* CNN-1D (4@1x3)
* Dropout (0.5)
* MaxPool (2)
* LSTM (16)
* Dropout (0.5)
* Dense (64)
* Dense (n)

### ConvLSTM2D-TrainTest.ipynb
* ConvLSTM2D (8@1x3)
* Dropout (0.5)
* Dense (64)
* Dense (n)

### LSTM-TrainTest.ipynb
* LSTM (8)
* Dropout (0.5)
* Dense (n)

### MLP o SVM.ipynb
Por defecto de scikit-learn