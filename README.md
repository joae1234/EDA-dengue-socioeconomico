# 🦟 Análise Exploratório de Casos de Dengue no Brasil (2017–2024)

Este projeto tem como objetivo realizar uma análise exploratória dos casos de **dengue no Brasil entre os anos de 2017 e 2024**, cruzando dados epidemiológicos com indicadores socioeconômicos como desemprego, pobreza e investimentos públicos em saúde e saneamento. O intuito é identificar padrões, correlações e vulnerabilidades regionais, contribuindo para o aprimoramento de políticas públicas.

## 📊 Objetivos

- Visualizar a evolução dos casos de dengue ao longo do tempo e entre os estados brasileiros;
- Investigar a influência de fatores socioeconômicos na incidência da dengue;
- Verificar a existência de sazonalidade e prever surtos futuros;
- Avaliar a efetividade de investimentos públicos em saúde e saneamento.

## 🧰 Tecnologias e Ferramentas

- Linguagem: **Python 3**
- Bibliotecas principais:
  - `pandas`, `matplotlib`, `seaborn` – análise e visualização de dados
  - `statsmodels`, `scipy` – modelagem estatística e séries temporais
  - `requests` – aquisição de dados via API
- Ambiente: Google Colab / Jupyter Notebook

## 📦 Conjunto de Dados

- **Casos de dengue (2017–2024):** obtidos da plataforma [InfoDengue](https://info.dengue.mat.br/)
- **Indicadores socioeconômicos:** obtidos do [IPEAdata](http://www.ipeadata.gov.br/)
  - Taxa de desemprego
  - Admissões e demissões
  - População
  - Taxa de pobreza
  - IVS – subíndice de Renda e Trabalho
  - Despesa com saúde e saneamento

## 📌 Destaques da Análise

- **Pareto dos Estados:** 10 estados concentram quase 80% dos casos por 100 mil habitantes, com destaque para o Distrito Federal.
- **Sazonalidade:** picos recorrentes entre fevereiro e março nos estados mais afetados.
- **Explosão em 2024:** o Brasil registrou mais de 6,6 milhões de casos, com destaque para SP, DF e MG.
- **Modelagem Temporal (SARIMA):** mostrou que modelos autorregressivos não antecipam surtos fora do padrão histórico.
- **Correlação Fraca:** não há relação linear direta entre gastos públicos e redução dos casos de dengue.
- **Contradição Socioeconômica:** mesmo com admissões superando demissões em vários estados, as taxas de pobreza seguem elevadas.

## 🔍 Principais Gráficos

- Pareto de casos por estado
- Linha temporal de surtos por estado
- Heatmap de casos por 100 mil habitantes
- Previsão SARIMA para o estado de São Paulo
- Evolução da taxa de pobreza e movimentação do mercado de trabalho

## 📽️ Apresentação

> Assista ao vídeo explicativo do projeto:  
[🔗 Clique aqui para assistir](https://youtu.be/eGhGRRXnFTk) *(substitua pelo seu link real caso deseje)*

# 👥 Integrantes

- João Pedro Soares dos Santos — RA: 21004102  
- Carlos Augusto Freire Maia de Oliveira — RA: 21007810  
- Nathan Zanoni da Hora — RA: 21.01208-3  
- Gabriel Zendron Allievi — RA: 21.01350-0  
- João Paulo de Souza Roddrigues — RA: 21.01809-0  

## 📚 Referências

- InfoDengue (Fiocruz): https://info.dengue.mat.br/  
- IPEAData: http://www.ipeadata.gov.br/  
- IBGE: https://www.ibge.gov.br/  
- Hyndman & Athanasopoulos – *Forecasting: Principles and Practice*  
- Bibliotecas: `pandas`, `matplotlib`, `seaborn`, `statsmodels`, `scipy`, `requests`

