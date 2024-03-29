# Breast Cancer Classifier Software

This is a software developed for the "Image Processing" subject. The objective is to create a software with interface using Python that reads a database and train a Neural Network to classify the type of radiography.

1) 
[X] Descritor Haralick com homogeneidade, entropia, energia e contraste aplicados às matrizes co-ocorrência
circulares C1, C2, C4, C8 e C16

[X] 7 momentos invariantes de Hu

[X] Reamostrar nº tons de cinza para <= 32  (parâmetro tem que ser reajustável pelo sistema)

[X] Valores calculados para a região selecionada deve ser exibidos em uma janela auxiliar

[X] O tempo de execução deve ser medido e exibido na interface

2)
[X] Treinar um dos classificadores com os descritores selecionados:
	§ Rede neural completamente conectada
	§ Distância de Mahalanobis
	§ Árvore de decisão
	§ K vizinhos mais próximos (variar K)
	
[X] 75% das imagens devem ser escolhidas de forma aleatória, mas balanceadas entre as classes. 

[X] O tempo de execução deve ser medido e exibido na interface.


3) 
[X] Classificar os 25% das imagens restantes. 

[X] O tempo de execução deve ser medido e exibido na interface, juntamente com métricas de sensibilidade média e especificidade média

[X] Para 4 classes com 25 imagens por classe teremos a matriz de confusão 4x4, M, onde a linha é a classe correta e a coluna a classe estimada

[X] A sensibilidade média = acurácia = Σ i=1..4 M i,i /100 e a 

[X] especificidade = 1- Σ i=1..4 Σ j≠i M j,i / 300.

4) 
[X] Classificar a região selecionada com o mouse ou a imagem carregada
