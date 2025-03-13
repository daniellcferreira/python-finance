# Python Finance

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific_Computing-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data_Visualization-FF7F0E?style=flat-square&logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-Scientific_Computing-8CA0FF?style=flat-square&logo=python&logoColor=white)


## Descrição

O **Python Finance** é um projeto que tem como objetivo auxiliar na análise e visualização de dados financeiros utilizando Python. O repositório contém notebooks Jupyter que cobrem diversos aspectos da análise financeira, desde a obtenção de dados até a modelagem de portfólios.

## Funcionalidades

- Leitura e manipulação de dados financeiros.
- Análise de séries temporais.
- Cálculo de indicadores financeiros.
- Visualização de dados econômicos.
- Construção e otimização de portfólios financeiros.
- Análise de risco e retorno.

## Estrutura do Projeto

O repositório está organizado em notebooks Jupyter que abordam os seguintes temas:

### Notebooks

- **aula01.ipynb**: Introdução à leitura de dados financeiros, importando datasets de fontes como Yahoo Finance e InfoMoney usando Pandas.
- **aula02.ipynb**: Manipulação de séries temporais financeiras, incluindo reamostragem, preenchimento de valores ausentes e cálculo de retornos.
- **aula03.ipynb**: Análise exploratória de dados financeiros, identificando tendências, sazonalidade e distribuição dos retornos.
- **aula04.ipynb**: Visualização de dados financeiros utilizando Matplotlib e Seaborn para criar gráficos de linha, histógramas e boxplots.
- **aula05.ipynb**: Introdução à modelagem financeira, abordando conceitos de precificação de ativos e cálculo de retornos esperados.
- **aula06.ipynb**: Análise de risco e retorno de ativos financeiros, incluindo métricas como volatilidade e Sharpe Ratio.
- **aula07.ipynb**: Introdução ao Value at Risk (VaR), utilizando diferentes abordagens para estimar perdas potenciais.
- **aula08.ipynb**: Backtesting de estratégias financeiras, simulando o desempenho de estratégias de investimento usando dados históricos.
- **aula09.ipynb**: Análise de correlação entre ativos financeiros, explorando matrizes de correlação e diversificação de portfólios.
- **aula10.ipynb**: Construção de portfólios eficientes, aplicando a teoria moderna de portfólios para otimizar a relação risco-retorno.

## Requisitos

Certifique-se de ter os seguintes pacotes instalados:

- Python 3.6 ou superior
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/daniellcferreira/python-finance.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd python-finance
   ```

3. Crie e ative um ambiente virtual:

   ```bash
   python -m venv env
   source env/bin/activate  # No Windows: env\Scripts\activate
   ```

4. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

## Uso

1. Inicie o Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Abra o notebook desejado (por exemplo, `aula01.ipynb`) e execute as células conforme necessário.

## Contribuição

Contribuições são bem-vindas! Para contribuir, siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma branch para sua feature:

   ```bash
   git checkout -b minha-feature
   ```

3. Commit suas alterações:

   ```bash
   git commit -m 'Adiciona minha feature'
   ```

4. Envie para o branch original:

   ```bash
   git push origin minha-feature
   ```

5. Abra um Pull Request.



