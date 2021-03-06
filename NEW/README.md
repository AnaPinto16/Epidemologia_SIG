# Projeto2: COVID-19

O presente projeto tem como objetivo a apresentação de dados relativos a todo o Mundo, a comparação do Top5 países com maior número de casos e por fim, o estudo de caso de Itália.

O notebook "Visualização_dados", presente na pasta Notebooks, é relativo à apresentação dos dados do dataset "owid-covid-data.csv" presente na pasta DATA e a sua representação em tabelas que permitem uma melhor visualização dos valores para cada coluna, dando destaque ao Top5 de total de casos, Top5 de mortes e Top5 de novos casos. Uma vez que é do interesse do presente projeto o tratamento de dados de Itália, procedeu-se à criação de um novo dataset com informação apenas sobre Itália desde 2019-12-31 até 2020-05-29.

No notebook "Gráficos" encontram-se diversos gráficos com o objetivo de representar dados importantes, de forma a esquematizar os dados desde o início da pandemia até 19/05.

De forma a visualizar como é que os dados se comportam, foi criado um gráfico com as curvas de número total de casos, número total de mortes, bem como as curvas de novos casos dos anteriores.

![Gráfico Total](https://github.com/AnaPinto16/Epidemologia_SIG/tree/master/NEW/Imagens/Total.png)


Atualmente, os países mais afetados pela pandemia são Itália, Brasil, USA, Russia e Espanha, sendo por essa razão feita a comparação dos dados que cada um destes apresenta. Os resultados obtidos encontram-se no gráfico seguinte, onde é possível visualizar o aumento exponencial do número total de casos em USA.

![Gráfico Top5](https://github.com/AnaPinto16/Epidemologia_SIG/tree/master/NEW/Imagens/Top_5.png)

O mesmo gráfico foi feito para o número total de óbitos dos mesmos países, verificando-se novamente que USA é o que apresenta valores mais elevados.

![Gráfico Top5_mortes](https://github.com/AnaPinto16/Epidemologia_SIG/tree/master/NEW/Imagens/Top5_mortes.png)


# Caso de Estudo: Itália

Itália foi um país fortemente atacado pelo COVID-19 aquando do alastramento do vírus pelo mundo, sendo que atualmente foi ultrapassado por outros países.

Desta forma, foi desenvolvido um gráfico que mostra a evolução do número de casos em Itália desde o início da pandemia até 29/05, bem como um gráfico de barras apenas com o número de casos no mês de maio.

![Gráfico IT_inicio](https://github.com/AnaPinto16/Epidemologia_SIG/tree/master/NEW/Imagens/Total_IT_inicio.png)

O mesmo gráfico foi desenvolvido para o número de mortes no mesmo intervalo de tempo.

![Gráfico IT_inicio_mortes](https://github.com/AnaPinto16/Epidemologia_SIG/tree/master/NEW/Imagens/Total_IT_inicio_mortes.png)


# Caso de Estudo II: Testes realizados

Uma das principais preocupações aquando do aparecimento do vírus foi a deteção do vírus numa pessoa, de modo a atuar desde o primeiro dia de forma a combater o vírus. Este estudo encontra-se no notebook "Testes_mundo" onde são apresentados os mesmos tipos de gráficos que nos notebooks anteriores, com a diferença que neste notebook o objetivo era a visualização das curvas dos testes realizados em países desenvolvidos e nos países não desenvolvidos. É possível concluir, como esperado, que o número de testes disponibilizados aos países não desenvolvidos é muito inferior aos países desenvolvidos por diferentes razões. Os gráficos seguintes mostram a comparação da curva dos USA e Nepal, uma vez que foram os que apresentaram valores mais elevados, verificando-se que o número de testes feitos para o Nepal é aproximadamente 0, enquanto que a curva dos USA cresce exponencialmente. Uma das razões para este desfazamento de testes, encontra-se no gráfico que compara o número de mortes e número de casos infetados, sendo que no Nepal ronda valores aproximados do 0.

## Gráfico comparativo de testes feitos em USA e Nepal
![Gráfico_vs_testes](https://github.com/AnaPinto16/Epidemologia_SIG/tree/master/NEW/Imagens/testesvs.png)

## Gráfico comparativo de infetados em USA e Nepal

![Gráfico_vs_infetados](https://github.com/AnaPinto16/Epidemologia_SIG/tree/master/NEW/Imagens/infetadosvs.png)

## Gráfico comparativo de mortos em USA e Nepal

![Gráfico_vs_mortos](https://github.com/AnaPinto16/Epidemologia_SIG/tree/master/NEW/Imagens/mortesvs.png)

# Projeto desenvolvido por:

-Ana Pinto a93660 MIEBIOM

-04/06/2020
