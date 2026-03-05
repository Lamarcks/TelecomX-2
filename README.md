# Projeto Telecom X — Previsão de Churn (Parte 2)

Neste desafio, atuei como **Assistente de Análise de Dados** na empresa Telecom X, dando continuidade ao projeto de **Evasão de Clientes (Churn)** iniciado na etapa anterior.  
Enquanto a Parte 1 concentrou-se na limpeza e na análise exploratória dos dados, esta fase teve como foco principal a **construção de modelos preditivos** para estimar a probabilidade de cancelamento dos clientes.

O propósito foi transformar análises descritivas em soluções analíticas capazes de apoiar decisões estratégicas e ações de retenção baseadas em dados.

---

## Objetivo do Projeto

- Desenvolver modelos de Machine Learning para previsão de churn  
- Comparar algoritmos de classificação  
- Avaliar o desempenho dos modelos por meio de métricas estatísticas  
- Identificar os fatores mais relevantes associados à evasão  
- Propor ações estratégicas de retenção orientadas por dados  

---

## O que foi realizado

- Preparação dos dados para aplicação dos modelos preditivos  
- Codificação e normalização de variáveis  
- Análise de correlação entre atributos  
- Separação dos dados em conjuntos de treino e teste (80/20)  
- Treinamento de modelos de classificação  
- Avaliação e comparação de desempenho  
- Interpretação das variáveis mais influentes no churn  

---

## O que foi praticado

- Pré-processamento de dados  
- Engenharia de atributos (Feature Engineering)  
- Aplicação de algoritmos de Machine Learning  
- Avaliação estatística de modelos  
- Leitura e interpretação de métricas  
- Análise de importância das variáveis  
- Construção de recomendações baseadas em resultados  

---

## Preparação dos Dados

### Tratamento e Transformação
- Correção de valores inconsistentes  
- Conversão de variáveis categóricas em numéricas  
- Padronização e normalização conforme o modelo aplicado  
- Estudo da relação entre as variáveis  

### Divisão dos Conjuntos
- Base separada em dados de treino (80%) e teste (20%)  

---

## Modelagem Preditiva

Foram implementados e comparados os seguintes algoritmos:

- Regressão Logística  
- Random Forest  

Cada modelo foi ajustado de acordo com suas particularidades, buscando maior capacidade de generalização e melhor desempenho preditivo.

---

## Avaliação dos Modelos

Para análise dos resultados, foram utilizadas as métricas:

- Acurácia  
- Precisão  
- Recall  
- F1-score  
- Matriz de confusão  

### Principais resultados:
- O modelo **Random Forest** apresentou desempenho superior, identificando padrões mais complexos nos dados.  
- A **Regressão Logística** possibilitou maior transparência na interpretação das variáveis e seus impactos sobre o churn.  

---

## Principais Variáveis Relacionadas ao Churn

As variáveis com maior influência na evasão foram:

- Tempo de permanência do cliente (customer_tenure)  
- Valor total gasto (account_Charges_Total)  
- Valor mensal (account_Charges_Monthly)  
- Tipo de contrato  
- Método de pagamento  

Os resultados indicam que clientes com contratos de curta duração e planos mensais possuem maior tendência ao cancelamento.

---

## Conclusões e Insights

A aplicação dos modelos permitiu identificar padrões relevantes no comportamento dos clientes:

- A probabilidade de churn é maior nos primeiros meses de contrato  
- Contratos mensais concentram maior volume de evasão  
- Valores mensais elevados impactam a permanência do cliente  
- O método de pagamento está diretamente relacionado ao risco de cancelamento  
- O Random Forest demonstrou melhor desempenho preditivo  

---

## Ferramentas Utilizadas

- **Python** — linguagem base do projeto  
- **Pandas** — manipulação e preparação dos dados  
- **NumPy** — operações matemáticas  
- **Matplotlib** — visualização gráfica  
- **Seaborn** — análise estatística visual  
- **Scikit-learn** — construção e avaliação dos modelos  
- **Jupyter Notebook / Google Colab** — ambiente de desenvolvimento  

---

## Recomendações Finais

Com base nos resultados obtidos, recomenda-se:

- Criar ações de retenção voltadas aos clientes nos primeiros meses de contrato  
- Estimular planos de maior duração  
- Acompanhar clientes classificados com alto risco de evasão  
- Incentivar o uso de métodos de pagamento automáticos  
- Integrar o modelo preditivo ao processo de tomada de decisão  

---

## Projeto Relacionado

Parte 1 – Análise Exploratória e Tratamento de Dados  
https://github.com/Lamarcks/TelecomX-1 

---

## 👤 Autor

Projeto desenvolvido por **Ihago Lamarcks**  


LinkedIn: www.linkedin.com/in/ihago-lamarcks1
