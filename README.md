# Frutas-Vegetais-Resnet

Notebook, utilizando rede ResNet50, resultado do instruction 1 - pesquisa de modelos.

Grupo: Auxílio na tomada de decisão no processo de compra de frutas e vegetais.

## Introdução

Para alcançar o nosso objetivo, precisamos obter o conhecimento necessário para a classificação com redes neurais. Como primeiro passo na nossa jornada, decidimos criar um tutorial de como usar 2 redes neurais famosas:
+ Resnet 50
+ Inception v3

Este repositório contém o conteúdo e o notebook da rede **ResNet50** , assim como um guia para auxiliar aqueles que estão dando os seus primeiros passos.

### O que é a ResNet
A ResNet (Residual Network) é uma arquitetura de rede neural profunda utilizada para classificação de imagens. Foi introduzida em 2015 pela Microsoft Research Asia e se tornou uma das redes mais populares para tarefas de visão computacional. A ResNet resolveu um problema conhecido como desvanecimento de gradientes, que ocorre quando as informações transmitidas pelo gradiente durante o treinamento da rede se tornam cada vez menores à medida que se avança pelas camadas. Isso acontece porque a profundidade da rede aumenta, o que dificulta a retropropagação do erro e o ajuste dos pesos da rede.  A arquitetura da ResNet é composta por blocos residuais, que podem ser empilhados para formar uma rede de várias camadas. Nesta aplicação, a variante utilizada é formada por 50 camadas de convolução, sendo portanto conhecida como **ResNet50** podendo ser utilizada para problemas complexos em visão computacional, como reconhecimento de objetos e classificação de imagens.

![top7_torneio_ILSVRC](https://user-images.githubusercontent.com/119753668/233491811-85bbdcd0-230b-4173-8be5-ba773889d1fa.png)

### Outros links úteis:

+ [CS231n Convolutional Neural Networks for Visual Recognition](https://cs231n.github.io/transfer-learning/) - Texto sobre Aprendizado por Transferência
+ [Transfer Learning - Machine Learning's Next Frontier](https://ruder.io/transfer-learning/) - Texto sobre Aprendizado por Transferência
+ [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385) - Artigo da ResNet
+ [Transfer Learning with ResNet50](https://www.kaggle.com/code/pmigdal/transfer-learning-with-resnet-50-in-keras) - Aprendizado por transferencia com ResNet50
+ [Keras Doc](https://keras.io/api/) - Documentação TensorFlow Keras
+ [Gridsearch Keras](https://machinelearningmastery.com/grid-search-hyperparameters-deep-learning-models-python-keras/) - Pesquisa Hiperparâmetros - Keras



## Nosso Tutorial

[ResNet50_+_DataExtraction](https://github.com/Projeto-Frutas-Vegetais-Programa-K/Frutas-Vegetais-Resnet/blob/main/1%20-%20(Starting%20point)%20resnet_data_organization.ipynb)

[ResNet50_+_3_output_classification](https://github.com/Projeto-Frutas-Vegetais-Programa-K/Frutas-Vegetais-Resnet/blob/main/2%20-%20detection_3_out.ipynb)

[ResNet50_+_18_output_classification](https://github.com/Projeto-Frutas-Vegetais-Programa-K/Frutas-Vegetais-Resnet/blob/main/3-%20detection_18_out.ipynb)

## Contato

Se após essas leituras ainda tiver alguma dúvida ou curiosidade sobre o tutorial, não hesite em entrar em contato no seguinte email: <lucasdejesus@discente.ufg.br>
