## Dashboard Interativo de Análise Salarial – Área de Dados ##

Este projeto realiza uma análise completa sobre salários no mercado de trabalho da área de dados, combinando:

🔹 Tratamento e transformação de dados

🔹 Análise exploratória

🔹 Feature engineering

🔹 Visualização interativa com Streamlit

O dataset contém 133.349 registros.

###  Arquitetura do Projeto 

O projeto foi estruturado em duas camadas:

🔹 Data Layer

Limpeza de dados

Padronização

Tradução de colunas

Conversão ISO-2 → ISO-3

Exportação para CSV tratado

🔹 Application Layer

Dashboard interativo com Streamlit

Filtros dinâmicos

KPIs executivos

Visualizações com Plotly

### Funcionalidades do Dashboard

Filtros por:

Ano

Senioridade

Tipo de contrato

Tamanho da empresa

Cálculo dinâmico de métricas

Top 10 cargos por salário médio

Distribuição salarial

Proporção de trabalho remoto

Mapa coroplético de salários por país

Tabela detalhada filtrável

## Técnicas Aplicadas

Data Cleaning

Feature Engineering

GroupBy e agregações

Manipulação de DataFrame

Visualização interativa

Estruturação para deploy web

## Tecnologias

Python

Pandas

Streamlit

Plotly

GitHub (data source)

## ▶ Como Executar Localmente

 Clone o repositório
git clone https://github.com/seu-usuario/seu-repo.git

 Instale as dependências
pip install -r requirements.txt

  Execute o app
streamlit run app.py

## Insights Possíveis

Diferença salarial por senioridade

Impacto do modelo remoto

Países com maior remuneração

Distribuição e dispersão salarial

Distruibuição de senioridade ao longo do tempo



