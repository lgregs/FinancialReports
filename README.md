# Projeto: Análise Financeira com Python

## Descrição do Projeto
Este projeto é o início de uma série de análises financeiras utilizando Python. Inicialmente, o foco é na coleta e manipulação de dados financeiros de empresas brasileiras, como **GOL**, **ITAÚ**, **AMBEV** e **PETROBRAS**, com a biblioteca **yfinance**. Futuramente, pretende-se implementar métodos de **machine learning** para prever tendências de mercado e realizar análises mais aprofundadas.

## Objetivos
1. Coletar dados históricos financeiros utilizando bibliotecas como **yfinance**.
2. Realizar análises exploratórias iniciais dos dados (EDA - Exploratory Data Analysis).
3. Preparar os dados para aplicação de modelos de **machine learning**.
4. Implementar modelos de **ML** para previsão e análise de desempenho financeiro.

## Ferramentas e Bibliotecas Utilizadas
- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/): Manipulação e análise de dados.
- [Numpy](https://numpy.org/): Cálculos numéricos eficientes.
- [Yfinance](https://pypi.org/project/yfinance/): Extração de dados históricos do mercado financeiro.
- [Pandas DataReader](https://pandas-datareader.readthedocs.io/): Coleta de dados de fontes financeiras.
- [Matplotlib](https://matplotlib.org/): Visualizações iniciais dos dados (futuramente).
- Machine Learning: Implementações planejadas para as próximas etapas.

## Estrutura do Projeto
O projeto é estruturado conforme segue:

```bash
financeiro-analise/
│
├── pythonFinanceiro.ipynb   # Notebook principal do projeto, com gráficos e análises.
├── data/                    # Dados extraídos ou preparados. (em breve).              
├── models/                  # Modelos de Machine Learning (em breve).
├── requirements.txt         # Lista de bibliotecas necessárias. (em breve).
└── README.md                # Documentação do projeto.
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
- Separar codigo de requests e utilizar somente arquivos baixados.
- Dividir carteira de acoes em duas.
- plotar grafico de historicos com plotly.
- Calcular Taxa de Retorno Diaria e Anual.
- Calcular Taxa de Retorno Logaritimica Diaria e Anual.
- Taxa de Retorno das Carteiras.
- Calculo de Riscos em Acoes.
- CAPM (Capital Asset Pricing Model).
- Previsao de precos futuros com modelos de IA e Series Temporais.

---

