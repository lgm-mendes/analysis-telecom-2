# 📊 Previsão de Churn de Clientes – Telecom X

## 🎯 Propósito da Análise

Este projeto tem como objetivo analisar os dados de clientes da **Telecom X** e prever quais clientes têm maior probabilidade de cancelar seus serviços (Churn) utilizando **modelos de Machine Learning**.  
O projeto aborda desde o pré-processamento dos dados até a interpretação dos resultados, com foco em gerar insights estratégicos para retenção de clientes.  

As etapas incluem:

- Preparação e limpeza dos dados (tratamento de valores ausentes, encoding, normalização)
- Análise exploratória e correlação entre variáveis
- Treinamento e avaliação de modelos de classificação
- Interpretação da importância das variáveis
- Geração de insights estratégicos para retenção

---

## 🗂 Estrutura do Projeto

### Importação e Limpeza dos Dados
Os dados foram carregados a partir de arquivos CSV, contendo informações sobre:
- Perfil do cliente (gênero, idade, tempo de contrato)
- Serviços contratados (internet, telefone, etc.)
- Gastos mensais e totais
- Tipo de contrato

Etapas de pré-processamento incluíram:
- Remoção de valores nulos e inconsistentes
- Conversão de colunas para tipos adequados
- Encoding de variáveis categóricas
- Normalização de variáveis numéricas

---

### 🔍 Modelagem e Análises Realizadas

#### Modelos Treinados
- Regressão Logística
- Random Forest
- Gradient Boosting (opcional)

#### Avaliação dos Modelos
- Métricas de desempenho: Acurácia, Precisão, Recall, F1-Score
- Curvas ROC e AUC para comparação de modelos

#### Insights das Variáveis
- Identificação das variáveis mais influentes na previsão do churn
- Correlação entre características do cliente e probabilidade de cancelamento

---

### 📊 Visualizações
O projeto inclui gráficos para:
- Distribuição de churn por gênero, idade e tipo de contrato
- Relação entre tempo de contrato, gasto mensal e probabilidade de cancelamento
- Importância das variáveis nos modelos de Machine Learning
- Comparação do desempenho dos diferentes modelos

---

## 📌 Conclusões

A análise e os modelos preditivos revelaram que:
- Clientes com **pouco tempo de contrato e alto gasto mensal** têm maior risco de churn
- O **início da jornada do cliente** é o ponto mais crítico para retenção
- Alguns serviços específicos (como Fibra Ótica) estão fortemente associados à evasão
- Modelos de Machine Learning permitem priorizar clientes de risco e criar ações proativas

---

## 🏁 Conclusão Final

Este projeto demonstra como a aplicação de **Machine Learning** em dados de clientes pode ajudar a **reduzir o churn** e melhorar a retenção.  
Os insights obtidos permitem à empresa tomar decisões estratégicas, oferecendo intervenções direcionadas para clientes de maior risco e aumentando a satisfação e fidelidade.
