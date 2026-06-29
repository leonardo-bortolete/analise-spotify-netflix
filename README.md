# Análise comparativa: Spotify e Netflix

Projeto de análise de dados que compara a evolução dos preços das ações e das receitas anuais do Spotify e da Netflix.

A análise utiliza períodos comuns e normalização em base 100 para tornar as comparações mais consistentes, considerando que as empresas possuem históricos diferentes e reportam suas receitas em moedas distintas.

## Objetivos

* analisar a evolução dos preços das ações;
* comparar a variação acumulada dos preços no período comum;
* analisar a evolução das receitas anuais;
* comparar o crescimento relativo das receitas.

## Principais resultados

No período comum analisado, entre abril de 2018 e junho de 2026:

* Spotify: variação acumulada do preço de aproximadamente **208,72%**;
* Netflix: variação acumulada do preço de aproximadamente **160,20%**.

Entre 2022 e 2025:

* a receita do Spotify apresentou variação acumulada de **46,55%**;
* a receita da Netflix apresentou variação acumulada de **42,91%**.

Nos dois critérios analisados, o Spotify apresentou a maior variação acumulada durante os períodos considerados.

## Tecnologias utilizadas

* Python
* pandas
* Matplotlib
* yfinance
* Google Colab

## Metodologia

Os dados históricos das ações e as demonstrações financeiras anuais foram obtidos com a biblioteca `yfinance`.

Para as ações, foi utilizado somente o período disponível simultaneamente para as duas empresas. Os preços foram normalizados utilizando o primeiro registro do período comum como base 100.

As receitas foram mantidas em suas moedas originais e posteriormente normalizadas, permitindo a comparação de seu crescimento relativo.

## Notebook

O notebook completo, com código, tabelas, gráficos e interpretações, está disponível abaixo:

[Visualizar a análise completa](analise_spotify_netflix.ipynb)

## Limitações

A análise é descritiva e considera somente a evolução dos preços ajustados e das receitas anuais retornadas pela fonte de dados. Não foram avaliados risco, volatilidade ou outros indicadores financeiros.
