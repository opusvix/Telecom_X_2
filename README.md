<p align="center">
  <img src="images/Alura.png" alt="Alura Logo" height="80">
  <img src="images/Logo-ONE.png" alt="Oracle Logo" height="80">
  </p>





# 🚀 Telecom X - Parte 2: Prevendo Churn

Este projeto faz parte da Formação em Data Science oferecida pela Alura e Oracle - Programa ONE | Tech Foundation.

## 🎯 Objetivo

Desenvolver um modelo de Machine Learning para prever a evasão de clientes (churn) com base nos dados da Telecom X.  
O objetivo é ajudar a empresa a identificar clientes com maior risco de cancelamento e propor estratégias de retenção.

---

## 📂 Estrutura do Projeto

Telecom_X_2

/

├── TelecomX_Churn_Prediction.ipynb # Notebook com o pipeline completo de modelagem

├── TelecomX_Data.json # Dados tratados da Parte 1 (formato JSON)

├── TelecomX_dicionario.md # Dicionário de dados

└── README.md # Este arquivo

---

## 🔍 Etapas do Projeto

### 1. **Preparação dos Dados**
- Remoção de colunas irrelevantes (ex: `customerID`)
- Conversão de colunas categóricas em variáveis numéricas (One-Hot Encoding)
- Normalização de variáveis numéricas (StandardScaler)
- Verificação da proporção da evasão (`Churn`)

### 2. **Correlação e Seleção de Variáveis**
- Matriz de correlação
- Análises direcionadas (boxplot e scatterplot)

### 3. **Modelagem Preditiva**
- Divisão em treino (70%) e teste (30%)
- Modelos treinados:
  - Regressão Logística
  - Random Forest
- Avaliação com métricas:
  - Acurácia
  - Precisão
  - Recall
  - F1-score
  - Matriz de Confusão

### 4. **Interpretação dos Resultados**
- Identificação das variáveis mais relevantes
- Gráfico de importância das variáveis (Random Forest)

---

## 📈 Principais Insights

- Clientes com contratos mensais, menor tempo de casa e pagamentos por débito automático apresentaram maior propensão à evasão.
- Random Forest superou a Regressão Logística em todas as métricas.
- Estratégias de retenção devem focar em clientes com baixo `tenure` e contrato mensal.

---

## ⚙️ Como Executar o Projeto

1. Instale as dependências no Google Colab ou Jupyter Notebook:

!pip install pandas seaborn scikit-learn matplotlib

Carregue o notebook TelecomX_Churn_Prediction.ipynb.

Execute todas as células para visualizar o pipeline completo.

## 📚 Bibliotecas Utilizadas
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## 👨‍💻 Autor

Desenvolvido por Maurício Barros

Especialista em Análise de Dados com interesse em IA Generativa.

