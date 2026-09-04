# Análise de Preços da Gasolina no Brasil ⛽

Análise exploratória de dados sobre preços da gasolina no Brasil (2004–2021), feita em Python com pandas, como exercício de estudo.

## Dados

- `gasolina_2000_.csv` — 2004 a 2010
- `gasolina_2010_.csv` — 2011 a 2021

## O que o notebook faz

- Combina os dois datasets em um só
- Converte as colunas de data para datetime
- Cria uma coluna de ano-mês
- Filtra os dados de gasolina comum
- Calcula preços médios por período e por estado
- Descobre quando cada estado ultrapassou R$ 5,00
- Calcula a variação percentual ano a ano no Rio de Janeiro

## Como rodar

Abra `analise_gasolina_br.ipynb` no Google Colab, suba os dois CSVs e execute as células em ordem.

## Principais achados

- Preço médio em agosto de 2008: **R$ 2,60**
- Preço médio em São Paulo, maio de 2014: **R$ 2,88**
- Acre foi o primeiro estado a passar de R$ 5,00 (2018); a maioria dos demais só passou em 2021
- Média da região Sul em 2012: **R$ 2,72**
- Maiores altas no RJ: 2018 (+18,3%) e 2021 (+17,4%)
