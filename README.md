# Análise e Classificação de Acidentes Fatais nas Estradas Australianas (1989-2021)

## 1. Introdução

Este repositório contém o projeto desenvolvido no âmbito da **UFCD 10811 – Projeto de Análise de Dados**, inserido na formação **G-EFFA-FME94SI0007 - Análise de Dados 2023**. A base de dados utilizada, intitulada **"Australian Fatal Road Accident 1989-2021"**, foi obtida do Kaggle e fornece detalhes sobre acidentes fatais nas estradas australianas, conforme relatados mensalmente pela polícia entre 1989 e 2021.

O objetivo deste projeto foi analisar a base de dados de forma clara e objetiva, com foco em identificar as variáveis que mais impactam o **Tipo de Acidente** (acidente simples vs. múltiplo). Para isso, foi realizado um processo de limpeza, pré-processamento e aplicação de diversos modelos de machine learning.

## 2. Objetivo do Projeto

O principal objetivo deste projeto foi classificar os acidentes fatais em estradas australianas em duas categorias:
- **Acidentes com um único veículo**
- **Acidentes com múltiplos veículos**

Vários modelos de machine learning foram aplicados para identificar qual deles apresenta o melhor desempenho na classificação do tipo de acidente.

## 3. Base de Dados

- **Nome**: Australian Fatal Road Accident 1989-2021
- **Fonte**: [Kaggle](https://www.kaggle.com/)
- **Descrição**: A base de dados inclui acidentes fatais reportados mensalmente na Austrália, com detalhes sobre o tipo de acidente, veículos envolvidos e outros fatores, como horário, dia da semana e tipo de usuário da via.

## 4. Processamento de Dados

O processamento dos dados envolveu:
- Tratamento de valores ausentes
- Codificação de variáveis categóricas
- Criação e transformação de variáveis

Esses passos garantiram a qualidade dos dados e sua compatibilidade para o treinamento dos modelos de machine learning.

## 5. Modelos de Machine Learning Utilizados

Os seguintes modelos foram aplicados para classificar o **Tipo de Acidente(crash_type)**:
- **Logistic Regression**: Um modelo estatístico utilizado para classificar eventos com base em variáveis independentes, conhecido por sua simplicidade e eficácia em problemas de classificação.
- **K-Nearest Neighbors (KNN)**: Algoritmo de aprendizado supervisionado que classifica novos pontos com base na classe predominante dos vizinhos mais próximos.
- **Radius Neighbors Classifier**: Variação do KNN que classifica os pontos com base na densidade de vizinhos dentro de um raio específico, útil para dados com distribuição irregular.
- **Decision Tree**: Modelo que utiliza uma estrutura de árvore para representar decisões e suas possíveis consequências, valorizado por sua interpretabilidade.
- **Random Forest**: Conjunto de árvores de decisão combinadas para melhorar a precisão das previsões, reduzindo o viés e a variância do modelo.



