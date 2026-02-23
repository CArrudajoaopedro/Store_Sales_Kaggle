# Store Sales - Time Series Forecasting

Este repositório contém a implantação de um algoritmo de aprendizagem de máquina para previsão de vendas em série temporal. O projeto foi desenvolvido como um trabalho da disciplina de Aprendizagem de Máquina do Departamento de Computação da Universidade Federal de Sergipe (UFS).

## 👥 Autores
* Carlos Daniel Lima de Gois
* João Pedro Cardoso Arruda
* Rafael Nascimento Andrade

## 🎯 Visão Geral do Projeto
O objetivo principal deste projeto é prever o número de vendas de determinados produtos em lojas no Equador ao longo de uma série temporal. A solução foi inteiramente desenvolvida em um ambiente de Notebook Python, abordando desde a análise exploratória e tratamento dos dados até a modelagem preditiva.

O modelo preditivo foi construído utilizando o algoritmo `XGBRegressor` da biblioteca XGBoost. A métrica de avaliação utilizada para o treinamento foi a `root_mean_squared_log_error`.

## Documentação
O arquivo docs/Relatorio.pdf contém toda a documentação teorica do projeto

## Submissão
A submissão mais atual é o arquivo submissions/second_submission.csv

## 📁 Estrutura do Repositório

Abaixo está a organização dos arquivos e diretórios do projeto:

```text
.
├── main.ipynb                  # Notebook principal com o código de tratamento de dados, análise exploratória e modelo de Machine Learning
├── README.md                   
├── data/                       # Diretório contendo os datasets da competição (Kaggle)
│   ├── holidays_events.csv     
│   ├── oil.csv                 
│   ├── sample_submission.csv   
│   ├── stores.csv              
│   ├── test.csv                
│   ├── train.csv               
│   └── transactions.csv        
├── docs/                       # Diretório para documentação e relatórios
│   └── Relatorio.pdf           # Documentação do projeto (Relatório técnico do trabalho da UFS)
└── submissions/                # Diretório contendo os arquivos de saída gerados pelo modelo
    └── first_submission.csv