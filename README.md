# Previsão de Diabetes com Machine Learning

Este projeto tem como objetivo desenvolver modelos de Machine Learning para prever o risco de diabetes em pacientes, utilizando o conjunto de dados **Pima Indians Diabetes Database**.

## -> Dataset

- **Fonte:** Kaggle — [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Total de registros:** 768
- **Total de variáveis:** 9 (8 preditoras + 1 target: `Outcome`)

## Objetivo

Explorar diferentes modelos de classificação para prever a presença de diabetes com base em dados clínicos.

## </> Modelos utilizados

Os seguintes classificadores foram treinados e avaliados:

- `LogisticRegression`
- `RandomForestClassifier`
- `SVC (Support Vector Classifier)`
- `XGBClassifier (Extreme Gradient Boosting)`

##  Estrutura do projeto

├── Analise_exploratoria_LogisticRegression.ipynb
├── analise_exploratoria_RandomForest.ipynb
├── Analise_exploratoria_SVC.ipynb
├── Analise_exploratoria_XGBClassifier.ipynb
├── diabetes.csv
├── requirements.txt
└── README.md


## Técnicas aplicadas

- Análise exploratória de dados (EDA)
- Pré-processamento com imputação e balanceamento (SMOTE)
- Treinamento e validação cruzada
- Otimização de hiperparâmetros com `GridSearchCV`
- Avaliação com métricas:
  - Accuracy
  - Precision, Recall, F1-Score
  - ROC AUC
  - Matriz de confusão
  - Curva ROC

## Requisitos

Instale as dependências com:

```bash
pip install -r requirements.txt
