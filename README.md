# 📊 Churn Prediction - IBM Dataset (Kaggle)

Este projeto tem como objetivo prever a evasão de clientes (churn) utilizando um conjunto de dados disponibilizado pela IBM no Kaggle. Ao longo da análise, aplicamos diversas técnicas de ciência de dados, desde a exploração inicial até o ajuste fino do melhor modelo preditivo.

## 📚 Bibliotecas Utilizadas

* Pandas
* NumPy
* Matplotlib / Pyplot
* Seaborn
* Scikit-learn
* Imbalanced-learn (imblearn.over_sampling)

## 📌 Etapas do Projeto

1. Entendimento do Dataset

* Leitura e descrição do conjunto de dados
* Identificação de variáveis explicativas (features) e variável-alvo (target)
* Verificação de tipos de dados e valores ausentes

2. Análises Exploratórias
   
* Análises univariadas: distribuição das variáveis
* Análises bivariadas: relação entre variáveis e o target
* Correlação entre variáveis numéricas
* Gráficos com Seaborn e Matplotlib para apoio visual

3. Pré-processamento
   
* Transformação de variáveis categóricas do tipo object em variáveis dummies
* Normalização de dados numéricos (se necessário)
* Balanceamento da base com oversampling (via SMOTE) para tratar desbalanceamento entre classes
* Divisão entre conjunto de treino e teste

4. Modelagem

* Criação e avaliação de diferentes algoritmos de classificação
* Comparação de desempenho com base em métricas como:
* Accuracy
* Precision
* Recall
* F1-score
* AUC-ROC

5. Otimização de Hiperparâmetros

* Aplicação de GridSearchCV no modelo com melhor desempenho
* Ajuste fino dos hiperparâmetros (tuning)
* Reavaliação do modelo após ajuste

6. Salvamento do Modelo
   
Exportação do modelo final treinado utilizando joblib ou pickle

## 📁 Dataset

Fonte: Kaggle - IBM Telco Customer Churn (https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data)

## ✅ Resultados

O modelo final apresentou uma boa capacidade de prever clientes com alta chance de churn, possibilitando a aplicação prática em estratégias de retenção de clientes.
O modelo com maior acurácia foi utilizando o Random Forest.

## 🚀 Como Rodar

* Clone este repositório
* Instale os requisitos do projeto: requirements.txt
* execute o notebook principal "churn_prediction.ipynb"

## 🤝 Contribuições

Sinta-se à vontade para abrir issues, sugerir melhorias ou criar pull requests!

## 👨‍💻 Autor

**Matheus Phillipe Carvalho Ferreira**
Transição de carreira para área de dados • Entusiasta em aprendizado de máquina e análise de dados

LinkedIn: https://www.linkedin.com/in/matheus-pcf

