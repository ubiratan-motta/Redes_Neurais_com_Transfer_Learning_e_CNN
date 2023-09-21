# Image Classification with CNN and Transfer Learning

## Overview

This project focuses on image classification to determine whether they contain a dog or a cat. We employ a Convolutional Neural Network (CNN) model for this task. The dataset used is the well-known Dogs vs. Cats dataset, widely used in computer vision problems.

## Problem Under Study

The objective is to train a model capable of distinguishing between images of dogs and cats. This is a classic task in machine learning and computer vision, suitable for beginners and also serves as an excellent example of how to implement a CNN.

## Development

In this project, we address the following aspects:

1. **Data Preprocessing:** How to load and prepare dog and cat images for model training.
2. **Custom CNN:** How to develop a Convolutional Neural Network from scratch for image classification.
3. **Transfer Learning:** How to use transfer learning with pretrained models to improve classification performance.

## Dataset

The original Dogs vs. Cats dataset comes from a Kaggle challenge: [Dogs vs. Cats](https://www.kaggle.com/competitions/dogs-vs-cats/data).

Due to processing limitations, we have reduced the training set to 500 images of cats and 500 images of dogs. The test set consists of 1500 images.

## Project Structure

The project is organized as follows:

- **Data Preparation:** This section deals with importing, preprocessing, and organizing images for training and testing.
- **Custom CNN Model:** Here, you will find the implementation of a CNN from scratch, including model training and evaluation.
- **Transfer Learning:** We demonstrate how to apply transfer learning techniques using pretrained models such as VGG16 to enhance classification.
- **Evaluation:** We analyze the performance of the models and discuss relevant metrics.

## How to Use This Project

To run this project in your local environment, follow these steps:

1. Clone this repository.
2. Make sure you have all the necessary libraries installed, which can be done using the `requirements.txt` file.
3. Follow the instructions in each section of the project to understand and apply the concepts.

This project serves as a practical guide for those who want to learn about image classification using CNNs and the power of transfer learning.
----------
# Classificação de Imagens com CNN e Transfer Learning

## Visão Geral

Este projeto se concentra na classificação de imagens para determinar se elas contêm um cachorro ou um gato. Utilizamos um modelo de Rede Neural Convolucional (CNN) para essa tarefa. O conjunto de dados utilizado é o conhecido Dogs vs. Cats, que é amplamente utilizado em problemas de visão computacional.

## Problema em Estudo

O objetivo é treinar um modelo capaz de diferenciar entre imagens de cachorros e gatos. Essa é uma tarefa clássica em aprendizado de máquina e visão computacional, adequada para iniciantes e também serve como um excelente exemplo de como implementar uma CNN.

## Desenvolvimento

Neste projeto, abordamos os seguintes aspectos:

1. **Pré-processamento de Dados:** Como carregar e preparar imagens de cães e gatos para treinamento do modelo.
2. **CNN do Zero:** Como desenvolver uma Rede Neural Convolucional a partir do zero para classificar as imagens.
3. **Transfer Learning:** Como usar o aprendizado de transferência com modelos pré-treinados para melhorar o desempenho da classificação.

## Conjunto de Dados

O conjunto de dados original do Dogs vs. Cats é proveniente de um desafio no Kaggle: [Dogs vs. Cats](https://www.kaggle.com/competitions/dogs-vs-cats/data).

Devido a limitações de processamento, reduzimos o conjunto de treinamento para 500 imagens de gatos e 500 imagens de cachorros. O conjunto de teste consiste em 1500 imagens.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- **Preparação de Dados:** Esta seção lida com a importação, pré-processamento e organização das imagens para treinamento e teste.
- **Modelo CNN Personalizado:** Aqui, você encontrará a implementação de uma CNN do zero, incluindo o treinamento e a avaliação do modelo.
- **Transfer Learning:** Mostramos como aplicar técnicas de aprendizado de transferência usando modelos pré-treinados, como o VGG16, para melhorar a classificação.
- **Avaliação:** Analisamos o desempenho dos modelos e discutimos métricas relevantes.

## Como Utilizar Este Projeto

Para executar este projeto em seu ambiente local, siga estas etapas:

1. Clone este repositório.
2. Certifique-se de ter todas as bibliotecas necessárias instaladas, o que pode ser feito usando o arquivo `requirements.txt`.
3. Siga as instruções em cada seção do projeto para entender e aplicar os conceitos.

Este projeto serve como um guia prático para aqueles que desejam aprender sobre classificação de imagens usando CNN e o poder do aprendizado de transferência.
