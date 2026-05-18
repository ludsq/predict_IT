# PredictIT - Sistema Inteligente de Predição de Falhas em Infraestrutura de TI

Projeto de portfólio em Data Science para prever falhas de servidores nas próximas 1 a 3 horas com base em métricas operacionais.

## Visão Geral

O projeto foi consolidado em um único notebook principal:

- [predict_IT.ipynb](predict_IT.ipynb)

Esse notebook reúne todo o fluxo analítico:

- Contexto e problema de negócio;
- Geração de dados simulados;
- Limpeza e preparação;
- Análise exploratória com gráficos;
- Modelagem preditiva;
- Análise de rede com PageRank;
- Conclusões e próximos passos.

## Técnicas Utilizadas

- Regressão Linear
- Regressão Logística
- Perceptron / MLP
- Deep Learning com TensorFlow / Keras
- Network Science com NetworkX

## Variáveis do Dataset

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

## Execução

O notebook foi preparado para execução simples no Google Colab.

Dependências usadas:

```python
!pip -q install numpy pandas matplotlib seaborn scikit-learn networkx tensorflow
```

Depois, basta executar o notebook `predict_IT.ipynb` em sequência.

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

- Redução de downtime;
- Priorização preventiva de incidentes;
- Melhor uso de monitoramento e resposta em infraestrutura de TI.
