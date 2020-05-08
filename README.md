# Estudo dos obitos por Covid no Brasil
Ajuste e projeção dos óbitos por Covid por uma logistica.

## Apresentação e dados

Óbitos confirmados por dia, utilizando informações curada pela Johns Hopkins University que segue casos mundiais deste o inicio da pandemia. Os dados estão disponibilizados publicamente no GitHub (https://github.com/CSSEGISandData/COVID-19). 

Os dados do Estado de São Paulo são fornecidos pela Secretaria de Estado da Saúde de São Paulo (SES) no GitHub, https://github.com/seade-R/dados-covid-sp .

Estes dados são lido atomaticamente do GitHub, e ajustados cpor uma Curva logistica de Gompertz em um programa Mathematica. O programa gera um gráfico, exemplo esta neste repositorio, além de informar o valor esperado para a metade do numero total de fatalidades e em quantos dias se espera que este numero seja alcançado.

## Licença
Todos os arquivos estão sob licença GPL 3.0. Para detalhes veja http://www.gnu.org/licenses/.
