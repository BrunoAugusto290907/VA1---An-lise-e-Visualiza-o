# VA1 - Análise e Visualização de Dados 📊

Este repositório contém o projeto de análise exploratória e visualização de dados referente às **Matrículas na Rede Municipal do Recife no ano de 2024**. O objetivo deste projeto é extrair insights descritivos sobre o perfil dos alunos matriculados, utilizando a linguagem Python e suas principais bibliotecas de análise de dados.

## 🗂️ Fonte dos Dados
Os dados utilizados neste projeto são públicos e foram obtidos através do [Portal de Dados Abertos da Prefeitura do Recife](https://dados.recife.pe.gov.br/). 
- **Dataset:** Matrículas na rede municipal do ano de 2024 (formato CSV).

## 🛠️ Tecnologias e Bibliotecas Utilizadas
O projeto foi desenvolvido em um **Jupyter Notebook** (`VA1_Análise_e_Visualização.ipynb`) e faz uso das seguintes bibliotecas:
- **[Pandas](https://pandas.pydata.org/):** Para manipulação, limpeza e tratamento do DataFrame.
- **[Matplotlib](https://matplotlib.org/):** Para a criação da estrutura das visualizações.
- **[Seaborn](https://seaborn.pydata.org/):** Para a estilização e plotagem de gráficos estatísticos mais atraentes.

## 🔍 Análises Realizadas
O script responde a uma série de perguntas de negócio focadas em entender a demografia e a distribuição dos estudantes:

1. **Total de Matrículas:** Contagem absoluta de registros na base de dados.
2. **Distribuição por Sexo:** Quantidade de alunos do sexo feminino e masculino.
3. **Média de Idade:** A idade média geral dos alunos matriculados.
4. **Idade Mínima e Máxima:** A faixa etária observada na rede municipal.
5. **Alunos por Turno:** Quantidade de estudantes distribuídos entre os turnos disponíveis.
6. **Alunos por Modalidade:** Distribuição dos alunos por modalidade de ensino.
7. **Turmas Mais Lotadas:** Identificação da turma que possui a maior quantidade de alunos.

## 📈 Visualizações Geradas
Para facilitar a interpretação dos dados, foram gerados os seguintes gráficos:
- **Gráfico de Barras (Countplot):** Distribuição de alunos por sexo e por turno.
- **Histograma (com KDE):** Distribuição de frequência das idades dos alunos.
- **Boxplot:** Relação e dispersão das idades segmentadas pelo sexo dos alunos.
- **Gráfico de Barras (Barplot):** Top 15 turmas com a maior quantidade de alunos matriculados e a idade média dos alunos por turno.

## 🚀 Como Executar o Projeto

1. Clone este repositório para a sua máquina local:
   ```bash
   git clone [https://github.com/SEU_USUARIO/VA1-An-lise-e-Visualiza-o.git](https://github.com/SEU_USUARIO/VA1-An-lise-e-Visualiza-o.git)
