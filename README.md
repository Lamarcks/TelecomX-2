<div align="center">

# 🤖 Telecom X — Previsão de Churn com Machine Learning

### Modelagem Preditiva para Identificação de Clientes com Risco de Evasão

Projeto desenvolvido durante minha formação em **Data Science no programa Oracle Next Education (ONE) + Alura**, dando continuidade à análise exploratória realizada no **Telecom X — Parte 1**.

Nesta etapa, o foco foi transformar os dados tratados em **modelos de Machine Learning capazes de identificar padrões relacionados ao cancelamento de clientes**.

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge\&logo=scikitlearn\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data%20Visualization-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0?style=for-the-badge)

</div>

---

## 📌 Sobre o projeto

A **Telecom X** enfrenta um problema de evasão de clientes e busca utilizar seus dados para compreender e antecipar possíveis cancelamentos.

Na **Parte 1**, o trabalho foi concentrado em **ETL, tratamento dos dados e Análise Exploratória (EDA)**.

Nesta segunda etapa, os dados preparados foram utilizados para desenvolver e comparar **modelos de classificação**, buscando identificar clientes com maior probabilidade de Churn e os fatores que mais influenciam esse comportamento.

> O projeto demonstra a evolução de uma análise descritiva para uma abordagem preditiva utilizando Machine Learning.

---

## 🎯 Objetivo

O projeto teve como principais objetivos:

* 🤖 Desenvolver modelos de Machine Learning para previsão de Churn
* 🔍 Identificar padrões associados à evasão de clientes
* ⚙️ Preparar os dados para modelagem preditiva
* 📊 Comparar algoritmos de classificação
* 📈 Avaliar o desempenho dos modelos
* 🧠 Identificar as variáveis mais relevantes para o Churn
* 💡 Gerar recomendações para estratégias de retenção

---

## 🔄 Pipeline de Machine Learning

O projeto seguiu um fluxo completo de preparação, treinamento e avaliação:

```text
Dados tratados — Parte 1
        ↓
Pré-processamento
        ↓
Codificação das variáveis
        ↓
Normalização / Padronização
        ↓
Análise de correlação
        ↓
Divisão treino e teste
        ↓
Treinamento dos modelos
        ↓
Avaliação das métricas
        ↓
Análise das variáveis
        ↓
Insights de negócio
```

---

## ⚙️ Preparação dos Dados

Antes da construção dos modelos, foram realizadas etapas de preparação para garantir que os dados estivessem adequados ao processo de Machine Learning.

Entre elas:

* Correção de valores inconsistentes
* Conversão de variáveis categóricas em numéricas
* Codificação das variáveis
* Normalização e padronização quando necessário
* Análise de correlação entre atributos
* Preparação das variáveis preditoras
* Separação da variável alvo **Churn**

Os dados foram posteriormente divididos em:

**80% para treinamento**
**20% para teste**

---

## 🤖 Modelos de Machine Learning

Foram implementados e comparados dois algoritmos de classificação.

### 📈 Regressão Logística

Modelo utilizado por sua capacidade de classificação e facilidade de interpretação dos efeitos das variáveis sobre a probabilidade de Churn.

### 🌲 Random Forest

Modelo baseado em múltiplas árvores de decisão, capaz de identificar relações mais complexas entre as características dos clientes.

---

## 📊 Avaliação dos Modelos

Os modelos foram avaliados utilizando diferentes métricas de classificação:

| Métrica                | Finalidade                                                  |
| ---------------------- | ----------------------------------------------------------- |
| **Acurácia**           | Percentual geral de previsões corretas                      |
| **Precisão**           | Proporção de previsões positivas realmente corretas         |
| **Recall**             | Capacidade de identificar clientes que realmente cancelaram |
| **F1-Score**           | Equilíbrio entre Precisão e Recall                          |
| **Matriz de Confusão** | Análise detalhada dos erros e acertos                       |

A utilização de diferentes métricas permitiu avaliar os modelos além da acurácia geral.

---

## 🏆 Comparação dos Modelos

A análise mostrou comportamentos diferentes entre os algoritmos.

### 🌲 Random Forest

Apresentou **melhor desempenho preditivo geral**, conseguindo identificar relações mais complexas existentes entre as variáveis.

### 📈 Regressão Logística

Apresentou maior facilidade de interpretação, permitindo compreender de forma mais transparente a influência das características dos clientes sobre o Churn.

> A escolha de um modelo não depende apenas da acurácia, mas também do objetivo de negócio, da capacidade de identificação dos clientes em risco e da interpretabilidade necessária.

---

## 🔎 Principais Variáveis Relacionadas ao Churn

A análise dos modelos destacou algumas características com maior relação com a evasão:

* ⏳ **Tempo de permanência do cliente**
* 💰 **Valor total gasto**
* 💵 **Valor mensal**
* 📄 **Tipo de contrato**
* 💳 **Método de pagamento**

Essas variáveis ajudam a compreender quais características devem receber maior atenção em estratégias de retenção.

---

## 💡 Principais Insights

A modelagem reforçou padrões importantes observados durante a análise dos dados:

### ⏳ Primeiros meses

Clientes nos primeiros meses de relacionamento apresentam maior risco de cancelamento.

### 📄 Contratos mensais

Contratos de curta duração concentram maior ocorrência de Churn.

### 💵 Mensalidades

Valores mensais elevados apresentam relação com maior risco de evasão.

### 💳 Forma de pagamento

O método de pagamento também apresentou associação relevante com o comportamento de cancelamento.

### 🤖 Machine Learning

Os modelos permitem transformar esses padrões em previsões que podem auxiliar a empresa na identificação antecipada de clientes em risco.

---

## 🎯 Recomendações de Negócio

Com base nos resultados, algumas estratégias podem ser consideradas:

* Criar ações de retenção para clientes nos primeiros meses de contrato
* Incentivar a migração para contratos de maior duração
* Acompanhar clientes identificados como alto risco
* Avaliar ofertas específicas para clientes com mensalidades elevadas
* Incentivar métodos de pagamento automáticos
* Integrar previsões de Churn aos processos de relacionamento com clientes

---

## 🛠️ Tecnologias utilizadas

| Tecnologia                 | Aplicação                                              |
| -------------------------- | ------------------------------------------------------ |
| **Python**                 | Desenvolvimento da análise e modelagem                 |
| **Pandas**                 | Manipulação e preparação dos dados                     |
| **NumPy**                  | Operações numéricas                                    |
| **Scikit-learn**           | Pré-processamento, treinamento e avaliação dos modelos |
| **Matplotlib**             | Construção de visualizações                            |
| **Seaborn**                | Visualizações estatísticas                             |
| **Google Colab / Jupyter** | Desenvolvimento e execução do projeto                  |
| **Git & GitHub**           | Versionamento e documentação                           |

---

## 📂 Estrutura do projeto

```text
TelecomX-2/
│
├── TelecomX_(2).ipynb
└── README.md
```

### `TelecomX_(2).ipynb`

Notebook contendo o processo completo de:

**pré-processamento → modelagem → treinamento → avaliação → interpretação → recomendações.**

---

## 🚀 Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/Lamarcks/TelecomX-2.git
```

### 2. Acesse a pasta

```bash
cd TelecomX-2
```

### 3. Abra o notebook

```text
TelecomX_(2).ipynb
```

O projeto pode ser executado utilizando:

* **Google Colab**
* **Jupyter Notebook**
* **Visual Studio Code com suporte a Jupyter**

---

## 🔗 Projeto relacionado

Este projeto é a continuação direta da análise realizada anteriormente:

### 📊 Telecom X — Parte 1 | ETL e Análise Exploratória

[➡️ Acessar Telecom X — Parte 1](https://github.com/Lamarcks/TelecomX-1)

A evolução entre os projetos pode ser representada por:

```text
Telecom X — Parte 1
ETL + EDA
        ↓
Telecom X — Parte 2
Machine Learning
        ↓
Previsão de Churn
        ↓
Apoio à retenção de clientes
```

---

## 📚 Conhecimentos desenvolvidos

Durante o projeto foram aplicados conceitos importantes de Machine Learning:

* Pré-processamento de dados
* Feature Engineering
* Codificação de variáveis
* Normalização e padronização
* Separação entre treino e teste
* Modelos de classificação
* Regressão Logística
* Random Forest
* Scikit-learn
* Acurácia, Precisão, Recall e F1-Score
* Matriz de Confusão
* Análise de importância de variáveis
* Interpretação de modelos
* Geração de recomendações orientadas por dados

---

## ✅ Status do projeto

**Concluído ✅**

Projeto desenvolvido como parte da formação em **Data Science — Oracle Next Education (ONE) + Alura**.

---

## 👨‍💻 Autor

**Ihago Lamarcks**

Estudante de **Análise e Desenvolvimento de Sistemas**, com foco em **Python, Dados, Inteligência Artificial e Cloud Computing**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ihago%20Lamarcks-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/ihago-lamarcks1/)

---

<div align="center">

### 🤖 Transformando dados em previsões para apoiar estratégias de retenção.

**Python • Machine Learning • Scikit-learn • Data Science • Oracle Next Education**

</div>
