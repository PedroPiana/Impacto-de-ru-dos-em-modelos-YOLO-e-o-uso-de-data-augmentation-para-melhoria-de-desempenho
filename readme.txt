Neste estudo, o modelo YOLO utilizado foi aplicado em um cenário específico de detecção de objetos em porcos, com o uso de keypoints e bounding boxes.
No entanto, o foco deste trabalho é a análise do impacto de ruído em imagens e a melhoria de desempenho do modelo por meio de técnicas de data augmentation.
A análise se concentra em determinar a relação entre o ruído nas imagens e a acurácia das predições do modelo,
além de propor e avaliar uma técnica de data augmentation, onde 30% do dataset é modificado com ruído, para melhorar a robustez do modelo.

RuidoAug: serve para fazer a augmentation do dataset, adicionando imagens com ruido gaussiano.
SNR: predição do modelo sem ser treinado com as imagens com ruido.
SNR_AUGMENT: predições do modelo treinado com o dataset aumentado com imagens ruidosas.
