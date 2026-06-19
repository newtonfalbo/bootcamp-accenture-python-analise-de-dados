# 💳 Detecção de Anomalias em Transações Financeiras

Projeto desenvolvido durante o Bootcamp **Accenture + DIO** utilizando Python e técnicas de Machine Learning para identificar transações potencialmente fraudulentas.

## Objetivo

Desenvolver um modelo capaz de detectar transações anômalas utilizando aprendizado de máquina não supervisionado, auxiliando na identificação de possíveis fraudes financeiras.

## Dataset

O projeto utiliza o conjunto de dados **Credit Card Fraud Detection**, contendo milhares de transações realizadas por cartão de crédito.

As variáveis foram previamente anonimizadas por meio de PCA para preservar a privacidade dos usuários.

## Tecnologias utilizadas

- Python 3
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Etapas do projeto

- Importação dos dados
- Análise exploratória
- Tratamento dos dados
- Padronização das variáveis
- Treinamento do modelo Isolation Forest
- Avaliação dos resultados
- Visualização da matriz de confusão

## Estrutura do projeto

```
.
├── Deteccao_Anomalias_Transacoes.ipynb
├── README.md
└── requirements.txt
```

## Como executar

1. Clone este repositório.

```bash
[git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/newtonfalbo/bootcamp-accenture-python-analise-de-dados.git)
```

2. Abra o notebook no Google Colab.

3. Execute todas as células na ordem.

## Resultados

O modelo foi treinado utilizando o algoritmo **Isolation Forest**, capaz de identificar observações consideradas anômalas dentro do conjunto de dados.

Os resultados foram avaliados utilizando:

- Matriz de Confusão
- Precision
- Recall
- F1-Score

## Aprendizados

Durante este projeto foram aplicados conceitos de:

- Machine Learning
- Detecção de Anomalias
- Pré-processamento de dados
- Engenharia de atributos
- Avaliação de modelos

## Autor

Newton Borges

Bootcamp Accenture + DIO
