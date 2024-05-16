# Projeto de Classificação Fashion MNIST com Keras e TensorFlow

![Static Badge](https://img.shields.io/badge/python-%23ffffff?style=for-the-badge&logo=python&logoColor=white&labelColor=%233776AB)
![Static Badge](https://img.shields.io/badge/keras-%23ffffff?style=for-the-badge&logo=keras&logoColor=white&labelColor=%23D00000)
![Static Badge](https://img.shields.io/badge/tensorflow-%23ffffff?style=for-the-badge&logo=tensorflow&logoColor=white&labelColor=%23FF6F00)
![Static Badge](https://img.shields.io/badge/numpy-%23ffffff?style=for-the-badge&logo=numpy&logoColor=white&labelColor=%23013243)
![Static Badge](https://img.shields.io/badge/matplotlib-%23ffffff?style=for-the-badge)

Este projeto tem como objetivo classificar imagens do conjunto de dados Fashion MNIST usando uma rede neural construída com Keras e TensorFlow. O conjunto de dados contém 60.000 imagens de treinamento e 10.000 imagens de teste, cada uma com 28x28 pixels. As imagens representam 10 diferentes categorias de itens de vestuário.

## Conjunto de Dados
O conjunto de dados Fashion MNIST é uma coleção de imagens em escala de cinza de itens de vestuário. Cada imagem tem o tamanho de 28x28 pixels, e existem 10 classes diferentes:
1. Camiseta
2. Calça
3. Pulôver
4. Vestido
5. Casaco
6. Sandália
7. Camisa
8. Tênis
9. Bolsa
10. Bota

## Estrutura do projeto
* Carregamento e Exploração do Conjunto de Dados
* Visualização dos Dados
* Normalização dos Dados
* Construção do Modelo
* Treinamento do Modelo
* Avaliação e Melhoria do Modelo
* Salvamento e Carregamento do Modelo
* Avaliação Final

## Resultados
O modelo final alcançou uma precisão de aproximadamente 83,24% no conjunto de teste, indicando um desempenho razoavelmente bom para esta rede neural simples.

## Conclusão
Este projeto demonstra o processo de construção, treinamento e avaliação de uma rede neural para classificação de imagens usando o conjunto de dados Fashion MNIST. Embora o modelo apresente um desempenho decente, melhorias adicionais podem ser feitas experimentando diferentes arquiteturas, hiperparâmetros e técnicas de regularização para reduzir o sobreajuste e/ou melhorar a precisão.
