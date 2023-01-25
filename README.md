# Clima_Tempo

Este projeto consite em um modelo de séries temporais para a previsão do tempo de Nova Deli, utilizando dados do [Kaggle](https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data) Daily Climate time series data. Um dos objetivos deste notebook é apresentar umas das formas de utilizar a biblioteca [Prophet](https://facebook.github.io/prophet/) do facebook que é a previsão do tempo.

>* O Prophet é uma ferramenta simples que nos possibilita fazer previsões em séries temporais — desde que dentro das limitações do framework — sem que haja a necessidade >de possuir conhecimentos profundos. Ainda que simples ela é muito poderosa, pois, com sua abordagem analyst-in-the-loop, é possível atingir excelentes resultados >realizando “tunning” dos parâmetros e/ou dados. Para o dataset estudado, esse framework se mostrou eficiente mesmo em suas
>configurações padrão, mostrando ser acessível para todos os analistas.
>* A previsão do tempo é uma aplicação de séries temporais em que usamos dados e algoritmos de séries temporais para determinado 
> momento. A previsão do tempo é de suma importancia pois ajudam a governos á tomarem medidas contra possíveis desastres naturais.

# Bibliotecas
~~~python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
from prophet import Prophet
