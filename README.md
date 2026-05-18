# Análise de Dados e Modelagem Preditiva: Varejo Walmart 

Este repositório contém o projeto de Business Intelligence e Analytics desenvolvido para a disciplina de **Gestão de Dados, Informação e Conhecimento** do Centro de Informática da UFPE (CIn-UFPE), sob a orientação do Prof. Paulemir Campos.

O objetivo principal do projeto é analisar dados históricos de vendas do Walmart para identificar padrões sazonais, avaliar o impacto de indicadores macroeconómicos no consumo e construir um modelo preditivo para estimar o faturamento futuro, visualizando os resultados num dashboard interativo no Google Looker Studio.

## 🚀 Link do Dashboard
Acede ao painel interativo aqui: [Link do Dashboard no Looker Studio](TBA)

## 📌 Contexto e Domínio do Problema
O setor do retalho (varejo) é altamente influenciado por fatores sazonais (como feriados de fim de ano) e variáveis económicas externas (inflação, desemprego e custo de vida). Utilizando a base de dados de vendas semanais do Walmart, este projeto adota uma abordagem de engenharia de dados ponta a ponta para responder a duas perguntas de negócio fundamentais:
1. De que forma os fatores externos e as datas comemorativas afetam o comportamento de compra dos consumidores?
2. Como podemos antecipar a procura futura para otimizar a cadeia de suprimentos (estoques) das lojas?

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Visualização de Dados (BI):** Google Looker Studio (pela agilidade, design limpo e capacidade colaborativa em tempo real).
* **Processamento e Engenharia de Dados:** Python, Pandas e NumPy (limpeza, agregação e enriquecimento da base bruta).
* **Análise Preditiva (Data Science):** Python (Scikit-Learn / Statsmodels / Prophet) para o cálculo isolado das projeções de séries temporais.

## 🗃️ Estrutura do Repositório
```text
├── data/
│   ├── raw/          # Base de dados bruta do Walmart (histórico original)
│   └── processed/    # Base final unificada (dados históricos + previsões calculadas)
│
├── notebooks/
│   ├── 1_analise_exploratoria.ipynb  # Estudo de correlação (CPI, Desemprego, Combustível)
│   └── 2_modelo_previsao.ipynb       # Script matemático que gera o Forecast das vendas
│
├── README.md         # Documentação principal do projeto
└── requirements.txt  # Bibliotecas Python necessárias para rodar o ambiente
