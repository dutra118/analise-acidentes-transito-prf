# analise-acidentes-transito-prf
# 🚗 Análise Exploratória e Preditiva de Acidentes de Trânsito – PRF

## 📌 Sobre o projeto

Este projeto tem como objetivo analisar os acidentes de trânsito registrados nas rodovias federais brasileiras, utilizando dados públicos disponibilizados pela Polícia Rodoviária Federal (PRF), por meio do sistema DATATRAN.

A análise foi desenvolvida utilizando Python para o tratamento, exploração e modelagem dos dados, além do Tableau para a criação de dashboards interativos.

O projeto busca identificar padrões relacionados à ocorrência de acidentes, analisar indicadores de gravidade e desenvolver modelos de regressão linear para estimar tendências de determinados indicadores nos meses seguintes ao período observado.

## 🎯 Objetivos

- Analisar a distribuição dos acidentes entre os estados e rodovias federais.
- Identificar rodovias com maior ocorrência de acidentes.
- Investigar indicadores relacionados às vítimas fatais e aos veículos envolvidos.
- Analisar o comportamento dos acidentes ao longo dos meses.
- Desenvolver modelos preditivos para estimar indicadores futuros.
- Apresentar os resultados por meio de dashboards interativos.

## 🛠️ Tecnologias e ferramentas utilizadas

| Tecnologia | Aplicação |
|---|---|
| Python | Desenvolvimento das análises |
| Pandas | Limpeza, tratamento e manipulação dos dados |
| NumPy | Operações e cálculos numéricos |
| Matplotlib | Criação de gráficos |
| Seaborn | Visualização e análise exploratória |
| Scikit-learn | Desenvolvimento dos modelos de regressão linear |
| Tableau | Criação de dashboards interativos |

## ⚙️ Etapas do projeto

### 1. Tratamento e preparação dos dados

Utilizando Python e Pandas, foram realizadas atividades de preparação da base de dados, incluindo:

- Identificação e tratamento de valores ausentes.
- Identificação e remoção de registros duplicados.
- Criação de novas colunas para auxiliar nas análises.
- Remoção de colunas desnecessárias.
- Conversão e adequação dos tipos de dados.

### 2. Análise exploratória dos dados (EDA)

Foram realizadas análises para investigar o comportamento dos acidentes de trânsito, considerando diferentes perspectivas:

- Distribuição dos acidentes por estado.
- Identificação das rodovias com maior número de acidentes.
- Análise da quantidade de vítimas fatais.
- Análise dos veículos envolvidos nos acidentes.
- Comportamento dos acidentes ao longo dos meses.
- Investigação de padrões e indicadores relacionados à gravidade dos acidentes.

### 3. Modelagem preditiva

Foi utilizada a biblioteca Scikit-learn para desenvolver modelos de regressão linear, com o objetivo de estimar indicadores dos meses seguintes com base nos dados históricos.

As previsões desenvolvidas contemplaram:

- Média diária de acidentes.
- Total de acidentes previstos para os próximos meses.
- Média de vítimas fatais por acidente.
- Média de veículos envolvidos por acidente.

As estimativas têm caráter exploratório e representam tendências projetadas pelo modelo, não resultados garantidos.

### 4. Desenvolvimento dos dashboards no Tableau

Após o tratamento e a análise dos dados, foi desenvolvido um dashboard interativo no Tableau para facilitar a exploração e interpretação dos resultados.

O painel conta com gráficos e indicadores que permitem analisar diferentes aspectos dos acidentes de trânsito.

Foram implementados filtros dinâmicos que atualizam simultaneamente as visualizações conforme as seleções realizadas pelo usuário, permitindo explorar os dados por diferentes dimensões.

## 📊 Dashboard interativo

**Acesse o dashboard publicado no Tableau Public:**

https://public.tableau.com/app/profile/gustavo.dutra6688/viz/dashPRF-Copia/Painel1

## 🔎 Principais descobertas

Nesta seção serão apresentados os principais resultados identificados durante a análise exploratória, incluindo padrões de distribuição dos acidentes, rodovias com maior ocorrência, indicadores de gravidade e tendências observadas nos dados.

## 📂 Estrutura do repositório

- `notebooks/`: notebooks com o desenvolvimento das análises em Python.
- `dashboards/`: arquivos do projeto desenvolvido no Tableau.
- `imagens/`: capturas de tela das visualizações.
- `demonstracao/`: vídeo demonstrativo do dashboard.
- `README.md`: documentação do projeto.

## 📚 Fonte dos dados

Os dados utilizados neste projeto são públicos e disponibilizados pela Polícia Rodoviária Federal (PRF), por meio do sistema DATATRAN.

## 🎓 Aprendizados

O desenvolvimento deste projeto proporcionou a aplicação prática de conhecimentos em análise exploratória de dados, tratamento de bases, manipulação de dados com Python, modelagem preditiva utilizando regressão linear e desenvolvimento de dashboards interativos no Tableau.

Além disso, permitiu trabalhar com dados públicos para transformar grandes volumes de registros em informações que facilitam a identificação de padrões e a compreensão dos acidentes de trânsito nas rodovias federais brasileiras.
