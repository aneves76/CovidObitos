# Estudo dos óbitos por Covid no Brasil
Ajuste e projeção dos óbitos por Covid por uma logística.

## Apresentação e dados

Óbitos confirmados por dia, utilizando informações curada pela Johns Hopkins University que segue casos mundiais desde o início da pandemia. Os dados estão disponibilizados publicamente no GitHub (https://github.com/CSSEGISandData/COVID-19). 

Os dados do Estado de São Paulo são fornecidos pela Secretaria de Estado da Saúde de São Paulo (SES) no GitHub, https://github.com/seade-R/dados-covid-sp .

Estes dados são lido automaticamente do GitHub, e ajustados por uma curva logística de Gompertz em um programa Mathematica. O programa gera um gráfico, exemplo esta neste repositório, além de informar o valor esperado para a metade do número total de fatalidades e em quantos dias se espera que este número seja alcançado.
Na versão 2, já atingimos quase a metade do total de fatalidades, portanto os gráficos foram extrapolados até aproximadamente 90% do total de fatalidades. Serve para uma previsão do fim da pandemia.

## Licença
Todos os arquivos estão sob licença GPL 3.0. Para detalhes veja http://www.gnu.org/licenses/.
