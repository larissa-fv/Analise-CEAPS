# Análise de Base de Dados CEAPS

[![Feito com Jupyter](https://img.shields.io/badge/feito%20com-Jupyter-orange?style=flat&logo=jupyter)](https://jupyter.org/)
[![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat&logo=python)](https://www.python.org/)
[![Licença MIT](https://img.shields.io/badge/Licença-MIT-green.svg)](https://opensource.org/licenses/MIT)

Este projeto tem como objetivo analisar dados públicos da base CEAPS (Centro de Estudos e Aperfeiçoamento dos Servidores do Senado), aplicando técnicas de ciência de dados para gerar insights relevantes sobre gastos parlamentares.

Tem como objetivo praticar análise de dados com Python e bibliotecas especializadas.


## Sobre o Dataset CEAPS

O dataset CEAPS (Centro de Estudos e Aperfeiçoamento dos Servidores do Senado) é uma base pública disponibilizada pelo Senado Federal do Brasil, que reúne informações detalhadas sobre despesas realizadas por parlamentares, servidores e órgãos do Senado.

Essa base faz parte do portal de Dados Abertos do Senado e tem como objetivo garantir transparência e permitir análises sobre a utilização de recursos públicos, incluindo gastos com passagens, divulgação, alimentação, hospedagem, entre outros.

Mais informações e acesso ao dataset oficial podem ser encontrados no site do Senado:  
[https://www12.senado.leg.br/transparencia/dados-abertos-transparencia/dados-abertos-ceaps](https://www12.senado.leg.br/transparencia/dados-abertos-transparencia/dados-abertos-ceaps)

Analise tendo considerados os dados disponíveis referentes ao período compreendido entre os anos de 2018 e 2022.


## Objetivos do Projeto

- Importação, inspeção e pré-processamento dos dados da base CEAPS, incluindo tratamento de valores ausentes e normalização de colunas.
- Realização de análise exploratória de dados (EDA) para compreender a estrutura, distribuições e possíveis inconsistências no dataset.
- Identificação dos parlamentares com maiores gastos por categoria, permitindo a análise do perfil de consumo de recursos públicos.
- Classificação e análise dos tipos de despesas mais frequentes, com segmentação por categorias como divulgação, transporte, entre outras.
- Criação de visualizações gráficas (barras, linhas e histogramas) para acompanhar a evolução temporal dos gastos e identificar tendências ou sazonalidades.
- Desenvolvimento de filtros para segmentar os dados por ano, tipo de despesa e parlamentar, facilitando análises específicas e comparativas.
- Utilização das bibliotecas Python pandas, matplotlib e seaborn para manipulação, análise e visualização dos dados de forma eficiente.
- Documentação do processo analítico no Jupyter Notebook, com explicações e interpretações dos resultados obtidos.


---

## Tecnologias Utilizadas

| Ferramenta       | Finalidade                           |
|------------------|---------------------------------------|
| Python 3.x       | Linguagem principal                   |
| Jupyter Notebook | Execução e documentação das análises |
| pandas           | Manipulação e análise de dados        |
| matplotlib       | Geração de gráficos                   |
| seaborn          | Visualizações estatísticas            |
| numpy            | Operações numéricas                   |
| Plotly           | Gráficos interativos                  |
| Streamlit        | Criação de dashboards interativos    |

---

## Estrutura do Projeto

Analise-CEAPS/
├── data_ceaps/ # Pasta com os dados originais (arquivos brutos do dataset CEAPS)
│ └── [arquivos do dataset] # 2018, 2019, 2020, 2021, 2022
├── Analise de BD CEAPS.ipynb # Notebook principal com a análise
├── README.md # Documentação do projeto


---

## Análises Realizadas

* Ingestão e inspeção exploratória dos dados: leitura dos arquivos originais do dataset CEAPS, análise dos tipos de dados, identificação de valores ausentes, duplicados e inconsistências estruturais.

* Pré-processamento e limpeza dos dados: normalização e padronização de colunas, tratamento de valores nulos, correção de formatação de datas, remoção de duplicatas e ajustes de tipos para garantir a qualidade da base para análise.

* Transformação e enriquecimento dos dados: criação de novas variáveis derivadas, categorização de tipos de despesas, e filtragem dos dados por intervalos temporais relevantes (2018–2022).

* Agrupamentos e segmentações avançadas: aplicação de funções de agregação para análise por parlamentar, por tipo de despesa, e por período (mensal, anual), possibilitando cruzamentos e comparações detalhadas.

* Análise estatística descritiva: cálculo de medidas centrais (média, mediana), dispersão (desvio padrão, variância) e identificação de outliers para melhor compreensão dos padrões de gastos.

* Visualizações gráficas e temporais: elaboração de gráficos de barras, linhas, histogramas e heatmaps, utilizando bibliotecas pandas, matplotlib e seaborn para ilustrar tendências, sazonalidades e distribuições das despesas.

* Interpretação crítica e insights: análise dos resultados para destacar padrões relevantes, discrepâncias nos gastos e potenciais áreas de interesse para investigações futuras ou acompanhamento contínuo.
  
* Documentação técnica e reproduzibilidade: organização da análise em Jupyter Notebook com descrições claras, código comentado e passos metodológicos para garantir transparência e facilitar a replicação do estudo


---

## Possíveis Melhorias Futuras

- Criação de um dashboard interativo com Streamlit ou Plotly Dash
- Automatização da atualização dos dados
- Análise comparativa por partido, estado ou região
- Integração com outras bases públicas

---

## Como Executar Localmente

1. Clone o repositório:

```bash
git clone https://github.com/larissa-fv/Analise-CEAPS.git
