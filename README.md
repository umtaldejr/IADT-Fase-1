# Tech Challenge - Fase 1 (IADT)

Este repositório contém a solução para o **Tech Challenge da Fase 1 do IADT**, cujo objetivo é aplicar os conhecimentos adquiridos ao longo das disciplinas para desenvolver um modelo preditivo de regressão.

## 🎯 Objetivo

Prever os **custos médicos individuais cobrados pelo seguro de saúde** com base em características demográficas e comportamentais de pacientes, como:

* Idade
* Gênero
* IMC (Índice de Massa Corporal)
* Número de filhos
* Fumante ou não
* Região

## 📊 Etapas do Projeto

O notebook segue as etapas propostas no desafio:

1. **Exploração de Dados (EDA)**

   * Leitura da base de dados
   * Análise estatística descritiva
   * Visualizações gráficas das variáveis

2. **Pré-processamento**

   * Conversão de variáveis categóricas
   * Normalização e tratamento de dados

3. **Modelagem**

   * Aplicação de diferentes algoritmos de regressão (como Regressão Linear e Gradient Boosting)
   * Divisão dos dados em treino e teste

4. **Avaliação**

   * Métricas de desempenho dos modelos (R², RMSE, MAE)
   * Validação estatística com `statsmodels` (p-values, intervalos de confiança)
   * Comparação entre modelos

5. **Visualização de Resultados**

   * Gráficos de valores previstos vs. reais
   * Análise de resíduos

## 📁 Arquivos

* `IADT_Fase_1.ipynb`: Notebook com todo o passo a passo da análise, modelagem e avaliação
* `insurance.csv`: Base de dados utilizada para treinar e testar os modelos
* `gradient_boosting_pipeline.pkl`: Pipeline treinado com Gradient Boosting para uso em previsões futuras

## 🎬 Entregável

Além deste repositório, preparamos um vídeo explicando as etapas seguidas, as decisões de modelagem e os principais resultados obtidos:

[![Assista ao vídeo no YouTube](https://img.youtube.com/vi/Jfr_T8sDwfo/hqdefault.jpg)](https://youtu.be/Jfr_T8sDwfo)

