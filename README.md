# Predição de Doenças Cardíacas com Aprendizado Federado 💓

Este repositório contém o código desenvolvido para o Trabalho de Conclusão de Curso (TCC), que investiga a aplicação do aprendizado federado na predição de doenças cardíacas a partir de dados simulados de dispositivos vestíveis, comparando o desempenho de modelos centralizados e distribuídos, e avaliando a preservação de privacidade conforme LGPD e GDPR.

## 📊 Base de Dados

A base utilizada é o **[Galaxy PPG Dataset](https://zenodo.org/records/14635823)**, que contém sinais fotopletismográficos (PPG) coletados por smartwatches.  
Os dados foram processados para extrair métricas de variabilidade da frequência cardíaca (HRV), como RMSSD e SDNN, e gerar rótulos heurísticos de risco cardíaco conforme critérios clínicos (RMSSD < 20 ms ou SDNN < 50 ms).
