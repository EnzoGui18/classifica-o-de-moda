# Classificação de Itens de Moda com Redes Neurais (MLP)

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![Python](https://img.shields.io/badge/python-3.9%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

Repositório do projeto de Pós-Graduação que desenvolve uma solução de Deep Learning para automatizar a classificação de peças de vestuário, utilizando o dataset Fashion-MNIST.

---

## 📝 Índice

* [Problema de Negócio](#-problema-de-negócio)
* [Objetivos do Projeto](#-objetivos-do-projeto)
* [Resultados Principais](#-resultados-principais)
* [Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [Instalação e Configuração](#-instalação-e-configuração)
* [Como Usar](#-como-usar)
* [Estrutura do Projeto](#-estrutura-do-projeto)
* [Autor](#-autor)

---

## 🎯 Problema de Negócio

No cenário competitivo do varejo de moda online, a agilidade na disponibilização de novos produtos é um diferencial crucial. O processo de catalogação manual, onde funcionários classificam cada item a partir de uma foto, gera gargalos logísticos, altos custos de mão de obra e está sujeito a erros que podem impactar a experiência do cliente. Este projeto visa solucionar esse problema através da automação inteligente.

---

## 🚀 Objetivos do Projeto

O objetivo principal é construir, treinar e avaliar um modelo de Rede Neural Artificial (um Perceptron de Múltiplas Camadas - MLP) para automatizar a tarefa de classificação de roupas. O modelo deve:
-   Receber uma imagem de 28x28 pixels de uma peça de roupa.
-   Classificá-la corretamente em uma das 10 categorias possíveis.
-   Atingir uma acurácia mínima de 85% no conjunto de dados de teste.
-   Ser robusto e generalista, evitando overfitting.

---

## 📊 Resultados Principais

Após uma fase de experimentação sistemática, o modelo final alcançou uma performance robusta, validando a solução para o problema de negócio.

* **Acurácia Final (Conjunto de Teste):** **88.45%**
* **Melhor Arquitetura:** MLP com 1 camada oculta de 300 neurônios (ReLU), regularizada com Dropout (taxa de 0.3) e com *Early Stopping*.
* **Principal Insight:** O modelo demonstrou excelente performance em classes com formas distintas (como Botas, Calças e Bolsas, com F1-Score > 0.9
