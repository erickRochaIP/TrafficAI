# TrafficAI

## Introdução

À medida que a pesquisa continua no desenvolvimento de carros autônomos, um dos principais desafios é a visão computacional, permitindo que esses carros desenvolvam uma compreensão de seu ambiente a partir de imagens digitais. Em particular, isso envolve a capacidade de reconhecer e distinguir sinais de trânsito - sinais de parada, sinais de limite de velocidade, sinais de trânsito e muito mais.

Neste projeto, é usado o TensorFlow para construir uma rede neural para classificar sinais de trânsito com base em uma imagem desses sinais. Para fazer isso, é preciso um conjunto de dados rotulado: uma coleção de imagens que já foram categorizadas pela placa de trânsito representada nelas.

Existem vários conjuntos de dados, mas para este projeto, usaremos o conjunto de dados German Traffic Sign Recognition Benchmark (GTSRB), que contém milhares de imagens de 43 tipos diferentes de sinais de trânsito.

## Como Usar

### pip install -r requirements

e

### python traffic.py gtsrb [model.h5]

gtsrb é a base de dados. model.h5 é um parâmetro opcional com o nome do arquivo que será salvo o model.

## Problemas

Pode ser muito complicado instalar o TensorFlow. Inicialmente tentamos usá-lo no Windows 10 com a versão mais atual do python, porém só funcionou em outro computador com Windows 7 e python 3.7.6. No [ambiente disponibilizado pelo CS50](https://ide.cs50.io/) dá um erro por falta de espaço.

## Projeto original

Projeto 5 do Curso: [CS50’s Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/2020/projects/5/)