# Epidemologia_SIG

# **Dados COVID-19 **

No ambito da cadeira Sistemas de Informação Geográfica foi proposto aos alunos do Mestrado em Engenharia Biomédica- Ramo Informática Médica a colheita de dados relativamente à situação epidemiológica do COVID-19 e posterior tratamento dos mesmos, através das funcionalidades do Jupyter.

## **Contextualização**

A Itália é o sexto país com mais casos de coronavírus em todo o Mundo, antecedido pelos EUA, Brasil, Rússia, Reino Unido e Espanha. Os dados e informações expostos podem sofrer desatualizações uma vez que a cada dia que passa há alterações nos valores. 

A apresentação de dados como número de óbitos, novos casos, número de casos totais, entre outros, tornam-se mais facilmente interpretados em gráficos, tabelas ou imagens, podendo encontrar neste GITHUB informação relativamente aos dados do COVID-19 em Itália.

![Mapa províncias Itália](https://github.com/AnaPinto16/Epidemologia_SIG/blob/master/ItaliaCovid/Imagens/ITALIA.png)


Como forma de apresentar também a atualidade dos dados registados em todo o mundo, foi realizado um notebook com os dados de todo o Mundo, presente na pasta MundoCovid.

###### Mapa gerado através do QGIS.

## **Origem dos dados**

Os ficheiros de ambos os repositórios encontram-se na pasta DATA.

[Repositório 1](https://github.com/pcm-dpc/COVID-19) - Situação epidemiológica Itália: Informação relativamente ao total de casos, novos casos, número de infetados, número de óbitos, número de recuperados, entre outros. (Desde 24/02-> 24/05).

[Repositório 2](http://www.diva-gis.org/datadown) - Mapa Itália

## **Resultados**

Através das funcionalidade do Jupyter, foi possível a criação de 2 mapas divididos por tons de cores diferentes, consoante o maior ou menor número de casos. 

Nota: Cores mais claras -> Menor número de casos; Cores mais escuras -> Maior número de casos.

### Mapa I: Número total de casos positivos

O primeiro mapa gerado é referente ao número total de casos positivos em Itália, podendo-se verificar que a província com maior número de casos positivos corresponde a Lombardia com 25614.

![Mapa Totale positivi](https://github.com/AnaPinto16/Epidemologia_SIG/blob/master/ItaliaCovid/Imagens/Geographic_distribution_totale_positiv.png)

### Mapa II: Número total de óbitos

O segundo mapra gerado é relativo ao número de óbitos registados em Itália, verificando-se novamente que Lombardia é a província com mais casos registados, contando com 15840 óbitos.

![Mapa Totale Deceduti](https://github.com/AnaPinto16/Epidemologia_SIG/blob/master/ItaliaCovid/Imagens/Geographic_distribution_totale_deceduti.png)

### Gráficos

De forma a comparar alguns parâmetros do dataset relativo à situação epidemiológica em Itália, foram elaborados alguns gráficos, presentes na pasta "Imagens", bem como o respetivo código para a obtenção dos gráficos na pasta "Gráficos".

Os gráficos obtidos permitiram a comparação do Top5 e Bottom5 do número total de casos e número de óbidos e o Top5 de maior número de registos de pessoas afetadas com COVID-19 a recuperar em casa e hospitalizados.

O gráfico VIII corresponde ao número de casos, desde 24/02 a 24/05, de Lombardia. 

![Mapa Totale Casi per giorni: Lombardia](https://github.com/AnaPinto16/Epidemologia_SIG/blob/master/ItaliaCovid/Imagens/casi_positivi_dias.png)

O mesmo tipo de gráfico foi feito para o número de óbitos em Lombardia, desde 24/02 a 24/05.

![Mapa Totale Deceduti per giorni: Lombardia](https://github.com/AnaPinto16/Epidemologia_SIG/blob/master/ItaliaCovid/Imagens/casi_deceduti_dias.png)


# ###############MUNDO###############

![Mapa Mundo](https://github.com/AnaPinto16/Epidemologia_SIG/blob/master/MundoCovid/Imagens/MundoCovid.png)

O trabalho feito para os dados recolhidos relativamente aos casos em todo o Mundo foram apresentados em gráficos uma vez que apenas se pretendia um estudo mais aprofundado no caso de Itália.

Os mapas apresentados são relativos à Taxa de Recuperados, Taxa de Mortalidade e a comparação entre os dados relativos à Taxa de Recuperados e Mortalidade.

![Mapa de Recuperados por COVID-19](https://github.com/AnaPinto16/Epidemologia_SIG/blob/master/MundoCovid/Imagens/RecuperadosMundo.png)

![Mapa Mortalidade por COVID-19](https://github.com/AnaPinto16/Epidemologia_SIG/blob/master/MundoCovid/Imagens/MortalidadeMundo.png)

![Mapa Mortalidade por COVID-19](https://github.com/AnaPinto16/Epidemologia_SIG/blob/master/MundoCovid/Imagens/RecvsMort.png)

Como referido anteriormente, Itália encontra-se na 6ª posição de infetados por COVID-19, mas até 16/04 encontrava-se na 3ª posição (consoante a informação dos dados utilizados).

![Mapa Mortalidade por COVID-19](https://github.com/AnaPinto16/Epidemologia_SIG/blob/master/MundoCovid/Imagens/Top10casos.png)

O gráfico da taxa de mortalidade, apresenta comportamentos muito diferentes, no entanto Itália apresenta um comportamento relativamente constante.
![Mapa Mortalidade por COVID-19](https://github.com/AnaPinto16/Epidemologia_SIG/blob/master/MundoCovid/Imagens/Top10morte.png)


