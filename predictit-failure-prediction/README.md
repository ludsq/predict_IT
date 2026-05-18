# PredictIT - Sistema Inteligente de Predicao de Falhas em Infraestrutura de TI

Projeto de portfolio em Data Science para prever falhas de servidores nas proximas 1 a 3 horas com base em metricas operacionais.

## Visao Geral

O projeto foi consolidado em um unico notebook principal:

- [predict_IT.ipynb](/c:/Users/ludmi/dev-projects/predict_it/predict_IT/predictit-failure-prediction/predict_IT.ipynb)

Esse notebook reune todo o fluxo analitico:

- contexto e problema de negocio;
- geracao de dados simulados;
- limpeza e preparacao;
- analise exploratoria com graficos;
- modelagem preditiva;
- network analysis com PageRank;
- conclusoes e proximos passos.

## Tecnicas Utilizadas

- Regressao Linear
- Regressao Logistica
- Perceptron / MLP
- Deep Learning com TensorFlow / Keras
- Network Science com NetworkX

## Variaveis do Dataset

- `timestamp`
- `server_id`
- `cpu_usage`
- `memory_usage`
- `disk_usage`
- `network_latency`
- `error_rate`
- `temperature`
- `risk_score`
- `failure_next_hour`
- `failure_next_3h`

## Execucao

O notebook foi preparado para execucao simples no Google Colab.

Dependencias usadas:

```python
!pip -q install numpy pandas matplotlib seaborn scikit-learn networkx tensorflow
```

Depois, basta executar o notebook `predict_IT.ipynb` em sequencia.

## Estrutura Final Para Git

```text
predictit-failure-prediction/
├── predict_IT.ipynb
├── executive_report.md
├── requirements.txt
└── README.md
```

## Objetivo do Projeto

Antecipar falhas operacionais de curto prazo para apoiar:

- reducao de downtime;
- priorizacao preventiva de incidentes;
- melhor uso de monitoramento e resposta em infraestrutura de TI.
