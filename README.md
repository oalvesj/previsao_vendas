# Previsão de Vendas com Regressão Linear

Projeto que usa um modelo de regressão linear (scikit-learn) para analisar as vendas mensais de uma loja, entender a tendência de crescimento e prever as vendas dos próximos meses. Feito em Python com Pandas, Matplotlib e scikit-learn em um Jupyter Notebook.

## O que o projeto faz

- Organiza os dados de vendas em um DataFrame do Pandas
- Prepara as variáveis (mês como número e vendas)
- Treina um modelo de regressão linear
- Mostra os coeficientes do modelo e a qualidade do ajuste (R²)
- Prevê as vendas dos próximos meses
- Visualiza os dados reais, a reta de regressão e as previsões

## Principais resultados

- Crescimento de cerca de **R$ 113 por mês**, partindo de um intercepto de aproximadamente **R$ 1.980**.
- **R² de 0,99**: a reta explica quase toda a variação das vendas, pois os dados são quase lineares.
- Previsões para os próximos três meses: aproximadamente **R$ 3.453**, **R$ 3.566** e **R$ 3.680**.

## Tecnologias

- Python 3
- Pandas
- Matplotlib
- scikit-learn
- Jupyter Notebook

## Como rodar

1. Instale as dependências:

```bash
pip install pandas matplotlib scikit-learn jupyter ipykernel
```

2. Abra o notebook `previsao_vendas.ipynb`, selecione o kernel Python e execute todas as células.
