O Boticário.
Beauty Marketing Intelligence

Análise de campanhas de Marketing Digital com Ciência de Dados para identificar oportunidades de melhoria nos investimentos e prever resultados.

📌 Visão Geral do Projeto (Metodologia CRISP-DM)

Este projeto tem como objetivo aplicar Ciência de Dados ao Marketing Digital, utilizando como estudo de caso o O Boticário.

A proposta é analisar dados de campanhas publicitárias para identificar quais estratégias e canais apresentam melhores resultados, considerando indicadores como investimento, impressões, cliques, conversões e receita.

O desenvolvimento seguirá a metodologia CRISP-DM, que organiza o projeto em seis etapas, desde a compreensão do problema de negócio até a apresentação de uma solução.

Serão utilizados dados simulados para fins acadêmicos, pois não temos acesso às informações internas de campanhas do O Boticário.

Ciclo CRISP-DM

Entendimento do Negócio

Entendimento dos Dados

Preparação dos Dados

Modelagem

Avaliação

Implantação

🛠️ Ciclo de Vida do Projeto (Fases do CRISP-DM)

1. Entendimento do Negócio

Problema de Negócio: Empresas que realizam campanhas de Marketing Digital precisam acompanhar seus resultados para entender quais canais e estratégias geram melhores retornos. No estudo de caso do O Boticário, queremos analisar o desempenho das campanhas e identificar oportunidades para melhorar os investimentos em publicidade.

Objetivo: Analisar os resultados das campanhas digitais e desenvolver um modelo capaz de estimar o número de conversões com base nas características dos anúncios.

Solução Proposta: Utilizar análise exploratória de dados, indicadores de Marketing e um modelo de Machine Learning para apoiar a tomada de decisões. Os resultados serão organizados em um painel de indicadores.

2. Entendimento dos Dados

Fontes: Base de dados simulada, criada exclusivamente para este projeto acadêmico, contendo informações fictícias sobre campanhas de Marketing Digital.

Variáveis analisadas: Canal de divulgação, investimento, impressões, cliques, conversões e receita.

Análise Exploratória (EDA): Analisar o comportamento dos dados, identificar valores ausentes, possíveis inconsistências e relações entre os indicadores.

Objetivo da etapa: Conhecer a estrutura da base e identificar informações importantes para as próximas fases.

3. Preparação dos Dados

Limpeza e Tratamento: Verificar dados ausentes, registros duplicados e possíveis erros nas informações.

Transformação: Organizar os dados e padronizar os formatos das variáveis.

Engenharia de Recursos (Feature Engineering): Criar indicadores como CTR, taxa de conversão, CPC e ROAS.

Organização: Preparar a base para utilização nos modelos de análise e Machine Learning.

4. Modelagem

Algoritmos Testados: Regressão Linear e Random Forest.

Abordagem: Utilizar aprendizado supervisionado para estimar o número de conversões das campanhas.

Treinamento: Dividir os dados em conjuntos de treinamento e teste para avaliar o desempenho do modelo.

Objetivo: Identificar qual abordagem apresenta melhores resultados na previsão de conversões.

5. Avaliação

Métricas do Modelo: Avaliar os resultados utilizando métricas como MAE, RMSE e R², adequadas para um problema de previsão numérica.

Avaliação de Negócio: Verificar se os resultados ajudam a compreender o desempenho das campanhas e apoiam decisões de Marketing.

Indicadores de Marketing (KPIs):

CTR: Percentual de impressões que resultaram em cliques.

CPC: Custo médio por clique.

Taxa de Conversão: Percentual de cliques que resultaram em conversões.

ROAS: Retorno sobre o investimento em anúncios.

Receita: Valor gerado pelas campanhas.

Os resultados numéricos serão apresentados após a execução e avaliação dos modelos.

6. Implantação

Aplicação dos Resultados: Organizar os resultados das análises em relatórios e indicadores que facilitem a interpretação dos dados.

Camada de Visualização (BI): Propor um painel no Power BI para acompanhar o desempenho das campanhas.

Visão Executiva: Apresentar os principais indicadores, investimentos e resultados por canal.

Visão Analítica: Comparar campanhas, conversões, custos e retorno dos investimentos.

A implantação será apresentada como uma proposta acadêmica, sem integração real aos sistemas internos do O Boticário.

📁 Estrutura de Pastas

├── docs/
│   ├── dicionario_dados.md
│   └── metricas_modelo.json

├── data/
│   └── campanhas_marketing.csv
├── notebooks/
│   ├── 1_eda/
│   └── 2_testes_modelagem/

├── src/
│   ├── data_prep.py
│   ├── train_model.py
│   └── predict.py
├── bi/

├── requirements.txt
└── README.md

Tecnologias utilizadas

Python

Pandas

Matplotlib

Scikit-learn

Power BI

GitHub

👥 Autora e Contato

Ana da Fonseca dos Santos e Lais Valeria — Estudante de Marketing.

Observação: Este projeto possui finalidade exclusivamente acadêmica. Os dados utilizados são simulados e não representam informações oficiais ou resultados reais do O Boticário.
