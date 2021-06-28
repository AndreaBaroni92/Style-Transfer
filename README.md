# Style-Transfer  
## Obiettivo
Studiare due tecniche di style transfer e riprodurne l'implementazione in colab tramite l'asulio della libreria TensorFlow 2.0.  
I due algoritmi studiati sono:  
1. [Image Style Transfer Using Convolutional Neural Networks](https://ieeexplore.ieee.org/document/7780634)
2. [Arbitrary Style Transfer in Real-Time with Adaptive Instance Normalization](https://ieeexplore.ieee.org/document/8237429)  

Per il primo algoritmo mi sono basato sulla seguente implementazione: [implementazione_1](https://keras.io/examples/generative/neural_style_transfer/) disponibile sul sito della libreria keras, mentre per la seconda: [implementazione_2](https://github.com/emla2805/arbitrary-style-transfer) di Emil Larsson.  
Entrambi gli algoritmi vengono illustrati nella presentazione disponibile in questo repository.
## Utilizzo  
| File        | Descrizione           | 
| ------------- |:-------------| 
| NstGatys     | Implementa il primo algoritmo della lista sopra. | 
| AdaInTrain     | Addestra la rete descritta nel secondo algoritmo (in particolare il decoder).       |  
| AdaIn | Avendo a disposizione i pesi della rete permette di effettuare il reasferimento di stile     | 