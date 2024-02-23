# Case de Predição de Fraudes em Transações de Cartão de Crédito 💳

## Contexto:

Você é um(a) cientista de dados em uma instituição financeira renomada. A empresa está enfrentando um aumento significativo nas transações fraudulentas de cartões de crédito, o que está prejudicando a confiança dos clientes e causando prejuízos financeiros. Sua tarefa é desenvolver um modelo preditivo que possa identificar transações fraudulentas com alta precisão, minimizando assim o impacto financeiro e protegendo a reputação da instituição.

## Base de Dados:

Você tem acesso à base de dados "**fraud_dataset.csv**", que contém informações detalhadas sobre as transações de cartões de crédito. 

## Objetivo:

Desenvolver um modelo preditivo utilizando o algoritmo de Regressão Logística com regularização L2 para prever se uma transação de cartão de crédito é fraudulenta ou não.

**Realize os seguintes passos na sua entrega:**

- Pré-processamento de Dados:
  - Verifique se a base de dados contém informações nulas.
  - Considere a padronização de variáveis numéricas.
- Divisão da Base de Dados:
  - Separe a base de dados utilizando a técnica hold out, mantendo uma proporção adequada para garantir a representatividade dos dados.
  - Caso a base de dados tenha algum tipo de desequilíbrio, aplique uma técnica de oversampling para equilibrar as classes.
- Modelagem:
  - Implemente o algoritmo de Regressão Logística com regularização L2.
  - Utilize a técnica de validação cruzada k-fold (com 5 folds) para avaliar o desempenho do modelo.
- Avaliação do Modelo:
  - Avalie o modelo utilizando métricas como precisão, recall, F1-score e área sob a curva ROC (AUC-ROC).
- Interpretação e Comunicação de Resultados:
  - Comunique os resultados de forma clara e acessível para as partes interessadas, destacando a eficácia do modelo na identificação de transações fraudulentas.

