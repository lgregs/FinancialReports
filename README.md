# Projeto: Análise Financeira com Python (Project: Financial Analysis with Python)

## Descrição do Projeto (Project Description)
Este projeto é o início de uma série de análises financeiras utilizando Python. Inicialmente, o foco é na coleta e manipulação de dados financeiros de empresas brasileiras, como **ITAÚ**, **AMBEV**, **PETROBRAS** e entre outras com a biblioteca **yfinance**. Futuramente, pretende-se implementar métodos de **machine learning** para prever tendências de mercado e realizar análises mais aprofundadas.

This project will have financial analysis with python. First enphasizing data scrapping, cleannig and manipulation from brazilian companies such as  **ITAÚ**, **AMBEV**, **PETROBRAS** and many others. In the future is intended to apply **Machine Learning** methods to predict market trends and analyze possible buying gaps.

## Objetivos (Objectives)
1. Coletar dados históricos financeiros utilizando bibliotecas como **yfinance**.
2. Realizar análises exploratórias iniciais dos dados (EDA - Exploratory Data Analysis).
3. Preparar os dados para aplicação de modelos de **machine learning**.
4. Implementar modelos de **ML** para previsão e análise de desempenho financeiro.
5. Identificar bons momentos de compra das ações analisadas.
--
1. Collect historical financial data using libraries such as **yfinance**.
2. Perform initial exploratory data analysis (EDA - Exploratory Data Analysis).
3. Prepare data for application of **machine learning** models.
4. Implement **ML** models for forecasting and analyzing financial performance.
5. Identify possible buying gaps.

## Ferramentas e Bibliotecas Utilizadas (Libs and Tools)
- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/): Manipulação e análise de dados.
- [Numpy](https://numpy.org/): Cálculos numéricos eficientes.
- [Yfinance](https://pypi.org/project/yfinance/): Extração de dados históricos do mercado financeiro.
- [Pandas DataReader](https://pandas-datareader.readthedocs.io/): Coleta de dados de fontes financeiras.
- [Matplotlib](https://matplotlib.org/): Visualizações iniciais dos dados (futuramente).
- Machine Learning: Implementações planejadas para as próximas etapas.

## Estrutura do Projeto (Project Structure)
O projeto é estruturado conforme segue:
The project will have the following structure:

```bash
financeiro-analise/
│
├── pythonFinanceiro.ipynb   # EDA. Exploratory Data Analysis
├── data.csv                 # Dados extraídos. Extracted Data              
├── models.ipynb             # Modelos de Machine Learning (em breve). ML Models
├── requirements.txt         # Lista de bibliotecas necessárias. (em breve). Libs and requirements to run the code.
└── README.md                # Documentação do projeto. Documentation
```

## Instalação e Configuração
1. Clone o repositório do projeto:
   ```bash
   git clone https://github.com/lgregs/FinancialReports.git
   cd FinancialReports
   ```

2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute o notebook em um ambiente Jupyter ou Colab.

## Contribuições
Contribuições são bem-vindas! Se você tiver sugestões de melhorias ou quiser implementar novas funcionalidades, fique à vontade!

## Proximos Passos / To do:
- Realizar uma análise exploratória mais completa dos dados.
- Separar codigo de requests da lib yfinance e utilizar somente arquivos baixados.
- Dividir carteira de acoes em duas.
- plotar grafico de historicos com plotly.
- Calcular Taxa de Retorno Diaria e Anual.
- Calcular Taxa de Retorno Logaritimica Diaria e Anual.
- Taxa de Retorno das Carteiras.
- Calculo de Riscos em Acoes.
- CAPM (Capital Asset Pricing Model).
- Previsao de precos futuros com modelos de IA e Series Temporais.

---

