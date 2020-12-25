# Redes Generativas

- Este repositório contém implementações de algumas técnicas para obtenção de modelos generativos baseados em redes neurais.

- Modelos generativos são modelos probabilísticos (isto é, suas entradas são variáveis aleatórias) que, durante o treinamento, têm os
seus parâmetros ajustados de modo que o modelo aprenda a distribuição por trás da geração dos dados de treinamento.

- Aqui trataremos de três técnicas aplicadas a duas bases de dados:
    - Autoencoder Variacional (VAE)
    - Redes Adversárias Generativas (GAN)
    - Autoencoders Adversariais (AAE)
    - MNIST
    - Cats vs Dogs

- Autoencoder Variacional: 
    - Analisamos a dimensão do espaço latente e diferentes funções custo de reconstrução (BCE Loss, MSE Loss e MAE Loss).

- Redes Adversárias Generativas (GAN):
    - A arquitetura DCGAN é utilizada como base para as duas bases de dados.
    - Estudados algumas técnicas para melhorar o treinamento das GANs e a qualidade das imagens sintéticas produzidas pelas redes
    generativas, tais como: Minibatch discrimination, Label Smoothing, Feature Matching e Experience Replay.

- Autoencoders Adversariais (AAE):
    - Estudo em progresso.